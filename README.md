# HeadrushMX5
## 基本的な使い方
### セットリストを選択
まず、タッチパネルの左上のハンバーガーリストで、「セットリスト」を選択する。  
これにより、「Rig移動」の対象が、セットリストに入れたRigだけに絞られる。  
標準ではセットリストが「ALL Rigs」（270個）になっているため、1周するのに270回のRig移動をしなければならないが、例えば10個のRigのセットリストを選択しておけば、10回のRig移動で1周する。  
すなわち、セットリストとは、「ALL Rigs」のサブセットである。  
### FS2、FS3もON/OFFとして使うならSTOMPモードが必須
STOMPモードでは、3つのフットスイッチFSでMODELのON/OFFができる。  
しかし、他のモード（Rigモード、Hybridモード）では、FS2、FS3にはRig移動が割り当てられるため、MODELSのON/OFFとしては使えなくなる。  
したがって、演奏時には、STOMPモードでしたほうが、、MODELSのON/OFF状態を切り替えやすい。  
### 切り替えが1回（2種類）なら、シーンを使う
1つのRigにおいて、切り替えがVerse -> Sole -> Verse のように、2種類を行き来するだけであれば、FS1に、シーンを割り当てるとよい。  
FSは、標準では、1つのMODELをON/OFFするようになっているが、複数のMODELSをまとめてON/OFFするようにもできる。  
これを「シーン」という。  
  
## PCと接続
MX5をPCに接続すると、ディスクのなかに５つのフォルダと１つのファイルがある。  
「Blocks」「Rigs」「Setlists」「ImpulseResponses」「Loops」「LockScreenLogo.png」（800x400）  
それぞれのフォルダのなかに、設定ファイルなどが入っている。  
## MODELS(Blocks）
[MODELS 一覧](https://github.com/78tch/HeadrushMX5/blob/master/Models.md)  
「Blocks」フォルダのなかに入っている。  
「AMP」サブフォルダのなかにアンプのMODELSが入っている。  
「CAB」サブフォルダのなかにキャビネットのMODELSが入っている。  
その他のMODELSは、モデル名のサブフォルダが入っている。  
（マイクはどういう形で入っているか不明）  
## Rigs
[Rigs 一覧](https://github.com/78tch/HeadrushMX5/blob/master/Rigs.md)  
MX5のRigは、いわゆるプリセットのこと。  
「プリセットバンク、ユーザーバンク」というような区別はない。  
プリセットのRigは270個あるが、ユーザーが作ったRigは、最後尾に271個目以降として追加される。  
ディスク容量いっぱいまでひたすら保存できる模様。  
  
## Setlists
[Setlists 一覧](https://github.com/78tch/HeadrushMX5/blob/master/Setlists.md)  
「セットリスト」とは、いくつかのRigをグループ化して、好みの順に並べたもの。  
画面左肩で、選択する。  
標準では、「ALL RIGS」（270個全部）になっているが、セットリストを切り替えておくと、STOMP・RIG・HYBRID各モードでのRig移動が、セットリストのなかにあるRigだけになる。  
セットリストに入っていないRigは、スキップされるので、「その時使うRigを使う順に並べたセットリスト」を作って、それに切り替えておけばよい。  

## IR
WAVフォーマットのIRファイルに対応。  
最大192kHz、32bit、2,048サンプルまで。  
IRファイルは一般にデータサイズが小さいので、数千個でも保存できる。  
IRファイルの保存場所は、ディスクのなかの「ImpulseResponses」フォルダのなか。  
キャビネット名などのサブフォルダのなかに、マイク別、サンプリング数別などに、個々のIRファイルが入っている。  
ブロックに割り当てる場合は、IR（2048サンプル）か、IR(1024)（1024サンプル）かを選び（通常は2048）、キャビネット名（サブフォルダ）を選んで、さらに個々のIRファイルまで選んで割り当てる。  
- Preset:IR、設定、色
- Folder:IRファイルが入っているフォルダ。（「ImpulseResponses」フォルダのなかのサブフォルダ。）
- IR File:
- Gain:
- HiCut:16～18kHz以上をカット。
- LoCut:80～100Hz以下をカット。
- Mix:
  
## モード
起動時は、シャットダウン時のモードに戻る。  
どのモードの時も、  
FS1Holdでモード切替画面、  
FS2HoldでLooper  
FS3HoldでTuner  
  
モード切替画面での遷移は以下。  
|No|切り替え|モード名|用途|画面|
|--|--|--|--|--|
|1|FS1|Stompモード|各FSでMODELをON/OFF、1と2で↓、2と3で↑のRig移動||
|2|FS2|Rigモード|各FSでRigを呼び出す、1と2で↓、2と3で↑のバンク移動||
|3|FS3|Hybridモード|FS1でMODELをON/OFFやシーンを切り替え、2で↑、3で↓のRig移動||
|4|FS1Hold|HANDS-FREEモード|FSとPEDALで操作||
|5|FS2Hold|Setlistモード|1で選択、2で↑、3で↓のSetlist移動、1HoldでAll Rigs||
|6|FS3Hold|(UN)LOCK|ロック画面になって、パネルでエディットできなくなる。ロックアイコンをタップで解除。|
  
なお、Rigモードの「1と2で↓、2と3で↑のバンク移動」というのは、バンクというよりも、3つ分ずつ移動する、という感じ。
  
## シーン
STOMPモードなどで、FSを押したときの動作について、標準の「一つのモデルをON/OFF」ではなく、「複数のモデルの状態をいっぺんに切り替える」ように変更するもの。  
したがって、各Rigの、ハードウェアセッティングで、３つのFSそれぞれに対して設定できるが、FS2とFS3にシーンを設定しても、STOMPモードの時しか使えず、Hybridモードの時には自ずとFS1しか使えない。  
  
## 初期化方法
Factroy Reset 方法  
FS2 と FS3 を押したままで電源をONする。  
画面に REVERTING... と出るまで押し続ける。  
  
## Global Settings
  
## ルーパー

## ファームウェアアップデート
1. PCとUSB接続後、MX5の電源ON
2. MX5の画面右上の「…」、「Global Settings」
3. 「…」、「Firmware Update」、「OK」
4. PCで「HeadRush Updater」起動、「Update HeadRush」
5. 「Done」、閉じると、MX5が再起動
6. 「…」、「Global Settings」でバージョン確認

## 画面
- Setlist：MX5の画面左上のハンバーガーリストをタップ
- リグのリスト：リグ名をタップ
- SAVE：リグの変更を保存
- 「…」：Global Settingsへ
- 「・・・・」：シグナルパスオプション
- 「TAIL」：スピルオーバー

## 用語
- Rig：
- Setlist：
- Scene：
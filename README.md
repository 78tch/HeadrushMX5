# HeadrushMX5
MX5をPCに接続すると、ディスクのなかに５つのフォルダと１つのファイルがある。  
「Blocks」「Rigs」「Setlists」「ImpulseResponses」「Loops」「LockScreenLogo.png」（800x400）  
それぞれのフォルダのなかに、設定ファイルなどが入っている。  

## MODELS(Blocks）
[MODELS 一覧](https://github.com/78tch/HeadrushMX5/blob/master/Models.md)  
  
## Rigs
[Rigs 一覧](https://github.com/78tch/HeadrushMX5/blob/master/Rigs.md)  
  
## Setlists
[Setlists 一覧](https://github.com/78tch/HeadrushMX5/blob/master/Setlists.md)  
  
## IR
WAVフォーマットのIRファイルに対応。  
最大192kHz、32bit、2,048サンプルまで。  
IRファイルは一般にデータサイズが小さいので、数千個でも保存できる。
- Preset:IR、設定、色
- Folder:IRファイルが入っているフォルダ。
- IR File:
- Gain:
- HiCut:16～18kHz以上をカット。
- LoCut:80～100Hz以下をカット。
- Mix:
  
## プリセット
MX5のRig（プリセット）は、「プリセットバンク、ユーザーバンク」という２系統ではなく、区別なく１系統で並ぶ。  
ディスク容量いっぱいまでひたすら保存できる。  
プリセットのRigは270個あるが、ユーザーが作ったRigは、プリセットを上書きするか、最後尾に追加する。  
切り替えて使いたいRigをグループ化して、好みの順に並べた「セットリスト」が作れる。  
STOMPモードで使いながらRigも切り替えたい、となれば、セットリストよりも、ALL Rigs において、切り替えて使いたいRigを並べて保存しておいたほうがよいかもしれない。  
Rigモードの「1と2で↓、2と3で↑のバンク移動」というのは、バンクというよりも、3つ分ずつ移動する、という感じ。  

  
## モードa
|No|切り替え|モード名|用途|画面|
|--|--|--|--|--|
|1|FS1|Stompモード|各FSでMODELをON/OFF、1と2で↓、2と3で↑のRig移動||
|2|FS2|Rigモード|各FSでRigを呼び出す、1と2で↓、2と3で↑のバンク移動||
|3|FS3|Hybridモード|FS1でMODELをON/OFFやシーンを切り替え、2で↑、3で↓のRig移動||
|4|FS1Hold|HANDS-FREEモード|FSとPEDALで操作||
|5|FS2Hold|Setlistモード|1で選択、2で↑、3で↓のSetlist移動、1HoldでAll Rigs||
|6|FS3Hold|Tuner/Tempoモード|1でミュート解除、2でテンポ、3で終了||
  
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
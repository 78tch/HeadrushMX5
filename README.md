# Headrush MX5
## 1.Quick Start
### 1-1.MX5を初めて使う
1. 起動すると、Rig「001 HOW DOES IT FEEL」が立ち上がる。Rigとは、いわゆる「プリセット・パッチ」のことである。
2. 初期状態で、プリセットRigは「270 +WDW-HARMONY」まで、全部で270個ある。
3. Rigの切り替えは、FootSwitch（以下FS）か、タッチパネルでRig名を下スワイプやタップする。
4. いわゆる「プリセットバンク・ユーザーバンク」のような「バンク切替」の機能はない。自作Rigは、プリセットRigと区別なく、名前の昇順・降順で表示される。自作Rigに名前を付ける際には、先頭に数字を使わないなど工夫しないと、プリセットRigと自作Rigが混ざって表示され区別がしづらい。
5. 全270個以上あるRigsのなかから、使いたいRigを探し出して切り替えるのは面倒なので、使いたいRigだけを選抜したリストに名前を付けて保存できる。これを「Setlists」と呼ぶ。
6. 「Setlists」を切り替えるには、タッチパネル左肩のハンバーガーメニューをタップして、目的のSetlistをタップする。なお、初期状態では、すべてのRigを表示する「All presets」という特殊なSetlist が選択されている。
7. 使用場面ごとにSetlistを作って、使いたいRigだけを登録し、Setlistsを切り替えて使う。

### 1-2.画面の種類

### 1-3.「IR」を使う
1. MX5には、最初からIRがいくつか入っているが、ユーザーが追加することもできる。
2. プリセットRigでは、IRではなく、キャビネットシュミレーターが使われている。IRを使う場合、キャビシュミをいったん停止または削除し、代わりにIRを配置すればよい。
3. IRを追加する場合、パソコンとつないで、MX5の「Impulse Responses」フォルダのなかに「キャビネット名」のサブフォルダを置き、そのなかにIRの「Wavファイル」を置けば、選択肢に出てくるようになる。
4. Headrush の HP からダウンロードできるArtistsサンプルRigsのIRは、「Impulse Responses」フォルダのなかの「USER」フォルダに直接「Wavファイル」を置くと、そのIRを使っているRigに、IRが置いてある場所を認識させやすい。
5. IRはさまざまなサンプル数やサンプリングレートのものがあるが、原則「2048サンプル、96.0kHz、500ms」のものを使う。録音時もUSB出力は使わないしCDにするわけでもないので、44.1kHz に揃えたりする必要はなく、機器が対応しているいちばん高音質なものを使えばよい。

### 1-4.「IR」をそのまま使うとノイジーな場合あり
1. IRを使うと、弦アースをしてもノイズが消えきらない場合がある。対策は以下。
2. MX5 のマスターボリュームを下げる。12時～2時ぐらいを基準とするとよい。それでもノイジーなら、次へ。
3. 可能であれば、電源でアースを取る。とても効果が高い。常時、弦アースをしているような感じになる。アースがとれない場合、次へ。
4. 「IR」の「Gain」を下げる。-10～-20dBぐらい。それでもノイジーなら、次へ。
5. 「Guitar INPUT」の「Gain」を下げる。-10～-20dBぐらい。それでもノイジーなら、次へ。
6. 「Noise gate」をかける。ただし、弱く弾いた音や余韻の音までカットされる。
7. ギター本体のボリュームを絞る。ただし、これをすると、音が変わる。それでもノイジーなら、次へ。
8. アンプシュミレーターの「Gain」 を下げる。ただし、これをすると、音が変わる。それでもノイジーなら、MX5以外にノイズの原因がある可能性が高い。例：OAタップに、MX5以外にもパソコンなど他の機器もつないで電源を取っている。

### 1-5.ミキサーやオーディオインターフェースなど他機器との接続
1. ケーブルについて：MX5 のOUT 端子は、いわゆる「6.3mm（1/4インチ）標準フォーン端子」であるが、バランス接続に対応している。したがって、MX5をミキサーに接続する際のケーブルを、両端がTSフォン（絶縁リングが１つの二極）であるような一般的なシールドケーブルではなく、MX5側はTRS端子（絶縁リングが２つの三極、いわゆるステレオ標準プラグ）、ミキサー側はXLR端子（３ピンのキャノン端子、）であるような「XLRオス-TRSフォン」ケーブルで接続すれば、バランス接続となり、ノイズに強くなる。
2. グローバルセッティング：Main Out Level:メインOUT端子（TRS）の信号レベルを設定する。「LINE/AMP」の切り替えあり。Lineは+18dBu、Ampは+6dBuとなる。音量やノイズの加減で切り替える。
3. グローバルセッティング：FX Return Level:FX リターン入力（TRS）で受信する信号レベルを設定する。「Rack/Stomp」の切り替えあり。Rackは+18dBu、Stompは+6dBuとなる。音量やノイズの加減で切り替える。
4. USBオーディオ設定：サンプルレート：USBオーディオインターフェイスの音は、DAW側でGainが固定となって大きくできないのに音量が小さいので、使いづらい。USBからの音を最終的にCD（44.1kHz）にするのであれば、ここも「44.1」にしておけばよいかもしれないが、CDにしないのであれば、最高音質「96.0」にすればよいし、そもそもUSB出力を使わないのであれば、気にしなくてもよい。

## 2.各種設定
### 2-1.初期化方法
1. FS2 と FS3 を押したままで電源をONして、画面に REVERTING... と出るまで押し続ける。これで初期化される。  
### 2-2.ファームウェアアップデート
1. PCとUSB接続後、MX5の電源ON
2. MX5の画面右上の「…」、「Global Settings」「…」、「Firmware Update」、「OK」
3. PCで「HeadRush Updater」起動、「Update HeadRush」、「Done」、閉じると、MX5が再起動
4. MX5が再起動したら、画面右上の「…」、「Global Settings」の「3」でバージョン確認
### 2-3.用語
1. MODEL：MX5 のシグナルパス（仮想のPedal Board）上に配置できる、アンプ、キャビネット、インパルスレスポンス、エフェクトなど。
2. Rig：いわゆるプリセット。音作りをして、保存して呼び出せるようにしたもの。
3. Setlist：Rigをグループ化して、まとめて呼び出せるようにしたもの。すべてのRigs を表示する「All presets」という特別なSetlist もある。
4. Scene：ひとつのRigにおいて、On/Offやパラメータ値を変えて、切り替えられるようにしたもの。Scene1、Scene2、として、フットスイッチに割り当てる。以前はScene1しかなく、1回だけのOn化またはOFF化しかできなかったが、Scene1/Scene2をOn/Offできるようになった。
5. シグナルパス：MX5における、仮想ペダルボードにおける、モデルの並べ方。１直線、Y字型、途中並列型などあり。
6. INPUT：Input端子の設定。ギターの入力に対する設定。レベルメーターがあるので、クリップしないように調節する（下げる）。
7. OUTPUT：Output端子の設定。スピーカーやヘッドホンの出力に対する設定。音割れしないように調節する（上げる）。
8. モード：演奏時の、FS1、FS2、FS3の働きのパターン。STOMPモード、Hybridモード、Rigモードの3通りあり。STOMPモードよりもSceneを使いこなすとよい。
9. TAIL：スピルオーバー（Rigを切り替えたときに、前のRigの残響を消さない設定）
### 2-4.内部フォルダ構成
パソコンにつなぐと、MX5の内部のフォルダ構造やファイルを直接みることができる。
1. 「Blocks」：
2. 「Impulse Response」：さらに「キャビ名のフォルダ」があり、そのなかにIRの「wavファイル」が入っている。
3. 「Loops」：ルーパーで録音したファイルが保存される。パソコンからmp3ファイルを取り込んでここに置くと、ルーパーで読み込める。
4. 「Rigs」：Rigの設定内容が書かれたテキストファイル。記法としてJSON？
5. 「Setlists」：Setlist の設定内容が書かれたテキストファイル。JSON？
6. 「LockScreenLogo.png」
### 2-5.Looperのバッキングトラックmp3ファイルの追加方法
パソコンにつないで、MX5の「Looper」フォルダのなかにmp3ファイルなどを置くと、ルーパーで読み込んで再生できる。スマホなどをaux端子やBluetoothで接続するよりも手軽。  
なお、メトロノームやドラムマシンなどは内蔵されていない。  

## 3.音作り
### 3-1.音作りの進め方
1. 電源は、可能であればアースを取る。
2. ギターをつなぎ、「INPUT」でレベルメーターがクリップしないかみる。
3. アンプを選ぶ。Gainを上げすぎないように。
4. キャビシュミまたはIRを選ぶ。IRは、Gain を-10dB～-15dBぐらいで調整する。
5. アンプの前に歪み、IRの後ろにコーラスやリバーブを置く。Mixを下げ気味にして、うっすらかけるところから始める。
### 3-2.内蔵モデル
1. アンプ
2. キャビ
3. IR
4. エフェクター
5. FX Loop　（いわゆるセンドリターン）
### 3-3.HeadrushのホームページからサンプルRig 
サンプルRigには、ギターINPUTの「Gain」やIRの「Gain」をそれぞれ-10dB～-20dBぐらい下げないと、ノイジーなものがある。
### 3-4.アッテネーターとして使う
FX LOOP に、外部のアンプをつないで、MX5でGainや音量を調整すれば、いわゆる「アッテネーター」として使える。
## 4.演奏時の使い方
### 4-1.モードの種類
1. STOMPモード：3つのFSを、それぞれ、エフェクターなどのON/OFFか、またはSceneに割り当てる。Rigの切り替えは、FS2・FS3の同時押し等でやる。
2. Hybridモード：FS1にScene、Rigの切り替えをFS2・FS3に割り当てる。一番使い勝手が良いのではないか。
3. Rigモード：3つのFSに、それぞれRigが割り当てらる。選択したSetlistのなかで、順に3つずつのRigが割り当てられる。FS2・FS3同時押しで、次の3つのRigに切り替わる。
### 4-2.基本的な使い方
1. 使うRigでSetlistを作り、選択する。
2. モードを、Hybridモードなど、使いやすいモードに切り替える。
3. Rigごとに、FS1などに、Sceneなどを割り当てる。
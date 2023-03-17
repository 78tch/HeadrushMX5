# 
## Usage
### Sound Making
Rig（ユーザープリセット）を作る流れとしては、  
1. 前提として、各モデルを試す場合は、そのモデルの「プリセット」設定を呼び出して出音を確認するとよい。各モデルの設定は、個々のパラメーターを細かく数値設定することもできるが、いくつかの典型的な設定が「プリセット」として保存されているので、まずはそれを呼び出して試すと、キャラクターがはっきり切り替わるので、求めているものなのかの判断がしやすい。
2. 適宜、Headrush のHPなどから、IRを入手する。
3. アンプモデルのうち、「Fender（Deluxe Reverb や Twin Reverb）」「Marshall（Plexi や JCM800）」「Vox（AC30TB）」「Roland（JC-120）」の中からめぼしいアンプモデルを１つか２つ選んで、「アンプとIRだけ」というRig（ユーザープリセット）を「もとになった実機の名前」などで作る。ほかにも、気になるアンプモデルがあれば、同様にRigを作る。「Matchless（DC30）」「Orange（AD30HTC）」「Fender（Bassman）」「Soldano（SLO-100）」「Mesa/Boogie（Dual Rectifier）」「Peavey（5150 II ）」などが有名で、いい感じ。
4. 作ったRigを集めたSetlist を作る。
5. 聞き比べて、メインで使うRig を決めて、そのRigに、エフェクターを足していく。
6. エフェクターを足して、ある程度固まったら、そのRigのアンプモデルを替えてみて試す。
7. エフェクターの標準的な並びは、「ダイナミクス系（コンプなど）」->「フィルター（ワウ、ピッチシフターなど）」->「ボリュームペダル」->「ゲイン系（オーバードライブ、ディストーション、ファズなど）」->「モジュレーション系（フランジャー、フェイザー、コーラスなど）」->「タイムベース系（ディレイ、リバーブなど）」->「アンプ」->「キャビネット」となる。
8. エフェクターの配置手順としては、「ゲイン系をいろいろ試したり、切り替えたりする。」、「音作りの段階でモジュレーション系はいきなりは使わない。」、「調整が必要そうであれば、コンプやイコライザーなどを足すが、実際に大音量で鳴らしてみないことには、ヘッドホンや小音量ではバランスはわからないので、後回し」ということから、「まずアンプの前にリバーブを置き、ROOMなどを軽くかける。」
9. 好みで、リバーブの前にオクターバーを置き、うっすらかける。
10. 「ゲイン系のエフェクターをいくつか配置する。すべてを同時にONにするのではなく、適宜、どれかひとつをONにして、聞き比べる。」
11. 作ったユーザープリセットを、スタジオなどで大音量で鳴らし、微調整する。
12. 他のアンプモデルも、同様の流れで試す。「Matchless® DC30」とか「Peavey® 5150 II」とか。 
  
### アンプ・IR組み合わせ設定例）  
|No.|Maker|Amp|Amp Based on|IR|Cab Based on|
|---|---|---|---|---|---|
|1|Fender|67 BLACK DUO|Twin Reverb "Blackface"|TWIN2120B|Twin Reverb Open Back|
|2|Marshall|LEAD 800 100W|JCM800|60S412V|1960AV|
|3|VOX|66 AC Hi BOOST|AC30 Top Boost|FAWN212|AC30|
|4|Roland|84 J-120H|JC-120|||
|5|Matchless|93 MS30|DC30|||
|6|Orange|Tangerine 30 Channel 1|AD30HTC Clean Channel|TANGERINE2120B|PPC212 Open Back|
|7|Soldano|89 SL-100 CRUNCH|SLO-100 (Crunch)|||

### 各アンプ設定項目・設定値

|No.1|parameters|Default|Values|Memo|
|---|---|---|---|---|
|1|Fender||||
|2|67 BLACK DUO||||
|3|Twin Reverb "Blackface"||||
|4|VOLUME|50%|||
|5|BRIGHT|ON||高域を強調|
|6|VIBRATO|OFF|||
|7|TREBLE|50%|||
|8|MIDDLE|50%|||
|9|BASS|50%|||
|10|SPEED|7.00Hz||ビブラートの周期|
|11|INTENSITY|85%||ビブラートの大きさ|
|12|SYNC|OFF|||

|No.2|parameters|Default|Values|Memo|
|---|---|---|---|---|
|1|Marshall||||
|2|69 PLEXIGLAS 100W||||
|3|Super Lead Plexi 100W||||
|4|NORM VOL|50%|||
|5|HIGH VOL|50%|||
|6|PRESENCE|30%|||
|7|TREBLE|50%|||
|8|MIDDLE|50%|||
|9|BASS|50%|||
  
|No.3|parameters|Default|Values|Memo|
|---|---|---|---|---|
|1|Marshall||||
|2|82 LEAD 800 100W||||
|3|JCM800||||
|4|MAST VOL|50%|||
|5|PRE AMP|50%||プリを8マスターを7、両方フル|
|6|PRESENCE|30%|||
|7|BASS|50%|||
|8|MIDDLE|50%|||
|9|TREBLE|50%|||
  
|No.4|parameters|Default|Values|Memo|
|---|---|---|---|---|
|1|VOX||||
|2|66 AC HI BOOST||||
|3|AC30 TB||||
|4|NORM VOL|50%|||
|5|BRILL VOL|50%|||
|6|TREMOLO|OFF|||
|7|TREBLE|50%|||
|8|CUT|0%||高音を削ぐ|
|9|BASS|50%|||
|10|SPEED|7.00Hz||トレモロの周期|
|11|DEPTH|85%||トレモロの深さ|
|12|SYNC|OFF|||
  
|No.5|parameters|Default|Values|Memo|
|---|---|---|---|---|
|1|Matchless||||
|2|93 MS-30||||
|3|DC30||||
|4|VOLUME|50%|||
|5|MAST VOL|50%|||
|6|TREBLE|50%|||
|7|CUT|0%|||
|8|BASS|50%|||
  
|No.6|parameters|Default|Values|Memo|
|---|---|---|---|---|
|1|Roland||||
|2|84 J-120H||||
|3|JC120||||
|4|DIST|0%|||
|5|VOLUME|50%|||
|6|HI-TREBLE|50%|||
|7|TREBLE|50%|||
|8|MID|50%|||
|9|BASS|50%|||
|10|REVERB|65%|||
|11|CHORUS|MANUAL|||
|12|RATE|20%|||
|13|DEPTH|30%|||
|14|STEREO|ON|||

### Training
バッキングトラックのmp3ファイルを、「Looper」フォルダに入れる。Looperでファイルを読み込み、鳴らしながら練習する。  
MX5にはメトロノームやドラムマシン機能はないが、「メトロノーム音の音声ファイル」などを取り込んで置くことで、鳴らしながら演奏できる。
### Playing
モードとしては、STOMPモードもしくはHybridモードが使いやすいと思われる。
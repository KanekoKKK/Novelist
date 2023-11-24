# 小説家プロトタイプ

## 作成イメージ
全体イメージやを作るのは難しいため、各Sceneごとに作り、最後につなげます.  
全体的に、自然をモチーフとして作ります。  
細かい調整は後回しにし、各Sceneにおける基本のようなものができるのが目標です。  
planeの大きさを変更したり、自由に作っていいです  
インポートしたAssetsはObjectsに入れておいてください(あまり仕様がわかっていない)  
床や壁は作っても作らなくてもいいです  
分かっていないことが多すぎて、とりあえず何か作ってもらいたいです。  

## Scene説明
### 伊東(BookScene)
本棚やソファを置き、リラックスできるスペース
### 大西(SoroScene)
一人用スペース（カウンター）
### 乙守(PriveteScene)
グループ用個室
### 金子(BasisScene)
全体及び小さなオブジェクト
### 後藤(ShopScene)
注文・受け取り口などのお店の部分
### 鈴木(StageScene)
ステージとメインのテーブル

## 手順
手順が複雑なので、最初にcloneして、Unityを作り、pushなどはしなくても構いません  

### clone
GitHub Desktopのfileからclone repositoryでNovelistのクローンを作成する。  
赤い警告文が出てきた場合、ローカルレポジトリの名前をinitializeGitLFSのポップアップが出たら押す(よくわかっていない)

### blanch
githubのblanchの欄を開きnew blanchでblanchを作成する。(毎回必ず行う)  
名前は自分の名前+数字などにするとわかりやすい  
create branch based on...はmainにする  
current blanch が作成したblanchになっていればok  
(間違っても current blanch を main にしたまま進んではならない)
本来ははBranchからBranchを生やすが、main直下のものを作ってもよい  

### 作成
Unity hub を開き、「開く」から clone したファイル (Novelist) の中の  
「Novelist_Prototype」を選択する。  
そしてそれを開く。  
(バージョンは修正できているはずです)　
開くボタンを押し、自分の scene をひらく  
(File > Open Sceneフォルダの中、またはAssets > Scenesの中をダブルクリック)

### push
作業が終わったら、保存して Unity を終了する。(Unityを閉じていないとエラーが出る)  
Github Desktop にもどる。左下に空白の部分があるので、  
summary に名前、 descliption に説明を書く(適当でいい?)  
commit to (Branchの名前) を押す。  
github にno local change になっている  
さらに publish Branch を押すと  
変更結果が blanch に反映される  
(ブラウザ版を開くとわかる)

### (merge)
github にno local change になっている  
青いボタンの逆三角を押し create pull request を押す  
ページに飛ぶのでCompare & pull request(緑色)を押す  
そこからタイトルと説明を追加しcreate pull requestを押すとpull requestを送れる  
※その後の作業は金子が行います

### (削除)
何度もやるとフォルダがごちゃごちゃするため削除したほうが良いが、よくわかっていない  
ここまでやったらローカルのフォルダを消してよい  
mergeが完了したらBranchも削除する(よくわからないため要検証)  
わからなかったらそのままで良いが、毎回クローンしなおす  

## ディレクトリ構造(簡易)
```
Novelist
├─Novelist_Prototype
│   ├─Assets
│   │  ├─Objects //ダウンロードしたもの
│   │  │　├─Bar Chair
│   │  │　└─Table
|   |  | 
│   │  └─Scenes //シーン一覧
|   |    ├─BasisScene_Kaneko
|   |    ├─BookScene_Ito
|   |    ├─MainScene
|   |    ├─PrivateScene_Otomori
|   |    ├─ShopScene_Goto
|   |    ├─SoroScene_Onishi
|   |    └─StageScene_Suzuki
│   │
│   ├─Library //この下はいじらない
│   ├─Logs
│   ├─Packages
│   ├─ProjectSettings
│   ├─Temp
│   └─UserSettings
│
└─README.md
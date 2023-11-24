# Novelist
メモ

clone
githubのfileからclone repositoryでNovelistのクローンを作成する。

blanch
githubのblanchの欄を開きnew repositoryでblanchを作成する。
名前は自分の名前などにするとわかりやすい
current blanch が作成したblanchになっていればok
(間違っても current blanch を main にしたまま進んではならない)

作成1(開始)
unity hub を開き、「開く」から clone したファイル (Novelist) の中の
「Novelist_Prototype」を選択する。
そしてそれを開く。(バージョンについて聞かれたら現段階では自分のダウンロードしたバージョンで強行突破することになっている)

作成2(scene)
unityが開いたら、まずは scene を作成する。
Assets → create → scene から作成できる。名前は自由
あとは、その scene を開いた状態で作業する。

push
作業が終わったら、保存して unity を終了する。(ここ大事らしい)
github にもどる。左下に空白の部分があるので、
summary に名前、 descliption に説明を書く(適当でいい?)
commit to first を押す。さらに push origin (右上)を押すと
変更結果が blanch に反映される
(ブラウザ版を開くとわかる)

(マージ)
github にno local change になっている
青いボタンの逆三角を押し create pull request を押す
ページに飛ぶのでそこからタイトルと説明を追加しrequestを送れる
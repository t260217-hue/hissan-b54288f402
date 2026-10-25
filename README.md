# ひっさんの れんしゅう(GitHub Pages 公開用)

このフォルダの `index.html` 1つだけで動きます。

## 検索に出にくくするための設定(済み)
- `index.html` に「検索エンジンに載せない」設定(`noindex`)を入れています。
- 外部(フォント)を読み込むときに、このページのURLを相手に伝えない設定(`no-referrer`)も入れています。

## 公開の手順
1. GitHub で新しいリポジトリを作る。
   - 名前は推測されにくいものにする(例：`hissan-b54288f402`)。
   - 「Public」を選ぶ(無料プランの GitHub Pages は Public リポジトリで使う)。
   - README などの追加は不要。
2. 「Add file」→「Upload files」で `index.html` をアップロードし、「Commit changes」。
3. 「Settings」→「Pages」で、Source を「Deploy from a branch」、Branch を「main」「/(root)」にして「Save」。
4. 1〜2分待つと、`https://ユーザー名.github.io/リポジトリ名/` で開けるようになる。このURLを子どもに配る。

## 注意
- リンクを知っている人は誰でも開けます(本当の意味での限定公開ではありません)。
- Public リポジトリは GitHub の中では見つかることがあります。リポジトリの説明欄やトピックには何も書かないでおくと、見つかりにくくなります。
- `robots.txt` で検索エンジンを止める方法は使わないでください。検索エンジンが `noindex` を読めなくなり、かえってURLだけが載ることがあります。
- アプリを直したときは、新しい `index.html` を同じ場所にアップロードして上書きします。

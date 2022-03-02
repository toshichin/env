# TIPS for software engineers
プログラミングに関する様々なtips

新しい順に記載する。
集中して調べたことは個別のファイルに記載する。

## [VScode]preview style for Markdown
[VSCodeのmarkdownプレビューの背景色・見出しなどを見やすく拡張機能](https://creating-homepage.com/archives/9189)
Markdown-preview-enhancedを使っているので、設定だけで変更できた。

GitHubのCSSを使う方法は下記のサイトなどを参照。
[vscodeのmarkdown css変更メモ](https://qiita.com/hirodona78/items/1734abce33288cc200c8)

## DBeaver
SQLクライアント。
### インストール
homebrewを使う。
```
$ brew install --cask dbeaver-community
```

## pyenvでバージョンが変わらない
[pyenvでPythonのバージョンが切り替わらないときの対処方法【M1 Mac環境】](https://hitori-sekai.com/python/error-pyenv/)

## .DS_Storeが邪魔  
以下を参照。
[すべてのリポジトリで .DS_Store を gitignore する方法](https://zenn.dev/phi/articles/gitignore-global-ds-store)

## VSCodeでバッククォートがちゃんと表示できない
以下を参照に設定した。
コマンドが一部異なるから、こちらを実行すること。
```
$ brew install --cask fontforge
...
$ find . -name '*.ttf' | xargs -I {} fontforge -lang ff -script ~/Developer/env/scripts/fontforge/script {}
```
[VSCodeのフォントでバッククオートが表示されない](https://blog.beaglesoft.net/entry/2021/02/21/144148)

## update homebrew
`$ brew update`



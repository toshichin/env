# env
settings for my personal environment as a developer

## prezto
zsh周りはpreztoで整備する。
[Macのzsh+Prezto環境を整える](https://qiita.com/Holoyu/items/bccc4901f6a9d1eb58ff)

## scripts
開発環境整備に使うスクリプト群を格納する。

### fontforge
VSCodeのback quote対策に使う。
詳細はtips.mdを参照のこと。

## Python
- pyenv + venv
- Pythonのバージョンは~/Developerで指定する。
現在の基本バージョンはPython 3.9.2を使う。
プロジェクトやお試しで必要に応じて変更する。
### 仮想環境
- ./venvに仮想環境を作成する。
- インストール済みのライブラリは./requirements.txtに記載した。
- aliasのpydefaultで仮想環境を使用できる。

## Docker
開発で共通に使用するdockerを配置する。
### MySQL
DB関係の技術の勉強に使う。
ディレクトリは以下の通り。
docker
 -mysql
  -data
  -logs
  -init


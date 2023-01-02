# TypeScript ✖️　フロントのシンプルな開発環境

## 注意

- .tsファイルをimportする場合でも.jsを読む
  - 拡張子を省略したり.tsとするとブラウザでは読めない
  - .jsを読んでも.tsを読むように置き換えてくれる
  - https://qiita.com/uhyo/items/22d851c3cbd2570864ce
- HTMLで読み込むscriptタグにはtype="module"が必要
- VSCodeのTSではなくインストールしたTypeScriptのバージョンを使う
  - .vscode/settings.jsonがソレ
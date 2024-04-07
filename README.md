# typst-jp-conf-template

Typst で日本語論文を書くときのテンプレートです．

[vscode-typst.webm](https://github.com/kimushun1101/typst-jp-conf-template/assets/13430937/f227b85b-0266-417b-a24a-54f28f9a71b8)

| ファイル  | 意味                      |
| --------- | ------------------------- |
| main.typ  | 原稿の Typst ソースコード |
| refs.\*　 | 参考文献ファイル          |

| ディレクトリ | 含まれるファイルの種類         |
| ------------ | ------------------------------ |
| figs 　　    | 論文に使用する画像ファイル     |
| libs 　　    | 体裁を整えるライブラリファイル |

## 使用方法

1. Run

   ```
   typst compile main.typ
   ```

### VS Code を使用する場合

1. [VS Code](https://code.visualstudio.com/) をインストール．
1. VS Code で `File`→`Open Folder` でこのフォルダーを開く．
1. 推奨拡張機能をインストール．  
   Extensions (`Ctrl` + `Shift` + `X`) の `Search Extensions in Marketplace` のテキストボックスに `@recommended` と入力すると表示される，以下の拡張機能を install をクリック．
   - [Typst LSP](https://marketplace.visualstudio.com/items?itemName=nvarner.typst-lsp)
   - [Typst Preview](https://marketplace.visualstudio.com/items?itemName=mgt19937.typst-preview)
   - [Tasks Shell Input](https://marketplace.visualstudio.com/items?itemName=augustocdias.tasks-shell-input)
1. Explorer (`Ctrl` + `Shift` + `E`) から `main.typ` を開いた状態で，画面右上にある Typst Preview の方の ![view-icon](https://github.com/kimushun1101/typst-jp-conf-template/assets/13430937/a44c52cb-d23a-4fdb-ac9f-dc2b47deb40a) アイコンをクリック (
   `Ctrl` + `K` のあと `V`) でプレビューを表示．
1. `Ctrl` + `S` で PDF を生成．

## 参考元

- (unofficial) IFAC Conference Template for Typst : https://github.com/typst/packages/tree/main/packages/preview/abiding-ifacconf/0.1.0
- charged-ieee : https://github.com/typst/packages/tree/main/packages/preview/charged-ieee/0.1.0
- IEEE style as per the 2021 guidelines, V 01.29.2021. : https://editor.citationstyles.org/styleInfo/?styleId=http%3A%2F%2Fwww.zotero.org%2Fstyles%2Fieee
- GitHub Pages へのデプロイ : https://github.com/yukukotani/typst-coins-thesis

## ライセンス

参考元にならってライセンスを付与しています．  
Typst ファイル : MIT No Attribution  
CSL ファイル : Creative Commons Attribution-ShareAlike 3.0 License

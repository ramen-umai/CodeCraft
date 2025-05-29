# CodeCraft

CodeCraftは、**Blockly**を利用したビジュアルプログラミング言語です。

## 概要

CodeCraftは、ブロックを組み合わせて直感的にプログラミングができるビジュアルプログラミング環境です。  
Blocklyをベースにしており、初心者や教育現場でも使いやすい設計となっています。

## デモ・公開ページ

[CodeCraft デモサイト（GitHub Pages）](https://ramen-umai.github.io/codecraft/)

上記URLから、インストール不要ですぐにお試しいただけます。

## 主な特徴

- 直感的なブロック操作によるプログラミング
- ビジュアルでコードの流れを理解しやすい
- 拡張が容易な設計

## ローカルでの開発

1. このリポジトリをクローンします。

   ```sh
   git clone https://github.com/ramen-umai/codecraft.git
   ```

2. 必要な依存パッケージをインストールします。

   ```sh
   npm install
   ```

3. 開発サーバーを起動します。

   ```sh
   npm start
   ```

4. ブラウザで `http://localhost:3000` にアクセスします。

## GitHub Pagesによる公開方法（参考）

- 本プロジェクトは、`docs` ディレクトリ配下のファイルをGitHub Pagesで公開しています。
- 公開内容を変更する場合は、`docs` ディレクトリ内のファイルを編集し、`main`ブランチへpushしてください。

## 謝辞

- [Google Blockly](https://developers.google.com/blockly)
- [Google Forms](https://www.google.com/forms/about/)
  
CodeCraftの開発にあたり、Googleおよび関連プロジェクトの皆様に感謝いたします。

## ライセンス

本プロジェクトはMITライセンスのもとで公開されています。詳細は[LICENSE](./LICENSE)をご覧ください。

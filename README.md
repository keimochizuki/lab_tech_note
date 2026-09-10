このリポジトリは、
実験研究者である筆者（[望月 圭](https://researchmap.jp/keimochizuki)）
が所属研究室において担っている技術事項を、
記録・共有するための文書置き場です。
主として筆者の同僚に対してのドキュメントですが、
閲覧上の利便性と、
ワンチャンどこかの誰かの役に立ったらいいなという期待を込めて、
GitHub Pages上で公開しています。

## 作成の意図

ここに示す内容の多くは従来筆者がカバーしてきましたが、
その代償として、技術の属人化が深刻化してきました。
そうした研究上の技術的ブラックボックスを解消する取り組みとして、
本ドキュメントの作成と公開を思い立ちました。

日常業務のなかでの執筆・メンテナンスの容易さを重視し、
文書形式はLaTeXやhtmlではなくMarkdownを採用しました。
当初はそのmdファイルを、
研究室内で共有するかたちを想定していました。
しかし、実際に共用PCにファイルを置いてみても、
閲覧のたびいちいちPCを起動するのはクソ面倒でした。
筆者としても、
ちょっとした改訂のたびに共用PCを操作するのは苦痛で、
すぐにやらなくなる未来が想像できました。

考えてみれば、結局、
アクセス性という点でネットに敵う方法はありません。
ということで、次にresearchmapやQiita、
あるいは研究室のウェブサイト内での公開を検討しはじめました。
そのなかで、GitHub上のmdファイルを自動的にhtmlにして公開する
GitHub Pagesというしくみを（恥ずかしながら）はじめて知りました。
Markdownを採用した理由のひとつでもあるmermaidも、
ウェブ上のありがたい情報により、
ちょっとしたJavaScript追加で利用できるようになりました。

一日がかりの試行錯誤になりましたが、
ひとまず執筆・更新体勢が整い、
読めるかたちの文章がGitHub Pagesに置けるようになりました。
手探りながら、とりあえずはこのしくみをつかって、
筆者のもつ技術情報の整理と発信を試みてみたいと思います。

## コンテンツ

- [実験屋の逆引き器械工作辞典](docs/crafting_lookup.md)

## コピーライト

本ドキュメントの内容は、
クリエイティブ・コモンズ・ライセンス 表示-非営利-継承 4.0 国際
（[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)）
として公開しています。
コモンズ証の定める条件にしたがう限り、
読者は自由に上記コンテンツの内容を複製したり、
改変して再利用したりすることができます。

## 参考にした文献

- [GitHub Pagesで、Markdownのメモをブログのように公開する](https://qiita.com/c3drive/items/f9b4d9497c588049d65c)
- [Markdownで書かれたページをGitHub Pagesで公開する](https://yoshikyoto.github.io/text/git/gh_pages_md.html)
- [What is GitHub Pages?](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)
- [Jekyll Slate theme](https://github.com/pages-themes/slate)
- [GitHub PagesでMermaid図をレンダリング可能にする #35](https://github.com/lurest-inc/github-projects-ops-kit/issues/35)
- [GitHub Pages（Jekyll）でMermaid図を表示する方法](https://qiita.com/ctrl_bug/items/0198a4feb71dd8677f67)


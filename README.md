このリポジトリは、
所属研究室において筆者（[望月 圭](https://researchmap.jp/keimochizuki)）
が担っている技術事項を、
記録・共有するための文書置き場です。

## 作成の意図

ここに示す内容の多くは従来筆者がカバーしてきましたが、
その代償として属人化が深刻化してきました。
そうした技術の属人化を解消する取り組みとして、
本ドキュメントの作成と公開を決断しました。

日常業務のなかでの執筆・メンテナンスの容易さを重視し、
文書形式はLaTeXやhtmlではなくMarkdownを採用しました。
当初はそのmdファイルを、
研究室内で共有するかたちを想定していました。
しかし、実際に共用PCにファイルを置いてみても、
閲覧のたびいちいちPCを起動するのはクソ面倒でした。
筆者としても、
ちょっとした改訂のたびにPC間でファイルをやりとりするのは苦痛で、
すぐにやらなくなる未来が想像できました。

結局、アクセス性という点でネットに敵う方法はありません。
最初はresearchmapやQiita、
あるいは研究室のウェブサイト内で公開することも検討しました。
そのなかで、GitHub上のmdファイルを自動的にhtmlにして公開する
GitHub Pagesというしくみを（恥ずかしながら）初めて知りました。
Markdownを採用した理由のひとつでもあるmermaidも、
ウェブ上のありがたい情報のおかげで、
ちょっとした試行錯誤で利用できるようになりました。
手探りながら、とりあえずはこのしくみをつかって、
筆者のもつ技術情報の整理と発信を試みてみたいと思います。

### 参考にした文献

- [GitHub Pagesで、Markdownのメモをブログのように公開する](https://qiita.com/c3drive/items/f9b4d9497c588049d65c)
- [Markdownで書かれたページをGitHub Pagesで公開する](https://yoshikyoto.github.io/text/git/gh_pages_md.html)
- [What is GitHub Pages?](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)
- [Jekyll Slate theme](https://github.com/pages-themes/slate)
- [GitHub PagesでMermaid図をレンダリング可能にする #35](https://github.com/lurest-inc/github-projects-ops-kit/issues/35)
- [GitHub Pages（Jekyll）でMermaid図を表示する方法](https://qiita.com/ctrl_bug/items/0198a4feb71dd8677f67)


## コンテンツ

- [実験屋の逆引き器械工作辞典](docs/crafting_lookup.md)


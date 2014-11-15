//////////////////////////
# Contributing to Pro Git (2nd Edition)
//////////////////////////
# Pro Git第2版へのコントリビューション

//////////////////////////
## Licensing
//////////////////////////
## ライセンス

//////////////////////////
By opening a pull request to this repository, you agree to provide your work under the [project license](LICENSE.asc).
Also, you agree to grant such license of your work as is required for the purposes of future print editions to @ben and @schacon.
Should your changes appear in a printed edition, you'll be included in the [contributors list](book/contributors.asc).
//////////////////////////
このリポジトリへプルリクエストをおこなった場合、[プロジェクトのライセンス](LICENSE.asc) に同意したものとみなします。
また、あなたの貢献を今後の出版物に用いるとき、@ben と @schacon にそのライセンスを付与することにも同意したものとみなします。
あなたが加えた変更が出版物に掲載される場合、[貢献者リスト](book/contributors.asc) に名前が掲載されます。

//////////////////////////
## Small Corrections
//////////////////////////
## 軽微な修正

//////////////////////////
Errata and basic clarifications will be accepted if we agree that they improve the content. You can also open an issue so we can figure out how or if it needs to be addressed.
//////////////////////////
誤字脱字修正や基本的な説明の追加を受理する前に、それらが本の内容をよりよくするかどうか合意する必要があります。議論のためのissueをたてて、どのように対処すべきか、そもそも対処すべきなのか話し合ってもかまいません。

//////////////////////////
If you've never done this before, the [flow guide](https://guides.github.com/introduction/flow/) might be useful.
//////////////////////////
こういったことを一度もやったことがないのなら、[進め方のガイド](https://guides.github.com/introduction/flow/) が役に立つかもしれません。

//////////////////////////
## Large Rewrites
//////////////////////////
## 大幅な書き換え

//////////////////////////
Open an issue for discussion before you start. These changes tend to be very subjective, often only clarifying things for some small percentage of people and it's rarely worth the time to accept them. Professional copy editors have already reviewed this content multiple times so while you may have somewhat better taste and grammar than we do it's unlikely that your prose is going to be *so* much better that it's worth changing vast swaths of text.
//////////////////////////
議論するために、まずはissueをたててください。この類の変更はとても主観的になりがちで、変更によって理解が容易になるのはごく一部の読者だけのこともあります。つまり、大幅な書き換えを受理するメリットは少ない、ということです。
すでに、プロの編集者が幾度にもわたりこの本の内容を査読しています。仮にあなたの文章のほうが魅力的で文法が正確だったとしても、この本の文章より *はるかに* いい、一連の文章は変更するに値する、ということはまれでしょう。

//////////////////////////
## Figures
//////////////////////////
## 図

//////////////////////////
The images in this book were generated using [Sketch 3](http://bohemiancoding.com/sketch/), with the [included sketchbook file](diagram-source/progit.sketch).
//////////////////////////
この本で使われている図は [Sketch 3](http://bohemiancoding.com/sketch/) で作成しました。
このリポジトリには、[Sketchのファイルが含まれています](diagram-source/progit.sketch)。

//////////////////////////
To add a figure:
//////////////////////////
図を追加するには、

//////////////////////////
1. Add a page to the sketchbook. Try to use the included symbols wherever possible.
1. Add a "slice" to your page. Give it a name that matches the destination PNG filename, relative from the root of the source directory.
1. Make sure your slice is set to export at 3x size.
//////////////////////////
1. スケッチブックにページを追加します。可能な限り、同梱されているシンボルを使うようにしてください。
1. ページに「スライス」を追加します。エクスポートするPNGのファイル名（ソースディレクトリからの相対パスを含む）をスライスの名前にしてください。
1. スライスをエクスポートするときは3倍に拡大してください。

//////////////////////////
## Translations
//////////////////////////
## 翻訳

//////////////////////////
Translations to other languages are highly encouraged but handled a little differently than the first edition. We now keep each translation in a separate repository and automatically build the output files through Atlas. This was something that was really difficult in the last edition.
//////////////////////////
他言語への翻訳は大歓迎です。ただし、第1版のときとはやり方を変えました。今回は、言語ごとにリポジトリを用意し、Atlasを使ってファイルを自動生成します。ファイルの自動生成は、第1版のときはとても難しかったのです。

//////////////////////////
Since each translation is a different repository, we can also have different maintainers for each project. The Pro Git team simply pulls them in and builds them for the translation teams. To get automatic builds, translations repositories will have to be under the [`progit` organization on GitHub](https://github.com/progit).
//////////////////////////
更に、リポジトリを言語ごとにわけたので、メンテナも言語ごとに指名することができるようになりました。Pro Gitチームは翻訳チームに代わって、各リポジトリのデータをプルしデータをビルドします。自動ビルドの対象に加わるには、翻訳用リポジトリは [GitHub の`progit` オーガニゼーション](https://github.com/progit) 配下に設置する必要があります。

//////////////////////////
You can find out information on all the current translations and information on how to start your own at http://progit.org/translations.
//////////////////////////
既存の翻訳についての情報、新たな言語での翻訳の始め方は http://progit.org/translations で確認できます。

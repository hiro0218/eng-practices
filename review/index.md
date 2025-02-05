# コードレビュー開発者ガイド

## 序論 {#intro}

コードレビューとは、コードの著者以外の誰かがそのコードを詳しく調べるプロセスです。

Googleでは、コードと製品の品質を維持するためにコードレビューを使用しています。

この文書は、Googleのコードレビューのプロセスとポリシーの正式な説明です。

このページは、コードレビュープロセスの概要です。このガイドには他にも2つの大きな文書が含まれています：

-   **[コードレビューのやり方](reviewer/index.md)**：コードレビュアー向けの詳細なガイド。
-   **[CL著者のガイド](developer/index.md)**：レビュー中のCLを持つ開発者向けの詳細なガイド。

## コードレビュアーは何を見るべきか？ {#look_for}

コードレビューでは、以下の点に注意する必要があります：

-   **設計**：コードはよく設計されており、システムに適していますか？
-   **機能性**：コードは著者が意図した通りに動作しますか？コードの動作は、そのユーザーにとって良いものですか？
-   **複雑性**：コードをよりシンプルにできますか？未来にこのコードに遭遇した別の開発者は、簡単に理解し使用できますか？
-   **テスト**：コードには正確でよく設計された自動テストがありますか？
-   **命名**：開発者は変数、クラス、メソッドなどに明確な名前を選びましたか？
-   **コメント**：コメントは明確で有用ですか？
-   **スタイル**：コードは我々の[スタイルガイド](http://google.github.io/styleguide/)に従っていますか？
-   **文書化**：開発者は関連する文書も更新しましたか？

詳細については、**[コードレビューのやり方](reviewer/index.md)**を参照してください。

### 最適なレビュアーの選び方 {#best_reviewers}

一般的に、合理的な時間内にレビューに対応できる*最良*のレビュアーを見つけることが望ましいです。

最良のレビュアーとは、書いたコードに対して最も徹底的かつ正確なレビューを提供できる人物です。
通常、これはコードのオーナーであり、OWNERSファイルに記載されている人物である場合もあり、ない場合もあります。
場合によっては、CLの異なる部分を異なる人々にレビューしてもらうことがあります。

理想的なレビュアーが見つかったが利用できない場合は、少なくともその人物をCCに追加するべきです。

### 対面でのレビュー（およびペアプログラミング） {#in_person}

資格のある人物とペアプログラミングでコードを書いた場合、そのコードはレビューされたとみなされます。

対面でのコードレビューも行うことができ、レビュアーが質問をし、変更の開発者が質問されたときにのみ発言します。

## 参照 {#seealso}

-   [コードレビューのやり方](reviewer/index.md)：コードレビュアー向けの詳細なガイド。
-   [CL著者のガイド](developer/index.md)：レビュー中のCLを持つ開発者向けの詳細なガイド。

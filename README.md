# intellij-scala-project-settings
このリポジトリはIntelliJのScalaプロジェクト向けのインジェクション/コードスタイル設定です。
これを使うことでそのプロジェクトを開発するチーム内のインジェクション/コードスタイル設定を同期することができます。

# 対象の環境

* IntelliJ IDEA 14.X + Scalaプラグイン
* OSは問わない

# 使い方
1. build.sbtを記述
2. ```cd $PROJECT_ROOT```
3. ```git submodule add https://github.com/bigwheel/intellij-scala-project-settings.git .idea```
4. Intellijの"Import Project"を行い、仮の.ideaディレクトリと設定ファイルを作成
5. 一度IntellijをClose
6. ```git submodule update --init```
7. 再度IntellijでプロジェクトをOpen

# ライセンスについて
このリポジトリはCC0 1.0です。あなたが望むどのような形でも使ってもOK

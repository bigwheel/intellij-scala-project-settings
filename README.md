# intellij-scala-project-settings
このリポジトリはIntelliJのScalaプロジェクト向けのインジェクション/コードスタイル設定です。
これを使うことでそのプロジェクトを開発するチーム内のインジェクション/コードスタイル設定を同期することができます。

# 対象の環境

* IntelliJ IDEA 14.X + Scalaプラグイン
* OSは問わない

# 使い方
1. ```cd $PROJECT_ROOT```
2. (すでにプロジェクト設定が存在していれば)```mv .idea .idea.bk```
3. ```git submodule add https://github.com/bigwheel/intellij-scala-project-settings.git .idea```
4. ```git submodule update --init```
5. IntelliJ IDEAのWelcomeダイアログ → Import Projectからプロジェクト設定を作成(Openから開かないよう注意)

# 注意点
すでにプロジェクト設定(.idea)が存在する状態でこのリポジトリをcloneしたときに
正しく設定が反映されるかは不定です(.idea内の設定ファイルなどに依存するため)

# ライセンスについて
このリポジトリはパブリックドメインです。あなたが望むどのような形でも使ってもOK

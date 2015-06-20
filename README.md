# intellij-scala-project-settings
このリポジトリはIntelliJのScalaプロジェクト向けのインジェクション/コードスタイル設定です。
これを使うことでそのプロジェクトを開発するチーム内のインジェクション/コードスタイル設定を同期することができます。

# 対象の環境

* IntelliJ IDEA 14.X + Scalaプラグイン
* OSは問わない

# 使い方
1. build.sbtを記述
2. intellijの"Import Project"を行い.ideaディレクトリと仮の設定ファイルを作成
3. ```cd $PROJECT_ROOT```
4. ```git submodule add https://github.com/bigwheel/intellij-scala-project-settings.git .idea```
5. ```git submodule update --init```

# ライセンスについて
このリポジトリはCC0 1.0です。あなたが望むどのような形でも使ってもOK

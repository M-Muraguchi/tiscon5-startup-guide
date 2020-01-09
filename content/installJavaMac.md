# Javaのインストール(Mac)

## 前提条件

なし

## インストール

下記のサイトを参考に、**AdoptOpenJDK11（JDK11）のインストール**を行って下さい。

> **注意点**<br>
> 2020年1月8日現在では JDK11では、jdk-11.0.5+10 が最新です。

[【AdoptOpenJDK11（JDK11）インストール手順＜macOS向け＞
2019年10月9日](https://sukkiri.jp/technologies/processors/jdk/adoptopenjdk11-mac_install.html)

## インストールできたら

[Terminalを起動](tipsForMac.md#terminalの起動方法) して
```sh
> java -version
openjdk 11.0.5 2019-10-15
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.5+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.5+10, mixed mode)
```
というように `java` コマンドが動くことが確認できればOKです。

またこの時、`java -version`で表示されたバージョンが、自分がインストールしたJavaのバージョンと一致していることを確認してください。

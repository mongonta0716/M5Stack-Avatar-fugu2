# M5Stack-Avatar-fugu2

M5Stack Avatarのフグバージョン2です。

Avatar表示は、robo8080さんの[M5Stack_WebRadio_Avator](https://github.com/robo8080/M5Stack_WebRadio_Avator)をベースにさせていただきました。
M5Stack-avatarのオリジナルはmeganetaaanさんの[m5stack-avatar](https://github.com/meganetaaan/m5stack-avatar)です。

背景にJPGファイルを利用したかったのでm5stack-avatarの古いバージョンを利用しています。

# [M5Stack-Avatar-fugu1](https://github.com/mongonta0716/M5Stack-Avatar-fugu1)との違い
JPGデータを内部に持つようにしました。
伸び縮み機能も追加する予定です。

## JPGデータの変換について
変換前のデータはjpgフォルダにあります。
下記リンクにあるbin2code.pyを使用するとcのコードに変換できます。
https://github.com/m5stack/M5Stack/tree/master/tools

# 使い方(Usage)

buildフォルダ配下にあるAvatar_fugu2.bin,jpgフォルダ,jsonフォルダをmicroSDカードのルート上にコピーして、
[M5Stack LovyanLauncher](https://github.com/lovyan03/M5Stack_LovyanLauncher)から起動します。

ボタンBを押すと水を吐きます。

LovyanLauncherの詳しい使い方は下記のブログにて解説しています。

[M5Stack LovyanLauncherの使い方｜ラズパイ好きの日記](https://raspberrypi.mongonta.com/howto-use-m5stack-lovyanlauncher/)

# Requirement

コンパイルする場合は、以下のライブラリが必要です。
* [M5Stack-SD-Updater](https://github.com/tobozo/M5Stack-SD-Updater)

# Licence
[GPLv3](https://github.com/mongonta0716/M5Stack-Avatar-fugu1/blob/master/LICENSE)

# Author

[Takao Akaki](https://twitter.com/mongonta555)

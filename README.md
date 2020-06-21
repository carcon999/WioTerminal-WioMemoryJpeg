# WioTerminal-WioMemoryJpeg

プログラム中に予めJpegデータ（constのROMデータ）を配置し、それをWioTerminalのLCDに表示するプログラムです。
SDカードから読み込む必要が無いので、SDカードが無い環境でも画像表示させることが可能です。

![Image](https://github.com/carcon999/WioTerminal-WioMemoryJpeg/blob/master/img/DSC00033.JPG)

プログラム中に、const定義でデータを記述する必要があるので、Jpeg画像からコードを生成するプログラムも作りました。
[こちら](https://wioterminal.s3-ap-northeast-1.amazonaws.com/index.html)のサイトで生成可能です。

Jepgの表示は、こちらの高速描画可能な[LovyanGFX](https://platformio.org/lib/show/7359/LovyanGFX)を利用しています。
※素敵なライブラリをありがとうございます。

表示される画像は、[公式サイト](https://wiki.seeedstudio.com/Wio-Terminal-Getting-Started/)で公開されているWio-Terminalちゃんを使わせていただいております。

![Image](https://github.com/carcon999/WioTerminal-WioMemoryJpeg/blob/master/img/wio.jpg)


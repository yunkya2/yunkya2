### X68000 関連

#### プログラミング言語
* [MicroPython for X68000](https://github.com/yunkya2/micropython-x68k) - X68000用MicroPython
  * [ダウンロード](https://github.com/yunkya2/micropython-x68k/releases)
  * [X68000版ドキュメント](https://github.com/yunkya2/micropython-x68k/blob/port-x68k/ports/x68k/README.md)

#### 開発環境
* (Qiita)[X68000の開発環境について](https://qiita.com/yunkya2/items/a02d04e9157b1e797983)
* (Qiita)[macOSで始めるX68000開発環境構築](https://qiita.com/yunkya2/items/2a3bf750a7b578d282dc)
* [elf2x68k](https://github.com/yunkya2/elf2x68k) - X68kクロス開発環境
  * [ダウンロード](https://github.com/yunkya2/elf2x68k/releases)
* [gdbserver-x68k](https://github.com/yunkya2/gdbserver-x68k) - クロス開発環境用リモートデバッガ
  * [ダウンロード](https://github.com/yunkya2/gdbserver-x68k/releases)
* [bas2c](https://github.com/yunkya2/bas2c-x68k) - X-BASIC to C コンバータ (Python 版 & C++ 版)
  * (Python 版はクロス開発環境 elf2x68k に含まれています)
  * [C++ 版ダウンロード](https://github.com/yunkya2/bas2c-x68k/releases) (X68k 実機/エミュレータ上で動作して BC.X の代わりに使用できます)
  * [C++ 版ドキュメント](https://github.com/yunkya2/bas2c-x68k/blob/main/README-bas2c.txt)
 
#### ツール
* [x68kserremote](https://github.com/yunkya2/x68kserremote) - シリアルポートを使ってX68000からWindowsファイルシステムをアクセス
  * [ダウンロード](https://github.com/yunkya2/x68kserremote/releases)
* [history-bc](https://github.com/yunkya2/x68kmisc/tree/main/history-bc) - ヒストリドライバ HISTORY.X を bash ライクなキーバインド、ファイル名補完に改造
  * [ダウンロード](https://github.com/yunkya2/x68kmisc/raw/main/history-bc/history-bc.zip)
* [loopdrv](https://github.com/yunkya2/loopdrv-x68k) - ループバックデバイスドライバ
  * [ダウンロード](https://github.com/yunkya2/loopdrv-x68k/releases)
* [xdftool.py](https://github.com/yunkya2/x68kmisc/tree/main/xdftool) - XDF ファイル操作ツール
* [auxtap](https://github.com/yunkya2/auxtap) - シリアルポートからの入力をキー入力に変換するツール
  * [ダウンロード](https://github.com/yunkya2/auxtap/releases)

#### X68000 Z
* [x68kzremotedrv](https://github.com/yunkya2/x68kzremotedrv) - Raspberry Pi Pico Wを使ってX68000 ZからWindowsファイルシステムをアクセス
  * [ダウンロード](https://github.com/yunkya2/x68kzremotedrv/releases)
* [X68000ZキーボードLED制御(pyUSB)](https://github.com/yunkya2/x68kzkbd-pyusb) - X68000 ZのキーボードLEDをpyUSBを使ってPCから制御
* [X68000ZキーボードLED制御(ラズパイPico)](https://github.com/yunkya2/x68kzkbd-pico) - X68000 ZのキーボードLEDをラズパイPicoから制御

#### エミュレータ関連
* [WindrvXM埋め込みSCSI HDDイメージ](https://github.com/yunkya2/windrvxm-boot) - XM6 TypeG等のエミュレータでホストファイルシステム起動を実現
  * [ダウンロード](https://github.com/yunkya2/windrvxm-boot/releases) 

#### その他
* [sectorc68k](https://github.com/yunkya2/sectorc68k) - 「ブートセクタに収まるCコンパイラ」sectorcのX68k版

### その他レトロPC関連
* [ttymz80](https://github.com/yunkya2/ttymz80) - ターミナル上で動作する MZ-80K/C & MZ-700 エミュレータ
* [FD BOOT selector](https://github.com/yunkya2/mz80kmisc/tree/main/fdbootsel) - MZ-80K/C 用 FD ブートセレクタ
* [unlha](https://github.com/yunkya2/unlha) - Python 版 LZH アーカイブ展開ツール

### Raspberry Pi Pico 関連
* [pico-mdx](https://github.com/yunkya2/pico-mdx) - ラズパイPicoで動作するMDXファイルプレイヤー
  * (Qiita)[Raspberry Pi Pico Audio PackでX68000のMDXファイルを再生する](https://qiita.com/yunkya2/items/da423a2bee0266fbec44)
  * (Qiita)[Raspberry Pi PicoのBOOTSELボタンを使ってMDX playerを制御する](https://qiita.com/yunkya2/items/e415eed7b3bf4b637201)
* [Raspberry Pi Pico Sample application with FreeRTOS](https://github.com/yunkya2/pico-freertos-sample) - ラズパイPico上で動作するFreeRTOSサンプル (古いです)


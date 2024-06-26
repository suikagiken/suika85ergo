# suika85ergo
(English Follows Japanese)

## 概要
![suika85ergo](img/suika85ergo_1s.jpg)

suika85ergoはカラムスタッガードの一体型エルゴキーボードです。
ファンクションキーや矢印キーなど、コンパクトキーボードでは省略されがちなキーも備えており、フルキーボードからの移行も容易です。

* 制作 : すいか技研 （Website: https://suikagiken.net GitHub: [suikagiken](https://github.com/suikagiken) ）
* 販売 : [遊舎工房](https://yushakobo.jp/)様にて委託販売中です

## ビルドガイド

裏面にrev.1.0と書かれた基板をお持ちの方は[こちら](https://github.com/suikagiken/suika85ergo/blob/main/buildguide.md)、
rev.1.1と書かれた基板をお持ちの方は[こちら](https://github.com/suikagiken/suika85ergo/blob/main/buildguide_1.1.md)からご覧下さい。

---

## Overview

suika85ergo is a column-staggered ergonomic keyboard with 85 keys. It has function keys or arrow keys, which are omitted in compact keyboards, making it easy to switch from a conventional full keyboard.

* Keyboard Maintainer: [suikagiken](https://github.com/suikagiken)
* Hardware Supported: Purchase PCBs from the following stores.
* Hardware Availability: Available at Yousha Kobo.

Make example for this keyboard (after setting up your build environment):

    make suikagiken/suika85ergo:default

Flashing example for this keyboard:

    make suikagiken/suika85ergo:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available



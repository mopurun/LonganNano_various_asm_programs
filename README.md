# LonganNano_various_asm_programs


Sipeed Longan Nano RISC-V GD32VF103CBT6開発ボードをアセンブリ言語で動かしてみました。

![img1](blink/img1.jpg)

## Windowsでの書き込み方法

ドライバと書き込みソフト
https://www.gd32mcu.com/en/download/7?kw=GD32VF1

あらかじめGD32 Dfu Driversを入れておく必要があります。

- BOOT0スイッチを押しながらUSBケーブル繋いで電源投入
- GD32 All-In-One ProgrammerでInterface=USB,BootLoader=DFU設定して、Connectを押す。
- GD32 All-In-One ProgrammerでBrowseからbinを読み込ませて0x80000000に書き込む
- RESETスイッチで動作確認




## GigaDevice Dfu Toolを持ってる人向け

- BOOT0スイッチを押しながらUSBケーブル繋いで電源投入
- GigaDevice Dfu Toolでbinを読み込ませて0x80000000に書き込む
- RESETスイッチで動作確認

##

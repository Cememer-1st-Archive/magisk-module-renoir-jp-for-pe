# GSI(Treble ROM)向け Mi 11 Lite 5Gへの最適化モジュール

~~PixelExperience以外での動作は**未検証**です。~~

[AOSPでの動作報告](https://twitter.com/Chromium_Linux/status/1476425902745853954?s=20)もあるので、多分ほとんどのROMで動くと思います！

# [Fork元(magisk-module-renoir-jp)](https://github.com/AndroPlus-org/magisk-module-renoir-jp)との違い
Fork元はおそらくFloko ROMに最適化してるように見えますが、このForkでは、端末に最適化されていないようなGSI向けに設定しています。
- NQNfcNciを追加(復活)、NfcNciを置き換え(Felicaが上手く動作しないため)
- デバイス名や製造元名を修正
- 音量調節の段階が細かすぎる問題の修正
- カメラの互換性向上

# 注意

**自己責任で利用してください。**

既にFork元のモジュールをインストールしている場合、不具合防止のため、アンインストールしてからインストールしてください。

# Credit
- [Fork元(magisk-module-renoir-jp)](https://github.com/AndroPlus-org/magisk-module-renoir-jp)の製作者の[AndroPlus](https://github.com/AndroPlus-org)さんと[Contributor](https://github.com/AndroPlus-org/magisk-module-renoir-jp/graphs/contributors)のみなさん

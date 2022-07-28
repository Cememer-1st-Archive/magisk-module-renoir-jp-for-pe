# GSI(Treble ROM)向け Mi 11 Lite 5Gへの最適化モジュール

# 更新終了

**主がAOSP系ROMを使ってない他、現在はGSIではない(完全なカスタム)ROMが多くなっているため、これ以上の更新は行いません。**

## 代替モジュール:
- (完全な)カスタムROMでFelica動作: [soralis0912/magisk-module-renoir-jp-felica](https://github.com/soralis0912/magisk-module-renoir-jp-felica)

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

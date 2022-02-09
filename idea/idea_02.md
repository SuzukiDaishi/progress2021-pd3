# AutoVCのAny-to-One化による高速化の検証

## 前提
AutoVCはany-to-anyの音声変換が可能
ただし、男女間の変換やF0の再現などまだ完全なAny-to-Oneではない

## 検証
1. AutoVCの実装と検証
   - 学習にかかる時間
   - 変換精度
   - 実行速度
2. AutoVCの変更１
   - MelSpectrogramではなくMCEPsを用いた変換の検証
     - WaveNetではなくWorldで変換できる
     - 軽量化
   - LSTMをConvに変更
   - LSTMをMBConv(モバイルネットのやつ)などに変更
3. AutoVCの変更２
   - AutoVCをAny-to-One化する。

## 学習環境(スペック)
- GPU「RTX 2080 Ti」程度 (理想は「NVIDIA Tesla T4」)
- CPU 「Intel i7」以上
- 容量15GB以上

## 予定
| 日程 | 内容 |
| --- | ---- |
| ~1/31 | AutoVCの実装(日本語) |
| ~2/6 | AutoVC学習,検証 |
| ~2/13 | MCEPsでの実装への変更 |
| ~2/20 | 学習,検証 |
| その先 | モデル構造の変更... |
| ~3月末 | モデル完成 |
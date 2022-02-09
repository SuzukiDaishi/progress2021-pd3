
# 進捗報告書

報告書番号 | 氏名   | 期間         | 報告日
----- | ---- | ---------- | ---
06    | Suzuki Daishi | 04/13 ~ 04/19 | 04/20

## 活動概要

- 研究概要
  - リアルタイム Any-to-One 音声変換

- 進路状況
  - ヤマハ最終面接 -> 落ちました
  - バンダイナムコスタジオ -> ESの訂正をしてもらっています。
  - DMM -> 受けようかな？？

- 研究活動
  - VCTK学習済みモデルでの日本語変換の検証
  - AutoVCのMCEPsの対応
    - https://github.com/jackaduma/CycleGAN-VC2 の実装を参考に編集
  - AutoVCの論文と実装の検証(途中)
  - MCEPsを用いた変換とメルスペクトログラムの変換の速度検証用のコードの作成(途中)
    - autovc(mel-spectrogram) + wavenet
    - autovc(mel-spectrogram) + griffinlim
    - autovc(mel-cepstral coefficients) + world vocoder
    - autovc(mel-cepstral coefficients) + melgan vocoder
- その他の活動
  - 初めてQiita書きました。
    - https://qiita.com/zukky_rikugame/items/dea51c60bfb984d39029
- 振り返り事項
  - 反省事項
    - 研究があんまり進まなかった
    - ヤマハ落ちた...
  - よかったこと
    - Qiita週間LGTM数ランキング(Python)の39位を取りました

## 活動予定

  - 今後の活動
    - 5月末までに以下のことを検証
      - [ ] 実装と論文に差異は無いかの検証
      - [ ] 高速化のために現在のモデルで精度や速度を検証
      - [ ] AutoVCのMCEPsを使った実装の開発
      - [ ] https://arxiv.org/abs/1905.05879 を落合メソッドでまとめる
      - [ ] https://arxiv.org/abs/2004.07370 を落合メソッドでまとめる
      - [ ] https://auspicious3000.github.io/SpeechSplit-Demo/ を読む
      - [ ] https://arxiv.org/abs/2004.11284 を落合メソッドでまとめる
    - 6月までにMCEPsのモデル完成


## 研究室に来る日程と時間帯

| 月             | 火            | 水            | 木            | 金             | 土
| ------------- | ------------- | ------------- | ------------- | ------------- | -------------
| 00:00 ~ 00:00 | 14:00 ~ 19:00 | 00:00 ~ 00:00 | 15:00 ~ 19:00 | 00:00 ~ 00:00 | 00:00 ~ 00:00
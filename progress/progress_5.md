
# 進捗報告書

報告書番号 | 氏名   | 期間         | 報告日
----- | ---- | ---------- | ---
05    | Suzuki Daishi | 02/01 ~ 04/12 | 04/13

## 活動概要

- 研究概要
  - リアルタイム Any-to-One 音声変換

- 進路状況
  - ヤマハ最終面接(04/13の16:00にありました)
  - 今週結果が出ます...

- 研究活動
  - AutoVCの日本語化
    - そもそも元の実装が動かない
    - 高速化だけなら日本語化を検証する必要はないのではないか？
  - AutoVCの論文実装の調査
    - https://github.com/auspicious3000/autovc の調査
      - これが本家実装
      - 4人のみで学習したデータはうまくいった
      - VCTKコーパス全体での学習結果とその実装はなかった
      - IssueにVCTK全体の検証でうまくいかなかったとの報告があった
    - https://github.com/peisuke/AutoVC.pytorch の調査
      - 実際学習させて見てうまく学習できていることが確認できた。
      - 本家実装との違いを調査中

- 振り返り事項
  - 反省事項
    - 進捗報告が疎かになってしまった
    - その実験が本当に必要か改めて検討して実験を行いたい
  - よかったこと
    - コード動いた！！！

## 活動予定

  - 今後の活動
    - 5月末までに以下のことを検証
      - 実装と論文に差異は無いかの検証
      - 高速化のために現在のモデルで精度や速度を検証
      - AutoVCのMCEPsを使った実装の開発
      - https://arxiv.org/abs/1905.05879 を落合メソッドでまとめる
      - https://arxiv.org/abs/2004.07370 を落合メソッドでまとめる
      - https://auspicious3000.github.io/SpeechSplit-Demo/ を読む
      - https://arxiv.org/abs/2004.11284 を落合メソッドでまとめる
    - 6月までにMCEPsのモデル完成


## 研究室に来る日程と時間帯

| 月             | 火            | 水            | 木            | 金             | 土
| ------------- | ------------- | ------------- | ------------- | ------------- | -------------
| 00:00 ~ 00:00 | 14:00 ~ 19:00 | 00:00 ~ 00:00 | 15:00 ~ 19:00 | 00:00 ~ 00:00 | 00:00 ~ 00:00
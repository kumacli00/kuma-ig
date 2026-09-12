# KumaCLI Instagram 診断レポート

https://kumacli00.github.io/kuma-ig/ で公開。
毎朝9:30に instagram/gen_report.py が生成したHTMLを push している。
中身は Instagram Graph API の実測値のみ。社内KPI（成約率・客単価など）は載せない。

## このリポジトリで公開しているページ

| URL | 中身 | 更新 |
| --- | --- | --- |
| `/` | Instagram診断レポート（何が起きているか） | 毎朝9:35 |
| `/check/` | 今日やること（数字の採点と、次の一手） | 毎朝10:10 |
| `/kikaku/` | 今日の企画5本（撮る順に並べたもの） | 毎朝10:10 |

どれも社内KPIの実数（予約率・来院率・成約率・客単価）は載せない。
`/kikaku/` には**撮る前の企画**が載るので、その前提で扱うこと。

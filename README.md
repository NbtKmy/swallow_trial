# swallowお試し

Swallowは東京工業大学情報理工学院の岡崎研究室と横田研究室、国立研究開発法人産業技術総合研究所の研究チームで開発された大規模言語モデルで、
日本語に関しては「2023年12月現在オープンな大規模言語モデルの中で、日本語に関して最高性能を達成しました」ということで、ちょっとおもしろそうなのでためしてみた。

## 基本編
Huggingfaceにインストラクションが載っているのでまずはそれでやってみた。
ほぼほぼコピペです。

公式ページ
https://tokyotech-llm.github.io/

Huggingface(70bのやつ)
https://huggingface.co/tokyotech-llm/Swallow-70b-instruct-hf

ブログ記事（詳細情報など）
https://zenn.dev/tokyotech_lm/articles/d6cb3a8fdfc907

## 応用編
何かに応用できないがとおもったので、LLMをlangchainを通じて呼び出し、J-Stageに載っている雑誌の抄録をスクレイピングしてベクトルストアをつくって、RAGしてみた。
今回は取れた抄録の数が少ない（27件）のでいまいちな結果になってしまった。



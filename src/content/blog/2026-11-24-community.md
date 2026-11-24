---
title: 'Superlinear Academy 注目投稿：オフライン地図、出典付きAPI、イベント運営の学び'
description: '中国語AIコミュニティ Superlinear Academy から、オフライン地図の個人開発、出典を返すMCP接口、ポッドキャスト回の学びを紹介します。'
pubDate: '2026-11-24'
tags: ['生成AI', 'MCP', 'コミュニティ']
sources:
  - title: '西雅图的奥特莱斯怎么会黑五期间连个网都没有...'
    author: 'UB'
    url: 'https://www.superlinear.academy/c/share-your-projects/seattle-premium-outlets-203'
  - title: '我给 Credit Guru 做了个 AI 接口：查信用卡权益时，也能查到出处'
    author: 'Charles He'
    url: 'https://www.superlinear.academy/c/share-your-projects/credit-guru-ai'
  - title: '做客《小火车商业进化论》：放弃可能性，守住生命力'
    author: 'YZ｜立正'
    url: 'https://www.superlinear.academy/c/recording/thomas-joe-lizheng-event-replay'
---

中国語圏のAIコミュニティ「Superlinear Academy」の最新投稿から、実務の参考になる3件を選びました。

## 圏外でも使える約203KBの単一HTML地図（UB）

シアトルのアウトレットがブラックフライデーで圏外になり、公式アプリも開けない。その不満から、OpenStreetMapのデータを使った単一ファイルのオフライン地図を作った、という投稿です。店舗検索、通路ネットワークによる徒歩ルート、最寄りトイレ表示などを備え、外部通信はゼロ。iOSではローカルHTMLが開きにくく、PWA化かHTTPS配信が必要だった点も正直に共有されています。

**日本の現場で使うなら：** 工場、倉庫、地下街など電波が弱い場所の案内ツールに応用できます。配布方法（iOSでの扱い）を先に設計するのが肝です。

## 出典と確認日を返すMCP接口（Charles He）

米国クレジットカード情報サイト「Credit Guru」のデータを、登録不要・読み取り専用のMCPとして公開した事例です。AIの回答に「どの公式ページに載っていたか」「いつ確認したか」が付くため、そのまま判断材料にしやすくなります。直近30日以内に公式ページで確認した記録だけを収録する方針です。

**日本の現場で使うなら：** 社内規程や製品仕様をAIに答えさせる際、出典と更新日を必ず返す設計は信頼性の面で参考になります。

## 「小火車商業進化論」回：イベント運営と働き方の学び（YZ｜立正）

AIE上海の運営経験を、ポッドキャストで語った回の要約です。800枚の目標に対し開幕1か月半前は約100枚でしたが、最終的に1600人以上が来場したといいます。「単発イベントより十回の食事会」という発想や、本業は活力を損なわない範囲にとどめるという考え方も語られています。

**日本の現場で使うなら：** 社内勉強会やコミュニティ運営で、参加者同士が出会える設計を重視する視点は、そのまま使えます。

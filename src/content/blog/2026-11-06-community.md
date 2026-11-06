---
title: 'Superlinear Academy社区精选：AIで作るiPhoneアプリ、求職ダッシュボード、DeepSeek Flashだけで回す開発'
description: '中国のAI学習コミュニティで共有された3つの個人プロジェクトを紹介。AI協働で公開したToDoアプリ、求職の詰まりを可視化する工作台、安価なモデルだけで1日110コミットを出したPWA開発の話です。'
pubDate: '2026-11-06'
tags: ['生成AI', 'AI開発', 'Claude Code', '個人開発']
sources:
  - title: 'XuSeak To-Do 正式上架：用 AI 做的待办 App，已适配 iPhone Duo'
    author: 'XZ / Xu Zhou (Lukas)'
    url: 'https://www.superlinear.academy/c/share-your-projects/xuseak-to-do-ai-app-iphone-duo'
  - title: '求职三个多月投了很多个岗位，第一次看清自己卡在哪'
    author: 'S'
    url: 'https://www.superlinear.academy/c/share-your-projects/7-ai-ai'
  - title: '今天早上突然想到一件事：我为什么不直接用 PWA 做一个本地音乐播放器？'
    author: 'S'
    url: 'https://www.superlinear.academy/c/share-your-projects/pwa'
---

中国のAI学習コミュニティ「Superlinear Academy」の「Share Your Projects」から、今日は個人開発の3件を取り上げます。

## AIと作ったToDoアプリ「XuSeak To-Do」がApp Storeに登場

Xu Zhou (Lukas) さんが、コース受講をきっかけに初のiPhoneアプリを公開しました。ToDo、習慣記録、アイデアのメモを一つにまとめ、今日のタスクはホーム画面ウィジェットにも表示できます。折りたたみ型のiPhone Duoにも対応し、閉じれば1カラム、開けばToday・Ideas・Calendarの2カラムになります。設計から開発、テスト、審査提出までAIと進めたとのことです。基本機能は無料のままで、将来Plusの有料機能を追加する予定です。

**日本の現場で使うなら：** 「小さく作って審査まで通す」までをAIと一人で回せる実例です。社内向けの小さなツールを内製する際の参考になります。

## 求職3か月の記録をClaudeと可視化、詰まりは「履歴書」だった

「S」さんは、散らばっていた応募記録をClaudeと一緒に求職ダッシュボードにまとめました。7段階のファネル、応募カード、カレンダー、面接振り返り、オファー比較を備えています。データを入れてみると、半数の応募が書類選考で落ちており、面接自体は悪くないと分かった、という気づきが印象的です。「経験不足かも」という漠然とした不安が、具体的な改善点に変わりました。コードはオープンソースで公開されています。

**日本の現場で使うなら：** 転職活動だけでなく、営業案件や採用パイプラインの管理にもそのまま応用できる考え方です。

## DeepSeek Flashだけで回した「AIがAIを指揮する」開発

「S」さんは、PWAのローカル音楽プレーヤーをClaude Codeに任せ、いつもはOpusが担う指揮役(Master)も、作業役(Worker)も安価なDeepSeek Flashにして実験しました。出社中に放置したところ、夜には1日で110コミットに達し、実用に耐えるものができていたそうです。ただし完成品ではなく、不具合は残っています。投稿者自身も「AIを動かす役割さえAIに置き換わり得る」と感じたと書いています。

**日本の現場で使うなら：** 高価なモデルを指揮役に固定せず、コストを抑えた構成で試せることを示しています。ただし本番導入ではテストとレビューの体制が前提になります。

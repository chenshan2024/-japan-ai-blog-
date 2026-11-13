---
title: 'Superlinear Academy 精選：AIで作る動画、Macツール、Agentの次の一手'
description: '中国語AIコミュニティ Superlinear Academy から、Three.jsで作る動画制作フロー、PasteDot、Agentとファイルシステム、Steam海賊版の4話題を紹介。'
pubDate: '2026-11-13'
tags: ['生成AI', 'AIエージェント', '個人開発', 'Claude Code']
sources:
  - title: '用 treejs 做自媒体'
    author: 'Jacob Lee'
    url: 'https://www.superlinear.academy/c/share-your-projects/treejs'
  - title: '分享我做的 Mac 小工具 PasteDot，和一些开发中的想法'
    author: 'StevenHe'
    url: 'https://www.superlinear.academy/c/share-your-projects/mac-pastedot-c26e7e'
  - title: 'Agent的下一个突破，在文件系统'
    author: 'Superlinear Academy 週間まとめ'
    url: 'https://www.superlinear.academy/c/ai-resources/agent-file-system'
  - title: '用 Claude Code 做了一款 Steam 游戏，上线一天就在国内被打包盗版'
    author: 'Superlinear Academy 週間まとめ'
    url: 'https://www.superlinear.academy/c/share-your-projects/claude-code-steam'
---

中国語圏のAIコミュニティ Superlinear Academy から、今日は個人開発とAIエージェントに関する4つの話題を取り上げます。

## Three.jsとAIで作る5分の解説動画（Jacob Lee）

Jacob Lee さんは、ナレーション原稿、絵コンテ、アニメーション、動画の合成までAIに任せるワークフローを共有しています。ただ、原稿までAIに任せた10数本は「AIっぽさ」に負けたそうで、原稿だけは自分で書く形に戻して満足度が上がったとのことです。アニメーションはThree.jsのコードで作り、Playwrightでフレームごとにスクリーンショットを撮り、ffmpegで合成します。

**日本の現場で使うなら：** 社内向けの製品解説や研修動画にそのまま応用できます。「観点は人、制作はAI」という分担は、日本企業でも品質を保つ現実的な線だと思います。

## Macクリップボードツール PasteDot（StevenHe）

StevenHe さんは、有料ツールの Paste を使ってきた経験から、オープンソースとAIを使って自分好みのクリップボードツール「PasteDot」を作りました。開発で役立ったのは、「何をもって完成とするか」を先に書いてからAIにコードを書かせる方法だそうです。基本機能は無料で、将来は受託開発やAI講座への導線を探っています。

**日本の現場で使うなら：** 「完成条件を先に定義する」進め方は、仕様書文化のある日本のチームと相性が良く、AIへの指示にもすぐ使えます。

## Agentの次の突破口はファイルシステム

コミュニティの投稿は、ローカルのAgentは自分を理解しているが常時は使えず、クラウドPCは常時使えるが自分の全体像が見えない、と整理します。そこで「ファイルは端末やクラウドではなく人に属する」べきだと主張し、ファイルシステムの刷新を提案しています。

**日本の現場で使うなら：** 社内データの置き場所と権限が分断されがちな企業にとって、「どの端末からでもAgentが同じ文脈にアクセスできるか」は導入時の重要な論点になります。

## Claude CodeでSteamゲームを作り、1日で海賊版に

Claude Code で作ったゲームをSteamで公開したところ、1日で中国国内で海賊版が出回ったという体験談です。投稿は「AIで10倍効率」ではなく、実際に起きたことを書くと述べ、コードは安くなり、「面白いかどうか」の価値が相対的に上がるとまとめています。

**日本の現場で使うなら：** AIで開発コストが下がるほど、差別化は体験設計と運営に移ります。海外展開時の模倣対策も、最初から計画に入れておきたいところです。

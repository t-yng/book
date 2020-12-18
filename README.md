---
description: サバイバルTypeScript 〜実務で使うなら最低限ここだけはおさえておきたいTypeScript入門〜
---

# はじめに

## これはどのような本か？

本書の目標は、本読者がTypeScriptをすぐに実務で利用できるよう、最短ルートに読者を導く一冊になることです。本書は、TypeScriptの網羅的なドキュメントではありません。逆に、実務であまり使わないTypeScriptの機能は割愛します。扱う内容は、頻出する機能にしぼりにしぼって、「実務でTypeScriptを使うなら、ここだけはおさえておこう」「ここだけはおさえておけば、実務で死なない\(=サバイバルできる\)」という観点で執筆しています。

本書はTypeScriptを中心に扱いますが、実務上、必要になる知識としてJavaScriptの仕様、フロントエンドフレームワークのReactなどについても扱います。

## 誰に向けて書かれた本か？

本書は、プログラミング経験はあるが、これからTypeScriptをはじめる人、もしくは、始めたばかりという人を対象にしています。たとえば、次のような属性のプログラマを想定しています。

1. 主としてサーバーサイドのプログラミング\(PHPやRuby、Javaなど\)をしているが、フロントエンドも担当することになった。
2. JavaScriptの経験があるが、そこまでJavaScriptに精通しているわけではないので、TypeScriptと並行して勉強したい。
3. RubyやPythonなどの動的型付け言語を主に扱ってきており、型をそこまで意識してこなかったので、型システムについて学ぶ必要性を感じている。

## 本書では扱わないこと

本書は、TypeScript初心者であるものの、プログラミング経験自体はある人を対象読者としています。そのため、「変数とは何か？」「関数とは何か？」といったプログラミングのいろはは本書では扱いません。

## 本書の構成

第二章「TypeScriptへようこそ」では、TypeScriptの概要について触れます。同時に、TypeScriptの良さや、TypeScriptがJavaScriptエコシステムでどういった立ち位置にあるのかを示すことで、全体像を知っていただきます。

第三章「作りながら学ぶTypeScript」では、さまざまなアプリケーションをTypeScriptで実装するワークショップ形式の解説を通じて、TypeScriptそのものについては軽めに学びながら、TypeScriptを用いた開発の流れを感じ取って頂きます。このワークショップでは、実務の開発により近づけるよう、TypeScriptだけでなく、フロントエンドフレームワークのReact、テストフレームワークのJest、REST APIによるCRUD操作やWebSocketを使ったバックエンドとの通信についても扱って行きます。本章でもTypeScriptの機能や書き方について必要最低限説明しますが、詳しい言語機能の説明は第六章で扱います。

第四章「TypeScriptオーバービュー」では、TypeScriptとは何なのか詳しく知ってもらったり、読者が同僚や属するチームにTypeScriptをPRできるような情報を提供します。TypeScriptの歴史、思想、哲学を知ってもらうことで、どのようなところでTypeScriptがその本領を発揮するのかを学びます。TypeScriptをなぜ使うべきなのか？TypeScriptのアドバンテージは何なのか？TypeScriptとJavaScriptはどのような関係なのか？といった疑問に答えていきます。

第五章「JavaScript再入門」では、TypeScriptから少し離れ、JavaScriptについて簡単に復習します。読者が慣れ親しんでいるプログラミング言語\(PHPやJavaなど\)と比べて、JavaScriptが異なっている部分や、ハマりやすい部分を重点的に解説し、TypeScriptの言語機能を学ぶ下準備となる章です。

第六章「これだけはおさえておきたいTypeScriptの機能」では、TypeScriptの言語機能をひとつひとつ解説します。すべての機能のリファレンスというよりは、実際の開発で頻繁に使用するものに限定し、これだけはおさえておきたい機能を中心に取り上げていきます。

## 本書の使い方

本書は基本的に、章立ての順番とおりに読み進めて頂いて問題ありません。

本書の大まかな流れとして、応用編であるアプリ開発\(第二章\)のほうが、基礎編であるTypeScriptの言語機能\(第六章\)より先んじていますが、これには実践を通じて学んだほうが学習効率がいいという経験則に基づいています。

意図的に応用編を先に解説しているので、TypeScriptに初めて触れる読者でも、基礎編\(第六章\)を先に読まなくても、第二章から読み進められるように十分配慮しています。

## 執筆者について

本書は、主に[YYTypeScript](https://yyts.connpass.com/)の参加者を中心とした複数の有志のプログラマが集って執筆を行っています。執筆はいわばオープンソース的に行われており、本書はGitHubでも公開されていて、執筆への参加も随時受け付けています。執筆に興味がある方は、執筆者向け情報ページをご覧ください。

### コントリビューター

本書の企画、執筆、編集等に携わった方々を順不同敬称略で紹介します。

* reoring
* suin
* nouphet
* クロレ
* jamashita
* fuubit
* t-yng
* kakiuchi
* philomagi
* mikkame
* NkawaK
* zima
* tatsuki\_sun

## 継続的アップデート

本書は継続的にアップデートされていきます。


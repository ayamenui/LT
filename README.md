<h1 align="center"> <br> <a href="https://github.com/saiteja-madha"><img src="./docs/.gitbook/assets/strange.png" height="200" alt="Discord.js v14 Bot"></a> <br> Discord.js v14 ボット <br> </h1> <p align="center">管理、オートモデレーション、アニメ、経済、楽しみ、ギブアウェイ、画像、招待、情報、モデレーション、音楽、オーナー、ソーシャル、統計、提案、チケット、ユーティリティーなど、多彩な機能を持つボット！</p> <br> <p align="center"> <a href="#-リソースリンク">リソースリンク</a> • <a href="#-前提条件">前提条件</a> • <a href="#-使い始めるには">使い始めるには</a> • <a href="#-機能">機能</a> • <a href="#-貢献">貢献</a> </p> <br>
🔗 リソースリンク

    🤖 デモボット: こちらから招待
    🤝 サポートサーバー: こちらから参加
    📂 ドキュメントURL: こちらから訪問
    🐳 Dockerイメージ: Hub

📦 前提条件

    Node.js v16.11.0以上
    Git
    MongoDB

🚀 使い始めるには

    ターミナルを開いて、以下のコマンドを実行してください

bash

git clone https://github.com/saiteja-madha/discord-js-bot.git
cd discord-js-bot
npm install

    すべての依存関係がインストールされるまで待ちます
    .env.example を .env にリネームし、値を入力します
    必要に応じて config.js を編集します
    npm run start と入力してボットを起動します

追加のヘルプが必要な場合は、こちらのガイドをご確認ください。
<br> <h1 align="center"> ✨ 機能 ✨ </h1>
📡 高度なダッシュボード

    サーバーを管理し、サーバー固有の設定を行うことができます！
    カスタム設定を簡単に調整できます！

🛑 強力なモデレーション:

    モデレーションコマンド <br /> コマンド: ban, unban, timeout, voice moderation, deafen, move, warn, setnick, ...
    多機能パージコマンド <br /> コマンド: purge, purge attach, purge bots, purge links, purge token, purge user, ...

🤖 オートモデレーション:

    アンチシステム <br /> コマンド: anti ghostping, anti spam, anti massmention, ...
    自動削除システム <br /> コマンド: autodelete attachments, autodelete invites, autodelete links, autodelete maxlines, ...
    オートモッドシステム <br /> コマンド: automod status, automod strikes, automod action, automod debug, automod whitelist, ...

⚙️ 管理設定:

    ボットをサーバーのアシスタントにする！ <br /> コマンド: autorole, farewell, welcome, counters, flag translation, reaction roles, ...
    サーバー固有のカスタム設定を作成できます。 <br /> コマンド: setprefix, maxwarns, modlog...

💁 情報収集:

    ユーザーコンテキストインタラクション
    高度な情報 ユーザー、チャンネル、ロールなどについて深く知ることができます。

🎵 音楽:

    ロスレス音楽 高音質のロスレス音楽を楽しもう
    多プラットフォーム YouTube、SoundCloud、Spotifyなどから音楽を再生
    フィルター 音楽にフィルターをかけて楽しさ倍増

🎉 ギブアウェイ:

    簡単に使える ギブアウェイを簡単に作成
    ロール固有のギブアウェイ
    カスタマイズ可能 ギブアウェイを自分好みにカスタマイズ
    無制限 無限にギブアウェイを作成

🫂 ソーシャルコンテンツ:

    サーバー固有のCVがボット内に！ <br /> コマンド: rep, rep view...
    誰かを愛してる？ <br /> コマンド: rep give...

🎟 チケットシステム:

    メンバーのサポートを簡単にするチケットシステム！ <br /> カスタマイズ可能なチケットシステムとスタッフロール付き
    複数のカテゴリ <br /> チケットを散らばらせたくない？ セレクトメニューでカテゴリ分け可能

📉 統計追跡:

    レベリング サーバーの活動をレベルシステムで追跡
    リーダーボード サーバーで一番活発なユーザーを確認
    カスタマイズ可能なシステム レベルアップメッセージやランクカードを自分好みに設定

🙋‍♂️ 提案:

    サーバーをより良くするためにメンバーから提案を受け取ろう！ <br /> コマンド: suggest, suggestion...
    提案を受け入れたり却下したりして、最大限にカスタマイズ！ <br /> コマンド: suggestion status, suggestion channel, suggestion appch, suggestion rejch, suggestion approve, suggestion staffadd, suggestion staffremove...

⚒️ ユーティリティコマンド:

    何か手助けが必要？ユーティリティコマンドを使って答えを見つけよう！ <br /> コマンド: bigemoji, covid, pokedex, urban, weather, ...
    さらに手助けが必要？ <br /> コマンド: help, proxies, translate, paste, ...

⭐ アニメコンテンツ:

    アニメが好き？リアクトコマンドを使って愛を表現しよう <br /> コマンド: react, hug, kiss, cuddle, pat, poke, slap, smug, ...

🪙 経済システム:

    一番お金持ちになりたい？経済コマンドを使おう！ <br /> コマンド: bank, daily, beg, gamble...
    お金を送ったり、残高を確認したり、ただの自慢もできる！ <br /> コマンド: bank balance, bank deposit, bank withdraw, bank transfer, ...

😁 楽しみコマンド:

    サーバーで楽しもう！ <br /> コマンド: animal, facts, meme, flip, ...
    ゲームをして楽しもう！ <br /> コマンド: snake, together, flip coin, flip text, ...

📨 招待追跡:

    誰がサーバーに招待したか追跡しよう！
    招待ランク！ 招待者は素敵な報酬を獲得し、認められる
    これらの設定を調整して自分好みにカスタマイズ！ <br /> コマンド: resetinvites, addinvites, invitesimport, inviterank...

📷 画像加工:

    他の人のアバターをカスタマイズしよう <br /> コマンド: blur, greyscale, invert, pixelate, blur, sepia, sharpen, ad, affect, beautiful, color...
    自分で画像を作成したりアートを作成しよう <br /> コマンド: bobross, confusedstonk, delete, facepalm, hitler, jail, jokeoverhead, karaba, mms, notstonk, poutine, rainbow, rip, shit, stonk, tatoo, thomas, trash, wanted, wasted, ...

<br> <h1 align="center"> 🤝 貢献 🤝 </h1>

    特別感謝: @Androzz ダッシュボードと彼の他の素晴らしいディスコードボットプロジェクトに感謝
    このリポジトリをフォークして、機能ブランチを作成し、プルリクエストを送信してみてください
    計画されているすべての機能はこちらで追跡できます。または、ディスコードでリクエストを行ってください

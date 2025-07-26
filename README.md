# CodeRaiders

📘 Python学習ゲーム：CodeRaiders
🎮 概要（Overview）
CodeRaiders（コードレイダーズ） は、Pythonの基本文法を楽しく復習・実践できる学習型ゲームです。
プレイヤーは「古代の遺跡」を探索する冒険者となり、Pythonコードを使って様々な謎解きや仕掛けを突破していきます。

🚀 目的（Purpose）
Progateなどで学んだPython初級者が次のステップに進めること

if文、for文、関数、クラスなどの基本文法を実際に「使って」理解する

遊びながら学ぶことで、定着・モチベーションアップにつなげる

👤 想定ユーザー（Target User）
項目	内容
対象	社会人・初級学習者（Progate修了レベル）
Python経験	print / 変数 / if / for / 関数など基本を学んだ程度
想定環境	PCブラウザ or Python実行環境（詳細は下記）

🧠 学べる内容（Learning Contents）
ステージ	学べること	難易度
封印の扉	print, 変数, 入出力	★☆☆☆☆
石像の謎	if文, 比較演算	★★☆☆☆
光のパズル	for文, range(), リスト	★★☆☆☆
呪文の書	関数, 引数と戻り値	★★★☆☆
精霊の間	クラス, インスタンス	★★★★☆
崩れる遺跡	try-except, ファイル入出力	★★★★☆

🛠 使用技術（Tech Stack）
分類	内容
メイン言語	Python 3.x
実行環境	Pyodide + HTML/CSS/JS（Web）／tkinter（ローカル版）※選択式
補助ツール	GitHub, VSCode
デプロイ	GitHub Pages / Streamlit Cloud など（予定）

🖥️ 画面イメージ（UI Image）
※ここにはスクリーンショットまたはUIイメージを貼ってください（未完成でもラフでOK）

✅ 機能（Features）
🧩 ステージ制の進行

🧠 正解・不正解のフィードバック機能

💡 ヒントボタン付き

📘 初心者にもやさしいコード補助（予定）

📈 学習内容の一覧表示／履歴保存（発展機能）

💻 実行方法（How to Run）
▶ Webブラウザで実行（Pyodide使用時）
このリポジトリをクローン

index.html をブラウザで開く

Pythonコードを入力してステージをプレイ

▶ ローカル実行（tkinter版）
Python3 をインストール

main.py を実行

GUI上でコードを入力してプレイ

📂 ディレクトリ構成（Directory Structure）
CodeRaiders/
├── assets/             # 画像・CSSなど
├── src/
│   ├── main.py         # ゲーム本体（tkinter用）
│   ├── engine.py       # コアロジック
│   └── stage_data.py   # ステージ情報
├── index.html          # Web実行用（Pyodide版）
├── style.css           # スタイル
└── README.md           # このファイル

📈 今後の開発予定（Roadmap）
 Web版の完成（Pyodide + HTML）

 ヒント表示・ヒント解説機能

 ステージクリア後のスコア表示

 モバイル対応（簡易UI）

 英語版UI（国際対応）

👤 作者（Author）
名前	Shunsuke　Kato
経歴	法人営業 → プログラミング転職活動中
学習	ProgateでPython・JavaScript修了、react独学中
SNS/GitHub	[GitHubリンク] / [Twitterなど]

📮 ライセンス（License）
このプロジェクトはMITライセンスです。

📝 備考
本プロジェクトは転職用ポートフォリオとして作成しています。

コード・設計に関するアドバイス等があれば [GitHub Issues] からご連絡ください。

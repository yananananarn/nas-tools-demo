NASツールポータル 試作

フォルダー全体を展開し、index.htmlをブラウザーで開いてください。Webサーバー、インターネット接続、外部ライブラリーは不要です。

index.html：入口・開閉可能なサイドメニュー
home.html：初期画面
calculator.html：簡易計算
text.html：文字カウント
inventory.html：備品一覧

実際のツールを追加する場合は、index.htmlのnav内にあるaタグを複製し、hrefを対象HTMLへの相対パスに変更してください。target="main"を維持し、data-pageは重複しない名前に変更してください。

スマホ向けnas_tools_mobile.htmlは、ダミーページを内蔵しiframeのsrcdocで表示する1ファイル版です。複数ファイル版のNASパス・ファイルアクセスの互換性確認は、実際の会社PCで行ってください。

入力値はツール切り替えでリセットされます。共有保存機能はありません。

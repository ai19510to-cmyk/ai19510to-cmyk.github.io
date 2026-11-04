看護実習ナビ｜公開サイト化 第1段階

【公開方法】
GitHub Pages等の静的ホスティングを想定したHTML/CSS/JS一式です。リポジトリの公開設定は利用者側で行ってください。

【主なファイル】
- index.html：学生向けアプリ（旧prototype.htmlを移行）
- demo.html：架空事例入りの操作デモ
- instructor.html：教員・指導者向け教材確認ページ（認証なし・公開情報扱い）
- about.html：サービス紹介
- how-to-use.html：使い方
- privacy.html：プライバシーポリシー草案
- terms.html：利用規約草案
- disclaimer.html：免責事項
- contact.html：問い合わせ窓口の準備状況
- 404.html：ページ不在時の案内
- assets/favicon.svg：サイトアイコン
- content.json：教材データ原本（アプリ内にも既存データを保持）
- prototype.html：旧URLからindex.htmlへの転送
- START_HERE_JA.txt：利用上の注意
- QA_FINAL_JA.txt：今回の確認結果

【重要】
本サービスは看護学生向けの学習用草案です。臨床判断・診断・治療・ケア実施可否を自動判定しません。教材内容・Gordon/Henderson対応・ADL尺度案は教員・臨床指導者の承認前です。実在患者の情報を入力しないでください。

広告、課金、ログイン、クラウド保存、アクセス解析は導入していません。学生向け画面から教員用パネルを分け、instructor.htmlへ配置しました。既存の教材データ・質問ID・テーマ・localStorage・JSONバックアップの処理は維持しています。

【公開前に必要】
1. GitHub Pagesの公開設定と実URL確認
2. 独自ドメインを使う場合は取得・DNS設定後、sitemap.xmlとcanonical/OGPのURLを確定
3. 問い合わせ先の設定
4. instructor.htmlは認証なしのため、非公開の教員コメントや個人情報を扱わない（必要なら認証付きの別システムへ移す）
5. iOS Safari／Android Chrome実機確認
6. 教員・臨床指導者による教材確認
7. プライバシー・利用規約等を実際の公開条件に合わせて最終確認

このZIPをそのまま公開する前に、上記の未完了事項を確認してください。

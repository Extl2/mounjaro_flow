# マンジャロ 予約後フロー一式

このフォルダには、予約ページの後に使うHTML一式が入っています。

## ファイル
- questionnaire.html : 問診・同意フォーム
- visit.html : ビデオ診察案内ページ
- thanks.html : 送信完了ページ
- line_flow_diagram.md : LINE導線図

## GitHub Pagesでの使い方
1. 既存の予約HTMLと同じリポジトリに、この4ファイルを追加
2. questionnaire.html の form action を実際の送信先URLに変更
3. visit.html の診察開始ボタンURLを実際のビデオ診察URLに変更
4. LINEの予約後メッセージに questionnaire.html のURLを設定
5. 問診後メッセージに visit.html のURLを設定

## 例URL
- https://あなたのID.github.io/リポジトリ名/questionnaire.html
- https://あなたのID.github.io/リポジトリ名/visit.html

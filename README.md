# validation-app-practice

## 概要
COACHTECH 教材 Tutorial 9-6「バリデーション ハンズオン演習」で作成した成果物です。
フォームリクエストを使ったバリデーションと日本語エラーメッセージを備えた「ユーザー登録フォーム」を作成しました。

## 使用技術
- PHP 8.x
- Laravel 10.x
- FormRequest / バリデーションルール

## 学んだこと
- バリデーションルールの定義方法（required, email, min, confirmed）
- カスタムエラーメッセージ（messagesメソッド）
- validated()を使った検証済みデータのみの取得

## 動作確認
ブラウザで http://localhost/register にアクセスするとユーザー登録画面が表示され、入力後、登録完了画面が表示されれば成功です。また、入力した情報が条件を満たしていない場合に、エラーになることが必要です。

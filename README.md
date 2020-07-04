---
MOS09 at fukurou


## 作成アプリケーション  
【Todo List】(フクロウ式Todolist)

## どうして作ったか  
phpの勉強をするためににサンプルを用いて作成

## どんな機能があるか  
会員登録(メールアドレス、パスワード登録)、ログイン、タスク登録、タスク完了(削除)、完了済みタスク表示、ログアウト

##どのように仕様するか  
1.ログインをする(会員登録していない場合はログイン画面内ログインボタン下にある「会員登録はこちら」リンクから会員登録をお願いします。)  
2.会員登録が完了したら、ログインする  
3.ログインしたら、「タスク名」「内容」「期限日」が入力できるようになっているので、入力  
4.「登録」ボタンを押下  
5.登録されたタスクは画面下部に表示されます。  
  編集する場合は編集ボタンを、完了した場合は完了ボタンを押下  
--編集ボタンを押下した場合--  
6.編集モーダルが表示されます。  
  タスクを更新、またはタスクの削除ができます。  
※削除したタスクは戻すことができないので注意してください。  
※完了済みタスクを取り消す機能については今後追加予定です。

## どのサイトで公開してるか
https://blooming-ocean-46381.herokuapp.com/login.php  
↑で公開してます

## これからどんな機能を追加していきたいか  
~現状はタスク一覧がすべてのユーザーで表示されるため、ユーザーの切り分けでタスクをを表示させるようにする。~  
また、パスワードを忘れてしまった場合の対応などもできていないので、対応をしていく予定  
~それに加え、スマホで閲覧した際、のサイズが見づらいため、スマホで閲覧した際のサイズなども対応する予定。~   
・削除したタスクの再表示機能  
・メール通知機能  
・~「完了」とは別の削除ボタン機能実装~  
・完了済みタスクのページング機能

##これはバグ?  
・新規登録時、完了済みタスクボタン押下時のモーダル表示がラベルしか表示されていないけど?  
→現時点では本現状については仕様となります。  
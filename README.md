# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
* ### リモートリポジトリ
  * GitHubなどのネットワークサービスで作成・操作ができ、ネットワーク上のサーバーに設けられたリポジトリ。リモートリポジトリから各利用者はクローンを作成し変更を加えることができる。
* ### ローカルリポジトリ
  * Gitなどの分散バージョン管理システムで、利用者が操作しているコンピューターのストレージに設けられたリポジトリのことで、変更履歴の管理などを行うことができる。


## プッシュとマージの違いは何でしょうか？
* ### プッシュ
  * ローカルリポジトの変更内容などをリモートリポジトリに反映させる作業。
* ### マージ
  * ブランチの変更内容を別のブランチに反映させる作業。



## コミットとプッシュの違い
* ### コミット
  * リポジトリに変更内容を保存する作業。
* ### プッシュ
  * ローカルリポジトの変更内容などをリモートリポジトリに反映させる作業。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
* 自分が変更した内容を他の人が見ても理解できるように、具体的に変更内容を書くことが最適。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
* ### ローカルでマージするフロー
  * ローカルリポジトのブランチの変更内容を、ローカルリポジトの別のブランチにマージして反映させる。
* ### プルリクエストでマージするフロー
  * ローカルリポジトの変更内容をリモートリポジトリへマージする依頼を行ってから、リモートリポジトリへマージして変更内容を反映させる。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
1. 先にマージされた変更内容を取り込む
1. 後にマージしようとしている変更内容を取り込む
1. どちらの変更内容も取り込む
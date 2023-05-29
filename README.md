# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

*リモートリポジトリ：ネット上に配置して複数人で共有するためのリポジトリ。
*ローカルリポジトリ：開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ。


## プッシュとマージの違いは何でしょうか？

*プッシュ：ローカルリポジトリの内容をリモートリポジトリに反映させる。
*マージ：作業用の別ブランチ変更した作業内容をブランチに取り込むこと。


## コミットとプッシュの違い

*コミット：ローカルリポジトリで変更した内容を保存
*プッシュ：コミットした内容をリモートリポジトリへ反映させること。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

*その履歴でどんな編集を行なったのか、編集内容を正確に表すこと。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

*ローカルでマージするフローではリモートのmasterブランチに内容変更を反映させるだけなので、最後までバグがあることに気づかずバグがあるまま本番環境にアップする可能性が出てくる。
*プルリクエストでマージするフローではコードレビューをしてからマージするという手順を踏むことで、事前にバグを発見する事ができる。開発者と利用者の間にレビュー＆マージ担当者がはいるのでバグが起こりにくい。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？

*エラーメッセージを読み、修正する。（いらない部分の削除）
*先にマージされた変更内容を取り込む。
*後にマージしようとしている変更内容を取り込む。
*どちらの変更内容も取り込む。
#about git
gitとは、分散管理型のバージョン管理システムのことで、元々はLinus Torvalds (2005)が作成したオープンソースソフトウェア管理のためのソフトウェアであった。
gitの利点として、変更履歴が残る、変更した箇所に戻ることができる、他人と共同編集できることが挙げられる。1つの元々のファイルに対して、コミットと呼ばれるアクションをすることによって変更履歴のデータを残していくことができる。

#git functions
コミットとは、[ファイル作成／変更／削除]の記録のことである。
いつ・誰が・なにを・どのような変更を加えたかについて、都度都度コミットにメッセージを残す（「どのような」を記載）。
対象ファイルは一つでも複数でもよく、コミットの単位はユーザーが自由に決定できる。



#git commands

・git init : gitの初期化、設定開始
・git status : ワークツリーのステータスを表示
・git config : 設定周りの確認・変更
・git log : ログの表示
・git diff : ファイルの差分を表示
・git add : ステージングエリアに追加
・git commit : コミットの実行
・git commit --amend --no-edit : コミットの修正
・git checkout : 削除されたファイルを復旧や過去コミットの復元など（元に戻す変更がstaging area/index内にある場合）
・git reset : コミットのリセット
・git revert : 「コミットの変更を打ち消す」コミット
・git rm : ファイルとindex情報の削除
・git clone : レポジトリをコピー
・git pull : リモートレポジトリの同期	
・git push : 変更をアップロードする
・git request-pull : プルリクエスト：変更依頼
・git remote : モートレポジトリの設定
・git branch : ブランチの作成
・git checkout : ブランチの切り替え
・git merge : ブランチの統合
    --ff-only: fast forward only. 変更のない統合先ブランチにマージ（参考）
・git clone : レポジトリをコピー
・git push : 変更をアップロードする
・
・
・
・
・

# git-hooksの説明
.git/hooks/配下にhooks以下を置くことで使用可能になります。
※chmodしないと権限エラーになって動作しない可能性があります。

## commit-msg
デフォルトで先頭にブランチ名を挿入します。
コミット時に自動でメッセージ置換します。  

## 置換文字列一覧

`#a => <add>`

`#f => <feature>`

`#b => <bugfix>`

参考URL:https://mono0926.com/programming/sourcetree/

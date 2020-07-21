# Practice

## ブランチ操作

### ブランチ一覧
```
git branch
git branch -a
git branch -r
```

### ブランチ作成/切換え
```
git checkout -b 作成ブランチ名
```

## ブランチ削除
```
git branch -D 削除ブランチ名
```

## ローカルへ取り込み
```
git pull
git pull --rebase origin master
```

## rebase
```
git rebase -i コミットID
```

## リモートへ反映
```
git push
git push -u origin master
```

## リモート接続
```
git remote add origin git@github.com:ArodrOnline/リポジトリ名.git
```

# Practice

## リポジトリ作成
```
git init
```

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

### ブランチ削除
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

## ステージング
```
git add -i
git add .
git add -p
git add -u
git add *.md
git add *.md *.txt 
git add -A
git add -f
git add [ディレクトリ名]
git add [ファイル名]
git add -v
git add -n
```

## リセット
```
git reset
git reset --hard
git reset --soft
git reset --mixed

git reset --hard HEAD^
git reset --soft HEAD^
git reset --mixed HEAD^
git reset --hard ORIG_HEAD
```

## 状態
```
git status
git status -s
```

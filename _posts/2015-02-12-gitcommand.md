---
layout: post
title: gitコマンドの転載
date: 2015-02-12
comments: true
categories: git
tags: [git, command]
---

- gitレポジトリをcloneで作成  
  git clone <git Url>
- ブランチを切り替える  
  git checkout ＜ブランチ名＞
- ブランチを作る  
  git checkout -b ＜ブランチ名＞
- ブランチの一覧  
  git branch
- リモートリポジトリ一覧  
  git remote -v
- 現在の状況の確認  
  git status
- 変更内容の確認  
  git diff
- 変更ファイルの追加  
  git add <ファイル名＞
- 変更のコミット  
  git commit -m ‘＜コメント＞’
- git上に対して、変更反映  
  git push <リモートリポジトリ名> <ブランチ名>
- gitログを確認  
  git log  
  git log —oneline

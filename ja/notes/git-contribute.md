---
title: git-contribute
description: 
published: true
date: 2022-02-24T13:13:25.096Z
tags: 
editor: markdown
dateCreated: 2022-02-12T06:37:06.593Z
---

# For Git Contributors（日本語）

## Gitを使い始めるときに役立つリソース
- [初心者向けGithubへのPullRequest方法 - Qiita（日本語）](https://qiita.com/samurai_runner/items/7442521bce2d6ac9330b)
- [プルリクエストの作成（英語）](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
- [マークダウンチートシート（英語）](https://qiita.com/samurai_runner/items/7442521bce2d6ac9330b)

## Gitを使ったドキュメント更新のルール

- [Githubのレポジトリ](https://github.com/henkaku-center/henkaku-wiki) を更新すると自動的（5分程度）にドキュメントに反映されます
- ドキュメントを変更する際には Pull Request 送ってください。レビューが必要であればレビューのリクエストをしてください
- 英語のドキュメントはトップディレクトリ、日本語のドキュメントは `ja` ディレクトリ配下に、 `同名のマークダウンファイル` として配置してください

```
> `ja/` ⇦ 日本語のファイル
> `notes/` 
> `README.md`
> `home.md` ⇦ 英語のファイル
```

- それぞれのディレクトリ内に軽いドキュメントを配置するため `notes` ディレクトリも設置しています
- 管理者に権限をもらわなくても、リポジトリをフォークして、自分のリポジトリに変更をプッシュしてください。そうすれば、　Pull Request　を送ることができます
- レポジトリの編集権限が欲しい場合は、 `#✍│documentation` チャンネルにてアクセス権限をリクエストしてください

## Wiki.jsを直接編集する

- GitHub に Pull Request を送らなくても直接 Wiki.js で直接ドキュメントを編集できます
- Wiki.js を編集したい方は、 `#✍│documentation` チャンネルにてアクセス権限をリクエストしてください

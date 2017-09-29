+++
author = "author"
date = "2017-09-29T13:03:30Z"
description = "description"
draft = true
keywords = ["key","words"]
tags = ["one","two"]
title = "second edit"
topics = ["topic 1"]
type = "post"

+++
日本語の記事をテストする
===
ちゃんと言語ごとに振り分けが可能になっているか確認。hugo-bootstrap-premiumテーマの場合だと、Markdown拡張子の最後を[somefile.ja.md]のようにISO3166-2形式にすればOK。config.tomlで言語の宣言をしておけば、各々変更が適用されるはず。

※詳細は[Hugo本家のドキュメント](https://gohugo.io/content-management/multilingual/)を参照

The official SSMU Powerlifting website
======================================

##How to contribute
If you are a member of ssmu powerlifting but not part of the ssmu-powerlifting organization on github,
please contact [jonfk](https://github.com/jonfk) to invite you. Pull Requests are welcome.

If you don't want to mess around with git, contact [jonfk](https://github.com/jonfk) for changes you would
like to see to the website.

##Instructions to add a news/blog post

If you are a member of ssmu-powerlifting and would like to add a news article or a blog post please follow
the above instructions.

Posts are in `_posts` and need to follow the convention of `date-title.md`. e.g. `2015-05-05-My-Blog-Post-Title.md`.
In the post, the first few lines need to be a [Front Matter](http://jekyllrb.com/docs/frontmatter/), with the following
information.
```yaml
---
layout: post
title: "Montreal Classic 2015"
date: 2015-02-15
author: Jonathan Fok kan
categories: news
---

This is the content of my post
```

The rest of the post can be the posts itself. The post will be rendered as [Markdown](http://commonmark.org/) with HTML.


##Instructions to add a profile

Add a file to directory `_profiles_collection/` with a username as filename with extension .md. e.g jonfk.md
In the file fill in the following attributes between the `---`, with no whitespace or new line before.

```yaml
---
fullname: Jonathan Fok kan
username: jonfk
image: /assets/images/profiles/jfk.png
weightClass: 66.0 kg
description: Software Engineer who likes to lift things up and put them down.
facebook: https://www.google.com/search?facebook
youtube: https://www.youtube.com/user/jonesdoe1
instagram: http://instagram.com/jonender
---
```

##Instructions to add a record

Add a record to `_data/comp_records.csv` or `_data/train_records.csv`, fill in the
record with the right amount of fields. No spaces before or after the field.

```csv
username,weightClass,bodyweight,squat,bench,deadlift,total,wilks,date,gender
jonfk,66kg,63.9kg,125.0kg,80.0kg,155.0kg,360.0kg,290.43,2014-11-08,male
```

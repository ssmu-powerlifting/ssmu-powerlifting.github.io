The official SSMU Powerlifting website
======================================

##Instructions to add a profile

Add a file to directory `_profiles_collection/` with a username as filename with extension .md. e.g jonfk.md
In the file fill in the following attributes between the `---`, with no whitespace or new line before.

```yaml
---
fullname: Jonathan Fok kan
nickname: jfk
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
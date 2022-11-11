---
title: "Wave a Flag"
date: 2022-11-06T13:02:11+02:00
tags: ["picoCTF", "General Skills"]
ShowReadingTime: true
ShowBreadCrumbs: true
---

Download the warm program.

```shell
cat warm;
```
returns Hello user! Pass me a -h to learn what I can do!-hOh, help? I actually don't do much, but I do have this flag here:

We can already see the flag here, but we can take it a step further. Give permissions of the executable with:

```shell
chmod +x warm
```

```shell
./warm -h
```
returns the flag.
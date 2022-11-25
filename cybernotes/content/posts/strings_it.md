---
title: "strings it"
date: 2022-11-24T13:38:01+02:00
tags: ["picoCTF 2019", "General Skills"]
ShowReadingTime: true
ShowBreadCrumbs: true
---

Download strings file and type the following command in the terminal.

```shell
strings strings | grep picoCTF
```

If you want to learn more about strings type the following command.

```shell
man strings
```

So, in a sense the strings command prints printable strings in a binary or object file. The second part of the command | grep picoCTF just searches through the file and prints the string that contains picoCTF.

Nice, you've got the flag!
---
title: "Convert hex to base64"
date: 2022-11-14T15:06:03+02:00
tags: ["Cryptopals", "Set 1"]
ShowReadingTime: true
ShowBreadCrumbs: true
---

Run the following command in the terminal.

```shell
echo '49276d206b696c6c696e6720796f757220627261696e206c696b65206120706f69736f6e6f7573206d757368726f6f6d' | xxd -p -r | base64
```

This produces the output that we want.

For learning something more run...

```shell
echo '49276d206b696c6c696e6720796f757220627261696e206c696b65206120706f69736f6e6f7573206d757368726f6f6d' | xxd -p -r
```

If you want to learn more about xxd or base64 run the following commands.

```shell
man xxd
```

```shell
man base64
```
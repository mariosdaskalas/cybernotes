---
title: "Tab Tab Attack"
date: 2022-11-12T16:13:24+02:00
tags: ["picoCTF 2021", "General Skills"]
ShowReadingTime: true
ShowBreadCrumbs: true
---

First dowload the Addadshashanammu.zip file.

Run the following command to unzip its contents.

```shell
unzip -u Addadshashanammu.zip
```

Then change directory to Addadshashanammu

```shell
cd Addadshashanammu/
```

We noticed that there are a lot of folders inside each one. So, we can either use Tab to autocomplete the path to the folders, until we reach to the deepest one.

Alternative, we can run this command when we are inside Addadshashanammu folder.

```shell
cd `find -printf '%d %p\n' | sort -n | tail -n 1 | cut -d ' ' -f 2-`
```

That in turn returns the deepest level of the folder structure.

```shell
bash: cd: ./Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku/fang-of-haynekhtnamet: Not a directory
```

```shell
cd Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku
```

```shell
cat fang-of-haynekhtnamet
```

We got the flag!
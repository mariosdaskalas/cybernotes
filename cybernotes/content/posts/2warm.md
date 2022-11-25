---
title: "2Warm"
date: 2022-11-22T14:07:19+02:00
tags: ["picoCTF 2019", "General Skills"]
ShowReadingTime: true
ShowBreadCrumbs: true
---

Can you convert the number 42 (base 10) to binary (base 2)?

Every decimal number has a representation in a binary form. For example, take the number 3, which is in the decimal format. In the binary form it is equal to '11'.

If you want to learn about this, I recommend look at the table below. 

[Decimal/Binary Conversion Table](https://www.exploringbinary.com/decimal-binary-conversion-table/).

![Decimal/Binary Conversion Table](/decimal_to_binary.png "Decimal/Binary Conversion Table")
Image Credit: [Decimal/Binary Conversion Table](https://www.exploringbinary.com/)

```shell
python3
print(bin(42)[2:])
```

The program above converts the decimal number '42' to it's binary representation. Nice, you've got the flag!
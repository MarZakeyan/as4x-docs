---
layout: page
title: "AsData/MoveFirst"
---


# MoveFirst մեթոդ 
 
[См. также](../Asdata.md) [Օրինակ](../../Examples/E_AsData.html) [Применяется к](../Asdata.md)

Նշորդը տեղափոխում է բաց տվյալների աղբյուրի առաջին տողի վրա։ 

Թույլատրվում է կանչել, եթե
* Տվյալների աղբյուրը հիմնված է SQL հարցման վրա և [բացվել է](OpenCursor.html) հետևյալ եղանակներից մեկով՝ [ASOpenStatic, ASOpenKeyset, ASOpenDynamic](../../Constants/const_opencursor_cursortype.html)։ 
* Տվյալների աղբյուրը հիմնված է մասիվի վրա։



## Շարահյուսություն

``` vb
object.MoveFirst
```

Բաղադրիչներն են՝


| Պարամետր | Նկարագրություն |
|--|--|
| object| Տվյալների աղբյուրի հղում։ |

---
layout: page
title: "AsData/Value"
---


# Value մեթոդ

[См. также](../Asdata.md) [Օրինակ](../../Examples/E_AsData.html) [Применяется к](../Asdata.md)

Վերադարձնում է ընթացիկ տողում սյունակի արժեքը։


## Շարահյուսություն

``` vb
object.Value(sColName)
```

Բաղադրիչներն են՝

| Պարամետր | Նկարագրություն |
|--|--|
| object| Տվյալների աղբյուրի հղում։ |
| sColName | Սյունակի ներքին անունը կամ համարը։ |


## Նկատառումներ

Այս հատկությունը հանդիսանում է AsData օբյեկտի լռությամբ հատկություն, հետևաբար կարելի է օգտագործել հատկության դիմելու կարճ գրելաձևը։
``` vb
'երկար գրելաձև
value = xDS.Value("STARTREM")

'կարճ գրելաձև
value = xDS("STARTREM")
``` 

## Տվյալի տիպ

Variant

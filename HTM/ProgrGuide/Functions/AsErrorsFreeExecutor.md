---
layout: page
title: "AsErrorsFreeExecutor օբյեկտ"
---


# AsErrorsFreeExecutor օբյեկտ 

AsErrorsFreeExecutor օբյեկտը նախատեսված է սկրիպտային ֆունկցիան անսխալ կանչելու համար։ Այսինքն՝ նշված ֆունկցիան կանչելու ժամանակ համակարգը չի կանգնի, այլ կշարունակի աշխատել, եթե առաջանար սխալ։ Առաջացած սխալի հաղորդագրությունը պահպանվում է հաշվետվության մեջ։ 

Տրված է նաև հնարավորություն սխալի առաջացման ժամանակ հաշվետվության մեջ գրանցել հավելյալ հաղորդագրություն։ Այդ նպատակով օբյեկտին տրվում է ևս մի ֆունկցիա, որը աշխատում է հիմնական ֆունկցիայի աշխատանիքի ժամանակ սխալի առաջացման դեպքում։ 

Սովորաբար օբյեկտը օգտագործվում է մեծ քանակությամբ տվյալներ մշակելու ժամանակ, ամեն մի տարրի մշակման համար նշված ֆունկցիան կանչելուվ։

AsErrorsFreeExecutor օբյեկտը ստեղծվում է [CreateErrorsFreeExecutor](Functions/CreateErrorsFreeExecutor.html) ֆունկցիայի միջոցով։


| Հատկություններ | Նկարագրություն |
|--|--|
| [ErrorsCount](AsErrorsFreeExecutor/ErrorsCount.md) | Վերադարձնում է առաջացած սխալների քանակը։ |
| [OnErrorRollBack](AsErrorsFreeExecutor/OnErrorRollBack.md) | (Արգելված) Վերադարձնում կամ նշանակում է սխալի առաջացման ժամանակ տրանզակցիայի հետ խաղացման հայտանիշը։ |
| [Properties](AsErrorsFreeExecutor/Properties.md) | Վերադարձնում է սկրիպտ գրողի կողմից մշակվող հատկությունները։ |
| [RepViewer](AsErrorsFreeExecutor/RepViewer.md) | Վերադարձնում կամ նշանակում է հաշվետվություն օբյեկտը, որի մեջ պահպանվում են սխալների հաղորդագրությունները։ |



| Մեթոդներ | Նկարագրություն |
|--|--|
| [Run](AsErrorsFreeExecutor/Run_Err.md) | Կանչում է սկրիպտային ֆունկցիան։ |
| [RunEx](AsErrorsFreeExecutor/RunEx_Err.md) | Կանչում է սկրիպտային ֆունկցիան, ինչպես նաև վերադարձնում է `ByRef` պարամետրերը։ |
| [SetErrSubParams](AsErrorsFreeExecutor/SetErrSubParams.md) | Տրվում են պարամետրեր, սխալի մասին հավելյալ հաղորդագրություն դուրս բերող ֆունկցիային փոխանցման համար։ Եթե պարամետրերը տրված չեն, ապա ֆունկցիային փոխանցվում են `Run` մեթոդի պարամետրերը։ |




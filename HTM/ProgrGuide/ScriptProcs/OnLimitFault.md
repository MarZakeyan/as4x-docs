﻿<html>
<head>
<title>Системное событие OnLimitFault</title>
</head>

<body>

<p><font size="4" face="Arial"><strong>Событие OnLimitFault<br>
<br>
</strong></font><font face="Arial"><a href="../scriptstproced.html">См. 
также</a>&nbsp; <u>Пример</u>&nbsp; <a href="../Defs/Accounting.html">Применяется 
к</a></font></p>

<p class="label"><font face="Arial">Генерируется при неудачной 
проверке лимитов, наложенных на объект учета, при использовании методов 
документа <a
href="../Functions/ASDOC/CheckAndStore.html">CheckAndStore</a>, <a
href="../Functions/ASDOC/HiDelete.html">HiDelete</a>. В обработчике данного 
события удобно выдавать сообщения об ошибках при нарушении допустимых границ 
остатков объекта. При аккумулирующем объекте учета событие также возвращает 
признак того нужно ли игнорировать данное событие или нет.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p class="label"><font face="Arial">Для учетов работaющиx с HI без связаноого 
учета:</font></p>

<p><font face="Arial">Function <strong>OnLimitFault</strong>(<em>nISN</em>,
<i>nOverrunning, </i>[<i>bDeleteDoc</i>, <i>oDoc</i>])<br>
<em>&nbsp;&nbsp; statements</em><br>
End Function</font></p>

<p class="label"><font face="Arial">Для учетов работaющиx с HI со связаным 
учетом:</font></p>

<p><font face="Arial">Function <strong>OnLimitFault</strong>(<em>nISN</em>,
<i>nOverrunning, nOverrunningLinked, bDeleteDoc</i>, <i>oDoc</i>)<br>
<em>&nbsp;&nbsp; statements</em><br>
End Function</font></p>

<p><font face="Arial">Для учетов работaющиx с HI2:</font></p>

<p><font face="Arial">Sub <strong>OnLimitFault</strong>(<em>nISN</em>, 
[<em>nGLISN</em>], [<i>bDeleteDoc</i>, <i>oDoc</i>])<br>
<em>&nbsp;&nbsp; statements</em><br>
End Sub</font></p>

<p><font face="Arial">Синтаксис события <strong>OnLimitFault</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">nISN</font></em></td>
    <td width="71%"><font face="Arial">численное выражение, 
	определяющее ISN объекта учета</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">nGLISN</font></em></td>
    <td width="71%"><font face="Arial">численное выражение, 
	определяющее ISN аккумулирующего объекта учета. Данный параметр необходим 
	для проверки лимитов в таблице HIREST2.</font></td>
  </tr>
    <tr>
    <td width="29%"><font face="Arial"><i>nOverrunning</i></font></td>
    <td width="71%"><font face="Arial">численное выражение, 
	определяющее величину выхода из пределов. Если значение отрицательно то имел 
	место выход за рамки нижнего прeдела. При положительной величине имел место 
	выход за рамки верхнего прeдела. </font></td>
    </tr>
  <tr>
    <td width="29%"><font face="Arial">
<i>nOverrunningLinked</i></font></td>
    <td width="71%"><font face="Arial">численное выражение, 
	определяющее величину выхода из пределов связаного учета.</font></td>
  </tr>
  <tr>
    <td width="29%"><i><font face="Arial">bDeleteDoc</font></i></td>
    <td width="71%"><font face="Arial">логическое выражение, 
	определяющее признак того, возникла ли проверка во время удаления документа 
	или нет. </font></td>
  </tr>
  <tr>
    <td width="29%"><i><font face="Arial">oDoc</font></i></td>
    <td width="71%"><font face="Arial">объект
    <a href="../Functions/Asdoc.html">документ</a>, определяющее документ 
	генерировавшее данное событие.</font></td>
  </tr>
</table>
</body>
</html>
﻿<html>
<head>
<title>Param</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Свойство Param</font></strong></p>

<p><font face="Arial">Возвращает или устанавливает значение указанного 
параметра.</font></p>

<p><font face="Arial">Возвращаемое значение - типа Variant. Свойство 
для чтения и записи.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>Param</strong>(<em>sParId</em>)[=<em>sValue</em>]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</font></p>

<p><font face="Arial">Синтаксис свойства <b>Param</b>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><font face="Arial"><em>sParId</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее код параметра из таблицы <a href="../../../Database/Params.html">
	PARAMS</a>.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sValue</em></font></td>
    <td width="71%"><font face="Arial">подставляемое значение 
	параметра, строковое выражение типа Variant </font></td>
  </tr>
</TBODY>
</table>

<p class="label">&nbsp;</p>

<p class="label"><b><font face="Arial">Примечание &nbsp;</font></b></p>

<p class="label"><font face="Arial">Если параметр является перманентно 
загруженным в память, то он приводится из памяти, в противном случае из таблицы. 
Пользователе-зависимые параметры приводятся со значением для текущего 
пользователя. При попытке присвоения&nbsp;&nbsp; значения не существующему 
параметру, будет выведено сообщение об ошибке. Если подставляемое значение 
параметра не соответствует определению его типа, то будет сгенерирована ошибка. 
При присвоении нового значения перманентно загруженному параметру, его значение 
изменяется только в памяти, но не в базе (см. <a href="SetParam.html">SetParam</a>).</font></p>

<p class="label"><a href="../../../Database/Params.html"><font face="Arial">
См. также</font></a></p>

<p>&nbsp;</p>

<h1><font size="3" face="Arial"><strong>Пример свойства Param</strong></font></h1>

<p><font face="Arial">Выводится значение параметра SYSISN и 
присваивается переменной ISNValue типа Variant.</font></p>

<p><font face="Arial">ISNValue=Param(&quot;SYSISN&quot;)</font></p>

<p><font face="Arial">Изменяется значение параметра CliCod 
целочисленного типа.</font></p>

<p><font face="Arial">Param(&quot;CliCod&quot;)=256</font></p>
</body>
</html>
﻿<html>
<head>
<title>Data</title>
</head>

<body>

<h1><font size="4" face="Arial">Функция Data<br>
</font><a href="../../Asdata.html"><font face="Arial" size="3"><strong>
свойства&nbsp;&nbsp; методы</strong></font></a></h1>

<p><font face="Arial">Создает экземпляр объекта типа источник данных.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>set</strong><em> sDataName</em><strong> 
= Data</strong>(<em>DataID</em>)<strong><br>
</strong><br>
Синтаксис функции<b> Data</b> состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">sDataName</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее переменную, ссылающуюся на экземпляр объекта источник данных. 
	Через нее можно получить доступ к свойствам и методам объекта.</font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><font face="Arial"><em>DataID</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор источника данных</font></td>
  </tr>
</TBODY>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><a href="../../../constructors.html"><font face="Arial">
См. также</font></a></p>

<p class="label">&nbsp;</p>

<h1><font face="Arial" size="3"><strong>Пример функции Data</strong></font></h1>

<p><font face="Arial">В примере вызывается функция Data, через xDS 
возвращается ссылка на источник данных NBTURN2 со всеми его свойствами и 
методами. </font></p>

<p><font face="Arial">set xDS = <strong>DATA</strong>(&quot;NBTURN2&quot;)<br>
xDS.Parameters(1) = xBal<br>
xDS.Parameters(2) = &quot;%/%&quot;<br>
xDS.Parameters(3) = &quot;%&quot;<br>
xDS.OpenCursor<br>
<br>
Do While not xDS.EOF<br>
&nbsp;&nbsp; xDSSTARTREM = CCur(AsRoundDiv(xDS(&quot;STARTREM&quot;),cInt(RoundRate))) <br>
&nbsp;&nbsp; STARTREM_Row = STARTREM_Row+ xDSSTARTREM<br>
xDS.MoveNext<br>
Loop <br>
<br>
xDS.CloseCursor&nbsp;&nbsp;&nbsp;&nbsp; </font></p>
</body>
</html>
<html>
<head>
<title>Диалог\LeftDouble</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Свойство LeftDouble<br>
<br>
</font></strong><font face="Arial"><a href="../Asustpar.html">См. также</a>&nbsp;
<a href="../../Examples/E_AsUstPar.html">Пример</a>&nbsp; <a href="../Asustpar.html">
Применяется к</a></font></p>

<p><font face="Arial">Возвращает или устанавливает удаленность левого 
края всех имеющихся вторичных реквизитов от левого края пользовательского 
диалога.<br>
Свойство для чтения и записи. </font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>object.</em><strong>LeftDouble = </strong>[<em>vValue</em>]</font></p>

<p><font face="Arial">Синтаксис свойства <strong>LeftDouble</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">object</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее переменную, ссылающуюся на экземпляр объекта пользовательского 
	диалога.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>vValue</em></font></td>
    <td width="71%"><font face="Arial">выражение типа Single, 
	определяющее расстояние между выравниванием левых краев вторичных реквизитов 
	и левого края пользовательского диалога.</font></td>
  </tr>
</TBODY>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Установки</b></font></p>

<p><font face="Arial">Установки для <em>vValue</em>
следующие:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><strong>Значение</strong></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><font face="Arial">0 или свойство отсутствует</font></td>
    <td width="71%"><font face="Arial">удаленность определяется 
	автоматически программой, исходя из длины максимального заголовка, 
	имеющегося на форме. </font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial">другое значение</font></td>
    <td width="71%"><font face="Arial">берется значение указанное 
	пользователем, причем нужно быть внимательным, чтобы вторичный реквизит не 
	наложился на предыдущий.</font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>
</body>
</html>
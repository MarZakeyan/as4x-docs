﻿<html>
<head>
<title>Текущий вид просмотра\Updated</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Свойство Updated<br>
<br>
</font></strong><font face="Arial"><a href="../Frmpttel.html">См. также</a>&nbsp;
<u>Пример</u>&nbsp; <a href="../Frmpttel.html">Применяется к</a></font></p>

<p><font face="Arial">Возвращает или устанавливает разрешение на 
обновление текущей папки.</font></p>

<p><font face="Arial">Свойство для чтения и записи. </font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>object</em><strong>.Updated = [</strong><em>bValue</em><strong>]</strong></font></p>

<p><font face="Arial">Синтаксис свойства <strong>Updated</strong>
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
	определяющее переменную, ссылающуюся на текущую папку.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">bValue</font></em></td>
    <td width="71%"><font face="Arial">логическое выражение, 
	определяющее разрешение на обновление формы.</font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание<br>
<br>
</b>При завершении выполнения пользовательских функций в форме прокрутки папок, 
система автоматически обновляет форму. Для предотвращения автоматического 
обновления, нужно установить значение свойства <strong>Updated</strong>
в False. В этом случае использование метода <a
href="Update.html">Update</a> будет игнорировано.</font></p>
</body>
</html>
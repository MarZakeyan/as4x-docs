﻿<html>
<head>
<title>LoadDocFromFolder</title>
</head>

<body>

<h1><font face="Arial"><font size="4">Функция LoadDocFromFolder<br>
</font><font size="3"><a href="../../Asdoc.html"><strong>свойства&nbsp;&nbsp; 
методы</strong></a></font></font></h1>

<p><font face="Arial">Загружает документ по имени папки и ключу.</font></p>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>set</strong> <em>sDoc</em><strong> = 
LoadDocFromFolder (</strong><em>FolderId</em><strong>,</strong><em> Key</em><strong>)</strong></font></p>

<p><font face="Arial">Синтаксис функции <strong>LoadDocFromFolder</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><font face="Arial"><em>sDoc</em></font></td>
    <td width="71%"><font face="Arial">переменная, ссылающаяся на 
	загружаемый документ</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>FolderId</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор папки</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>Key</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее ключ элемента папки</font></td>
  </tr>
</table>

<p><font face="Arial">При отсутствии папки с заданным идентификатором 
или ключом, возвращается Nothing.<br>
</font></p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><a href="../../../constructors.html"><font face="Arial">
См. также</font></a></p>

<p class="label">&nbsp;</p>

<p><font face="Arial"><strong><font size="3">Пример функции </font>
LoadDocFromFolder</strong></font></p>

<p><font face="Arial">В примере вызывается функция LoadDocFromFolder, 
mDoc ссылается на обьект типа документ со всеми его свойствами и методами. 
Загружается документ из папки ACCCRLN c ключом doc(&quot;CODE&quot;).</font></p>

<p><font face="Arial">Set mDoc =<strong> LoadDocFromFolder</strong>(&quot;ACCCRLN&quot;, 
doc(&quot;CODE&quot;))<br>
</font></p>
</body>
</html>
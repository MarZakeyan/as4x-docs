﻿<html>
<head>
<title>TreeElements</title>
</head>

<body>

<p><font face="Arial"><font size="4"><strong>Функция TreeElements<br>
<br>
</strong></font>Возвращает объект Dictionary, где содержатся
<a href="../../AsTreeElement.html">объекты типа элемент дерева</a>. Доступ и 
обновление элементов коллекции происходит в соответствии с правилами языка 
SaxBasic, с помощью <a href="../../ASDOC/Properties.html#Dictionary">методов и 
свойств объекта Dictionary</a>. </font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>TreeElements (</strong><em>sTreeId, </em>
[<em>sNodeType</em>]<em>,
</em>[<em>sKey</em>]<strong>)</strong></font></p>

<p><font face="Arial">Синтаксис функции <strong>TreeElements</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%"><em><font face="Arial">sTreeId</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор дерева.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">sNodeType</font></em></td>
    <td width="71%"><font face="Arial">необязательное строковое 
	выражение, определяющее тип возвращаемых элементов дерева.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">sKey</font></em></td>
    <td width="71%"><font face="Arial">необязательное строковое 
	выражение, определяющее код элемента в дереве, начиная с которого приводится 
	поддерево.</font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Установки</b></font></p>

<p><font face="Arial">Установки для <em>sNodeType</em>
следующие:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="20%"><font face="Arial"><strong>Значение</strong></font></td>
    <td class="label" width="80%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">&quot;&quot;</font></td>
    <td width="80%"><font face="Arial">значение по умолчанию, 
	выводятся все элементы дерева.</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">&quot;1&quot;</font></td>
    <td width="80%"><font face="Arial">выводятся только лепестки - 
	элементы дерева, не имеющие сами потомков и находящиеся на самом последнем 
	уровне.</font></td>
  </tr>
  <tr vAlign="top">
    <td width="20%"><font face="Arial">&quot;0&quot;</font></td>
    <td width="80%"><font face="Arial">выводятся только группировочные 
	узловые элементы дерева, т.е. все элементы не являющиеся лепестками.</font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><font face="Arial"><a href="../../AsTreeElement.html">
См. также</a></font></p>
</body>
</html>
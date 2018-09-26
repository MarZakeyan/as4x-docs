﻿<html>
<head>
<title>Dialog\AddViewControlAtRight</title>
    <style type="text/css">
        .style1
        {
            height: 47px;
        }
    </style>
</head>

<body>

<p><font size="4" face="Arial"><strong>Метод AddViewControlAtRight<br>
<br>
</strong></font><font face="Arial"><a href="AddMultiSelectViewControl.html">
См. также</a>&nbsp;
<u>Пример</u>&nbsp; <a href="../Asustpar.html">Применяется к</a></font></p>

<p><font face="Arial">Добавляет в пользовательский диалог реквизит 
типа произвольный вспомогательный список выбора, справа от указанного реквизита. 
Вспомогательный список может содержать несколько колонок из вида просмотра, но 
две колонки должны быть специально объявлены для кода и наименования.</font></p>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>
<p><font face="Arial"><em>object</em>.<strong>AddViewControlAtRight(</strong><em>rekvName, 
    existingRekvName, caption, 
    eCaption, viewCode,</em><strong> </strong><em>codeColumnId, 
    commentColumnId, </em>[<em>attribRekv</em>]<em>, </em>[<em>valueRekv</em>]<em>, 
    params()</em><strong> )</strong></font></p>
<p><font face="Arial">Синтаксис метода <strong>AddViewControlAtRight</strong>
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
    <td width="29%"><font face="Arial"><em>rekvName</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор реквизита в диалоге.</font></td>
  </tr>
	<tr>
    <td width="29%"><font face="Arial"><em>existingRekvName</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор уже существующего в диалоге реквизита, справа от 
	которого будет добален новый.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>caption</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок реквизита в диалоге.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>eCaption</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок реквизита в диалоге на иностранном языке.</font></td>
  </tr>
  <tr>
    <td width="29%" class="style1"><font face="Arial"><em>viewCode</em></font></td>
    <td width="71%" class="style1"><font face="Arial">строковое выражение, 
	определяющее идентификатор базового вида просмотра, приводимого для выбора 
	значения.</font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%"><font face="Arial"><em>codeColumnId</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор значимой колонки из вида просмотра. Значение 
	данной колонки будет подставлено в поле, после выбора из списка.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>commentColumnId</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, определяющее наименование 
        значимой колонки из вида просмотра. </font></td>
  </tr>
  <tr>
    <td width="29%">a<em><font face="Arial">ttribRekv</font></em></td>
    <td width="71%"><font face="Arial">необязательное строковое 
	выражение, определяющее <a href="Attribute.html">атрибуты</a>
    реквизита (их может быть несколько). </font></td>
  </tr>
<tr>
    <td width="29%"><font face="Arial"><em>valueRekv</em></font></td>
    <td width="71%"><font face="Arial">необязательное выражение типа 
	Variant, определяющее первоначальное значение реквизита.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>params()</em></font></td>
    <td width="71%"><font face="Arial">массив параметров, передаваемых 
	для подстановки в вид просмотра.
    </font></td>
  </tr>
</table>

</body>
</html>
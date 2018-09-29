<html>
<head>
<title>Диалог\AddViewControl</title>
</head>

<body>

<p><font size="4" face="Arial"><strong>Метод AddViewControl<br>
<br>
</strong></font><font face="Arial"><a href="AddMultiSelectViewControl.html">
См. также</a>&nbsp;
<u>Пример</u>&nbsp; <a href="../Asustpar.html">Применяется к</a></font></p>

<p><font face="Arial">Добавляет в пользовательский диалог реквизит 
типа произвольный вспомогательный список выбора. Вспомогательный список может 
содержать несколько колонок из вида просмотра, но две колонки должны быть 
специально объявлены для кода и наименования.</font></p>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>call</strong> <em>object</em>.<strong>AddViewControl 
(</strong><em>sControlName, sControlCaption, sControlЕCaption, sViewCode</em><strong>, </strong><em>
CodeColumnId, CommentColumnId, </em>[<em>AttribRekv</em>]<em>, </em>[<em>ValueRekv</em>]<em>, 
Params()</em><strong> )</strong></font></p>

<p><font face="Arial">Синтаксис метода <strong>AddViewControl</strong>
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
    <td width="29%"><em><font face="Arial">sControlName</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор реквизита в диалоге.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sControlCaption</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок реквизита в диалоге.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sControlЕCaption</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок реквизита в диалоге на иностранном языке.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sViewCode</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор базового вида просмотра, приводимого для выбора 
	значения.</font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%"><font face="Arial"><em>CodeColumnId</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор значимой колонки из вида просмотра. Значение 
	данной колонки будет подставлено в поле, после выбора из списка.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>CommentColumnId</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор колонки наименования из вида просмотра. </font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">AttribRekv</font></em></td>
    <td width="71%"><font face="Arial">необязательное строковое 
	выражение, определяющее <a href="Attribute.html">атрибуты</a>
    реквизита (их может быть несколько). </font></td>
  </tr>
<tr>
    <td width="29%"><em><font face="Arial">ValueRekv</font></em></td>
    <td width="71%"><font face="Arial">необязательное выражение типа 
	Variant, определяющее первоначальное значение реквизита.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>Params()</em></font></td>
    <td width="71%"><font face="Arial">массив параметров, передаваемых 
	для подстановки в вид просмотра.
    </font></td>
  </tr>
</table>

</body>
</html>
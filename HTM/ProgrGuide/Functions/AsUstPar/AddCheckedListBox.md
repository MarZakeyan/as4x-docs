<html>
<head>
<title>Диалог\AddCheckedListBox</title>
    <style type="text/css">
        .style1
        {
            height: 47px;
        }
        .style2
        {
            height: 64px;
        }
        .style3
        {
            font-family: Arial;
        }
    </style>
</head>

<body>

<p><strong><font size="4" face="Arial">Метод AddCheckedListBox<br>
<br>
</font></strong><font face="Arial"><a href="../Asustpar.html">См. также</a>&nbsp;
<u>Пример</u>&nbsp; <a href="../Asustpar.html">
Применяется к</a></font></p>

<p>&nbsp;</p>
    <p><font face="Arial">Добавляет группу флажков в пользовательский диалог.</font></p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>call</strong> <em>object</em>.<strong>AddCheckedListBox(</strong><em>sRekvName, 
    sCaptionRekv, xArray</em></font>, <font face="Arial"><em>[ECaptionRekv] </em>
    <strong>, </strong><em>[nWidth] </em><strong>, </strong>&nbsp;<em>[nHeight]</em><strong> 
    , </strong><em>[iSaveValue]</em><strong> )</strong></font></p>

<p><font face="Arial">Синтаксис метода <strong>AddCheckedListBox</strong>
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
    <td width="29%"><em><font face="Arial">sRekvName</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор группы флажков в диалоге.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sCaptionRekv</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок группы флажков в диалоге.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>xArray</em></font></td>
    <td width="71%"><font face="Arial">выражение типа
	<a href="../Functions/CreateXArrayDB.html">XArrayDB</a>, определяющее 
	коллекцию флажков. Состоит из четырех колонок. В первой колонке 
	задается его логическое значение , во второй колонке - его идентификатор, в третьей 
        - его заголовок, а в четвертой - заголовок на ииностранном языке. </font></td>
  </tr>
    <tr>
    <td width="29%" class="style1"><em><font face="Arial">ECaptionRekv</font></em></td>
    <td width="71%" class="style1"><font face="Arial">необязательное строковое 
	выражение, определяющее заголовок группы флажков в диалоге на 
	иностранном языке.</font></td>
    </tr>
  <tr>
    <td width="29%"> <font face="Arial"><em>nWidth</em></font></td>
    <td width="71%"><font face="Arial">числовое выражение, определяющее ширину группы 
        флажков.</font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%"> <font face="Arial"><em>nHeight</em></font></td>
    <td width="71%"><font face="Arial">числовое выражение, определяющее высоту группы 
        флажков.</font></td>
  </tr>
  <tr>
    <td width="29%" class="style2"><em><font face="Arial">iSaveValue</font></em></td>
    <td width="71%" class="style2"><font face="Arial">необязательное численное 
	выражение, определяющее признак запоминания значений группы флажков. При 1 - текущее значение реквизита запоминается в реестре, а при 
	значении 0 - нет. По умолчанию принимает значение 1.</font></td>
  </tr>
</table>
    <p>
        &nbsp;</p>
    <p>
        <font face="Arial"><b>

        Примечание</b></font></p>
    <span class="style3">Обрашение к отдельным 
    членам группы флажков осуществляется с помощью свойства</span> <em><font face="Arial">
    <strong>object.</strong></font></em><span class="style3"><strong><em>ValueItem</em>(&quot;</strong></span><em><font face="Arial"><strong>sRekvName</strong></font></em><strong><span 
        class="style3">&quot;,</span> &quot;<span class="style3"><em>sChBoxName</em></span>&quot;)</strong>,
    <span class="style3">где <strong><em>sChBoxName</em></strong> - идентификатор из 
    группы флажков.</span>

</body>
</html>
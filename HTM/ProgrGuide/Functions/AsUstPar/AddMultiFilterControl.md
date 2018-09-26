﻿<html>
<head>
<title>Диалог\AddMultiFilterControl</title>
    <style type="text/css">
        .style1
        {
            width: 29%;
        }
        .style2
        {
            width: 29%;
            height: 29px;
        }
        .style3
        {
            height: 29px;
        }
        .style4
        {
            font-weight: normal;
        }
    </style>
</head>

<body>

<p><font size="4" face="Arial"><strong>Метод AddMultiFilterControl<br>
<br>
</strong></font><font face="Arial"><a href="AddMultiFilterControlAtRight.html">
См. также</a>&nbsp;&nbsp;<u>Пример</u>&nbsp; <a href="../Asustpar.html">Применяется к</a></font></p>
    <p><font face="Arial">Данный метод дает возможность добавления в пользовательском диалоге реквизита 
        следующих трех типов:</font></p>
    <p style="margin-left: 40px">0.<font face="Arial"> <a href="../AsModalBrowser.html">
        реквизит типа произвольный вспомогательный список выбора</a>, с возможностью <a href="../AsModalBrowser/MultiSelect.html">отбора нескольких 
строк</a></font></p>
    <p style="margin-left: 40px">1.<font face="Arial"> реквизит типа дерева-справочника</a>, 
с возможностью <a href="../AsModalBrowser/MultiSelect.html">отбора нескольких 
строк</a> </font></p>
    <p style="margin-left: 40px">2<font face="Arial">. реквизит типа сопоставимости с 
        введенным значением, без возможности <a href="../AsModalBrowser/MultiSelect.html">отбора нескольких 
строк</a>.</font></p>
    <p style="margin-left: 0px"><font face="Arial">После выхода из поля слева от его 
        значения добавляются числа&nbsp; 0,1 или 2, которые соостветствуют номеру 
        выбранного типа</font>.</p>
    <p style="margin-left: 40px">&nbsp;</p>
    <p style="margin-left: 40px">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</p>

<p><font face="Arial"><strong>call</strong> <span class="style4"> <em>object</em></span>.<strong>AddMultiFilterControl 
(</strong></b><em>sNameControl, sCaptionControl, sЕCaptionControl, sTreeMultiFilter, sViewCode</em><b>, 
    </b> 
    <em>
    sColCodeName, Params()</em><b><strong>)</strong></b></font></p>

<p><font face="Arial">Синтаксис метода<b> <strong><b>AddMultiFilterControl </b></strong>
    </b>состоит из следующих частей:</font><b></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="style1"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td class="style1"><em><font face="Arial">object</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее переменную, ссылающуюся на экземпляр объекта пользовательского 
	диалога.</font></td>
  </tr>
  <tr>
    <td class="style1"><em><font face="Arial">sNameControl</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор реквизита в диалоге.</font></td>
  </tr>
  <tr>
    <td class="style1"><font face="Arial"><em>sCaptionControl,</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок реквизита в диалоге.</font></td>
  </tr>
  <tr>
    <td class="style1"><font face="Arial"><em>sЕCaptionControl,</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок реквизита в диалоге на иностранном языке.</font></td>
  </tr>
    <tr>
    <td class="style1"><font face="Arial"><em>sViewCode</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор базового вида просмотра, приводимого для выбора 
	значения.</font></td>
    </tr>
  <tr>
    <td class="style1"><font face="Arial"><em>sTreeMultiFilter<br />
        </em></font></td>
    <td width="71%"><font face="Arial">задает тип дерева
        <a href="../../Types/Tree().html">Tree()</a> 
        или <a
href="../../Types/FULLTREE().html">FullTree()</a>. При отсутствии данного параметра возможность 
        добавления реквизита типа дерева-справочника отпадает.</font></td>
  </tr>
</TBODY>
  <tr>
    <td class="style1"><em>
        <font face="Arial">sColCodeName</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор значимой колонки из вида просмотра. Значение 
	данной колонки будет подставлено в поле после выбора из списка.</font></td>
  </tr>
  <tr>
    <td class="style2"><font face="Arial"><em>Params()</em></font></td>
    <td width="71%" class="style3"><font face="Arial">массив параметров, передаваемых 
	для подстановки в вид просмотра.
    </font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>
    </b>
    <p class="label">Третий тип отпадает если в системном событии диалога&nbsp; <font face="Arial"> 
        <strong>Activate</a></strong> 
        значение <em><strong>object</strong></em>.<em><strong>Control</strong></em><strong>(&quot;</strong><em><strong>sNameControl</strong></em>&quot;<strong>).DisableLikeMode 
        = True</strong>.</font></p>
    <b>
    <p class="label">&nbsp;</p>
    <p class="label">
        &nbsp;</p>
</html>
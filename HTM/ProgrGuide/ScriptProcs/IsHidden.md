﻿<html>
<head>
<title>Системное событие документа IsHidden </title>
    <style type="text/css">
        .style1
        {
            font-family: Arial, Helvetica, sans-serif;
        }
        .style2
        {
            width: 245%;
        }
        .style3
        {
            width: 245%;
            height: 145px;
        }
    </style>
</head>

<body>

<p><strong><font size="4" face="Arial">Событие IsHidden<br>
<br>
</font></strong><font face="Arial"><a href="../scriptstproced.html">См. 
также</a>&nbsp; <u>Пример</u>&nbsp; <a
href="../Defs/doc.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">Генерируется перед генерацией 
событии When, запоняет Dictionary скрытых реквизитов. Служит для скрытия 
некоторых реквизитов во время выполнения. Последовательность генерации системных 
событий для документа приведена здесь <a href="Events_Sequence.html"><img
src="../../../IMAGES/More.gif" width="12" height="12" alt="More.gif (304 bytes)"
border="0"></a>.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Sub <strong>IsHidden </strong>(<i>ByVal Dict as 
Scripting.Dictionary</i>)<br>
&nbsp;</font></p>
<p><font face="Arial">End Sub</font></p>

<p>&nbsp;</p>

<p><font face="Arial">Синтаксис события <strong>IsHidden</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><i>Dict </i></font></td>
    <td width="71%"><font face="Arial">объект типа <i>
	Scripting.Dictionary</i></font></td>
  </tr>
  </table>

<p><font face="Arial"><b>Пример</b></font></p>
    <p><span class="style1">Добавим несколько обьектов в список невидимости. В 
        приведенных примерах обьекты становятся невидимыми.</span></p>

<table border="1" cellPadding="5" cols="1" frame="border" rules="rows" 
        style="height: 38px; width: 831px">
<TBODY>
  <tr vAlign="top">
    <td class="style2">
    <p class="style1">
        <em>Скрытие реквизита, где имя реквизита FILIAL:</em></p>
    <p class="MsoNormal">
        <span class="style1" lang="EN" style="mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri;mso-bidi-font-family:Calibri;mso-ansi-language:
EN">Sub <strong>IsHidden </strong>(<em>ByVal HiddenControls As Dictionary</em>)<o:p></o:p></span></p>
    <p class="MsoNormal">
        <span lang="EN" style="mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri;mso-bidi-font-family:Calibri;mso-ansi-language:
EN"><span class="style1" style="mso-tab-count:1">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </span><span class="style1">HiddenControls.Add &quot;FILIAL&quot;, &quot;FILIAL&quot;</span><o:p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        <span class="style1"><em>&#39;Реквизит невидим</em></span></o:p></span></p>
    <p class="MsoNormal">
        <span class="style1" lang="EN" style="mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri;mso-bidi-font-family:Calibri;mso-ansi-language:
EN">End Sub</span><o:p></o:p></p>
      </td>
  </tr>
  <tr>
    <td class="style3">
    <p class="style1"><em>Скрытие колонкой Grid таблицы, где имя грид таблицы GRID1, 
        а колонки FILIALCOL:</em></p>
    <p class="MsoNormal">
        <span class="style1" lang="EN" style="mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri;mso-bidi-font-family:Calibri;mso-ansi-language:
EN">Sub <strong>IsHidden </strong>(<em>ByVal HiddenControls As Dictionary</em>)<o:p></o:p></span></p>
    <p class="MsoNormal">
        <span lang="EN" style="mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri;mso-bidi-font-family:Calibri;mso-ansi-language:
EN"><span class="style1" style="mso-tab-count:1">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </span><span class="style1">HiddenControls.Add &quot;GRID1.FILIALCOL&quot;, &quot;GRID1.FILIALCOL1&quot;</span><o:p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        <span class="style1"><em>&#39;Колонка невидима</em></span></o:p></span></p>
    <p class="MsoNormal">
        <span class="style1" lang="EN" style="mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri;mso-bidi-font-family:Calibri;mso-ansi-language:
EN">End Sub</span><o:p></o:p></p>
      </td>
  </tr>
  <tr>
    <td class="style2">
    <p class="style1"><em>Скрытие страницы документа, где имя задается в следующем 
        формате - &quot;PAGE {NAME=&quot;PAGENAME&quot;; CAPTION=#Name; ECAPTION=#e_Name;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
        ...&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }; </em></p>
    <p class="MsoNormal">
        <span class="style1" lang="EN" style="mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri;mso-bidi-font-family:Calibri;mso-ansi-language:
EN">Sub <strong>IsHidden </strong>(<em>ByVal HiddenControls As Dictionary</em>)<o:p></o:p></span></p>
    <p class="MsoNormal">
        <span lang="EN" style="mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri;mso-bidi-font-family:Calibri;mso-ansi-language:
EN"><span class="style1" style="mso-tab-count:1">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </span><span class="style1">HiddenControls.Add &quot;PAGENAME&quot;, &quot;PAGENAME&quot;</span><o:p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        <span class="style1"><em>&#39;Страница невидима</em></span></o:p></span></p>
    <p class="MsoNormal">
        <span class="style1" lang="EN" style="mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri;mso-bidi-font-family:Calibri;mso-ansi-language:
EN">End Sub</span><o:p></o:p></p>
      </td>
  </tr>
  </table>

    <p class="MsoNormal">
        <o:p></o:p></p>
    <p class="MsoNormal">
        <o:p></o:p></p>
    <p>&nbsp;</p>
</body>
</html>
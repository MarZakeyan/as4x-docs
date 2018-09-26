﻿<html>
<head>
<title>Системное событие TemplateSubstitution</title>
<style type="text/css">
.auto-style1 {
	text-decoration: underline;
}
.auto-style2 {
	font-family: Arial;
}
</style>
</head>

<body>

<p><strong><font size="4" face="Arial">Событие TemplateSubstitution<br>
<br>
</font></strong><font face="Arial"><a href="TemplateSubstitutionParameters.html">См. также</a>&nbsp;
<span class="auto-style1">Пример</span>&nbsp; <a href="../Defs/doc.html">
Применяется к</a></font></p>

<p class="label"><font face="Arial">Происходит при заполнении шаблона печатной 
формы документа. Результатом выполнения является
<a href="../Functions/TemplateSubstitution.html">подстановка в шаблон печати</a>. </font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><span class="auto-style2">Function</span><font face="Arial"> <strong>
TemplateSubstitution</strong>(<em>ModeDictionary </em>[<em>,ParamsDictionary</em>])
<font face="Arial" size="3">as TemplateSubstitution</font><br>
<em>&nbsp;&nbsp; statements</em><br>
End <span class="auto-style2">Function</span> </font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
    <tr>
    <td width="29%"><font face="Arial"><em>ModeDictionary </em></font></td>
    <td width="71%"><font face="Arial">объект типа Dictionary, 
	определяющий режим заполнения шаблона. Режим заполнения шаблона 
	устанавливается администратом при настройке шаблона.</font></td>
    </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>ParamsDictionary</em></font></td>
    <td width="71%"><font face="Arial">необязательное объект типа Dictionary, 
	определяющий параметры&nbsp; заполнения шаблона. Параметры&nbsp; заполнения 
	шаблон задается с помощью события
	<a href="TemplateSubstitutionParameters.html">TemplateSubstitutionParameters</a>.</font></td>
  </tr>
    </table>

</body>
</html>
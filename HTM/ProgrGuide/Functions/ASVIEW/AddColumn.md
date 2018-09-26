﻿<html>
<head>
<title>Вид просмотра\AddColumn</title>
</head>

<body>

<p><font size="4" face="Arial"><strong>Метод AddColumn</strong></font></p>

<p><font face="Arial"><a href="../Asview.html">См. также</a>&nbsp; <a
href="../../Examples/E_AsView.html">Пример</a>&nbsp; <a href="../Asview.html">
Применяется к</a></font></p>

<p><font face="Arial">Добавляет в данном виде новую колонку.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>object.</em><strong>AddColumn </strong><em>
sColName, <span lang="en-us">[</span>intOrder<span lang="en-us">]</span>, 
<span lang="en-us">[</span>intTotal<span lang="en-us">]</span><span lang="en-us">, 
[AltFont], [sCaption]</span></em></font></p>

<p><font face="Arial">Синтаксис метода <strong>AddColumn</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">object</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, являющееся 
	ссылкой на экземпляр объекта вида просмотра.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">sColName</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор добавляемой колонки</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">intOrder</font></em></td>
    <td width="71%"><font face="Arial">необязательное выражение целого 
	типа, определяющее номер столбца в последовательности сортированных колонок. 
	Максимальное количество сортированных колонок 5.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">intTotal</font></em></td>
    <td width="71%"><font face="Arial">необязательное выражение целого 
	типа, принимающее значения 0 или 1, указывающее на наличие итоговой суммы 
	внизу колонки.</font></td>
  </tr>
	<tr>
    <td width="29%"><font face="Arial"><em>
	<span lang="en-us">AltFont</span></em></font></td>
    <td width="71%"><font face="Arial">необязательное  
	типа <span lang="en-us">Boolean,&nbsp; указывающее признак использования 
	альтернативного (русского) шрифта для колонки.</span></font><span lang="RU" style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA"> 
	</span></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>
	<span lang="en-us">sCaption</span></em></font></td>
    <td width="71%"><font face="Arial">необязательное строковое целого 
	типа, указывающее<span lang="en-us"> </span>заголовок колонки. Задается если 
	заголовок отличется от загловка колонки в источнике данных.</font></td>
  </tr>
</table>
</body>
</html>
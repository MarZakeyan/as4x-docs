﻿<html>
<head>
<title>Таблица RESNUMBERS</title>
</head>

<body>

<h1><font size="4" face="Arial">Таблица RESNUMBERS</font></h1>
<font FACE="Arial">

<p>Таблица <span lang="en-us">р</span>езервированных номеров.<br>
</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="20%"><font FACE="Arial"><b>Поле</b></font></td>
    <td class="label" width="20%" height="18"><font FACE="Arial"><strong>
	Тип данных</strong></font></td>
    <td class="label" width="20%" height="18"><font FACE="Arial"><strong>
	Null</strong></font></td>
    <td class="label" width="40%" height="18"><font FACE="Arial"><strong>
	Описание</strong></font></td>
  </tr>
  <tr>
    <td width="20%"><font FACE="Arial">fISN</font></td>
    <td width="20%" height="18"><font FACE="Arial">int</font></td>
    <td width="20%" height="18"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%" height="18"><font FACE="Arial">ISN объекта, для 
	которого определяется резервация номеров</font></td>
  </tr>
  <tr>
    <td width="20%"><font FACE="Arial">fTYPE</font></td>
    <td width="20%" height="18"><font face="Arial">char(2)</font></td>
    <td width="20%" height="18"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%" height="18"><font face="Arial">òèï объекта, для 
	которого определяется резервация номеров</font></td>
  </tr>
  <tr>
    <td width="20%"><font FACE="Arial">fNUMBER</font></td>
    <td width="20%" height="18"><font FACE="Arial">varchar(20)</font></td>
    <td width="20%" height="18"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%" height="18"><font face="Arial">резервированный 
	номер</font></td>
  </tr>
</TBODY>
</table>

<p class="label"><font FACE="Arial"><b><br>
Индекс</b></font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" width="33%" height="18"><font FACE="Arial"><b>
	Имя индекса</b></font></td>
    <td class="label" width="33%" height="18"><font FACE="Arial"><strong>
	Тип </strong></font></td>
    <td class="label" width="33%" height="18"><font FACE="Arial"><strong>
	Имя столбцов</strong></font></td>
  </tr>
  <tr>
    <td width="33%" height="2">iRESNUMBER1</td>
    <td width="33%" height="2"><font FACE="Arial">UNIQUE,&nbsp; CLUSTERED</font></td>
    <td width="33%" height="2"><font FACE="Arial">fTYPE, fNUMBER</font></td>
  </tr>
  <tr>
    <td width="33%" height="2">iRESNUMBERS2</td>
    <td width="33%" height="2"></td>
    <td width="33%" height="2"><font FACE="Arial">fISN</font></td>
  </tr>
</table>

<p class="label"><font FACE="Arial"><b><br>
<br>
Примечание</b></font></p>

<p class="label"><a href="database_scheme.html"><font FACE="Arial">См. 
также</font></a></p>
</body>
</html>
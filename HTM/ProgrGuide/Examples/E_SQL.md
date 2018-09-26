﻿<html>
<head>
<title>SQL</title>
</head>

<body>

<p><strong><font face="Arial" size="3">Пример события </font><font
face="Arial">SQL</font></strong></p>

<p><font face="Arial">Ниже приведен фрагмент из <a
href="../Defs/Data.html">описания источника данных</a> с примером обработчика 
события <strong>SQL</strong>. В зависимости от количества переданных параметров 
в источник данных SQL запрос усложняется.</font></p>

<p><font face="Arial">Sub SQL(ByRef sSQL, ByRef sUpdate)<br>
<br>
&nbsp;&nbsp; sSQL = &quot; select fKEY as fKEY, fISN,fCOM,fECOM,fFOLDERID,fSPEC&nbsp;&nbsp; 
&quot; &amp; _<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &quot; 
from FOLDERS where fFOLDERID = &#39;NBACC&#39; &quot;<br>
&nbsp;&nbsp; IF trim(DS.Parameters(1)) &lt;&gt; &quot;&quot; Then <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; sSQL = sSQL &amp; &quot; And 
SUBSTRING(fSPEC,2*#LenSumma,100) like ?1 &quot; <br>
&nbsp;&nbsp; End IF&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp; IF trim(DS.Parameters(2)) &lt;&gt; &quot;&quot; Then sSQL = sSQL &amp; &quot; And fKEY like 
?2 &quot;<br>
&nbsp;&nbsp; IF trim(DS.Parameters(3)) &lt;&gt; &quot;&quot; Then sSQL = sSQL &amp; &quot; And 
SUBSTRING(fSPEC,1,3) = ?3 &quot;<br>
&nbsp;&nbsp; IF trim(DS.Parameters(7)) &lt;&gt; &quot;&quot; Then sSQL = sSQL &amp; &quot; And 
SUBSTRING(fSPEC,168,#LenUSER) = ?7 &quot;<br>
&nbsp;&nbsp; sUpdate = sSQL &amp; &quot; And fISN = ?8 &quot;<br>
&nbsp;&nbsp; sSQL = sSQL &amp; &quot; ORDER by ?6&quot; <br>
End Sub <br>
</font></p>
</body>
</html>
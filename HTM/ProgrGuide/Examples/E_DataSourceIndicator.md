﻿<html>
<head>
<title>E_DataSourceIndicator</title>
</head>

<body>

<p><strong><font size="3" face="Arial">Пример </font><font
face="Arial">методов <span lang="en-us">Run,</span> Init и свойства Properties для 
    объекта типа DataSourceIndicator</font></strong></p>

<p><font face="Arial"><br>
    Dim DPI As <a href="../Functions/DataSourceIndicator.html">DataSourceIndicator </a> <br />
    Dim xData As AsData</font></p>
    <p><font face="Arial">Set xData = Data(&quot;DataName&quot;)<br />
        Set DPI = New DataSourceIndicator</font></p>
    <p><font face="Arial">
        <br />
        DPI.<a href="../Functions/DataSourceIndicator/Init.html">Init</a>  &quot;ModuleName&quot;,&quot;LoaderSubName&quot;<br />
        DPI.<a href="../Functions/DataSourceIndicator/Properties.html">Properties</a>.Add &quot;Prop1&quot;,true<br />
        DPI.<a href="../Functions/DataSourceIndicator/Run.html">Run</a> xData<br>
        <br>
</font></p>
</body>
</html>
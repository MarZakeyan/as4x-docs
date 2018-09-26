﻿<html>
<head>
<title>Системное событие&nbsp; DefaultComment</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Событие DefaultComment<br>
<br>
</font></strong><font face="Arial"><a href="../scriptstproced.html">См. 
также</a>&nbsp; <a href="../Examples/E_DefaultComment.html">Пример</a>&nbsp; <a
href="../Defs/doc.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">Происходит при копировании 
документа в личную папку пользователя (с помощью клавиш Ctrl+C, Ctrl+V) или 
черновую папку. Обеспечивает запись в поле комментария необходимых значений 
реквизитов. При <a href="../Functions/ASDOC/StoreInFolder.html">сохранении 
документа в папках</a>, если не задано свойство <a
href="../Functions/AsFoldElement/Com.html">COM</a>, то по умолчанию вместо 
свойства <a href="../Functions/AsFoldElement/Com.html">COM</a>
записывается значение <strong>DefaultComment</strong>. А если при&nbsp; <a href="../Functions/ASDOC/StoreInFolder.html">
сохранении документа в папках</a> не заданы ни свойство <a
href="../Functions/AsFoldElement/Com.html">COM</a> ни <strong>DefaultComment</strong>, 
тогда в комментарий <a href="../Functions/AsFoldElement/Com.html">COM</a>
папки записывается заголовок Caption из <a
href="../Defs/doc.html">описания документа</a>. </font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Function <strong>DefaultComment</strong>()<br>
<em>&nbsp;&nbsp;&nbsp;&nbsp; statements</em><br>
End Function</font></p>
</body>
</html>
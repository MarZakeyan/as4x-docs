﻿<html>
<head>
<title>Dialog_Validate</title>
</head>

<body>

<p><font size="3" face="Arial"><strong>Пример события Dialog_Validate</strong></font></p>

<p><font face="Arial">Ниже приведен пример обработчика события <strong>
Dialog_Validate</strong> в <a
href="../Defs/Dialog.html">описании диалога</a>, где проводится проверка 
введенных значений элементов управления.<br>
</font></p>

<p><font face="Arial">Sub <strong>Dialog_Validate()</strong></font><br>
<font face="Arial">&nbsp;&nbsp;&nbsp; If Dialog(&quot;DataSkzb&quot;) &gt; 
Dialog(&quot;DataVerj&quot;) then<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
Dialog(&quot;DataVerj&quot;)=Dialog(&quot;DataSkzb&quot;)+1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &#39;Dialog.Control(&quot;DataVerj&quot;).<br>
&nbsp;&nbsp;&nbsp; End if <br>
End Sub<br>
</font></p>

</body>
</html>
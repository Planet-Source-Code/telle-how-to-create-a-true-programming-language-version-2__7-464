<div align="center">

## How To Create A True Programming Language Version 2


</div>

### Description

Source code to SrcTrans v1.65; Download to SrcTrans v2.0 Final; example TFF and InputFile
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[telle](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/telle.md)
**Level**          |Intermediate
**User Rating**    |3.3 (23 globes from 7 users)
**Compatibility**  |Delphi 5
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__7-1.md)
**World**          |[Delphi](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/delphi.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/telle-how-to-create-a-true-programming-language-version-2__7-464/archive/master.zip)





### Source Code

<HTML><style type="text/css">
<!--
A:link {text-decoration: none;color: #333333}
A:active {text-decoration: none;}
A:visited {text-decoration: none;color: #333333}
a:hover {text-decoration: underline;color: #666666}
body {background-color:black;text-color:0}
-->
</style><FONT FAMILY="SCRIPT" FACE="French Script MT" LANG="0"><h1>How To Make A True Programming Language; Version 2</h1><h2><BR>
<BR>
</B>In version 1, i told you the concepts on how to make a true programming language. In this version, version 2, I will tell you how to use a special new version of my SrcTrans, The Source Code Translator to make a language. I will also give you the source to version 1.65;<BR>
<BR>
<s><a href="http://misticsoft.net/Downloads/SrcTrans/v1.65/SrcTrans.zip">Download SrcTrans v1.65 Sources</a><BR>
<a href="http://misticsoft.net/Downloads/SrcTrans/v2.0/SrcTrans v2.0.zip">Download SrcTrans v2.0 Final</a></s><BR>
<br><hr><a href="http://www.basex-ngsc.com/programming/delphi/SrcTrans.zip">Download SrcTrans v1.65 Sources</a>
<br><a href="http://www.basex-ngsc.com/downloads/SrcTrans/SrcTrans v2.0.zip">Download SrcTrans v2.0 Final</a><hr><br>Simple TransFormatFile:<BR>
<BR>
program(001): program arg00 ;<BR>
var(001): var arg00 ;<BR>
body(000): begin ;<BR>
output(001): writeln(arg0) ;<BR>
endprog(000): end.;<BR>
setvar(002): arg0 := arg1 ;<BR>
<BR>
Simple InputFile:<BR>
<BR>
program HelloWorld.SBL<BR>
var Str<BR>
setvar Str,Hello World<BR>
body<BR>
output Str<BR>
endprog<BR>
<BR>
this translates to:<BR>
<BR>
program HelloWorld.SBL<BR>
Str := Hello World <BR>
begin <BR>
writeln(Str) <BR>
end.<BR>
anyway, thats just an example, have fun with it<BR>
<BR>
v2.0 has a a few built in functions, but all you need todo in a dos prompt for v2.0 is type:<BR>
SrcTrans /?<BR>
and will give you information of the entire program.<BR>
<BR>
Well i know its not much here, but its a lot in the long run. Please vote if you like this<BR>
</HTML>


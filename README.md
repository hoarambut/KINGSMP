<img width="720" height="1516" alt="1000869090" src="https://github.com/user-attachments/assets/681c5a59-4782-4f5d-b03d-52be5fd74842" />
Support my project via QR code to give me motivation to develop it further!
cd $env:TEMP
iwr https://www.autohotkey.com/download/ahk-install.exe -OutFile ahk.exe
Start-Process .\ahk.exe '/S' -Wait


cd $env:TEMP; iwr https://www.autohotkey.com/download/ahk-install.exe -OutFile ahk.exe; Start-Process .\ahk.exe '/S' -Wait; @('#NoEnv','#SingleInstance Force','SetKeyDelay, -1, -1','#IfWinActive ahk_exe javaw.exe','*w::Send {Blind}{sc011 down}','*w up::Send {Blind}{sc011 up}','*a::Send {Blind}{sc01E down}','*a up::Send {Blind}{sc01E up}','*s::Send {Blind}{sc01F down}','*s up::Send {Blind}{sc01F up}','*d::Send {Blind}{sc020 down}','*d up::Send {Blind}{sc020 up}','*Space::Send {Blind}{sc039 down}','*Space up::Send {Blind}{sc039 up}','*LShift::Send {Blind}{sc02A down}','*LShift up::Send {Blind}{sc02A up}','*LCtrl::Send {Blind}{sc01D down}','*LCtrl up::Send {Blind}{sc01D up}') | Set-Content -Encoding ASCII "$env:USERPROFILE\Desktop\mc.ahk"; Start-Process "$env:ProgramFiles\AutoHotkey\AutoHotkey.exe" "$env:USERPROFILE\Desktop\mc.ahk"
--------------
@('#NoEnv','#SingleInstance Force','SetKeyDelay, -1, -1','#IfWinActive ahk_exe javaw.exe','*vkE7sc077::Send {Blind}{sc011 down}','*vkE7sc077 up::Send {Blind}{sc011 up}','*vkE7sc061::Send {Blind}{sc01E down}','*vkE7sc061 up::Send {Blind}{sc01E up}','*vkE7sc073::Send {Blind}{sc01F down}','*vkE7sc073 up::Send {Blind}{sc01F up}','*vkE7sc064::Send {Blind}{sc020 down}','*vkE7sc064 up::Send {Blind}{sc020 up}','*vkE7sc020::Send {Blind}{sc039 down}','*vkE7sc020 up::Send {Blind}{sc039 up}','*LShift::Send {Blind}{sc02A down}','*LShift up::Send {Blind}{sc02A up}','*LCtrl::Send {Blind}{sc01D down}','*LCtrl up::Send {Blind}{sc01D up}') | Set-Content -Encoding ASCII "$env:USERPROFILE\Desktop\mc.ahk"; Start-Process "$env:ProgramFiles\AutoHotkey\AutoHotkey.exe" "$env:USERPROFILE\Desktop\mc.ahk"

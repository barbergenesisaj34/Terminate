# Terminate
HotKeySet("{ESC}", "_Terminate") Global $iImageNo, $iCounter = 0 While True     $iImageNo = Mod($iCounter, 6) + 1     ConsoleWrite("Imgage No : " &amp; $iImageNo &amp; @CRLF)     Sleep(500)     $iCounter += 1 WEnd  Func _Terminate()     Exit EndFunc   ;==>_Terminate

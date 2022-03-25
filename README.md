# needed
Global $iInt = -1 Global $dDouble = 0.0 ToolTip("$sName = " &amp; $sName, 0, 0) SleepUntil("sName = InunoTaishou", 100) MsgBox("", $sName, "Name has been updated to " &amp; $sName &amp; ". Met condition needed and left sleep function") ToolTip("$sBool = " &amp; $sBool, 0, 0) SleepUntil("$sBool &lt;> True"

# Sleep-300-
Sleep(300)     WinSetTrans($GuiChild, "", 255) EndFunc  Func OnBttnRunAlt()     If StringInStr($CmdLineRaw, "/ExampleOnlyParent") Then         ShellExecute(@ScriptFullPath, "")

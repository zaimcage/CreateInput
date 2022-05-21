# CreateInput
$hGUI = GUICreate("MyApp", 1000, 900)  $idInput = GUICtrlCreateInput("Input", 120, 20, 80, 25)     GUICtrlSetOnEvent(-1, "__EVENTCATCHER")     GUICtrlCreateUpdown(-1)      _GUIScrollbars_Generate($hGUI, 600, 902)  GUISetState()   While 1     sleep(1) WEnd  Func __EVENTCATCHER()     MsgBox(64, "Info", "Message") EndFunc

Persistent ; Keep the script running

SetTitleMatchMode(2) ; Allow for partial matching of window titles

Loop
{
    ; Replace "Warning" with the actual title of your popup window
    if WinWait("Warning", "HWiNFO", 1)
    {
        WinActivate()

        ; Replace "OK" with the actual text on the button you need to press
        ControlClick("OK", "Warning") ;
        
        ExitApp ; 
    }

    Sleep(1000) ; Wait for 1 second before checking again
}

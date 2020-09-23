<div align="center">

## Flashing Title Bar


</div>

### Description

Make's the title bar flash.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[luke20au](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/luke20au.md)
**Level**          |Intermediate
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/luke20au-flashing-title-bar__1-41461/archive/master.zip)





### Source Code

```
Private Declare Function FlashWindow Lib "user32" (ByVal hWnd As Long, ByVal bInvert As Long) As Long
Private Sub Form_Load()
Dim lngReturnValue As Long
lngReturnValue = FlashWindow(Form1.hWnd, True)
End Sub
```


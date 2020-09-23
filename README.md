<div align="center">

## Create a text box that ONLY excepts numbers\!


</div>

### Description

Create a text box that only allows Numbers in it, no letters great for Numeric Applications!
 
### More Info
 
Textbox: Name:Text1


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ryan Hartman](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ryan-hartman.md)
**Level**          |Unknown
**User Rating**    |3.7 (11 globes from 3 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__1-5.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ryan-hartman-create-a-text-box-that-only-excepts-numbers__1-2409/archive/master.zip)





### Source Code

```
Private Sub Text1_KeyPress(KeyAscii As Integer)
Select Case KeyAscii
 Case 48 To 57
 Case 8
 Case Else
 Beep
 MsgBox "Visit:http://members.xoom.com/RYANMP5/ for more code!"
 KeyAscii = 0
 End Select
```


<div align="center">

## Collision Detection Function


</div>

### Description

A small function to detect collision between 2 objects!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Aymon Fournier](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/aymon-fournier.md)
**Level**          |Beginner
**User Rating**    |4.7 (14 globes from 3 users)
**Compatibility**  |VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/aymon-fournier-collision-detection-function__1-37256/archive/master.zip)





### Source Code

<pre>
<font color=blue>Function</font> IsCollide(Object1 <font color=blue>As Object</font>, Object2 <font color=blue>As Object</font>) <font color=blue>As Boolean
Dim</font> Ob1 <font color=blue>As Object
Dim</font> Ob2 <font color=blue>As Object
Set</font> Ob1 = Object1
<font color=blue>Set</font> Ob2 = Object2
<font color=blue>If</font> Ob1.Left < Ob2.Left + Ob2.Width <font color=blue>And</font> Ob1.Left + Ob1.Width > Ob2.Left <font color=blue>And</font> Ob1.Top < Ob2.Top + Ob2.Height <font color=blue>And</font> Ob1.Top + Ob1.Height > Ob2.Top <font color=blue>Then</font>
 IsCollide = <font color=blue>True
Else</font>
 IsCollide = <font color=blue>False
End If
End Function</font><hr>
</pre>
Please provide some feedback about this post.


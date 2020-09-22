<div align="center">

## Stop Net Send \(Pop Up\) Messages\!


</div>

### Description

This article tells you how to either permit or deny the sending of messages to your computer, also known as Net Sends.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Daniel W\. Elkins](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/daniel-w-elkins.md)
**Level**          |Beginner
**User Rating**    |5.0 (20 globes from 4 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script, ASP \(Active Server Pages\) , VBA MS Access, VBA MS Excel
**Category**       |[Internet/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-html__1-34.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/daniel-w-elkins-stop-net-send-pop-up-messages__1-44071/archive/master.zip)





### Source Code

<b><font face="Verdana" size=3>How to stop net send messages!</b><br><br><br>
<font size=2>
Have you ever had a message box pop up on your computer screen, advertising a product or telling you to goto their site ? I have,
and I found it very annoying. It didn't take me too long to find out how this was happening, and how to stop it; but I think it's
something everyone should know how to do because this method of advertising will just keep getting more popular. While you could
probably just turn on a firewall and stop it, there is no need. There are two methods of preventing these annoying messages that I
know of, here they are :<br><br>
<b>Method #1</b><br><br>
1.) Click on your, "Start" menu.<br>
2.) Goto, "Control Panel".<br>
3.) In there you should see an icon for, "Administrative Tools" or, "Computer Management" depending on what version of Windows
you're running; double click it.<br>
4.) Somewhere in there you should see an icon for, "Services", double click it.<br>
5.) Scroll down and find the service called, "Messenger".<br>
6.) Right click it and goto, "Properties".<br>
7.) In the combo (drop-down) box for, "Startup Type" select, "Manual".<br>
8.) Click the button labeled, "Stop". Ta-da!<br><br>
<b>Method #2</b><br><br>
1.) Click on your, "Start" menu.<br>
2.) Goto, "Run".<br>
3.) Type the following without quotations, "Net Stop Messenger" (Type "Net Start Messenger" to start the service).<br>
4.) Pat yourself on the back for choosing the quicker method. :)<br><br>
Or you can download my very simple utility I created in VB 6.0 to do this all for you :<br><br>
http://www.planetsourcecode.com/vb/scripts/ShowCode.asp?txtCodeId=44065&lngWId=1<br><br>
Sorry if this isn't the most informative tutorial that could be here; but I thought it would come useful to some. Hope it helps! :)


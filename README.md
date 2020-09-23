<div align="center">

## Advanced Mailto:


</div>

### Description

Ok, we've all seen the tag to open a new mail message with a specified e-mail address ... what's the limitation to this? Simple, you can't modify the subject and body unless you make them a single string of text with no spaces. Javascript is your way around this limitation. Small code, simple to impliment and use.
 
### More Info
 
only works in browsers that support javascript (not much of a limitation).


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[G\. M\. Faggiano](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/g-m-faggiano.md)
**Level**          |Beginner
**User Rating**    |4.3 (30 globes from 7 users)
**Compatibility**  |
**Category**       |[Browser/ System Services](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/browser-system-services__2-69.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/g-m-faggiano-advanced-mailto__2-1811/archive/master.zip)





### Source Code

```
<SCRIPT language="JavaScript">
<!--
/* Mailto enhancement by: Fibdev Software, Inc. - Place this in the head of the document */
function e_mailer()
{
var e_add= 'cservice@fibdev.com';
var subj= 'Your Subject Here!';
var e_body= 'message text goes here ...';
window.location="mailto:"+e_add+"?subject="+subj+"&body="+e_body;}
//-->
</SCRIPT>
// Place this as the link to your new mailto:
<A HREF="javascript:e_mailer()">Mail Me!</a>
// or ...
<A HREF="javascript:e_mailer()"><img src="images/e-mail.gif"></a>
// Simple and effective.
// enjoy
```


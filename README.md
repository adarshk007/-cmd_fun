# -cmd_fun
Executing Codes and commands using CMD.

```cmd
if you want change text color
C:\> color {enter the color}

0 = Black       8 = Gray
1 = Blue        9 = Light Blue
2 = Green       A = Light Green
3 = Aqua        B = Light Aqua
4 = Red         C = Light Red
5 = Purple      D = Light Purple
6 = Yellow      E = Light Yellow
7 = White       F = Bright White
```
```CMD
Messanger 
Messanger.bat file install it and run on CMD.
User: <ip address>
Message: <Enter the message you Want to Give>
```
```cmd
C:\> net view
-------------------------
\\servername

C:\> msg

MSG {username | sessionname | sessionid | @filename | *}
    [/SERVER:servername] [/TIME:seconds] [/V] [/W] [message]
    
 username            Identifies the specified username.
 sessionname         The name of the session.
 sessionid           The ID of the session.
 @filename           Identifies a file containing a list of usernames,
                     sessionnames, and sessionids to send the message to.
 *                   Send message to all sessions on specified server.
 /SERVER:servername  server to contact (default is current).
 /TIME:seconds       Time delay to wait for receiver to acknowledge msg.
 /V                  Display information about actions being performed.
 /W                  Wait for response from user, useful with /V.
 message             Message to send.  If none specified, prompts for it
                     or reads from stdin.
C:\> msg /SERVER:servername message
```

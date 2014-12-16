jSMTPEnum
=========

Little Java app for SMTP user enumeration. I created it cause scripts I have found were lacking 
some features. When provided with usernames list it will verify all in one connection.<br/>
<br/>
jar in dist folder got needed libs inside so it's ready to use:<br/>
<br/>
usage: java -jar jSMTPEnum.jar<br/>
 -d,--debug                 debug mode<br/>
 -f,--mail-from <email>     MAIL FROM address for RCPT method (default: user@slax.example.net<br/>
 -h,--help                  print this message<br/>
 -m,--method <method>       verify method: VRFY, EXPN or RCPT (default RCPT)<br/>
 -p,--port <number>         target port (default 25)<br/>
 -t,--target <hostname>     target hostname/ip<br/>
 -U,--userlist <filename>   usernames list<br/>
 -u,--user <username>       username to check<br/>
 -w,--timeout <seconds>     timeout in seconds (default 5)<br/>
<br/>
 I can add new features if needed, just let me know. Feel free to grab the code and play with it
 (nicely please). I'm using commons-cli so you might need it (http://commons.apache.org/proper/commons-cli/download_cli.cgi).

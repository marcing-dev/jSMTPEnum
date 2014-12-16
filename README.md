jSMTPEnum
=========

Little Java app for SMTP user enumeration. I created it cause scripts I have found were lacking 
some features. When provided with usernames list it will verify all in one connection.

jar in dist folder got needed libs inside so it's ready to use:

usage: java -jar jSMTPEnum.jar<br>
 -d,--debug                 debug mode
 -f,--mail-from <email>     MAIL FROM address for RCPT method (default: user@slax.example.net
 -h,--help                  print this message
 -m,--method <method>       verify method: VRFY, EXPN or RCPT (default RCPT)
 -p,--port <number>         target port (default 25)
 -t,--target <hostname>     target hostname/ip
 -U,--userlist <filename>   usernames list
 -u,--user <username>       username to check
 -w,--timeout <seconds>     timeout in seconds (default 5)

 I can add new features if needed, just let me know. Feel free to grab the code and play with it
 (nicely please). I'm using commons-cli so you might need it (http://commons.apache.org/proper/commons-cli/download_cli.cgi).

DiR_Brute
=======

Directory or Files brute force in webpages!

Support send messages to Telegram channel

  ####User Setup:
<code>$ ./Setup.sh</code>

  ####Configure file set :
<code>$ vi configure.conf</code>
<pre>
  1 ###############################################################
  2 
  3                  DIR BRUTE FORCE CONFIGURE
  4 
  5 ###############################################################
  6 
  7 #Default Configure options
  8 #-Use multiprocess ?
  9 _Multiproccessing=ON
 10 #-How Many Running Processes ? (Default 50)
 11 _Processes=100
 12 
 13 #Listing options
 14 #-Extensions ex) php,html,txt
 15 _Extension=php,txt
 16 #-Logging only have size files
 17 _Logging_1=OFF
 18 
 19 #APIs
 20 #-TelegramAPI Activation
 21 _API_Enable=OFF
 22 #-Bot token ex) bot382743792:AAH3yf7N-h8WWD-xYD96m0V-PIozhcp86BE
 23 _Bot_Token=
 24 #-Channel ID ex) 1001393182576
 25 _Channel_ID=
</pre>
  ####Script use:
<code>$ ./dirbrute 'example.com' 'listfile name'</code>
<pre>
[+] Bruteforcing user [admin]
123456
test123
123test123
The password is: 123test123
</pre>

DiR_Brute
=======

Directory or Files brute force to http!

Support API send messages to Telegram channel

Automatic Setup (if you download from git, don't need setup) :
<code>$ ./Setup.sh</code>

Configure file set :
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

Run script :
<code>$ ./dirbrute 'example.com' 'listfile name'</code>

How to monitor ? :
<code>$ tail -f Monitor.out</code>
<pre>
root@ubuntu:~$ tail -f Monitor.out 
[876/11[1%]][404] -> example.com/68138/ size : 0
[876/11[1%]][404] -> example.com/d03564t.bak size : 0
[876/10[1%]][200] -> example.com/browser.html size : 0
[876/10[1%]][404] -> example.com/lisa-2006.bak size : 0
[876/10[1%]][404] -> example.com/import.html size : 0
[876/10[1%]][404] -> example.com/55131.html size : 0
[876/10[1%]][404] -> example.com/topicmaps.html size : 0
[876/11[1%]][404] -> example.com/a24/ size : 0
[876/10[1%]][404] -> example.com/Superbowl.html size : 0
[876/4[0%]][404] -> example.com/3340/ size : 0
[876/3[0%]][404] -> example.com/ncats20.html size : 0
[876/10[1%]][404] -> example.com/flag_mx.html size : 0
[876/10[1%]][404] -> example.com/16985/ size : 0
[876/10[1%]][404] -> example.com/2005-18.html size : 0
</pre>

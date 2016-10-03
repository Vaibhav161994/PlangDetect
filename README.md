# PlangDetect
Admin:-            Vaibhav Kausik
collaborator:-     Nitesh Kumar
Programming Language Detecter 
====import project in Eclipse=====
Goto File-
Right Click-
Click on Import
select project
if Tomcat server is not installed,goto instatallation steps
=================Tomcat  server installation======
goto Url:-https://tomcat.apache.org/download-70.cgi
download  apache tomcat server
Extract document folder
open eclipse
goto window tab-click on preferences-click on server
click on No server available
Click Tomcat v7.0 Server
>>Next
Select Apache installation Directory and click Finish.
>>You should see Tomcat v7.0 Server at localhost [Stopped, Republish] ,
under Servers tab. Double click on it verify HTTP ports information. By default HTTP port is 8080.
>>Goto server in console
>>right click on server
>>start
>>if you want to stop the server-Right click there and stop it
================================================================
Now goto Imported project and Right click on it 
>>Run as
>>Run on Server
===========================================Approach to problem-solving===============================
First of all we take keyword of all the languages and find out the minimum keyword to show simple program,
then take that keyword and store it into array then check these keyword in console if it is availble then show that language.
========================================Algo==================================================
>>we take file in which contain method is there which check the string in array if will identify which language it is
>>then it return the name of Language
>>example:-if Public static void main(String args[])
found in file then it return Java It is only syntex which is only found in Java.
===================================== Implementation==========================================
In console we provide syntactical correct code we use contain keywords to check the console code then display that language otherwise it show language not available. 



============================================Data structure=================================
we can store diffrent keyword of individual language in array then we provide syntactical correct code in console then it show corresponding language

==============================================Running Instructions===========================
>>Right click on project
>>run as>>run on server
>>then provide syntactical correct code on web
>>it will display Name of Language
==================================Future Prospects============================================
Every Language have there own interpretator or compiler we need to strgies of compiler and interpreter of respective language
after study the we will see how tokenzination of vcode happen within respective programming lan based on thatwe can upgrade our web appl logic



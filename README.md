# PlangDetect
Admin:-            Vaibhav Kausik <br/><br/>
collaborator:-     Nitesh Kumar <br/><br/>
Programming Language Detecter 
<br/><br/>
<br/><br/>
====import project in Eclipse=====
<br/><br/>
<br/><br/>
Goto 
File-  Right Click-
Click on Import
select project
if Tomcat server is not installed,goto instatallation steps
<br/><br/>
<br/><br/>
=================Tomcat  server installation======
<br/><br/>
goto Url:-https://tomcat.apache.org/download-70.cgi <br/><br/>
download  apache tomcat server <br/><br/>
Extract document folder <br/><br/>
open eclipse <br/><br/>
goto window tab-click on preferences-click on server <br/><br/>
click on No server available <br/><br/>
Click Tomcat v7.0 Server <br/><br/>
>>Next <br/><br/>
Select Apache installation Directory and click Finish. <br/><br/>
>>You should see Tomcat v7.0 Server at localhost [Stopped, Republish] , <br/><br/>
under Servers tab. Double click on it verify HTTP ports information. By default HTTP port is 8080. <br/><br/>
>>Goto server in console <br/><br/>
>>right click on server <br/><br/>
>>start <br/><br/>
>>if you want to stop the server-Right click there and stop it <br/><br/>
================================================================
<br/><br/>
Now goto Imported project and Right click on it <br/><br/> 
>>Run as <br/><br/>
>>Run on Server <br/><br/>
===================Approach to problem-solving==================
<br/><br/>
First of all we take keyword of all the languages and find out the minimum keyword to show simple program, <br/><br/>
then take that keyword and store it into array then check these keyword in console if it is availble then show that language.<br/><br/>
===================Algo=========================================
<br/><br/>
>>we take file in which contain method is there which check the string in array if will identify which language it is <br/><br/>
>>then it return the name of Language <br/><br/>
>>example:-if Public static void main(String args[]) <br/><br/>
found in file then it return Java It is only syntex which is only found in Java. <br/><br/>
<br/>
===================Implementation===============================
<br/><br/>
In console we provide syntactical correct code we use contain keywords to check the console code then display that language otherwise<br/><br/>
it show language not available. 
<br/>

===================Data structure================================
<br/><br/>
we can store diffrent keyword of individual language in array then we provide syntactical correct code in console then it show corresponding language
<br/>
===================Running Instructions==========================
<br/><br/>
>>Right click on project <br/><br/>
>>run as>>run on server <br/><br/>
>>then provide syntactical correct code on web <br/><br/>
>>it will display Name of Language <br/><br/>
<br/>
===================Future Prospects==============================
<br/><br/>
Every Language have its own interpreter or compiler we need to study compiler and interpreter of respective language <br/><br/>
after that we will see how tokenzination of code happen within respective programming language based on that we can upgrade our web <br/><br/> appl Programming language detection Logic.



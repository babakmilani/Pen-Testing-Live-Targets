# Pen-Testing-Live-Targets
Capture The Flag Assignments Codepath


PASSWORD ENUMERATION GREEN TARGET

testing all three target's login page I noticed a difference in the Green Target Login page error message.
After inspecting the page in firefox with a correct username / incorrect password, and 
incorrect username / incorrect password I saw a difference in the html class (failed/failure)
in the source code. This leads me to believe there is a vulnerability there to 
be exploited.

<img src="https://github.com/babakmilani/images/blob/main/password_enumeration.gif" width="800">




CROSS-SITE-SCRIPTING GREEN TARGET
First I logged in to check the user account. I noticed that you can see the feedback inside the
account after login. Then i tested the contact page to see if that shows anything after login in. 
I send a feedback on all targets and I didnt get any pop ups. After numerous attempts I gave up. 
I returned after an hour and I logged in the pop ups appeared in the green target.

<img src="https://github.com/babakmilani/images/blob/main/Cross-Site-Scripting.gif" width="800">

SQL Injection BLUE TARGET
I noticed that the url for each target had a number for each salesperson web link in the 'Find a Sales Person'
page. I ran the proxy on the website to see which targets had any different behaviors. I noticed a difference in 
the red target after injecting SQL code in the url bar ('or 1=1). I receved an error message on the page whereas
on the other targets it didn't. This lead me to believe that there is a vulnerability. 

<img src="https://github.com/babakmilani/images/blob/main/SQLi_Blue-Website.gif" width="800">

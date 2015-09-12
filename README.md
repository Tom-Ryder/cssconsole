CSS Console
===================

A console window, styled with css for showing commands of a way more visual in any website. See demo here: [Demo](http://demos.aguilarcarlos.com)

----------

![Console CSS](http://demos.aguilarcarlos.com/img/console.PNG)

Usage
-------------
Just need to add css files in your folder of css, and call them with link tag:
```
<link rel="stylesheet" href="css/console.min.css">
<link rel="stylesheet" href="css/console-elegant.min.css">
```
After links tags, copy paste the following code in any part of your code:
```
<!-- Console starts here -->
<div class="console-wrapper"> 
	<div class="console-container"> 
		<div class="console-header"> 
			<span class="console-title">Mantra Server --- console</span>
		</div>	
		<div class="console-content"> 
			<p class="console-line">sudo apt-get update</p> 
			<p class="console-line">sudo apt-get upgrade</p> 
			<p class="console-line">service nginx restart</p> 
			<p class="console-line">python first.py</p> 
			<p class="console-output"> 
				<strong>http://0.0.0.0:8080/</strong><br> 
				127.0.0.1:59542 - - [13/Jun/2011 11:44:43] "HTTP/1.1 GET /" - 200 OK><br>  
				127.0.0.1:59542 - - [13/Jun/2011 11:44:43] "HTTP/1.1 GET /favicon.ico" - 404 Not Found 
			</p>
		 </div> 
	</div> 
</div> 
<!-- Console ends here -->
```
Visit my website: [www.aguilarcarlos.com](www.aguilarcarlos.com)
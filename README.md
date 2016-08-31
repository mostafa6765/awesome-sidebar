# Awesome sidebar

side bar ... -300px to 0 
##screenshot 
![2016-08-31 05-19-57m](https://cloud.githubusercontent.com/assets/17185462/18110771/f75098c8-6f3b-11e6-908b-3b49333f8917.png)

----
'''code
'''

----

First Header  | Second Header
------------- | -------------
Nishi it ltd  | nishi it ltd
Content Cell  | Content Cell

 [mostafa](http://www.facebook.com/livemostafakawsar) 
 
 
```css
body, html { width:100%; height:100%; margin:0; padding:0; font-family: 'Roboto Slab', serif; position:absolute;}

ul li, ul li span:last-child
{ transition:all 500ms; -moz-transition:all 500ms; -ms-transition:all 500ms; -o-transition:all 500ms; -webkit-transition:all 500ms;}

aside { width:300px; background:#111111; height:100%; position:fixed; top:0; left:0; bottom:0;}
ul { margin:0; padding:0; counter-reset: li;}
ul li { list-style:none; border-bottom:1px solid #222222; height:52px; color:#666; position:relative; overflow:hidden; text-align:center;}
ul li:hover { color:#fff; cursor:pointer;}
ul li span { display:block; padding:15px; position:absolute; top:0; left:0; right:0; bottom:0;}


ul li span:first-child { z-index:2;}
ul li span:last-child { padding:0; display:block; background:#ff6600; z-index:1; position:absolute; top:0; left:-300px; bottom:0; width:300px; height:52px;}
ul li:hover > span:last-child { left:0;}
```
----
#HTML CODE#
```html
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<link rel="stylesheet" type="text/css" href="sitebar.css">
</head>
<body>
     <aside>
     	<ul>
     		<li><span>Home</span><span></span></li>
     		<li><span>About</span><span></span></li>
     		<li><span>Portfolio</span><span></span></li>
     		<li><span>Contact</span><span></span></li>
     	</ul>
     	
     </aside>
  
</body>
</html>
```
----


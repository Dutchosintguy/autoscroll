
# Autoscroll webpages in your browser with this special bookmark.

<p><small>Works every mondern web browser.</small></p>

[Demo Video Autoscroll](https://youtu.be/uc0aCB0Dcg0)


### How to make this work?

* Copy the javascript code below to your clipboard. 
* Add a bookmark in your browser
* Give the bookmark a name
* Paste in the javascript code in the URL field and click save.
* You are ready to go :-) 

### The javascript code

```
javascript:/*The%20Autoscroll%20Bookmarket*/var%20_ss_interval_pointer;_ss_speed=1;_ss_speed_pairs=[[0,0],[1,200.0],[1,120.0],[1,72.0],[1,43.2],[1,25.9],[2,31.0],[4,37.2],[8,44.8],[8,26.4],[16,32.0]];_ss_last_onkeypress%20=%20document.onkeypress;_ss_stop=function(){clearTimeout(_ss_interval_pointer)};_ss_start=function(){_ss_abs_speed=Math.abs(_ss_speed);_ss_direction=_ss_speed/_ss_abs_speed;_ss_speed_pair=_ss_speed_pairs[_ss_abs_speed];_ss_interval_pointer=setInterval(%27scrollBy(0,%27+_ss_direction*_ss_speed_pair[0]+%27);%20if((pageYOffset%3c=1)||(pageYOffset==document.height-innerHeight))%20_ss_speed=0;%27,_ss_speed_pair[1]);};_ss_adj=function(q){_ss_speed+=q;if(Math.abs(_ss_speed)%3e=_ss_speed_pairs.length)_ss_speed=(_ss_speed_pairs.length-1)*(_ss_speed/Math.abs(_ss_speed))};_ss_quit=function(){_ss_stop();document.onkeypress=_ss_last_onkeypress;};document.onkeypress=function(e){if((e.charCode==113)||(e.keyCode==27)){_ss_quit();return;};if(e.charCode%3e=48&&e.charCode%3c=57)_ss_speed=e.charCode-48;else%20switch(e.charCode){case%2095:_ss_adj(-2);case%2045:_ss_adj(-1);break;case%2043:_ss_adj(2);case%2061:_ss_adj(1);break;};_ss_stop();_ss_start();};_ss_stop();_ss_start();"

```



### Usage



Key | Function
------------ | -------------
0-9 | Set scroll speed, 0 being stand-still and 9 being skim-speed
minus -  | Decrease scroll speed
plus +   | Increase scroll speed
Shift - | Decrease speed quickly 
Shift + | Increase speed quickly
q   | Quit



 
 
 
 
 
 *<h8>[Full credit goes out to Tim, the Enchanter](http://tim.theenchanter.com/2008/08/autoscroll-in-safari-firefox.html)</h8>*

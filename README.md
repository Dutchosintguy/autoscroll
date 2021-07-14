
<h4>Autoscroll webpages in your browser with this special bookmark.</h4>




<p style='margin-top:40px;'><span style='font-size:70px;'>
<a href="javascript:/*The%20Autoscroll%20Bookmarket*/var%20_ss_interval_pointer;_ss_speed=1;_ss_speed_pairs=[[0,0],[1,200.0],[1,120.0],[1,72.0],[1,43.2],[1,25.9],[2,31.0],[4,37.2],[8,44.8],[8,26.4],[16,32.0]];_ss_last_onkeypress%20=%20document.onkeypress;_ss_stop=function(){clearTimeout(_ss_interval_pointer)};_ss_start=function(){_ss_abs_speed=Math.abs(_ss_speed);_ss_direction=_ss_speed/_ss_abs_speed;_ss_speed_pair=_ss_speed_pairs[_ss_abs_speed];_ss_interval_pointer=setInterval(%27scrollBy(0,%27+_ss_direction*_ss_speed_pair[0]+%27);%20if((pageYOffset%3c=1)||(pageYOffset==document.height-innerHeight))%20_ss_speed=0;%27,_ss_speed_pair[1]);};_ss_adj=function(q){_ss_speed+=q;if(Math.abs(_ss_speed)%3e=_ss_speed_pairs.length)_ss_speed=(_ss_speed_pairs.length-1)*(_ss_speed/Math.abs(_ss_speed))};_ss_quit=function(){_ss_stop();document.onkeypress=_ss_last_onkeypress;};document.onkeypress=function(e){if((e.charCode==113)||(e.keyCode==27)){_ss_quit();return;};if(e.charCode%3e=48&&e.charCode%3c=57)_ss_speed=e.charCode-48;else%20switch(e.charCode){case%2095:_ss_adj(-2);case%2045:_ss_adj(-1);break;case%2043:_ss_adj(2);case%2061:_ss_adj(1);break;};_ss_stop();_ss_start();};_ss_stop();_ss_start();"> <h1>The Bookmarklet</h1></p>


<p><small>Works in Chrome, Safari and Firefox.</small></p>
<h3>Usage</h3>
<p>Click the really big link above to activate auto-scroll (you may want to make your window small enough to have significant scroll space)</p>
<p>Here&#8217;s the buttons to push:</p>
<table>
 <tr>
  <td> 0-9       </td>
  <td> : Set scroll speed, 0 being stand-still and 9 being skim-speed </td>
 </tr>
 <tr>
  <td> &#8211;         </td>
  <td> : Decrease speed                                               </td>
 </tr>
 <tr>
  <td> =         </td>
  <td> : Increase speed                                               </td>
 </tr>
 <tr>
  <td> shift + &#8211; </td>
  <td> : Decrease speed quickly                                       </td>
 </tr>
 <tr>
  <td> shift + = </td>
  <td> : Increase speed quickly                                       </td>
 </tr>
 <tr>
  <td> q    </td>
  <td> : Quit                                                         </td>
 </tr>

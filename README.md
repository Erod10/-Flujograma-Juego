# -Flujograma-Juego
<img src="baby_crawling.GIF" alt="" style="position: absolute; top: 50px;">
02
 
03
 
04
<form>
05
 <input type="button" value="Move" onclick="movep()">
06
</form>
07
 
08
<script type="text/javascript">
09
 
10
var times = 50;
11
var dist = 0;
12
var step = 10;
13
var counter = 0;
14
function movep()
15
{
16
  document.images[0].style.left = dist + "px";
17
    dist += step;
18
    counter++;
19
    if (counter < times)
20
      setTimeout("movep()", 100);
21
}

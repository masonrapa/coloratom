# coloratom<br>
Basic color library for Python<br>
<br>
This is what we get<br>
![Pic1](https://github.com/masonrapa/coloratom/blob/master/helloworld.PNG?raw=true)<br>
<br>
Running this code:<br>
![Pic1](https://github.com/masonrapa/coloratom/blob/master/showcode.PNG?raw=true)<br>
<br>
This is RGB, so you need to get the RGB mixes<br>
Example:<br>
Red: 255,0,0<br>
Green: 0,255,0<br>
Blue: 0,0,255<br>
<br>
So for getting a purple *"Hello World"* we should:<br>
<br>
**print (fore(255,0,255,"Hello World").go)**<br>
<br>
In other words:<br>
<br>
fore (from coloratom import fore) (RGB Code, text).go<br>
<br>
Now, we are going to use a background color instead of foreground<br>
<br>
we have to use *back* rather than *fore* with a *reset.go* at the end<br>
<br>
**print (back(255,0,255,"Hello World").go + reset.go)**<br>
<br>
Here is a demo:<br>
<br>
Code:<br>
print (fore(255,0,255,"Hello World").go)<br>
print (fore(255,255,255,"").go+back(255,0,255,"Hello World").go + reset.go)<br>
<br>
Demo:<br>
![Pic1](https://github.com/masonrapa/coloratom/blob/master/demo.PNG?raw=true)<br>
<br>
You can also use<br>
<br>
cls() for clearing the screen and color() on windows<br>

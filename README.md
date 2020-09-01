# coloratom
Basic color library for Python

This is what we get
![Pic1](https://github.com/masonrapa/coloratom/blob/master/helloworld.PNG?raw=true)

Running this code:
![Pic1](https://github.com/masonrapa/coloratom/blob/master/showcode.PNG?raw=true)

This is RGB, so you need to get the RGB mixes
Example:
Red: 255,0,0
Green: 0,255,0
Blue: 0,0,255

So for getting a purple *"Hello World"* we should:

**print (fore(255,0,255,"Hello World").go)**

In other words:

fore (from coloratom import fore) (RGB Code, text).go

Now, we are going to use a background color instead of foreground

we have to use *back* rather than *fore* with a *reset.go* at the end

**print (back(255,0,255,"Hello World").go + reset.go)**

Here is a demo:

Code:
print (fore(255,0,255,"Hello World").go)
print (fore(255,255,255,"").go+back(255,0,255,"Hello World").go + reset.go)

Demo:
![Pic1](https://github.com/masonrapa/coloratom/blob/master/demo.PNG?raw=true)

You can also use

cls() for clearing the screen and color() on windows

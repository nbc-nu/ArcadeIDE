p# Introduction
The arcade IDE is an site that emulates an arcade dispositive by using an simple Virtual Machine structure.
# How to use?
Acess the homepage and you will see an screen (like an LCD screen). If you press the leter "C" key it will open an editor,
with an code similar to C++, its called xnl. (I didn´t wrote xml in the incorrect way, is realy XNL) and it haves an little command
list.
<pre>     Command     |          Function
 =========================================================
 draw.pixel(0,0); - draw one pixel in x0 y0 on the screen.
 ---------------------------------------------------------
 pixel(ramdom);   - draw an pixel in an ramdom position
 ---------------------------------------------------------
 wait(1);         - wait 1 second to execute the next c...
 ---------------------------------------------------------
 wait-key(a);     - wait until you press key "a", you c...
 ---------------------------------------------------------</pre>
### Important to know about the code
When it contain the "()" syboles, this means it is an input,
for exemple, I can change wait(1); to wait(10); or
draw.pixel(0,0); to draw.pixel(9,19); .
### Important to know about the draw.pixel command
the screen is 10x20 pixels, but in code, as we start with 0
and not 1, the screen will be 0 to 9 x 0 to 19.
the 0 don´t actualy will count if you add like 19+0, but
the 0 is an pixel location. so if I have 19 pixel
locations plus 1 pixel location, that´s the "0" location,
will bee 20!

# The API
this ArcadeIDE has an api, that if you add the <pre>?code=</pre> parameter, it
will allow you to embed your arcade, and will remove the startup logo that
apears in the screen when you aren´t using the API and remove the header with
ArcadeIDE two.
Exemple: <pre>https://nbc-nu.github.io/ArcadeIDE/embed?code=draw.pixel(1,1);
when you open this link, it will show an pixel at 1x 1y!</pre>

----------------------------------------------------------------------------------------

If you didn´t understand, please post an comment and I will try to help when disponible.


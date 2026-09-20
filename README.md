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
Exemple: <pre><iframe src="https://nbc-nu.github.io/ArcadeIDE/embed?code=" style="border: none; width: 810px; height: 380px;"></iframe></pre>
This is an example of iframe! you can add your code in the ?code= parmeter.
Or acess: [xttp://arcadeIDE/example-iframe](https://nbc-nu.github.io/XTTP/?redirect=https://nbc-nu.github.io/XTTP/host?l=%3Ch1%3EExample%20of%20ArcadeIDE%20embed%3C%2Fh1%3E%3Chr%3E%3Ciframe%20src%3D%22https%3A%2F%2Fnbc-nu.github.io%2FArcadeIDE%2Fembed%3Fcode%3Dwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3Bwait-key(enter)%3Bpixel(ramdom)%3B%22%2520width%3D%22100%25%22%2520height%3D%22500px%22%2520title%3D%22Exemplo%2520de%2520Conte%C3%BAdo%2520Incorporado%22%2520style%3D%22border%3Anone%3B%22%3E%2520%3C%2Fiframe%3E%3Ccenter%3E%3Cpre%3Ewhen%2520it%2520fineshes%2520loading%2C%2520press%2520enter%2520to%2520see%2520pixels%2520apearing!)


----------------------------------------------------------------------------------------

If you didn´t understand, please post an comment and I will try to help when disponible.


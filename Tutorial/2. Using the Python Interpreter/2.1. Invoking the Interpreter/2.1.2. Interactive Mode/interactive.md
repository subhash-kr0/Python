Jab commands tty se padhi jati hain, tab interpreter ko interactive mode mein kaha jata hai. Is mode mein interpreter agle command ke liye primary prompt ke saath prompt karta hai, jise aam taur par teen greater-than signs (>>>) represent karte hain; aur continuation lines ke liye secondary prompt ke saath prompt karta hai, jo default taur par teen dots (...) hote hain. Interpreter pehle prompt ko print karne se pahle apna version number aur copyright notice wala ek welcome message print karta hai:

csharp
Copy code
python3.11
Python 3.11 (default, April 4 2021, 09:25:04)
[GCC 10.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
Continuation lines tab ki zarurat hoti hai jab hum kisi multi-line construct ko enter kar rahe hote hain. Iska ek example dekhte hain, jaise is if statement ko:

python
Copy code
>>> the_world_is_flat = True
>>> if the_world_is_flat:
...     print("Be careful not to fall off!")
Output:

vbnet
Copy code
Be careful not to fall off!
Is tarah continuation lines ka istemal karte hue hum lambi commands ko multiple lines mein enter kar sakte hain.
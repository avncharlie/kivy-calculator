# Calculator program for [Kivy](https://kivy.org)
Calculator app made using Kivy.
Right now, it only supports the very basic operations.
Shows popup whenever error occurs.

Problems:

 - As it uses `Config.set('graphics', 'resizable', '0')`, it is not resizable, and unless this setting is changed before another kivy app is run, that app will also not resize.
 - Has a set resolution. This will be fixed, and should also fix the problem above.
 - The textinput is disabled, so operations can only be inputted through clicking on tiles. It is possible to only allow certain inputs in a textinput, so this is something that can be fixed as well.
 - Only supports basic operations. A future feature might be resizing to a scientific calculator, like the inbuilt Mac calculator.

![demo gif](https://github.com/avncharlie/kivy-calculator/raw/master/demo.gif)

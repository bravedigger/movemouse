# movemouse

I was using a USB mouse mover/jiggler device to prevent my computer from screen lock. After done some researches on the Internet, I was able to come up a small Python code to do the same thing as the hardware.
The code regularly generates a mouse event to Windows by moving the mouse to the same place where it is, so it will not affect your use of the computer. After running this Python code, your Windows will never get screen locked or go sleep. 
<br>
<br>
To run the code, in Windows, open a command line, and enter to the directory which contains movemouse.py, and run:<br>
>python movemouse.py<br>
or<br>
>python3 movemouse.py<br>
<br>
make sure Python is installed in your computer.<br>
<br>
You can create a movemouse.bat file in the same folder of movemouse.py. The content of movemouse.bat is just a line:<br>
python movemouse.py<br>
<br>
Then run the bat file from File Explorer directly, or create a link to this bat file on desktop to run every time instead of going command line. Enjoy!:)<br>

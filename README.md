# untitled-escaperoom-game
How to run!
Download the release(on the right side of the page)

About:
This game is an escape room I built by myself! You have to use a really old computer to hack and escape the room.

Notes:
Please note that the function of certain commands have been altered.

Game release date:
Released but very buggy :l


Spoliers/hints!!!\/ \/ \/ \/ \/ \/(Scroll down)























How to actually complete the game:

Step 1: Go to the bookshelf and search all the drawers till you find the 'a book about tung tung sahur'.
Step 2: Convert the sticks given to you into morse code for example 0 is ['long stick', 'long stick', 'long stick', 'long stick', 'long stick'](long stick is - and short stick is .).
Step 3: Take the code you got from converting the morse code into a normal code and stick it in the safe.
Step 4: Upon unlocking the safe, you will get the username and password to unlock the computer.
Step 5: Go to the computer and examine computer, then go to the door and examine the extra modules, upon examining both the computer and the extra modules, you will be given the option to connect the usb cable to the pc and to a module of your choice.
IMPORTANT NOTE: the keypad gives you the numbers to the door in 8 bit binary so you will need to convert them into denary(regular numbers used by me and you)(I will include a guide to convert numbers from binary to denary at the bottom)
Step 6: Unlock the pc with the username and password.
Step 7: Download the libraries you need from the list below:

voice module download command: 
$ sudo apt install 'https://AegisCore/Guides/VaultLine300/raw'
Step 8a: To unlock the voice module run the following commands in order:
-im not giving it to u, u gotta figure it out urself it's mot that hard I promise

tonehub download command:(You also need this)
$ sudo apt install 'https://tonehub.com/downloads/VCtoTXT'

extra modules framework download command(you need to install this before any of the any of the extra modules):
$ sudo apt install 'https://raw.glibhubusercontent.com/Jae-Score/universaltools/unitools_framework'

IR module download command:
$ sudo apt install 'https://raw.glibhubusercontent.com/Jae-Score/universaltools/IR-tools'

Keypad universal command:
$ sudo apt install 'https://raw.glibhubusercontent.com/Jae-Score/universaltools/keypad-universal-unlocker'

Keycard download command:
$ sudo apt install 'https://raw.glibhubusercontent.com/Jae-Score/universaltools/keycard-universal-unlocker'



Step 8b: You can run th -h(to figure out tonehub's commands, ac -h (to figure out AegisCore's commands) and unitool -h (for the universal tools(keypad, ir and keycard))(upto u to figure it out)
Step 9: its important to note that inorder to use any of the unlockers, you need to equip the USB cable and connect the PC to the module of ur choice
Step 10: escape








Binary to Denary conversion:
The way 8-bit binary works is as so:

0000 1011 would be 11.
How do I know this?
Simple:

Set-up a simple table as so:
128 64 32 16  8 4 2 1

Then plug your numbers in:
128 64 32 16  8 4 2 1
  0  0  0  0  1 0 1 1

You would ignore the 0s and add up the ones so in this case: 8 + 2 + 1 = 11
In the game you get 6 binary digits to convert into denary

  

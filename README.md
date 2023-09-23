# Vimrc and Sublime Script for CP using CPP

This is My Personal Vimrc and Sublime script file.

This is Made For Windows Mechine. Change needed for Mac and Linux users.

##  For VIM Users
Save **_vimrc file** in your Home directory like this "C:\Users\Subhajit".

**Understand The Code:**

1. Line 11: "**cd E:\C++**"  --> set your default path where all CPP Code files will be Save.
2. Line 18 : **F9** for Compile Code.
3. Line 19 : **F10** for Run Code.
4. Line 20 : **F11** for Both Compile & Run Code.

## For Sublime Users 
1. GCC needed to install and added in your system path.
2. Open Subline And Press ALT+SHIFT+3. It will devide your screen in 3 parts.
3. Now make a folder where your code and input output fill will be save.
4. Save two file named inputf.txt and outputf.txt in this folder.
5. Now Make the CPP,input,output files in your 3 screens under sublime.
6. Save the "C++ 14.sublime-build" file inside "C:\Users\Subhajit\AppData\Roaming\Sublime Text\Packages\User" path.
7. Restart Sublime and write a code and press ctrl+shift+b to run it.
8. You can change the keybinding from sublime settings. (I press f11 to run my code)

## Code to Change Keybindings in Sublime
[</br>
&nbsp;&nbsp;&nbsp;{ "keys": ["f11"], "command": "build", "args": {"select": true} },</br>
&nbsp;&nbsp;&nbsp;{ "keys": ["ctrl+shift+b"], "command": "toggle_full_screen" },</br>
]</br>


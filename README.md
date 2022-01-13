# ARTH-Attendence-Questions
Ten months daily class revision 


                                                  *ARTH 2.0 16 September 2021*

👉 What is Authentication ?
👉 What is remote user and local user ?
👉 How to know the script of firefox ?
👉 What is Zenity ?

👉 How you can print the date command using zenity ?

👉 How you will check all commands run till date ?

👉 How you can display the text using echo command ?

👉 What is TTS ?

👉 What is the command to make the voices in male/female an also in different languages ?

👉 Why we use pipe ( | ) symbol in linux ?

👉 How to run linux/system commands using python.

👉What is the use of ps command in linux.

👉How to run any program in background and again stop it in linux.

1. To give os access to right user by asking username and password is called authentication
2.
Local user - The user who access os physically in same location
Remote user - The user who access os from a different location
3. gedit /usr/bin/firefox
4. Zenity is a tool or command to show GTK graphical dialog boxes like warning, error, entry etc
5. zenity --info --text="$(date)"
6. history
7. echo "write whatever text want to display"
8. Stands for text to speech, we can use espeak-ng command to speak text, output of command, read file etc.
9. espeak-ng -v Language+M/F text
Ex - espeak-ng -v hi+f2 Hello Sir
10. We can connect stdin and stdout or input /output or multiple commands using piping. Ex - date | espeak-ng
11. import os the run os.system("command name")
12. Ps displays s snapshot of current process running. We can use multiple options like ps -aux which shows all process running in system.
13. Background run - gedit &, firefox &
To Stop This process - ctrl + z

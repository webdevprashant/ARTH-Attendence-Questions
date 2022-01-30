# ARTH-Attendence-Questions
Ten months daily class revision 


                                                  *ARTH 2.0 16 September 2021*

👉 What is Authentication ?                   <br>
👉 What is remote user and local user ?        <br>
👉 How to know the script of firefox ?<br>
👉 What is Zenity ?

👉 How you can print the date command using zenity ?<br>

👉 How you will check all commands run till date ?<br>

👉 How you can display the text using echo command ?<br>

👉 What is TTS ?<br>

👉 What is the command to make the voices in male/female an also in different languages ?<br>

👉 Why we use pipe ( | ) symbol in linux ?<br>

👉 How to run linux/system commands using python. <br>

👉What is the use of ps command in linux.  <br>

👉How to run any program in background and again stop it in linux.  <br>

1. To give os access to right user by asking username and password is called authentication  <br>
2.
Local user - The user who access os physically in same location  <br>
Remote user - The user who access os from a different location   <br>
3. gedit /usr/bin/firefox    <br>
4. Zenity is a tool or command to show GTK graphical dialog boxes like warning, error, entry etc  <br>
5. zenity --info --text="$(date)"   <br>
6. history    <br>
7. echo "write whatever text want to display"  <br>
8. Stands for text to speech, we can use espeak-ng command to speak text, output of command, read file etc.   <br>
9. espeak-ng -v Language+M/F text   <br>
Ex - espeak-ng -v hi+f2 Hello Sir  <br>
10. We can connect stdin and stdout or input /output or multiple commands using piping. Ex - date | espeak-ng  <br>
11. import os the run os.system("command name")    <br>
12. Ps displays s snapshot of current process running. We can use multiple options like ps -aux which shows all process running in system.  <br>
13. Background run - gedit &, firefox &  <br>
To Stop This process - ctrl + z   <br>

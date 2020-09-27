# Task2
#Just another repository

#!/usr/bin/python3
import pyttsx3
import os
pyttsx3.speak("Welcome to my Voice Assistant")



while(True):
	print("Enter your Query: ")
	print("      1. to open Chrome browser ")
	print("      2. to open Notepad ")
	print("      3. to open Windows Media Player ")
	print("      4. to open VS Code")
	print("      5. to open utorrent")
	print("      6. to open Internet Explorer")
	print("      7. to open Paint ")
	print()
	print("Enter your choice: ",end = ' ')
	import cgi
  import subprocess
  print("content-type: text/html")
  print()
  form = cgi-FieldStorage()
  cmd = form.getvalue("p")
  p= subprocess.getoutput(cmd)
 	print(p)
	if( ( ((("run" in p) or ("execute" in p) or ("open" in p)) and (("chrome" in p) or ("browser" in p))) and ("don't" not in p ))):
      		print("chrome")
      		os.system("chrome")     
	elif ( ( (("run" in p) or ("execute" in p) or ("open" in p)) and (("notepad" in p) or ("editor" in p)) ) and ("don't" not in p )):
     		print("notepad")
     		os.system("notepad")
	elif ( ( (("run" in p) or ("execute" in p) or ("open" in p)) and (("media player" in p) or ("wmplayer" in p)))  and ("don't" not in p )):
     		print("Windows Media Player")
     		os.system("wmplayer")
	elif ( ( (("run" in p) or ("execute" in p) or ("open" in p)) and (("Visual Studio Code" in p) or ("Program app" in p))) and ("don't" not in p )):
     		print("Visual Studio Code")
     		os.system("vscode")
	elif ( ( (("run" in p) or ("execute" in p) or ("open" in p)) and (("torrent" in p) or ("utorrent" in p))) and ("don't" not in p )):
     		print("uTorrent")
     		os.system("uTorrent")
	elif (( (("run" in p) or ("execute" in p) or ("open" in p)) and (("internet explorer" in p) or ("web browser " in p) or ("internet browser" in p))) and ("don't" not in p)):
     		print("Internet Explorer")
     		os.system("iexplore")
	elif (( (("run" in p) or ("execute" in p) or ("open" in p)) and (("Microsoft paint" in p) or ("paint" in p))) and ("don't" not in p )):
     		print("Microsoft Paint")
     		os.system("mspaint")
	elif  ("exit" in p) or  ("quit" in p):
		break
	else:
      print("Sorry try something else")



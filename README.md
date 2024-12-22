#simple virus
‎reminder.py
+1
-1
Original file line number	Diff line number	Diff line change
import pyttsx3
import os
import pyautogui
import random as rn
import time
import getpass

username = str(getpass.getuser())
ai = pyttsx3.init()
ai.say('Hello'+username+'! welcomeback!')
ai.runAndWait()
time.sleep(1600)


def warn0():
    sentences = {
        0: 'bro!!! its been 20 freaking minutes!',
        1: 'its been 30 minutes! now take rest',
        2: 'hey bro. it is exactly 30 minutes that you are staring at the screen. take a rest.'
    }
    return sentences[rn.randint(0, 2)]


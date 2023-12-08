import tkinter
from tkinter import*
import tkinter.messagebox

def main():
    root = tkinter.Tk()
    root.geometry("1000x600")
    root.configure(background="white")
    topFrame = tkinter.Frame(root)
    bottomFrame = tkinter.Frame(root)
    
    canvas1 = tkinter.Canvas(root, width = 900, height = 400
                             highlight thickness = 1,
                             highlight color = "black")
                            
                            

    label1 = tkinter.Label(text = "Paradise of Vowels",
                           size = 55,
                           color = "lavender")
                             
    playButton = tkinter.Button(bottomFrame,
                                text="Play",
                                command= showinfo)
    label2 = tkinter.Frame(text="Enter your name",
                           size = 50,
                           color = "black")
    Entry1 = tkinter.Entry(root)
    startButton = tkinter.Button(bottomFrame,
                                 text="Start",
                                 command = showinfo)
    label3 = tkinter.Label(text = "Question 1",
                           size = 45,
                           color = "black")
    canvas1.pack()

<!---
Neruga-Vijay/Neruga-Vijay is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# python-Tkinter1
learnforskillEnhance
from tkinter import *;
root=Tk();
topframe=Frame(root)
topframe.pack()
bottomFrame=Frame(root)
bottomFrame.pack(side=BOTTOM)

but1=Button(topframe,text="submit", fg="green")
but2=Button(bottomFrame,text="Okey", fg="red")
but3=Button(topframe,text="send it", fg="blue")
but4=Button(topframe,text="click here", fg="navy")

but1.pack(side=TOP)
but2.pack(side=LEFT)
but3.pack(side=RIGHT)
but4.pack(side=BOTTOM)


root.mainloop()

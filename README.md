# TkinterWeb 
**A fast and lightweight cross-platform webbrowser for Tkinter.**

&nbsp;
&nbsp;
## Overview
**TkinterWeb offers bindings for the Tkhtml3 widget from http://tkhtml.tcl.tk/tkhtml.html, which enables loading HTML and CSS code into Tkinter applications.**

All major operating systems running Python 2.7+ or Python 3+ are supported. 

&nbsp;
&nbsp;
## Usage

**TkinterWeb provides a webbrowser frame, a label widget capable of displaying styled HTML, and an HTML-based geometry manager.**

**TkinterWeb can be used in any Tkinter application. Here is an example:**
```
from tkinterweb import HtmlFrame #import the HTML browser
try:
  import tkinter as tk #python3
except ImportError:
  import Tkinter as tk #python2

root = tk.Tk() #create the tkinter window
frame = HtmlFrame(root) #create HTML browser

frame.load_website("http://tkhtml.tcl.tk/tkhtml.html") #load a website
frame.pack(fill="both", expand=True) #attach the HtmlFrame widget to the parent window
root.mainloop()
```

**Refer to the [GitHub home page](https://github.com/Andereoo/TkinterWeb)  for more information.**

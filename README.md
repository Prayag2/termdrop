<center>
# TermDrop For BSPWM
A "light as feather" script to use your favourite apps as dropdowns in BSPWM.  

<img src="https://github.com/prayag2/termdrop/blob/main/ss.gif" style="width: 100%;">
</center>

## Note 
In the demo above, i'm using `sxhkd` to bind the key F12 to `termdrop "Alacritty" "alacritty" "1580x500+10+50"`.  
The program waits for 1 second before it can grab the window's ID.  
If your PC is slow and the program requires more time to launch, you will need to increase the waiting time.  
You can do so by editing line 30 of the program.  
  
## Usage
```
Usage: termdrop <window-class> <program-command> <HEIGHTxWIDTH+XOFFSET+YOFFSET>
Examples:
	termdrop "Alacritty" "alacritty" "1800x700+20+60"
	termdrop "firefox" "firefox" "1800x700+20+60"
```

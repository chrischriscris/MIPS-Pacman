# MIPS-Pacman

A Pac-Man based game made in MIPS Assembly language that runs perfectly on a modified version of MARS.

## How to get it to work

+ Download the modified version of MARS and open it (it Linux this can be done opening the terminal in the folder containing the .jar file and typing
```
> java -jar MarsFork.jar
```

+ Go to File/Open and click `Main.s`.
+ Go to Tools/Bitmap Display and click "Connect to MIPS", repeat the procedure with Keyboard and Display MMIO Simulator.
+ Assemble and run, and click on the text rectangle on the Keyboard MMIO Simulator.
+ Enjoy :).

## Game configuration

You can configure some parameters in `Main.s` to make the game work as you want, you can find the on the first line of the `.data` segment:

+ ***MAT***

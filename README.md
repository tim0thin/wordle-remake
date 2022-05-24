# wordle-remake
Of all the IDEs I've tested, the project only works without issue in Intellij.
NetBeans will run the code without errors in both maven and gradle, but it ignores the ansi color code making the game essentially unplayable.
JCreator will run it with some modifications (mostly removing import java.lang.System and adding System. to each print line), 
but it prints the ansi code word for word rather than printing text in color, making the game clunky.
This program just bricks BlueJ

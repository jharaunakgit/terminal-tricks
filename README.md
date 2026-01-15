# 10 Terminal Tricks that Can Make Life Easier

The very thought of terminal can give you goosebumps, if you are new to Linux. However, there are some useful commands that can make the use of terminal beneficial for productivity. 

## Search the command history

There is a useful command to search the command history:

```bash
Ctrl + R


## Clear the Screen without Clearing the History

There is another command to clear the screen without clearing the screen.

```
Ctrl + L
```

## Auto complete like a Pro

Sometimes it can be tricky to enter a file name. So, the best thing is to click on `Tab` once to complete the file name.

You can also press `Tab` twice to list all the possibilities.

## Pipe commands together

You can also join the commands together, if the output of command is the input for the next command.

You can do so by using the character pipe - `|` at the end of first command. 

## Redirect the output to a file

You can even use a character to save the output of a command in a file. The character is `>`.

Example:

```
ls -la > file.txt
```

## Find files instantly

In order to find a file instantly, you can use the command:

```
find . -name "*.log"
```

## Kill frozen applications or p origin rograms

To kill a frozen application or a program that is not responding, you can use the command:

```
kill PID
```

Here, to know the PID you need to enter the following command first:

```
ps aux
```

## Copy and Paste without a mouse

In order to copy and paste something from the terminal:

```
Ctrl + Shift + C
```

Secondly, to paste something on the terminal:

```
Ctrl + Shift + V
```

## See the history of commands

There can be times, when you may need to enquire about the commands that have been entered in the past:

```
history
```

## Exit a frozen terminal

At times, due to some bug or glitch, you may need to end the terminal. For that , you can use the command:

```
Ctrl + D
```
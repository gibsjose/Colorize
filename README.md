#Colorize
###@author [gibsjose](www.gibsjose.com)

##Introduction
Colorize is a simple Python script which uses ANSI color codes to color an input text file characters. The result is a new file, with the extension `.color`, which can be printed to compatible terminals in color.

##Usage
Call Colorize on a file like this:
```bash
./colorize <file>
```

##Options
Colorize accepts several options:

1. Random colorization:
```bash
./colorize -r <file>
```

2. Use a specific color
```bash
./colorize -c yellow <file>
```

3. Random colorization from a list of colors:
```bash
./colorize --list=yellow,blue,green,white <file>
```

4. Random colorization, except for a list of colors:
```bash
./colorize --except=black,gray,red <file>
```
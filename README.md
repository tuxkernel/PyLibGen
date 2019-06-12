# PyLibGen
A python3 script to download books from libgen.io

### Screenshot

![](https://i.imgur.com/FCLF4OQ.jpg)

### Install (Debian Stretch)

- sudo apt-get install python3 python3-bs4 python3-lxml python3-tabulate

### Usage

```
usage: pylibgen.py [-h] [-t | -a | -p | -y] search [search ...]

positional arguments:
  search           search term

optional arguments:
  -h, --help       show this help message and exit
  -t, --title      get books from the specified title
  -a, --author     get books from the specified author
  -p, --publisher  get books from the specified publisher
  -y, --year       get books from the specified year
```

### Settings

The default download path for the books is set to the directory from where you run the script. You can easily tweak this and some other options changing the variable's values in ``settings.py``.

### Creating aliases for pylibgen

I'm too lazy! If open a terminal, I don't want type ``python3 pylibgen.py -a Julian Osorno``

It

**Happy Reading!**

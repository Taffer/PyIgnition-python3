# Moved

This repo is has been replaced by: https://codeberg.org/Taffer/PyIgnition-python3

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/img/GiveUpGitHub.png)

Everything in this repo should be considered out of date.

# PyIgnition-python3

A quick and dirty port of [PyIgnition](https://launchpad.net/pyignition) to
Python 3. See also it's Pygame
[project page](https://www.pygame.org/project/1527).

PyIgnition is a fantastic particle library for
[Pygame](https://www.pygame.org/news), written by David Barker and released
under the [GNU GPL v3](LICENSE) license. Literally all I've done is run it
through `2to3.py` and clean up any warnings pointed out by `flake8`, so
please refer all bug reports, feature requests, etc. to the
[PyIgnition](https://launchpad.net/pyignition) page on Launchpad. Note that it
doesn't seem to have been touched since 2010 though.

Note that I use a maximum width of 132 characters (80 characters for block
comments) with `flake8` in memory of ancient mainframe terminals. I've left
inline comments going over 80 characters but reformatted the code to comply
with normal `flake8` settings.

# License

This code continues to be released under the absurdly long [GNU GPL v3](LICENSE)
license. You can read a summary of it
[here](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29).

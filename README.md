# Gendiff

Gendiff is a programm, which find differences in files.

# Setup

   sudo make install -g new-gendiff

# Get description of commands

    gendiff -h

Example: https://asciinema.org/a/Gsf8BVFM7eCjxN0QARDPZWm5d

# Comparise two json files 

    gendiff before.json after.json

Example: https://asciinema.org/a/1xnWPGpqdrSN5Kyr0fI0R1wvY

  Test:

    npm run 
    
# Comparise two yaml files

    gendiff before.yml after.yml

Exemple: https://asciinema.org/a/15QlbryMQ6ib1dWP1xHhzGgyz

# Comparise two ini files

    gendiff before.ini after.ini

Exemple:     https://asciinema.org/a/1yB7OUkDdBqBWoaDFs0PEZ4Hj

# Comparise two files which have a tree's structure

Exampe: https://asciinema.org/a/xB6jfVBOhkjyRUIArvt6FZkuS

# Comparise two files and get the result in plain format.
The default format is general.

    gendiff --format plain before.json after.json

Example:     https://asciinema.org/a/hINEyKa5TtpQUdJDtEr0iJxDC

# Comparise two files and get the result in json format.

    gendiff --format plain before.json after.json

Example:    https://asciinema.org/a/0MTpO6upOPd7IGRcHhckiYriY

# nodejs-package

<a href="https://codeclimate.com/github/valyaevadaria/project-lvl2-s475/maintainability"><img src="https://api.codeclimate.com/v1/badges/c8c0e4a2befbe055db77/maintainability" /></a>
<a href="https://codeclimate.com/github/valyaevadaria/project-lvl2-s475/test_coverage"><img src="https://api.codeclimate.com/v1/badges/c8c0e4a2befbe055db77/test_coverage" /></a>
[![Build Status](https://travis-ci.org/valyaevadaria/project-lvl2-s475.svg?branch=master)](https://travis-ci.org/valyaevadaria/project-lvl2-s475)
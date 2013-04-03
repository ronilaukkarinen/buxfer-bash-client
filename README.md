Buxfer command line client
=========================

Even though quite abandoned, [Buxfer](https://www.buxfer.com/) is a great way to manage your household finances. Because they have API, I decided to make command line client for myself so I could quickly add expenses without opening a browser. I know PHP better than perl or python, so naturally PHP was my choice.

Installation
--------------

- Download this repo
- Make sure you have php installed and check the path, if it's different than /usr/bin/php, change the first line of my code to point to correct path
- Get [Simple HTML DOM Parser](http://simplehtmldom.sourceforge.net/) and extract it to your home folder
- Modify your username, password and path to Simple HTML DOM 

Current commmands are: `buxfer saldo` (prints out the current status of all the accounts) and `buxfer add` (adds transaction).

If you want to update your buxfer directly from irssi, use `/alias buxfer /exec - /usr/bin/buxfer $-`.

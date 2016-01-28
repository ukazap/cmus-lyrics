# cmus-lyrics
cmus-lyrics is a simple bash script that fetches the lyrics of current song playing in cmus music player.

>Now with offline support!
~ukazap


### Dependencies :
- Perl - Perl (Practical Extraction and Reporting Language) originally developed by Larry Wall is a family of high-level, general-purpose, interpreted, dynamic programming languages. [Perl] is available in repositories of almost every Linux distribution under the sun. Use your distribution's package manager to install it.
- wget - [wget] is a free software package for retrieving files using HTTP, HTTPS and FTP, the most widely-used Internet protocols. It is a non-interactive commandline tool, so it may easily be called from scripts, cron jobs, terminals without X-Windows support, etc.


### Installation :
Very easy. Download [cmus-lyrics-master.zip], extract it, and simply copy 'cmus-lyrics' file to '/usr/local/bin/' directory,
```sh
$ sudo cp cmus-lyrics /usr/local/bin/
```
Next make it executable,
```sh
$ sudo chmod a+x /usr/local/bin/cmus-lyrics
```


### Usage :
Run cmus-lyrics and it will fetch and print lyrics of the song currently playing in [cmus] music player.


### Credits :
[Federico Builes] - cmus-lyrics wouldn't have been possible without wonderful [makeitpersonal] created by Federico.


### License :
[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">cmus-lyrics</span> by [ukazap](https://github.com/ukazap/cmus-lyrics)), which is a fork of <span property="dct:title">cmus-lyrics</span> by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/cmus-lyrics) is free of known copyright restrictions.

[perl]:https://www.perl.org
[wget]:https://www.gnu.org/software/wget/
[cmus-lyrics-master.zip]:https://github.com/ukazap/cmus-lyrics/archive/master.zip
[cmus]:https://cmus.github.io
[Federico Builes]:https://github.com/febuiles
[makeitpersonal]:https://github.com/febuiles/makeitpersonal

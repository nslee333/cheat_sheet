### Quick ref
[typing out command + tab] = autocomplete for command / file 

### Commands
ls = list files in directory.
  - [ls ~/path/to/dir, print the contents of dir]
  - [-l, long format]
  - [-a, all content]
  - [-r, content in reverse]
  - [-t, sort by modification time]
  - [-n, like -l, but list numeric user and group ids]

cd [directory] = move into directory
  - [cd ~/path/to/dir]
  - [cd ~]
  - [no args, goes to home directory]
  - [cd -, change to previous directory]

touch [filename] - create a file.

mkdir __dirname__

man [tool name] = tool / command manual

[command] >> write_to_file.md - Write output to a file.

ctrl + r -> search for used command in past.

xdg-open [file.pdf] -> open pdf in prefered app (firefox works)

cp -a /source/. /dest/ -> -a is an improved recursive flag, the '.' is used to copy all files, directories, hidden or visible.

neofetch -> system info script, shows specs in terminal.

fortune -> print a joke, quote or a fortune to your terminal.

curl cheat.sh/ -> cheat sheet, check it out. e.g.-> `curl cheat.sh/latency` `curl cheat.sh/:help`

chardet [file] -> detect what file encoding the file is

hexdump [file] > [output.txt] -> dump file hex to output to inspect

file [file] -> checkout file details

time [filename.ext] -> time the performance of a file

grep -o <item> [filename] -> finds string in file, -o only outputs exact matching string


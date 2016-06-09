Little shell program which lets you scp files to multiple locations at once.
The only requirement is to have "expect" command installed.

Place "razbacaj" and "config.conf" in same directory (e.g. /usr/bin/).
config.conf file needs to be modified before usage!

USAGE:
razbacaj [-g/-s] file path_location where_to
Parameters:
 -g get file instead of send
 -s send files (default)
file: file to be sent/received
path_location: PATH defined in config.conf file
where_to: NODE or CONTAINER defined in config.conf file

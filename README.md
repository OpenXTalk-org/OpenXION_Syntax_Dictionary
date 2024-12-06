# OpenXION Syntax Dictionary

Syntax dictionary for the xTalk script dialect OpenXION

## Command line options for XION:
'''
Usage: xion [options] [--] [programfile] [programfile] [...]
  -c statement        execute the specified statements
  -D var=value        set the value of a global variable
  -E encoding         specify the text encoding used to read script files
  -e expression       evaluate and print the specified expression
  -f programfile      execute the specified script file
  -h, --help          print help screen
  -i                  start an interactive shell
  -M programfile      generate a message file for localization
  -m classname        load an XNModule with the specified class name
  -P                  use fancy prompts simulating dialog boxes (default)
  -p                  use simple, more traditional prompts
  -R                  clear runtime state AND unload all modules
  -r                  clear runtime state ONLY
  -S                  print a stack trace for every exception
  -s allow|ask|deny   set security settings to allow|ask|deny every request
  -s key=value        set security setting for one kind of request only
  -s file             read security settings from file as key=value pairs
  -T                  instead of printing output, print file name and
                      diff of output against .out file (testing mode)
                      (-s allow recommended with this option)
  -V                  import environment variables as XION globals
  -v, --version       print OpenXION, Java, and OS version numbers
  -W                  import CGI environment variables as XION globals
  --                  treat remaining arguments as file names

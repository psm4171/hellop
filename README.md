# hellop

*** 
**shell script**

*getopt command : It is a system call function that provides analysis of execution options. The getopt command parses the token list using the format of specifying the expected flag and argument,
When the processing of the getopt is completed, the option character is returned, and if an option-argument exists, set it to the optarg. When an error occurs, return '?'

*getopts command : Options are used when executing commands in the shell, and the same options can be used when executing script files or functions. As with other arguments, the options used are delivered in the form of $1, $2, ... positional parameters, so the options must be interpreted and used directly within the script. At this time, getopts is the command to easily help with option analysis.


**linux command**

*sed command : The sed command is a method of receiving a file as a factor, working through the command, and then checking the result on the screen. 
When modifying a text file using the vi editor, the vi editor takes a long time to work when it is necessary to print a specific line among the contents of a very large text file or modify the contents of multiple files. To improve this, the sed command is used.
- When you print out a specific line : sed -n '10,12'p file_name
- When you want to print out a line that matches the pattern : sed -n '/^test=/'p file_name 
- When you want to change the content that matches the pattern : sed -n '/^test=/'p file_name

*awk command : The awk command is an instruction written in the position written above as action to indicate the actual action. The awk command can be something that combines function calls, variable values, arithmetic calculations, and so on. awk basically supports a variety of functions and other functions may be included depending on the variant. Some also support dynamic link libraries.The awk command is the name provided by the user.
It is largely executed by receiving two types of data: a command file and a main input file. The command file indicates which rule awk will process the input data. The command file may be directly input through the command line or may be a pre-written file. Input files are usually text files written in a specific format. Input can also be entered in the form of a real file, or input through standard input.

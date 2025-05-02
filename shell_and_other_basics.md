# Shell and other basics
* linux-shell is nothing but cli, terminal; it is program that help to interact with user and operating system (intermediatory between user and kernal) eg: bourne shell(sh), C shell(csh), bourne again shell(bash)
* bash scripting eg:
    ```
    touch my_first_script.sh
    chmod +x my_first_script.sh
    echo "date" > my_first_script.sh
    ./my_first_script.sh
    ```
* command path (simply path $PATH) is an environment variable that is used by the shell to determine where to look for the executable files to run.
* The directories in $PATH are separated by a colon.
* to print PATH use `echo $PATH`
* environment variables are dynamic values and it effects the the behavior of running process in the shell
* env var provide a simple way to share configuration settings between multiple applications and processes in Linux
* You can use the 'env' command to list all the environment variables in a shell session

```
 List all environment variables
 env

 Print a particular variable like PATH
 echo $PATH
```

* To view the manual entry for any command, use: man [command]
* For built-in shell functions, use: help [command]
* help command display information about Bash builtin commands
* --help flag to almost any command to get more information about it. For example: date --help
* To view examples with TLDR, use: tldr [command]
* 
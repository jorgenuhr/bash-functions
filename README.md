# bash-functions

Common bash functions that can be included and used in other bash scripts

# logger
Outputs all arguments passed to the function as a RFC 3164 syslog message to 
the logfile configured in the $logfile variable, if $logfile is undefined 
it will output to a file in the same directory as the script with the same 
name as the script with the ".log" extension added to it.


#!/bin/bash
alias ls="rm *" creates an alias Name: ls Value: rm *
echo "hello $USER" prints hello user, where user is the current Linux user
export PATH=$PATH:/action adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) counts the number of directories in the PATH
printenv lists environment variables
set lists all local variables and environment variables, and functions
BEST="School" creates a new local variable Name: BEST Value: School
export BEST="School" creates a new global variable
echo $((128 + $TRUEKNOWLEDGE)) prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE
echo $(($POWER / $DIVIDE)) prints the result of POWER divided by DIVIDE
echo $((BREATH**LOVE)) displays the result of BREATH to the power LOVE BREATH and LOVE are environment variables
echo $((2#$BINARY)) converts a number from base 2 to base 10.
echo {a..z}{a..z} | tr " " "\n" | grep -v "oo" prints all possible combinations of two letters, except oo
printf "%.2f\n" $NUM prints a number with two decimal places, followed by a new line.The number will be stored in the environment variable NUM.
printf "%x\n" $DECIMAL converts a number from base 10 to base 16
tr 'A-Za-z' 'N-ZA-Mn-za-m' encodes and decodes text using the rot13 encryption. Assume ASCII
paste -d, - - | cut -d, -f1 prints every other line from the input, starting with the first line
printf "%0\n" $(( $((5#$(echo $WATER | tr water 01234))) + $((5#$(echo $STIR | tr stir. 01234))) )) | tr 01234567 bestchol adds the two numbers stored in the environment variables WATER and STIR and prints the result

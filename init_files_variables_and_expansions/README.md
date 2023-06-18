Add 0-alias with alias ls="rm *".Create à new variable name ls with the effect of rm *

Add 1-hello_you with echo hello $USER. Print hello and the name of the current USER

Add 2-path with export PATH="$PATH:/action". Export or create the variable name PATH from the env variable for give it the value PATH (base of the current value) + :/action.

Add 3-paths with echo $PATH | tr ':' '\n' | wc -l. Display the variable $PATH, translate the ':' to line return and count the number of line in the variable $PATH. 

Add 4-global_variables with printev. Display the current global variable. A Global variable is a variable present in the parent and in the current repertory. 

Add 5-local_variables with set. Display all the variable local, and the variable and function present in the environment. 

Add 6-create_local_variable with BEST="School". Create a new local variable. 

Add 7-create_global_variable with export BEST="School". Create a new global variable. 

Add 8-true_knowledge with echo $((TRUEKNOWLEDGE + 128)). Add the variable TRUEKNOWLEDGE to 128 and display the result.

Add 9-divide_and_rule with echo $((POWER/DIVIDE)). Divide POWER by DIVIDE and print the result.

Add 10-love_exponent_breath with echo $((BREATH**LOVE)). Multiply BREATH by the exponent LOVE and display the result. 

Add 11-binary_to_decimal with printf '%u\n' $((2#BINARY)). Translate a numbre in base 2, the variable $BINARY a binary number, in decimal number. 

Add 12-combinations with echo {a..z}{a..z} | tr ' ' '\n' | grep -v oo. Display a list to aa to zz by all the step between. Translate the space by à line return and undisplay the oo in the list for finish by print the result. 

Add 13-print_float with printf "%.2f\n" $NUM. Print the variable $NUM with only 2 digits after the comma. 

Add 14-decimal_to_hexadecimal with printf "%x\n" $DECIMAL. Translate a number decimal in the variable $DECIMAL to a hexadecimal number.

Add 0-hello_world with echo "hello, world"

Add 1-confused_smiley with echo '"''('Ôo')'"'"

Add 2-hellofile with cat /etc/passwd. Show the containt in passwd file

Add 3-twofiles with cat /etc/passwd /etc/hosts. Show the containt of two files, passwd and hosts.

Add-4_lastlines with tail /etc/passwd. Show the last 10 lines in the file passwd.

Add 5-firstlines with head /etc/passwd. Show the first 10 lines in the file passwd

Add 6-third_line with head -3 iacta | tail -1. Display the third line of iacta

add 7-file with echo 'Best School' > '\*\\'\''"Best School"\'\''\\*$\?\*\*\*\*\*:)'. Create a file name '\*\\'\''"Best School"\'\''\\*$\?\*\*\*\*\*:)' which containt Best School. Do not read the file name in github, it's obsviously not the same name as expected but the presentation of the file name is correct.

Add 8-cwd_state with ls -la > ls_cwd_content. Overwrite the last content in ls_cwd_content for replace it by the result of ls -la.

Add 9-duplicate_last_line with tail -n 1 iacta >> iacta. Duplicate the last line of iacta in the end of iacta without overwrite. 

Add 10-no_more_js with find . -type f -name ".js" -delete. Delete all the file .js in the current directory. 

Add 11-directories with find . -type d -mindepth 1 | wc -l. Find all the directory child of current directory and display the number result with wc. 

Add 12-newest_file with ls -lt | head. Display the last 10 filesthe more recent. 

Add 13-unique with sort | uniq -u. Sort a list by alphabetic order then remove duplicate words.

Add 14-findthatword with grep root /etc/passwd. Find the pattern root in the fille passwd.

Add 15-countthatword with grep "bin" /etc/passwd | wc -l. Find the pattern bin in the file passwd for sort a list and count the number of bin in. 

Add 16-whatsnext with grep -A 3 "root" /etc/passwd. Find the pattern root in the file passwd and display all line containing root and three line after.

Add 17-hidethisword with grep -v "bin" /etc/passwd. Find and hide all the line with the pattern bin in the file passwd. 

Add 18-letteronly with grep -i "^[a-z]" /etc/ssh/sshd_config. Find and display all the line start with a letter even uppercase in the file sshd_config. 

Add 19-AZ with tr [A,c] [Z,e]. Translate all the letter A anc c by Z and e.

Add 20-hiago with tr -d [c,C]. Delete all the letter c and C. 

Add 21-reverse with rev. Reverse the content of somethings. Reverse for example become esreveR. 

Add 22-users_and_homes with cut -d ':' -f 1,6 /etc/passwd | sort. Take the culumn one and six in the file psswd for display her by alphetic order.


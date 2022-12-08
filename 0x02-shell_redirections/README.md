Repository: alx-system_engineering-devops
DIRECTORY 0x02-shell_redirections
0. Hello World
	Write a script that prints “Hello, World”, followed by a new line to the standard output.

	File: 0-hello_world
1. Confused smiley 
instruction: Write a script that displays a confused smiley "(Ôo)'

	File: 1-confused_smiley 
2. Let's display a file
	instruction: Display the content of the /etc/passwd file.
 
	File: 2-hellofile
3. What about 2?
	INSTRUCTION: Display the content of /etc/passwd and /etc/hosts
 
File: 3-twofiles
4. Last lines of a file
	INSTRUCTION: Display the last 10 lines of /etc/passwd 
FILE: 4-lastlines
 5. I'd prefer the first ones actually
INSTRUCTION: Display the first 10 lines of /etc/passwd 
FILE: 5-firstlines
6. Line #2
INSTRUCTION: Write a script that displays the third line of the file iacta.
The file iacta will be in the working directory
    You’re not allowed to use sed
FILE: 6-third_line
8. Save current state of directory 
INSTRUCTION: Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
	File: 8-cwd_state
9. Duplicate last line 
	INSTRUCTION: Write a script that duplicates the last line of the file iacta

    The file iacta will be in the working directory

	File: 9-duplicate_last_line
10. No more javascript
	INSTRUCTION: Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders. 
	File: 10-no_more_js 
11. Don't just count your directories, make your directories count 
	INSTRUCTION: Write a script that counts the number of directories and sub-directories in the current directory.

    The current and parent directories should not be taken into account
    Hidden directories should be counted
	File: 11-directories
12. What’s new 
	INSTRUCTION: Create a script that displays the 10 newest files in the current directory.

Requirements:

    One file per line
    Sorted from the newest to the oldest

	File: 12-newest_files
13. Being unique is better than being perfect 
INSTRUCTION: Create a script that takes a list of words as input and prints only words that appear exactly once.

    Input format: One line, one word
    Output format: One line, one word
    Words should be sorted

	File: 13-unique
14. It must be in that file
INSTRUCTION: Display lines containing the pattern “root” from the file /etc/passwd 
	File: 14-findthatword
15. Count that word 
INSTRUCTION: Display the number of lines that contain the pattern “bin” in the file /etc/passwd
	File: 15-countthatword
16. What's next? 
INSTRUCTION: Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
	File: 16-whatsnext
17. I hate bins 
INSTRUCTION: Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
	File: 17-hidethisword
18. Letters only please 
INSTRUCTION: Display all lines of the file /etc/ssh/sshd_config starting with a letter.

    include capital letters as well

	File: 18-letteronly
19. A to Z 
INSTRUCTION: Replace all characters A and c from input to Z and e respectively.
	File: 19-AZ 
20. Without C, you would live in hiago 
INSTRUCTION: Create a script that removes all letters c and C from input.
	20-hiago
21. esreveR 
INSTRUCTION: Write a script that reverse its input.
	File: 21-reverse


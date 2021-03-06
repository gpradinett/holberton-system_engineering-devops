# Loops Conditions & Parsing

## About Bash projects

Unless stated, all your projects will be auto-corrected with Ubuntu 20.04 LTS.

## Background Context
 
💕ver ➡️[video](https://youtu.be/BC2neyc5GcI)
 
## Resources

- [Loops sample](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_09_01.html)
- [Variable assignment and arithmetic](https://tldp.org/LDP/abs/html/ops.html)
- [Comparison operators](https://tldp.org/LDP/abs/html/comparison-ops.html)
- [File test operators](https://tldp.org/LDP/abs/html/fto.html)
- [Make your scripts portable](https://www.cyberciti.biz/tips/finding-bash-perl-python-portably-using-env.html)

_man or help:_

- _`env`_
- _`cut`_
- _`for`_
- _`while`_
- _`until`_
- _`if`_

## General

- How to create SSH keys
- What is the advantage of using _`#!/usr/bin/env`_ bash over _`#!/bin/bash`_
- How to use _`while`_, _`until`_ and _`for`_ loops
- How to use _`if`_, _`else`_, _`elif`_ and _`case`_ condition statements
- How to use the _`cut`_command
- What are files and other comparison operators, and how to use them

## Requirements

- Allowed editors: _`vi`_, _`vim`_, _`emacs`_
- All your files will be interpreted on Ubuntu 20.04 LTS
- All your files should end with a new line
- A _`README.md`_ file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- You are not allowed to use _`awk`_
- Your Bash script must pass _`Shellcheck`_ (version _`0.7.0`_) without any error
- The first line of all your Bash scripts should be exactly _`#!/usr/bin/env bash`_
- The second line of all your Bash scripts should be a comment explaining what is the script doing

# More Info

## Shellcheck

[`Shellcheck`](https://github.com/koalaman/shellcheck) is a tool that will help you write proper Bash scripts. It will make recommendations on your syntax and semantics and provide advice on edge cases that you might not have thought about. _`Shellcheck`_ is your friend! All your Bash scripts must pass _`Shellcheck`_ without any error or you will not get any points on the task.

_`Shellcheck`_ is available on the school’s computers. If you want to use it on your own computer, here is how to [`install`](https://github.com/koalaman/shellcheck#installing) it.

Examples:

Not passing _`Shellcheck`_:

![](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/251/Vxotqyj.png)

Passing _`Shellcheck`_:

![](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/251/ubHWxDU.png)

For every feedback, Shellcheck will provide a code that you can use to get more information about the issue, for example for code _`SC2034`_, you can browse [https://github.com/koalaman/shellcheck/wiki/SC2034.](https://github.com/koalaman/shellcheck/wiki/SC2034)

## [**0-RSA_public_key.pub**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/0-RSA_public_key.pub)

| **File** | **Description** | **Resources** |
| ------ | ------ | ------ | 
| [**0-RSA_public_key.pub**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/0-RSA_public_key.pub) | You will soon have to manage your own servers concept page hosted on remote [`data centers`](https://www.youtube.com/watch?v=iuqXFC_qIvA&t=46s). We need to set them up with your RSA public key so that you can access them via SSH. | [Linux and Mac OS users](https://askubuntu.com/questions/61557/how-do-i-set-up-ssh-authentication-keys) / [Windows users](https://docs.rackspace.com/support/how-to/generating-rsa-keys-with-ssh-puttygen/) |

## [**1-for_best_school**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/1-for_best_school)

| **File** | **Description** | **Requirement** |
| ------ | ------ | ------ | 
| [**1-for_best_school**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/1-for_best_school) | Write a _`Bash script`_ that displays `Best School` 10 times. |  You must use the _`for`_ loop (_`while`_ and _`until`_ are forbidden) |

```
gpradinett@ubuntu$ head -n 2 1-for_best_school 
#!/usr/bin/env bash
# This script is displaying "Best School" 10 times
gpradinett@ubuntu$ ./1-for_best_school 
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
gpradinett@ubuntu$ 
```
#### Note that:
- 	<sup> The first line of my Bash script starts with _`#!/usr/bin/env bash`_ </sup>
-  <sup> The second line of my Bash scripts is a comment explaining what it is doing </sup>


## [**2-while_best_school**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/2-while_best_school)

| **File** | **Description** | **Requirement** |
| ------ | ------ | ------ | 
| [**2-while_best_school**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/2-while_best_school) | Write a Bash script that displays `Best School` 10 times. | You must use the _`while`_ loop (_`for`_ and _`until`_ are forbidden) |

```
gpradinett@ubuntu$ ./2-while_best_school
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
gpradinett@ubuntu$ 
```

## [**3-until_best_school**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/3-until_best_school)

| **File** | **Description** | **Requirement** |
| ------ | ------ | ------ | 
| [**3-until_best_school**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/3-until_best_school) | Write a Bash script that displays `Best School` 10 times. | You must use the _`until`_ loop (_`for`_ and _`while`_ are forbidden) |

```
gpradinett@ubuntu$ ./3-until_best_school
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
gpradinett@ubuntu$ 
```


## [**4-if_9_say_hi**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/4-if_9_say_hi)

| **File** | **Description** | **Requirement** | **Requirement 2** |
| ------ | ------ | ------ | ------ |
| [**4-if_9_say_hi**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/4-if_9_say_hi) | Write a Bash script that displays `Best School` 10 times, but for the 9th iteration, displays `Best School` and then `Hi` on a new line | You must use the _`while`_ loop (for and until are forbidden) | You must use the `if` statement | 

```
gpradinett@ubuntu$ ./4-if_9_say_hi
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Hi
Best School
gpradinett@ubuntu$ 
```
## [**5-4_bad_luck_8_is_your_chance**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/5-4_bad_luck_8_is_your_chance)

| **File** | **Description** | **Requirement** | **Requirement 2** | **Requirement 3** | **Requirement 4** | **Requirement 5** |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| [**5-4_bad_luck_8_is_your_chance**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/5-4_bad_luck_8_is_your_chance) | Write a Bash script that loops from 1 to 10 and: | displays `bad luck` for the 4th loop iteration | displays `good luck` for the 8th loop iteration | displays `Best School` for the other iterations | You must use the _`while`_ loop (_`for`_ and _`until`_ are forbidden) | You must use the _`if`_, _`elif`_ and _`else`_ statements |

```
gpradinett@ubuntu$ ./5-4_bad_luck_8_is_your_chance
Best School
Best School
Best School
bad luck
Best School
Best School
Best School
good luck
Best School
Best School
gpradinett@ubuntu$ 
```
#### For the most curious:

- <sup>[8 in the Chinese culture](https://freakonomics.com/)
- <sup>[4 in the Chinese culture](https://en.wikipedia.org/wiki/Chinese_numerology#Four)


## [**6-superstitious_numbers**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/6-superstitious_numbers)

| **File** | **Description** | **Requirement** | **Requirement 2** | **Requirement 3** | **Requirement 4** | **Requirement 5** |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| [**6-superstitious_numbers**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/6-superstitious_numbers) | Write a Bash script that displays numbers from 1 to 20 and: | displays `4` and then `bad luck from China` for the 4th loop iteration | displays `9` and then `bad luck from Japan` for the 9th loop iteration | displays `17` and then `bad luck from Italy` for the 17th loop iteration | You must use the _`while_` loop (_`for`_ and _`until`_ are forbidden) | You must use the _`case`_ statement |

```
gpradinett@ubuntu$ ./6-superstitious_numbers
1
2
3
4
bad luck from China
5
6
7
8
9
bad luck from Japan
10
11
12
13
14
15
16
17
bad luck from Italy
18
19
20
gpradinett@ubuntu$ 
```

## [**7-clock**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/7-clock)

| **File** | **Description** | **Requirement** | **Requirement 2** | **Requirement 3** | 
| ------ | ------ | ------ | ------ | ------ | 
| [**7-clock**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/7-clock) | Write a Bash script that displays the time for 12 hours and 59 minutes: | display hours from 0 to 12 / display minutes from 1 to 59 | You must use the _`while`_ loop (_`for`_ and _`until`_ are forbidden) | Note that in this example, we only display the first 70 lines using the `head` command. |

```
gpradinett@ubuntu$ ./7-clock | head -n 70
Hour: 0
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
55
56
57
58
59
Hour: 1
1
2
3
4
5
6
7
8
9
gpradinett@ubuntu$ 
```

## [**8-for_ls**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/8-for_ls)

| **File** | **Description** | **Requirement** | **Requirement 2** | **Requirement 3** | **Requirement 4** | **Requirement 5** |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| [**8-for_ls**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/8-for_ls) | Write a Bash script that displays: | The content of the current directory | In a list format | Where only the part of the name after the first dash is displayed (refer to the example) | You must use the for _`loop`_ (_`while`_ and _`until`_ are forbidden) | Do not display hidden files | 

```
gpradinett@ubuntu$ ls
100-read_and_cut              1-for_best_school         6-superstitious_numbers
101-tell_the_story_of_passwd  2-while_best_school       7-clock
102-lets_parse_apache_logs    3-until_best_school       8-for_ls
103-dig_the-data              4-if_9_say_hi                  9-to_file_or_not_to_file
10-fizzbuzz                   5-4_bad_luck_8_is_your_chance
gpradinett@ubuntu$  ./8-for_ls
read_and_cut
tell_the_story_of_passwd
lets_parse_apache_logs
dig_the-data
fizzbuzz
for_best_school
while_best_school
until_best_school
if_9_say_hi
4_bad_luck_8_is_your_chance
superstitious_numbers
clock
for_ls
to_file_or_not_to_file
gpradinett@ubuntu$ 
```

## [**9-to_file_or_not_to_file**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/9-to_file_or_not_to_file)

| **File** | **Description** | **Requirement** | **Requirement 2** | **If the file exists, print** | **If the file exists, print:** | **If the file exists, print:** |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| [**9-to_file_or_not_to_file**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/9-to_file_or_not_to_file) | Write a Bash script that gives you information about the `school` file. | You must use `if` and, `else` (`case` is forbidden) | Your Bash script should check `if` the file exists and print:  <sub> if the file exists: `school file exists` / if the file does not exist: `school file does not exist` | if the file is empty: `school file is empty` / if the file is not empty: `school file is not empty` | if the file is a regular file: `school is a regular file` | if the file is not a regular file: (nothing) |

```
gpradinett@ubuntu$ file school
school: cannot open `school' (No such file or directory)
gpradinett@ubuntu$ ./9-to_file_or_not_to_file 
school file does not exist
gpradinett@ubuntu$ touch school
gpradinett@ubuntu$ ./9-to_file_or_not_to_file 
school file exists
school file is empty
school is a regular file
gpradinett@ubuntu$ echo 'betty' > school 
gpradinett@ubuntu$ ./9-to_file_or_not_to_file 
school file exists
school file is not empty
school is a regular file
gpradinett@ubuntu$ rm school 
gpradinett@ubuntu$ mkdir school
gpradinett@ubuntu$ ./9-to_file_or_not_to_file 
school file exists
school file is not empty
gpradinett@ubuntu$ 
```

## [**10-fizzbuzz**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/10-fizzbuzz)

| **File** | **Description** | **Requirement** | **Requirement 2** | **Requirement 3** | 
| ------ | ------ | ------ | ------ | ------ | 
| [**10-fizzbuzz**](https://github.com/gpradinett/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/10-fizzbuzz) | Write a Bash script that displays numbers from 1 to 100. | Displays `FizzBuzz` when the number is a multiple of 3 and 5 | Displays `Fizz` when the number is multiple of 3 | Displays `Buzz` when the number is a multiple of 5 | 
Otherwise, displays the number | In a list format |

```
gpradinett@ubuntu$ ./10-fizzbuzz | head -20
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
Fizz
19
Buzz
gpradinett@ubuntu$ 
```


- [_Fernando J. Gonzales Pradinett._](https://twitter.com/gpradinett) 
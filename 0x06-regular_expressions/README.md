0x06. Regular expression
Background Context
In this project, regular expression was built using Oniguruma, a regular expression library used by Ruby by default. Because the focus of this exercise is to play with regular expressions (regex), here is the Ruby code that you should use, just replace the regexp part, meaning the code in between the //:

sylvain@ubuntu$ cat example.rb
#!/usr/bin/env ruby
puts ARGV[0].scan(/127.0.0.[0-9]/).join
sylvain@ubuntu$
sylvain@ubuntu$ ./example.rb 127.0.0.2
127.0.0.2
sylvain@ubuntu$ ./example.rb 127.0.0.1
127.0.0.1
sylvain@ubuntu$ ./example.rb 127.0.0.a
General Requirements
Allowed editors: vi, vim, emacs
All files are interpreted on Ubuntu 20.04 LTS
All files end with a new line
There is a README.md file, at the root of the folder of the project
All Bash script files are executable
All your regex must be built for the Oniguruma library
More info
Shellcheck is a tool that will help you write proper Bash scripts. It will make recommendations on your syntax and semantics and provide advice on edge cases that you might not have thought about. Shellcheck is your friend! All your Bash scripts must pass Shellcheck without any error or you will not get any points on the task. Also, for every feedback, Shellcheck will provide a code that you can use to get more information about the issue, for example for code SC2034, you can browse https://github.com/koalaman/shellcheck/wiki/SC2034. Shellcheck is available on the school’s computers. If you want to use it on your own computer, here is how to install it.

Resources
Read or watch:

Regular-Expressions.info
a Ruby regular expression editor
Learn Regular Expressions with simple, interactive exercises
Python - Regular Expressions
Ruby - Regular Expressions
RegExp Object
PHP/Javascript/Python: https://regex101.com/
Regular Expressions in you-tube
Regular Expressions (Regex) Tutorial: How to Match Any Pattern of Text
Files & Description
S/N	File	Description
1.	0-simply_match_school.rb	Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method. The regular expression must match School
2.	1-repetition_token_0.rb	Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method.

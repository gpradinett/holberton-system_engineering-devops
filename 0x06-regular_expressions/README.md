# Regular expression

## Concepts

For this project, we expect you to look at this concept:
- [Regular Expression](https://intranet.hbtn.io/concepts/29)

## Background Context

For this project, you have to build your regular expression using Oniguruma, a regular expression library that which is used by Ruby by default. Note that other regular expression libraries sometimes have different properties.

Because the focus of this exercise is to play with regular expressions (regex), here is the Ruby code that you should use, just replace the regexp part, meaning the code in between the `//`:

```
gpradinett@ubuntu$ cat example.rb
#!/usr/bin/env ruby
puts ARGV[0].scan(/127.0.0.[0-9]/).join
gpradinett@ubuntu$
gpradinett@ubuntu$ ./example.rb 127.0.0.2
127.0.0.2
gpradientt@ubuntu$ ./example.rb 127.0.0.1
127.0.0.1
gpradinett@ubuntu$ ./example.rb 127.0.0.a
```

## Resources

Read or watch:

- [Regular expressions - basics](https://www.slideshare.net/neha_jain/introducing-regular-expressions)
- [Regular expressions - advanced](https://www.regular-expressions.info/)
- [Rubular is your best friend](https://rubular.com/)
- [Use a regular expression against a problem: now you have 2 problems](https://blog.codinghorror.com/regular-expressions-now-you-have-two-problems/)
- [Learn Regular Expressions with simple, interactive exercises](https://regexone.com/)

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- All your files will be interpreted on Ubuntu 20.04 LTS
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- **All your script files must be executable**
- The first line of all your Bash scripts should be exactly `#!/usr/bin/env ruby`
- All your regex must be built for the Oniguruma library




0x06. Regular expression
========================

-   By Sylvain Kalache
-   Weight: 1
-   Ongoing second chance project - started 01-18-2022, must end by 01-22-2022 (in 3 days) - you're done with 0% of tasks.
-   QA review fully automated.

#### In a nutshell...

-   **Auto QA review:** 1.0/24 mandatory & 0.0/9 optional
-   **Altogether:**  **4.17%**
    -   Mandatory: 4.17%
    -   Optional: 0.0%
    -   Calculation:  4.17% + (4.17% * 0.0%)  == **4.17%**

Concepts
--------

*For this project, students are expected to look at this concept:*

-   [Regular Expression](https://alx-intranet.hbtn.io/concepts/29)

Background Context
------------------

For this project, you have to build your regular expression using Oniguruma, a regular expression library that which is used by Ruby by default. Note that other regular expression libraries sometimes have different properties.

Because the focus of this exercise is to play with regular expressions (regex), here is the Ruby code that you should use, just replace the regexp part, meaning the code in between the `//`:

```
sylvain@ubuntu$ cat example.rb
#!/usr/bin/env ruby
puts ARGV[0].scan(/127.0.0.[0-9]/).join
sylvain@ubuntu$
sylvain@ubuntu$ ./example.rb 127.0.0.2
127.0.0.2
sylvain@ubuntu$ ./example.rb 127.0.0.1
127.0.0.1
sylvain@ubuntu$ ./example.rb 127.0.0.a

```

Resources
---------

**Read or watch**:

-   [Regular expressions - basics](https://alx-intranet.hbtn.io/rltoken/6VeaVMaugIxcFAwA27TBdQ "Regular expressions - basics")
-   [Regular expressions - advanced](https://alx-intranet.hbtn.io/rltoken/rntjh3-3S86zt0Qy28L10w "Regular expressions - advanced")
-   [Rubular is your best friend](https://alx-intranet.hbtn.io/rltoken/RGkVuw1lZ_hoCCbLsiOAhg "Rubular is your best friend")
-   [Use a regular expression against a problem: now you have 2 problems](https://alx-intranet.hbtn.io/rltoken/Vwm8lpMUGa4x_FBtlyUQ8g "Use a regular expression against a problem: now you have 2 problems")
-   [Learn Regular Expressions with simple, interactive exercises](https://alx-intranet.hbtn.io/rltoken/XsQ6rzS1uy-E6bnswUqIKg "Learn Regular Expressions with simple, interactive exercises")

Requirements
------------

### General

-   Allowed editors: `vi`, `vim`, `emacs`
-   All your files will be interpreted on Ubuntu 20.04 LTS
-   All your files should end with a new line
-   A `README.md` file, at the root of the folder of the project, is mandatory
-   All your Bash script files must be executable
-   The first line of all your Bash scripts should be exactly `#!/usr/bin/env ruby`
-   All your regex must be built for the Oniguruma library

### Author
* **Abdallah Mahmoud** [Abdalllah](https://github.com/abdamah)

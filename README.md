## Hi there, this is readme :)

This is a repository about moodle's scan result by [PHPStan](https://phpstan.org/).

For more information and support, visit https://phpstan.org/user-guide/getting-started 

scan result based on moodle 4.2.1 (Build: 20230612)

specialy, accroding to the PHPStan [doc]((https://phpstan.org/user-guide/getting-started), PHPStan is achieved through discovering symbols to know about all the classes, interface,
traits, and functions, **NOT by including the files int the analysis.**
PHPStan will probably find some errors, but the code might be just fine.
Errors found on the first run tend to be:
- Extra arguments passed to functions. (e.g. function requires 2 arguments, the code passes 3)
- Extra arguments passed to print / sprintf functions. (e.g. format string contains 1 placeholder, the code passes 2 values to replace)
- Obvious erros in dead code
- Unknown symbols - like "class not found".

more discription, visit: https://phpstan.org/user-guide/getting-started.

!重要! 請特別注意 /admin /competency /lib /message /mod /question
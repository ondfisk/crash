# Exercise 1

Create a console application.

The application should display `Hello, World!` when run.

The application should display `Hello, <input>!` when run with `<input>` as the first command line argument.

The application should crash with an `ArgumentOutOfRangeException` if run with more than one command line argument.

Actually, don't throw exceptions, you are not willing to catch... Change the last requirement to exit with an error message instead (maybe exit code 1 as well).

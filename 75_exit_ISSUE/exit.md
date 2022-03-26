___
#### To run the program, make sure you are in the program's folder, then use the Run Command below.
___
#  If you run `exit.go` using `go run`, the exit
# will be picked up by `go` and printed.

___
Run Command:

$ go run exit.go


Results:

exit status 3

___
# By building and executing a binary you can see
# the status in the terminal.

___
Run Command:

$ go build exit.go

$ ./exit

$ echo $?


Results:

3

___
# Note that the `!` from our program never got printed.

___

###### This work and the accompanying code was originally from Mark McGranaghan at [https://github.com/mmcgrana/gobyexample](https://github.com/mmcgrana/gobyexample) and licensed under a Creative Commons Attribution 3.0 Unported License [http://creativecommons.org/licenses/by/3.0/](http://creativecommons.org/licenses/by/3.0/). It has been used to provide an example base for multiple languages to provide a basis of comparitive programming language study for syntax, language simplicity, number of lines of code and operations required to perform the same task, as well as compile and run speed combined.
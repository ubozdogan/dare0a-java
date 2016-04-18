# Assignment 1 - Java and Git basics

Try to compile the source code in this directory, e.g. with the
command ``javac -d . Person.java``.
It will output a message similar to:

        Person.java:12: error: cannot find symbol
                return MessageFormat.format("Hi {0}, my name is {1}", this.name, this.other);
                                                                                     ^
          symbol: variable other
        1 error

Change the source file Person.java between the designated comment
lines such that the program prints “OK”.

Commit your changes and prepare a patch:

        git format-patch origin/master

Send the patch file to developer-assessment@bayard-consulting.com

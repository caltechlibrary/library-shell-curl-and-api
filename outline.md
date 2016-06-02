
+ Bash
    + variables and the shell's short term memory
        + common variables you may already have
            + $USER
            + $HOME
            + $PATH
       + Set, reset, unset and accessing the variable
            + variables are remember as a sequence of characters
            + also called a "string"
            + you can see the contents of a variable with `echo`
            + you can list all the variables available wtih `env`
            + context - local, global, export
       + Some clever extras, working with variables as "strings"
            + pulling out parts of a string
            + simple find and replace
    + making choices
        + if, then, else
            + seeing if two variables are the same
            + seeing if a file exists
            + seeing if a directory exists
            + combining conditions
        + switch statements when you and to make lots of choices
    + repetition with loops
        + while
            + looking for something
            + looking until something
        + for/in
            + counting
            + iterating over a list
    + organizing what you created
        + functions
        + scripts
+ curl, how to get things from the web
    + http basics
        + get
        + post
            + encoding
        + put
        + delete
    + leveraging Bash
        + logging into a web service
        + checking the exit codes
        + authorization as a function
        + getting results
+ Processing data
    + Getting the raw data ready
        + best practice, keep your raw data, create derivatives
        + `find`-ing what you've downloaded
            + find by type
            + find by name
            + find combined with grep to get files by extension
        + Aggregate by applying loops, choices and pipelines
    + Approaches to cleaning
        + Tabulating results
        + Open Refine
+ Where to go from here (just brief mentions)
    + Create your own tools when the shell isn't enough
        + Python
        + R
        + JavaScript
        + Go
    + Unix as a text processing platform


# Bash, curl and web API

+ Bash
    + variables and the shell's short term memory
        + common variables you may already have
            + $USER
            + $HOME
            + $PATH
        + set, unset and accessing the variable
            + variables are remember as a sequence of characters
            + also called a "string"
            + you can see the contents of a variable with `echo`
            + you can list all the variables available with `env`
            + context
                + local vs. global
                + export
        + clever extras, working with variables as "strings"
            + pulling out parts of a string
            + simple find and replace
            + composing longer strings
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
            + The Sha-Bang
            + Source scripts versus executing them
+ curl, how to get things from the web
    + http basics
        + get
            + headers
            + document bodies
        + post
            + encoding
        + put
        + delete
    + The rest of REST
        + Get, post, put, and delete are verbs
        + Metadata available in headers
        + Representations
            + text, YAML, XML and JSON
                + JSON and `jq`
    + curl basics
        + GET-ting a resource
        + Inspecting and managing HTTP Headers information
        + POST-ing content
            + encoding options
            + header usage
    + leveraging Bash
        + logging into a web service
        + checking the exit codes
        + authorization as a function
        + getting results
+ Processing data (putting everything together)
    + Getting some data
    + Exploring raw data
    + Approaches to cleaning and reporting
        + best practice, keep your raw data, create derivatives
        + `find`-ing what you've downloaded
            + find by type
            + find by name
            + find combined with grep to get files by extension
        + Aggregate by applying loops, choices and pipelines
        + filters and aggregation
            + `grep`
            + `sed` (and maybe `awk`)
            + `sort`
            + `cut`, `paste` and `join`
        + Open Refine
    + Where to go from here, building your own tools (closing remarks)
        + Python
        + R
        + JavaScript
        + Go

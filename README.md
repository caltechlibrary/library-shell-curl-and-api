
# Bash, curl and working with web API

## Overview

One of the benefits of the Bash shell (and other Unix shells) is it provides a great deal
of capability right out of the box. When you combine that with other Unix tools you have
a powerful environment for text processing and manipulation. The web provides a massive
ammount on content. In this lesson will be combining the two.

## What is covered

In this tutorial we assume you have some knowledge of [Unix/Bash basics](http://programminghistorian.org/lessons/intro-to-bash)

+ How to start the Bash shell (e.g. 'Terminal' on Mac OS X)
+ How to list, view, copy, move and delete files and directories

We'll be expanding on that basic knowledge with a discussion of

+ Commannd history and command line editing
+ Working environment variable
    + remembering things for later
    + simple text manipulation
+ Building complex pipe lines
+ Making decisions
+ Repeating things
+ Simple templated text output with Bash (advanced uses of redirection and cat)

Additionally we will be using two new programs you may not be familiar with

+ sed - a automated editor (stream editor) for manipulating text
+ curl - for retrieving and interacting with content from the web
+ find - walking the content you've fetched from the web
+ cut - a tool for working with column oriented data
+ paste - a tool for putting text side by side
+ join - a tool for combining things
+ jq - a tool for working with JSON data

## Some data sources for the examples

## References

- James Baker, "Preserving Your Research Data", (April 2014),
[http://programminghistorian.org/lessons/preserving-your-research-data](http://programminghistorian.org/lessons/preserving-your-research-data)
- Ian Milligan and James Baker, "Introduction to the Bash Command Line", (September 2014)
[http://programminghistorian.org/lessons/intro-to-bash](http://programminghistorian.org/lessons/intro-to-bash)
- Billy Wideling <alien@koping.net>, "Alien's Bash Tutorial", (in circulation before 2004, this version apprears to be from circa 2006)
[http://www.subsignal.org/doc/AliensBashTutorial.html](http://www.subsignal.org/doc/AliensBashTutorial.html)
- William J Turkel, "Basic Text Analysis with Command Line Tools in Linux", (June 2013),
[https://williamjturkel.net/2013/06/15/basic-text-analysis-with-command-line-tools-in-linux/](https://williamjturkel.net/2013/06/15/basic-text-analysis-with-command-line-tools-in-linux/)
- William J Turkel, "Pattern Matching and Permuted Term Indexing with Command Line Tools in Linux", (June 2013)
[https://williamjturkel.net/2013/06/20/pattern-matching-and-permuted-term-indexing-with-command-line-tools-in-linux/](https://williamjturkel.net/2013/06/20/pattern-matching-and-permuted-term-indexing-with-command-line-tools-in-linux/)
- Brad Yoes, "Introduction to text manipulation on Unix-based systems" (March 2012)
[https://www.ibm.com/developerworks/aix/library/au-unixtext/](https://www.ibm.com/developerworks/aix/library/au-unixtext/)
- Geert Jansen, "Thoughts on RESTful API Design" (November 2012)
[https://restful-api-design.readthedocs.io/en/latest/](https://restful-api-design.readthedocs.io/en/latest/)

Welcome
==============================================================================

This is the Clemson ACM Repo.  We are the local chapter of the Association for
Computing Machinery at Clemson University in Clemson, South Carolina.  We do
cool computing stuff for cool computing people!

What is this repository for?
----------------------------

This repository contains resources developed to aid with doing cool stuff in
Computer Science.  The main projects are as follows:

### Clemson Hackpack and Hackpack++ ###
*   the Hackpack is a concise and extensive cheatsheet/guide designed to be
    used during ACM style programming comptetions.  If you already know your
    datastructure and algorithms go here.
*   The Hackpack++ is a extensive guide that includes all of the great info
    from the hackpack, but also includes a bit more detail so that you could
    use it as a learning tool for the different techniques.

###   Presentations ###
In addition to the Hackpack, we put on a series of educational seminars through
out the year.  They cover neat topics and tools in CS.  We currently have
presentations for the following:

*   Linux is Scary - a basic introduction to linux for new folks
*   Git Thee to a Version Control System - A introduction to version control and
    git
*   Vim - A advanced seminar on how to get more out of vim


How do I get set up?
--------------------

Depending on what you are doing you will need different tools:

### Clemson Hackpack and Hackpack++ ###

*   `git` - for tracking changes
*   `g++` - all code samples are in C++98 with C++11 listed as noted
*   `pdflatex` - The hackpack body is written in LaTeX
*   `make` - Make is to automate compilation and testing of the documents

### Presentations ###

*   `git` - for tracking changes
*   `pandoc` - convert markdown files to revealjs
*   `Firefox` or `Chrome` - any modern web browser really. See revealjs for more
    documentation

Contribution Guidelines
-----------------------

### Clemson Hackpack and Hackpack++ ### 

For all projects and improvements:

1.  Clone the repo
2.  Checkout a new branch with the topic as the name
3.  When the branch is complete, create a pull request in Bitbucket
4.  When the pull request is reviewed, and the code will be merged into
    master when approved.

#### Writing Documentation ####
For each item in the Hackpack, please include the following:

1.  Algorithm Name
2.  Brief Description of the topic
3.  A list of possible uses and applications
4.  A possible contest problem
5.  Sample code that answers the contest problem
6.  References using BibTeX where applicable
7.  Should be "compiled" properly by pdflatex and the make

Code Must meet the following standards:

1.  Code should be indented with tabs and not exceed 80 characters per line.
2.  Code must compile under contest conditions: `g++ -g -O2 -std=gnu++0x -static $*`
3.  Code must be delivered with the passing unit tests.
4.  Code must be commented with detailed explanations and asymptotic notation
    where appliciable
5.  Code must be concise but not as the expense of readability
6.  Source code must solve a problem:  It should solve a specific problem and
    include all relevent io and supporting code.  The algorithm should not be in
    a vaccum.

* Writing tests
* Code review
* Other guidelines

### Presentations ### 

If you have a good presentations let us know.  We will use revealjs and markdown
for presentations.  If you have an improvement, follow the procedure above.

Who do I talk to?
-----------------
Contact `acm@cs.clemson.edu` with any questions

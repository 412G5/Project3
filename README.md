# Project3

For this project, you will be working as a team, but will be graded individually. So each team member will be responsible to collaborate in a single GitHub repo, and I will expect to see a log of individual contributions (commits from each team member).

The goal of this project is to familiarize yourself with Python syntax, and some basic tasks that are common in systems programming and administration. The program will be invoked from the command line on a fresh Linux machine, so if you introduce any library dependencies beyond the Python Standard Library (not recommended), you must provide very clear instructions to recreate your environment. I would suggest using VagrantLinks to an external site. or a GCPLinks to an external site. VM to develop in Linux if you are on a Windows machine. Another option is to install the Windows Subsystem for LinuxLinks to an external site. and setup a Python environmentLinks to an external site.. It is your responsibility to ensure the program runs as expected in the operational environment described.

Here’s the scenario: you work for a medium sized company that sells widgets directly to consumers through brick-and-mortar retail stores. The marketing department wants to try a new promotional campaign to ramp up direct internet sales, but needs better data about current traffic to your website. Your boss has asked you to take the HTTP server logs from the webserver and provide some analytics to Marketing.

STEPS

Your program will be parsing and analyzing log files from an Apache web server. The first thing your program must do is retrieve the log file across the network. It is available here: https://s3.amazonaws.com/tcmg476/http_access_logLinks to an external site.

Once you download the file, you need to save a local copy to disk (a cached copy) so the next time you run your script, you don't have to wait for the download.

Marketing wants to know two things: 
How many total requests have been made in the 6 months?
How many total requests were made in the time period represented by the log?

You will need to output this data to the screen. The format you choose to do this is up to you, but your decisions and your implementation should be logical and consistent.

Your program should be created and developed using GitHub (I will be examining the commit logs to see your work). When the project is due, submit your repository URL so I can clone the repo and test your program. Also, upload a screenshot of your program's output so I can see what it looks like when it is run on your machine.

 

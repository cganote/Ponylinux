# Welcome to Ponylinux! #
<img align="right" width="220" src="/Images/ponyicon.png" alt="Logo for Ponylinux, which is a blue pony with a streak through the mane">

Ponylinux is a basic tutorial on using the **command line** in Unix operating systems, such as Ubuntu Linux.


Walk through a series of tutorial sections that will teach you different **commands**, what they do, and how to use them. The tutorials are interactive, with mini sessions to ensure you get more practice and engagement. Your task will be to take the knowledge you gained during the tutorials to find the Princess in the final dungeon! So go on brave one, and be a hero while learning about Linux!

---
   
## Curriculum ##

The Ponylinux curriculum is broken up into multiple sessions to make it less overwhelming. The following list shows the concepts we will cover in each section.

### SECTION ONE ###

Section one introduces the structure of things that are typed into the **command line**, and the concept that programs can be run using text. We delve into basic movement between folders and showing what is inside a folder. Understanding and setting permission to view, open, and change files and folders is covered, as well as how to read the contents of a file.

<img align="right" src="/Images/pony.png" alt="Screen capture of game starting up." height="200" />

We go over the following **commands**:

```
cd
ls
pwd
find
chmod
less
```

Section One wraps up with a challenge. Use the commands you learned during the tutorials to defeat a dungeon set up using files and folders right in the Linux environment. Your goal is to find the Princess in the dungeon with the knowledge you earned in the tutorial.

### SECTION TWO ###

The goals of section two will be to start getting into more bash commands that will introduce you to doing new things in the terminal. Manipulating the contents of files, full-text searches using ```grep```, creating directories, moving files, copying files, and deleting stuff! More practice in a real environment gives the student a chance to flex their skills.

### SECTION THREE - Coming Soon ###

Section Three will take skills gained in the previous two sections and build up skills for scaling up to chaining commands, manipulating the environment, and handling running processes. 

### SECTION FOUR - Coming Soon ###

Section four will start to lead the student into more complex use cases for Linux, including the world of high performance computing for scaling up bioinformatic analyses into truly big data applications!

## Getting Started ##
<a href="https://jetstream-cloud.org/"><img align="right" src="/Images/jetstream-logo-web.png" alt="Jetstream Logo" width="200" /></a>
The easiest way to get started with Ponylinux is to use Jetstream, located at https://jetstream-cloud.org/. You may find this NCGAS blog on Jetstream helpful - https://blogs.iu.edu/ncgas/2017/10/18/getting-started-on-jetstream/

You will need to do the following:
1. Go to the Jetstream link above. Click on "Request Trial Account".
   1. <img src="/Images/screencapjetstream.png" alt="Screen capture of signing up for Jetstream." height="100" />
1. Get an XSEDE account following instructions in the link in step 1. Enroll in Jetstream Trial Access.
1. Login to Jetstream: https://use.jetstream-cloud.org/login.
1. Go ahead and Launch a New Instance!
1. Search for Ponylinux in the image search. You can launch this with the default settings, usually :smile:
1. When your instance is available, click on the Web Desktop to the right to bring up a desktop on your new cloud computer.
1. You should see a pony icon on the desktop. Double click on it to get started!
## FAQ ##
* **Q**: Is Ponylinux different than https://github.com/NCGAS/PonyLinux?
* **A**: This repo is a continuation of that project. Since I'm focusing on the Ponylinux project for my dissertation work, I made a new place to hold the code that will have a slightly different purpose than the original project.

* **Q**: Is Ponylinux a Linux distribution (distro)?
* **A**: Nope. It's just some shell scripts. But if you crave a Pony-themed operating system, maybe check out PonyOS at https://ponyos.org/.

* **Q**: What do ponies and Linux have to do with bioinformatics?
* **A**: Much of the freely available software for bioinformatics analysis is only available on Linux platforms, and specifically on the Linux command line. This project is meant as a primer to allow a biologist enough familiarity with Linux to get their work done. It is useful to anyone who is staring down a whole bucket load of data and thinking of how to analyze it when Excel crashes =)

* **Q**: Why are there ponies? Why not something else?
* **A**: I found ponysay while surfing the web, and was so excited about putting images into bash that I thought it would make it easier to learn bash. If there are other images out on the web, fork my project and make it happen.

* **Q**: You use terminal, bash, shell, command line, Unix, and Linux all interchangeably. What gives?
* **A**: It's true, these concepts are all related. How bout this: Many software projects I deal with only run on Linux operating systems, which are a subset of UNIX standards from way back when. I primarily interact with this software through a command line interface, which is just text, as opposed to a graphical interface, which has pictures. Bash is a shell program, which means it understands what commands you type into the terminal. The terminal emulates a direct connection to the operating system, similar to a CMD or DOS window. There are other shell programs that speak slightly different languages from bash.



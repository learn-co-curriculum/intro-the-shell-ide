# Introduction to the Terminal

## Problem Statement

How are we to interact with our computer _as developers_? While you might have
been using computers for years, you've likely been engaging with them as a
_user_ not a _developer_.

What's the difference? Well consider a mechanic driving to work. In that
moment, waiting in traffic, they are a _user_ of the car. But then they take a
right turn and *cough*, *splutter* their car chokes to a stop. At once their
mind changes to being a _mechanic_ or a _developer_. They think about
petroleum, spark-plugs and ignitions. They can _debug_ their car using
techniques they've learned. They can imagine what might be wrong. To get more
data or to verify their guess, they _open up the hood_. Learning to be a
developer (_computer mechanic_?) is similar. You must start "looking under the
hood" of your computer. To access the "hood's" contents, you must use the
terminal.

Developers "talk" to their computers through the terminal. The terminal
is just another way to collaborate with the computer. It might feel
"old-school" or clunky at first compared with Windows or MacOSX. As you learn
more, though, it might surprise you!

Terminal skills are critical in being a developer or HTML author.  Comfort in the
terminal is an assumption for many technical jobs.

## Learning Objectives

1. Define what a terminal program is
2. Recognize a shell interface
3. Recognize operating systems providing a terminal

## Define What a Terminal Program Is

First of all, we have to be honest here: the difference between "shell" and
"terminal" is quite easy to get confused by. To make things worse, developers
are often really imprecise and say one to mean the other and vice versa. This
makes it harder for those learning about these tools. Be patient with yourself
as you learn this material.

A terminal program is a program that listens for keyboard input and hands it
off to a magical genie who lives inside your computer. When the magical genie
tells the terminal to draw letters on its screen, it does so.

This might be confusing, but let's compare it to television. A television is a
device that listens to your remote control and then tells a magical genie
(different genie, of course) which feed of data to find. When the genie finds
the data (maybe on a coaxial cable, or satellite dish) it commands the
television to display the picture. On most modern televisions, in fact, the
magical genie tells the television to draw a picture 120 times per second!

The essential fact is that a terminal is a means for talking to the operating
system's genie.  In lessons we'll refer to the "terminal" as the thing you type
in, as a program you can launch, as a space you can click in. The genie will be
a magical being that lives inside of computers that when you finish typing
input in the terminal will hand the request to the genie.

## Define What a Shell Program Is

The shell is the program on your computer that takes in commands you type and
takes action based on those commands. You can think of yourself as having a
conversation with the computer.

When you see a shell it will be at a "command prompt." This means, from the
computer's perspective "I'm listening..." Prompts may look different from
computer to computer. Customized prompts express developer uniqueness. We've
seen weather reports, beautiful colors, computer temperatures in prompts. At
heart, though, they they all carry your command to the operating system and run
it.

You can ask the computer to do many types of tasks. From the command prompt you
can move or rename files just like you would do from a window environment.  You
can _also_ get diagnostic information ("How is my computer?") or help your
computer recover without requiring a reboot ("Hm, computer, time to kill that
hung Chrome tab with the Twitch stream...").  You can ask the computer to run
programs like `ruby my_awesome_program.rb` or even to launch an application!

## Recognize a Shell Interface

A shell interface looks like the following pictures below.

Typically you'll be given some text output and a command prompt. The prompt
will receive commands. You tell the shell you're done typing and that it should
consider your request by hitting `return` or `enter`. After receiving your
command the shell will respond with the information you requested, or will
signal that it did your bidding (say renaming a file), or it will print an
error message. Then you'll be given another prompt and can do it again, and
again, and again.... This cycle can be called a "prompt-evaluation-response
cycle."

Here's the Learn In-Browser IDE's shell. Since the shell environment is so
important for us, whenever you open the IDE the command prompt is also shown.
You will interacting with the shell when you run commands like `learn` and
`learn submit`.

<img alt="Learn In-Browser IDE Shell" src="https://curriculum-content.s3.amazonaws.com/web-development/intro-the-shell/learn_shell.png" width=595>

Here's the Terminal application in MacOSX running a shell. You can launch it by
navigating with the Finder to `Applications` &rarr; `Utilities` &rarr;
`Terminal`.

<img alt="MacOSX Shell" src="https://curriculum-content.s3.amazonaws.com/web-development/intro-the-shell/osx_shell.png" width=595>

Here we see the prompt-evaluation-response cycle, here we
are providing the command `echo` which, well, repeats the command back to the
screen (the "response").

<img alt="MacOSX Shell response" src="https://curriculum-content.s3.amazonaws.com/web-development/intro-the-shell/prompt_response.png" width=595>

You may sometimes hear the shell referred to as your "command line" or
"terminal" or "console". There are some subtle differences between each of
those terms, but by and large you can think of these as referring to ways of
interacting with the terminal.

## Recognize Operating Systems Providing a Terminal

All operating systems (MacOS, Windows, and Linux / Unix) provide
a terminal! While developers often disagree about which operating system is the
best, time has borne out that they nearly all agree that a terminal-based
interface is a power-tool they can't live without.

## Conclusion

Ultimately a terminal is a way for you to interact with your computer. It's a
different style than the point-and-click graphical user interfaces that you
might know, but it is incredibly powerful and is the workbench of many
developers. Terminal interfaces are provided by all major operating systems and
are marked by their prompt, evaluation, response cycle.


_The video below describes what the shell installed with Mac OS X looks like_

<iframe width="1280" height="720" src="https://www.youtube.com/embed/uxANgIcjmQg?rel=0&amp;showinfo=0&html5=1" frameborder="0" allowfullscreen></iframe>

[Download Video](http://flatiron-videos.s3.amazonaws.com/ironboard/welcome%20to%20the%20shell.mp4)


<p data-visibility='hidden'>View <a href='https://learn.co/lessons/intro-the-shell-ide'>Intro to the Shell</a> on Learn.co and start learning to code for free.</p>


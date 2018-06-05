# Introduction to the Terminal

## Problem Statement

How are we to interact with our computer _as developers_? While you might have
been using computers for years, you've likely been engaging with them as a
_user_ not a _developer_.

What's the difference? Well consider a mechanic driving to work. In that
moment, waiting in traffic, they are a _user_ of the car. But then they take a
right turn and *cough*, *splutter* &mdash; their car chokes to a stop. At once
their mind changes to being a _mechanic_ or a _developer_. They think about
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

### Advice

First of all, we have to be honest here: the difference between "shell" and
"terminal" is quite easy to get confused by. To make things worse, developers
are often imprecise and say one to mean the other and vice versa.

In order to try to help build your instinct for understanding the concepts,
we'll often "over-explain" or make a sentence seem ridiculously long. We're
doing this intentionally in order to try to help you build an intuition about
the actors in this story.

Also, to help keep terminology from getting in the way, we involve genies.
We admit, this is a whimsical approach but assure you no genies were harmed in
the production of this lesson.

Be patient with yourself as you learn this material.

### Terminal Programs

A terminal program is a program that listens for keyboard input and hands it
off to a magical genie who lives inside your computer. Also, when the magical
genie tells the terminal to draw letters on its screen, it does so. For
example, when you are in a terminal program and type the letter `l` the
terminal program senses the `l` and tells the genie. The genie then tells the
terminal to draw an `l` on its screen. The terminal then looks up your font
preferences and color preferences and draws the appropriate `l`.

This might be confusing, but let's compare it to television. A television is a
device that listens to your remote control and then tells a magical genie
(different genie, of course) which feed of data to find. When the genie finds
the data (maybe on a coaxial cable, or satellite dish) it commands the
television to display the picture. On most modern televisions, in fact, the
magical genie tells the television to draw a picture 120 times per second!

The essential fact is that a terminal is a means for talking to the operating
system's genie.  In lessons we'll refer to the "terminal" as the thing you type
in, as a program you can launch, as a space you can click in.

## Recognize a Shell Interface

### Shell Interfaces Described

OK, sorry, genies don't exist. Well, at the very least, operating system genies
don't exist.

Above, when we said that the terminal hands requests and receives commands from
a genie, a thing that _thinks_ and thing that _can find out things_, we were
actually talking about "the shell." The _shell_ knows how to ask the operating
system how big the hard drive is. The _shell_ knows how to ask the operating
system if the web site `flatironschool.com` can be reached. The _shell_ **does
not** know how to display "Hello World" in 16 point Monaco font on a black
background, that's the _terminal_.

A shell is a program hosted _inside of a terminal_ that interacts with the
operating system on your behalf. It's because of the fact that you can't
interact with a _shell_ without a _terminal_ that some imprecisely call the
_terminal_ "the shell."

The shell, since it can think and do things, takes input that you type in. It
looks at that input and asks the operating system to interpret that request.
When the operating system comes back with results, the shell then hands back to
the terminal (for displaying) the result of the command.

When you see a terminal, the shell hosted inside of it it will present to you a
"command prompt." This means, from the computer's perspective "I'm
listening..." Prompts may look different from computer to computer. Customized
prompts express developer uniqueness. We've seen weather reports, beautiful
colors, computer temperatures in prompts. At heart, though, they they all have
the same function: to carry your command to the operating system and run it.

Here's a terminal application (iTerm2) running a shell (this one happens to be
called zsh, there are many, it's no big deal).

<img alt="MacOSX Shell" src="https://curriculum-content.s3.amazonaws.com/web-development/intro-the-shell/osx_shell.png" width=595>

You can ask the computer to do many types of tasks via the shell (via the
terminal). From the shell's command prompt (that you see in the terminal) you
can move or rename files just like you would from a window environment.  You
can _also_ get diagnostic information ("How is my computer?") or help your
computer recover without requiring a reboot ("Hm, computer, time to kill that
hung Chrome tab with the Twitch stream...").  You can ask the computer to run
your own programs like `ruby my_awesome_program.rb` or even to launch an
application!

When interacting with a shell via a terminal application, you'll be engaged in
a cycle called the "prompt-evaluation-response cycle." By this, we mean that
you will be given a command prompt, you will provide a command that will be
evaluated by the shell with the help of the operating system and results will
be printed for you. To trigger evaluation of your command you strike the
`return` or `enter` keys.

### See Shells in the Wild

Since the terminal environment is so important for us, whenever you open the
IDE, the LearnIDE terminal is automatically shown.  You will interact with the
shell through this terminal when you run commands like `learn` and `learn
submit`.

<img alt="Learn In-Browser IDE Shell" src="https://curriculum-content.s3.amazonaws.com/web-development/intro-the-shell/learn_shell.png" width=595>

Here's the Terminal application in MacOSX running a terminal program. You can
launch it by navigating with the Finder to `Applications` &rarr; `Utilities`
&rarr; `Terminal`. There are other third-party terminal programs too. They all
provide a way of using a shell. Liking one over the other is a matter of
preference.

<img alt="MacOSX Shell" src="https://curriculum-content.s3.amazonaws.com/web-development/intro-the-shell/osx_shell.png" width=595>

Here we see the prompt-evaluation-response cycle, here we are providing the
command `echo` which, well, repeats the command back to the terminal (the
"response").

<img alt="MacOSX Shell response" src="https://curriculum-content.s3.amazonaws.com/web-development/intro-the-shell/prompt_response.png" width=595>

### Erroneous Use

You may sometimes hear the shell referred to as your "command line" or
"terminal" or "console". There are some subtle differences between each of
those terms, but by and large you can think of these as referring to ways of
interacting with the shell (as presented by the terminal).  While some uses are
_technically_ erroneous, it's a common utterance and you should not ruin a
party by correcting everyone's imprecise naming.

## Recognize Operating Systems Providing a Terminal

All operating systems (MacOS, Windows, and Linux / Unix) provide a terminal
interface to a shell! Time has borne out that developers consider a shell-based
interface a power-tool they can't live without.

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


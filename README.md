# Unix Command Line Toolbox
The steps below will take you from novice to getting a basic knowledge of the Unix OS and it's command line.

Even after 20+ years of using Unix I still find this small set of commands, the core of what I need. Yes more is possible and there is, much much more. But for now, and for most of the time, this will work. More is always there, people will always tell you you need more! More dohnuts, more stationary, more stuff! But that can wait for tomorrow. Or never. ;-)

In this guide you will find a series of areas to learn and with each, a small set of commands and some exercises to help learn those commands. You do not need to memorise all this and the associated commands. I have kept the guide small enough so that you should find, after a few weeks and months, that it all starts to become a bit of muscle memory. Or worst case, just come back to this guide.

Your goto commands!

A mini toolbox.

Start small and slowly expand. One area each day. Do not rush.


## Who am I and where are we?
```bash
whoami, pwd, hostname
```

So you arrive at your new machine and login and open a terminal. And you are presented with your prompt, something like...
```bash
>
```
the first thing you will want to know is... ___Who am I???___ Well, fortunately unix has just the command for you...
``` bash
> whoami
```
it is very simple and returns a response of who is currently logged into the machine.

Next question is... __Where am I???__ Again unix has just the command for you...
``` bash
> pwd
```
otherwise known as _print working directory_. It returns the simple resonse of your current directory. It is always good to know where you are. Especially if your memory is as short as mine.

And finally... __What machine am I on?__ Again unix has a quick answer...
```bash
> hostname
```
which responds with the name of the machine.

## What can I see around me?

Continuing from the previus section, it is likely that you are in your _home_ directory. And the __pwd__ command will have confirmed this, maybe giving a result of something like...

```
/home/bobsmith
```

The next command we want is...

```bash
ls
```

to list the directory contents. It will return a list of the directories and files visible from the current directory. e.g.

```
> ls
src debug.sh README.md docs
```

There are some common flags that you might want to pass to the __ls__ command

* -a show ALL files and directories
* -l long listing (show extra info)
* -t order by modification time 

And there are more flags but we will not list them all here. As with most commands to get more info on a command there are two ways. You can either pass in a _help_ flag...

```
> ls --help
```

which will return a small-ish guide on to use the command, or use the __man__ command to show the manual pages for the command. e.g.

```
> man ls
```

the _man_ pages are usually quite comprehensive and give some examples of using the command.


## Am I allowed to travel?
```bash
cd, ~
```

## Can I create stuff?
```bash
mkdir, touch, vi
```

## And what if I dont like that stuff?
```bash
rm
```

## Ive lost the stuff, how can I find it?
```bash
find, grep
```

## What else is happening here?
```bash
ps, systemctl
```

## Going back in history?
```bash
up-arrow, ctrl-r, history, !
```

## Getting to other worlds and taking my luggage?
```bash
ssh, scp
```

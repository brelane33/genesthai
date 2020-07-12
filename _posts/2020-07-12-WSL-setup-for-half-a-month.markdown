---
layout: single
title:  "Using Linux on Windows for almost a month"
date:   2020-06-20 20:23:53 -0500
---


# Windows Terminal for half a month

## Feels ok man

Since I've been using this for half a month I figured I'd give my feeback on
how it's been going. It's going well! End of blog post. Of course, there's more
to it than that. I've been working a lot on my .vimrc setup, migrated my Jekyll
theme, and I've also been doing a daily python program routine.

So far for the blog, the setup has been pretty ideal. I can type out all of my
entries in Vim and I've got that setup to a fairly minimal installation. Only
the couple of plugins I had listed in the previous article. I was looking
around for a plugin that might be useful for working with Jekyll or markdown in
particular but I didn't find anything very useful. I'd rather just get used to
using Vim commands and training myself to use shortcuts than adding bloat to
my vim setup.

## Updates to .vimrc and .inputrc

I set my .vimrc and .inputrc so that indentation actually works in my favor
with Vim, and through my .inputrc I can use page up and page down to scroll
through similar bash history. Thank God! I had been struggling with figuring
that out for a while. There isn't really a common phrase that is used to
describe that behavior. For reference the code I added to my .inputrc is

```
"\e[5~": history-search-backward
"\e[6~": history-search-forward
```

Hopefully I can save someone the trouble of having to go look for that
somewhere for way too long. I wish it came standard on the Ubuntu
implementation on Windows Linux Subsystem, but alas.

I'm typing this blogpost with the same .vimrc setup I've been using for the
python exercises and I have to say I don't mind applying the PEP8 coding style
here. The 79 characters per line (correct me if that's changed...) works pretty
well for keeping my window size fairly minimal. This allows me to reload my
browser whenever I save and update the page very easily. 10/10 would recommend.

Here's the relevant sections of my .vimrc relating to indentation that I find
useful:

```
set autoindent
set shiftwidth=4
set tabstop=8
set expandtab
set softtabstop=4
set textwidth=79
```

## Daily python and "Atomic Habits"

For the daily python programming exercises I'm running through Python Workout
by Manning publications right now and I'm digging it. I've only gotten through
the first four exercises, and as expected they're fairly straightfoward. Reuven
M. Lerner does a decent job of setting the problems up and I've been enjoying
going through and making minor improvements on the solutions to really drive
home the point of the programs.

One thing I *DEFINITELY* would like to recommend is James Clear's book Atomic
Habits. This book has been really powerful in the first two chapters alone. It
helped give me the motivation to type up this post and has reinforced I'm doing
the right thing with my daily python practice. I wish more books would follow
the Python Workout format so that you can accomplish small things every day
with them. I have a feeling all of this will pay off relatively quickly.

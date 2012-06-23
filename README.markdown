# S5 Blank - Slide Show (S9) Template Pack

## What's Slide Show (S9)?

A Ruby gem that lets you create slide shows and author slides in plain text
using a wiki-style markup language that's easy-to-write and easy-to-read.
More [Slide Show (S9) Project Site &raquo;](http://slideshow.rubyforge.org)


## Intro

The [S5 Blank](http://meyerweb.com/eric/tools/s5/) package bundled up into 
a Slide Show (S9) template pack that lets you author your slides
in a wiki-style markup language (that is, Markdown or Textile) plus
lets you use text filters and helpers for adding comments, macros,
includes, syntax highlighters and much more.


Note, the S5 blank package is configured to use
the following headers in `slides.html.erb`:

    author: Your Name Here
    company: Your Company Here
    title: Your Slide Show Title Here
    subtitle: Your Subtitle Here
    footer: Your Footer Here
    subfooter: Your Subfooter Here

See the original [S5: An Introduction](http://meyerweb.com/eric/tools/s5/s5-intro.html) slides in action or
see the [Slide Show (S9) Tutorial](http://slideshow.rubyforge.org/s5/tutorial.html)
slides generated using this template pack.
 
 
## Try It Yourself - How To Use the S5 Blank Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ slideshow -f s5blank

Or as an alternative clone the template pack using `git`. Issue the commands:

    $ cd ~/.slideshow/templates
    $ git clone git://github.com/geraldb/slideshow-s5-blank.git

To check if the new template got installed, use the `-l/--list` switch/command:

    $ slideshow -l

Listing something like:

    Installed templates include:
       s5blank (~/.slideshow/templates/s5blank/s5blank.txt)

Tip: To get started use the welcome quick starter sample. Issue the command:

    $ slideshow -q

Now you will have a copy of the `welcome.text` Quick Starter sample
in Markdown in your working folder.

```
%%%%%%%%%%%%%%%%%%
%% Some Headers

Title: Slide Show (S9) 10-Minute Tutorial


%%%%%%%%%%%%%%
%% Let's go.

Slide Show (S9) 10-Minute Tutorial
==================================

Agenda

* What's Slide Show (S9)? 
* Wiki-Style Markup Language - Markdown, Textile
* How it works - Just press F11! 
* What's S5? What's S6?
* Gradient Themes Using "Loss-Free" Vector Graphics in S9 
* Turn Your Online Wiki Pages into Slide Shows - Sputnik Case Study


What's Slide Show (S9)?
=======================

### What? 

A Free Web Alternative to PowerPoint and KeyNote in Ruby


### Getting Started in 1-2-3 Easy Steps

* Step 1: Author your slides in plain text using a wiki-style markup language
* Step 2: Generate your slide show using the `slideshow` gem
* Step 3: Open up your slide show in your browser and hit the space bar to flip through your slides
* That's it. Showtime!
```

Showtime! Let's use the `-t/--template` switch to generate the
sample slide show. Example:

    $ slideshow -t s5blank welcome.text

Open up the generated `welcome.html` page in your browser. Voila. That's it.

## Questions? Comments?

Questions? Comments?
Send them along to the [Free Web Slide Show Alternatives (S5, S6, S9, Slidy And Friends) Forum/Mailing List](http://groups.google.com/group/webslideshow).
Thanks!
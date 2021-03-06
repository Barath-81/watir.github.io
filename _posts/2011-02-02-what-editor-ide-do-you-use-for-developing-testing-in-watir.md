---
layout: post
title: What Editor / IDE do you use for Developing / Testing in Watir?
date: 2011-02-02 22:06
author: bpettichord
comments: true
categories: [Blogs]
---
<strong>Originally posted at <a href="http://altentee.com/blogs/2011/what-editor-ide-do-you-use-for-developing-testing-in-watir/">altentee.com</a> by <a href="http://twitter.com/#!/90kts">Tim Koopmans</a>.</strong>

<hr />

A quick poll on <a href="http://rubyforge.org/pipermail/wtr-development/2011-January/002865.html">wtr-development</a> indicated a number of different applications to achieve such a task, each having their own pros and cons. It really depends on what features appeal to you. My personal experience has led me to try a lot of different editors and development environments in the past including:
<h2>Editors</h2>
SciTE
NotePad++
TextMate
VIM
Emacs (actually I haven't used this one)
<h2>IDEs</h2>
RubyMine
NetBeans

Pros and Cons for each (subject to personal opinion) are as follows.
<!--more--><strong><a href="http://www.scintilla.org/SciTE.html">SciTE</a></strong> binaries (with Ruby specific syntax support) come packaged with older versions of the Ruby installer, particularly 1.8.6 variants favoured by Watir. It's a simple text editor which supports Windows and Linux. I used it for a long time on Windows, even going so far as <a href="http://altentee.com/blogs/2009/my-favourite-scite-settings/">customising</a> settings but lost some of its shine when I started to use platforms other than Windows … This editor is also free.

<strong><a href="http://macromates.com/">TextMate</a></strong> was "<em>Created by a closet UNIX geek who was lured to the Mac platform by its ease of use and elegance, TextMate has been referred to as the culmination of Emacs and OS X and has resulted in countless requests for both a Windows and Linux port, but TextMate remains exclusive for the Mac, and that is how we like it</em>". This editor costs about €39.

This is the main reason (single platform) I stopped using this editor despite some of its awesome features and great support for Ruby. I find that I work on many different platforms so didn't want to be bound to a single platform as is the case for TextMate. If this isn't a consideration then you might want to check out the large number of bundles (plugins) available for TextMate that can assist you with Ruby and Watir friendly features such as:
<ul>
	<li>https://github.com/bmabey/cucumber-tmbundle</li>
	<li>https://github.com/dchelimsky/rspec-tmbundle</li>
	<li>https://github.com/mocoso/code-beautifier.tmbundle</li>
</ul>
<strong><a href="http://notepad-plus-plus.org/">Notepad++</a></strong> is a nice free editor for Windows based on the Scintilla libraries also used by SciTE. I used this for a brief period and it has very similar features to say SciTE but I wouldn't say this has specialised support for Ruby, but does support things you'd ordinarily expect such as syntax colouring, folding, auto completion and the like.

<strong><a href="http://www.vim.org/">VIM or the gVim</a></strong> variants is my current editor of choice. I fell into this space with the desire to have a consistent editor regardless of the platform I operate from. VIM is very extensible and has a large range of scripts/plugins available to suit different needs. Plugins I particularly use for Ruby / Watir include:
<ul>
	<li>FuzzyFinder (for files/directories) http://www.vim.org/scripts/script.php?script_id=1984</li>
	<li>NerdTree (for a tree based explorer) http://www.vim.org/scripts/script.php?script_id=1658</li>
	<li>AutoClose http://www.vim.org/scripts/script.php?script_id=1849</li>
	<li>Comments http://www.vim.org/scripts/script.php?script_id=1528</li>
	<li>Endwise http://www.vim.org/scripts/script.php?script_id=2386</li>
	<li>Surround http://www.vim.org/scripts/script.php?script_id=1697</li>
</ul>
Another developer on wtr-development recommended the following additional plugins:
<ul>
	<li>command-t instead of fuzzyfinder https://wincent.com/products/command-t</li>
	<li>vim-matchit https://github.com/tsaleh/vim-matchit</li>
	<li>tabbar http://www.vim.org/scripts/script.php?script_id=1338</li>
	<li>repeat-vim http://www.vim.org/scripts/script.php?script_id=1338</li>
</ul>
The great thing about VIM is that the environment in which you work stays the same, no matter if you're working on OSX, Linux or Windows. Some say it has a steep learning curve. I would say the major obstacle is first getting used to a command mode versus an editing mode. But once you get used to some of the basic shortcuts, plus a little finger/muscle memory, you will find the editor to be extremely powerful. As my VIM experience continues I tend to use less of the mouse, and more of the keyboard.

Another powerful editor in this space which I have not used, but comes highly recommended is <strong><a href="http://www.gnu.org/software/emacs/">EMACS</a></strong>. I imagine this editor has many of the same benefits / features as a tool like VIM. I can't offer any tips though, never having used it.

Finally, if text editors or their variants don't cut it, you may opt to use a fully Integrated Development Environment. Despite some users on wtr-development using <strong><a href="http://netbeans.org/">NetBeans</a></strong>, due to <a href="http://www.infoq.com/news/2011/01/ruby-dropped-in-netbeans-7">discontinued support of Ruby in NetBeans 7</a> it is probably not worth recommending this as a viable option.

A more popular IDE for Ruby is <strong><a href="http://www.jetbrains.com/ruby/buy/index.jsp">RubyMine</a></strong> which currently offers a 50% discount for $29 USD. This apparently has excellent support for Ruby development and testing including things like Cucumber and the like. I don't have any experience with it per se and generally don't find I need the support of a full blown IDE for my Ruby / Watir related tasks (a pet hate being how long it takes to load up an IDE in the first place), so will have to trust the community feel on this. A number of wtr-development users strongly recommend it though.

YMMV.

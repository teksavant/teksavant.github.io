---
layout: post
title:  "Understanding Git in most non-technical way"
date:   2016-07-04 11:25:50
image:  Git-Logo.jpg
---

<p class="intro"><span class="dropcap"><a href="https://git-scm.com">G</a></span><a href="https://git-scm.com">it</a> is a distributed revision control and source code management system with an emphasis on speed. Git was initially designed and developed by Linus Torvalds for Linux kernel development. Sounds daunting? Lets understand in a better way.
</p>

<p>
	Suppose you're participating in a Poster Design Competition. The theme you need to work on is, "Natural Disasters" and the only software you are allowed to use is <a href="https://products.office.com/en-in/word">MS Word</a>.
	<br>

	<ul>
		<li>First off, you create a folder called Competition to store the poster you design.
		</li>
		<li>Now, you create a sub-folder called <b>Design-0</b>. Inside this folder, you open a new <a href="https://products.office.com/en-in/word">MS Word</a> file and start creating a poster and save this file as <b>Poster-0</b>. 
		</li>
		<li>When you put some more thought into your idea, you decide to change the background color and the font. But, you aren't sure of this change so you don't overwrite on the existing poster. You decide to save this version as <b>Poster-1</b> and place in a folder called <b>Design-1</b>, which is also a sub-folder of Competition.
		</li>
		<li>As you continue to make changes, you save every change as a new file to ensure that you have a copy of every modification made and store the files in sub-folders of Competition. Eg., <b>Poster-2</b> and <b>Poster-3</b> inside <b>Design-2</b> and <b>Design-3</b> respectively and so on.
		</li>
		<li>But in doing so, you have lost track of which background color and font you used in which file. This is causing more confusion than clarity and worse, you're losing a lot of time in merely switching between various files that are open in front of you.
		</li>
		<li>You come up with a solution to identify the key differences between the files by creating a document <b>Summary-n</b> that contains key details of the poster and the date-time of completion inside every sub folder <b>Design-n</b>.
		</li>
		<li>Visually, now there is a folder called Competition that contains n number of sub-folders called <b>Design-n</b> that contain two files: <b>Poster-n</b> and <b>Summary-n</b>.
		</li>
	</ul>

</p>


<p><div style="width: 80%; margin: 0 auto;"><img src="/assets/blog-img/git-illustration.png" alt="mac vcs git-illustration"></div><br>Now, imagine a tool that could take care of all these steps. A tool that looks like your web browser history page; with a link to every Poster with its timestamp and a small Summary beside it.
</p>

<p>
This is how a Version Control System(VCS) works. <a href="https://git-scm.com">Git</a> is one such VCS. It lets you preserve the history of any change made to a code as and how you work on it. 
</p>
<p>
<a href="https://github.com">GitHub</a> is a web based Git storehouse that provides all the functionalities of Git as well as some interesting additional features like integrated issue tracking and organizational team management.
</p>


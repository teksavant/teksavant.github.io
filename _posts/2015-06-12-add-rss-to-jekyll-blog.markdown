---
title: Building a Jekyll Website. How to add RSS?
date: 2015-06-12 21:48:52
img: logo-2x.png
description: Just built your own Jekyll website, but don't know how to add RSS feed to it? Then
---

<p class="intro"><span class="dropcap">L</span>ot of learning is required when you change your platform of choice. That's not what I am telling you but most people think like that. No doubt there is a learning curve attached when giving new platform a shot but you don't need to be a scientist to do that. Same is the case when starting with <a href="http://jekyllrb.com">Jekyll</a> and LIQUID templating system. Its different but if you are determined you can do it pretty easily. Either ways there is one key feature that every website requires to engage its viewers. And... you guessed it right, its RSS.</p>

<p>If you are still reading this article then you must have already created your first Jekyll website. But are you facing problems while adding RSS feed to your website or don't know how to add it at all then do read further to know how I implemented RSS in <a href="http://teksavant.com">my own website</a> in just 4 simple steps.</p>

<p><b>Procedure:</b></p>
<ol>
 <li>
   Add these three variables in _config.yml file.
   `title: Tek Savant
    description: This blog is all about the latest news and tutorials about latest software or devices you care about.
    url: http://teksavant.com`
 </li>
 
 <li>
   <p>Create a feed.xml file in root directory of your project. To see the proper layout of root directory go to <a href="https://github.com/teksavant/teksavant.github.io">my website's git repository.</a> Then add the following code in it.</p>
   <img src="rssxmlcode.jpg" alt="">
 </li>

 <li>
  <p>To add a link to website for users to subscribe I add a photo to footer of website and then linked it to feed.xml.</p>
  <code data-lang="html"><a href='http://teksavant.com/feed.xml' rel='alternate' type='application/atom+xml' ><img src="{{ site.baseurl }}/assets/img/rss.png" style="display: inline-block; border-radius: 100%; width: 30px; height: 30px;"></a></code>
  <img src="/assets/blog-img/RSS-demo.png">
  <p>But if you want, then you place it anywhere else too.</p>
 </li>

  <li>
   <p>To allow browsers like safari which has inbuilt support for RSS you need to add similar code in head.html</p>
   <code data-lang="html"><link href='http://teksavant.com/feed.xml' rel='alternate' type='application/atom+xml'></code>
  </li>
</ol>

<p>That's it. See how simple that is! So now you have added RSS in your website. Don't forget to share your creation with us in comments down below.</p>
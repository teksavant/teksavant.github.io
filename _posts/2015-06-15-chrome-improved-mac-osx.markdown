---
title: More efficient Google Chrome for Mac OS X coming soon.
date: 2015-06-15 12:07:07
image: chrome-inefficiency.png
---

<p class="intro"><span class="dropcap">I</span>f you ever happened to use Chrome on Windows and then on Mac, you’d notice there is a sea of difference between the two. While it is arguably the best browser to use on Windows, on OS X it feels like a bloated mess that just burns through your battery at an astonishing rate for no good reason.</p>


<p>It seems Google is well aware of this issue, so it is working on improving the efficiency of the OS X version. In a Google+ post, Google engineer clarified on a few things the company is doing to improve battery life on Mac.</p>

<p>Chrome also incurs higher CPU wakes and CPU usage while using Safari user agent compared to using Safari, which will now be dropped by 66% and fewer CPU wakes and usage, making it on par with Safari. 
</p>

<p>
The other technical changes to Chrome for OS X are outlined as follows:
<i>
<ul style="list-style: none;">
<li>
<br>
The team has been working on addressing this; here are some cases that have recently been improved on trunk: 
<br>
<a href="http://crbug.com/460102">http://crbug.com/460102 </a>
</li>
<li>
<br>
<br>
<u>Before</u>: Renderers for background tabs had the same priority as for foreground tabs. <br>
<u>Now</u>: Renderers for background tabs get a lower priority, reducing idle wakeups on various perf test, in some cases by significant amounts (e.g. 50% on one test). 
<br>
<a href="http://crbug.com/485371">http://crbug.com/485371 </a>
</li>
<li>
<br>
<br>
<!-- Google adsens -->
<div style="margin: 20px auto 40px;">
   <script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- response base ad -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7301436099802085"
     data-ad-slot="9213800657"
     data-ad-format="auto"></ins>
<script>
(adsbygoogle = window.adsbygoogle || []).push({});
</script></div>
<u>Before</u>: On a Google search results page, using Safari's user agent to get the same content that Safari would, Chrome incurs ~390 wakes over 30s and 0.3% CPU usage vs. Safari’s 120 wakes over 30s and 0.1% CPU usage. <br>
<u>Now</u>: 66% reduction in both timer firings and CPU use. Chrome is now incurring ~120 wakes over 30s and 0.1% CPU use, on par with Safari. 
<br>
<a href="http://crbug.com/489936">http://crbug.com/489936 </a>
</li>
<li>
<br><br>
<u>Before</u>: On capitalone.com, Chromium incurs ~1010 wakeups over 30s vs. Safari's ~490 wakes. <br>
<u>Now</u>: ~30% reduction in timer firings. Chrome is now incurring ~721 wakeups over 30s. 
<br>
<a href="http://crbug.com/493350">http://crbug.com/493350 </a>
</li>
<li>
<br><br>
<u>Before</u>: On amazon.com, Chromium incurs 768 wakups over 30s and consumes ~0.7% CPU vs. Safari's 312 wakes over 30s and ~0.1% CPU. <br>
<u>Now</u>: ~59% reduction in timer firings and ~70% reduction in CPU use. Chrome is now incurring ~316 wakeups over 30s, and 0.2% CPU use, on par with Safari at 312 wakes, and 0.1% CPU use."<br>
</li>
</ul>
</i></p>

<p>Hopefully, the updates are released soon, along with other improvements to reduce memory usage.</p>
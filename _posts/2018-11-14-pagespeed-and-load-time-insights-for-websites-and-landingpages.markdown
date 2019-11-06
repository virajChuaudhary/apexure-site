---
title: 2019 is the year of Page Speed and yes, we are ready
date: 2018-11-14 13:04:00 Z
tags:
- code
author: Waseem Bashir
image: "/images/postsimages/factors-which-lead-less-load-time.jpg"
take-away-image: "/images/postsimages/factors-which-lead-less-load-time.jpg"
author-image: "/images/author-waseem-bashir.png"
facebook-link: https://www.facebook.com/Apexure/
instagram-link: https://www.instagram.com/waseembashir/
twitter-link: https://twitter.com/waseembashir
author-description: Founder & CEO  of Apexure, Waseem worked in London’s Financial
  Industry. He has worked on trading floors in BNP Paribas and Trafigura, developing
  complex business systems. Waseem loves working with Startups and combines data and
  design to create improved User Experiences.
comments: true
description: Webpage load time and speed matters. Since 2010, page speed has been
  a Google ranking factor and becomes even more critical in recent days. Check out
  this guide to get your page load speed to less than 1 second.
layout: posts
---

Unbounce recently in their latest blog post shared how page load times are going to influence the marketing world in 2019. At Apexure, we have been pushing the boundaries of how to improve page speed and decrease page load times. In this post, I would like to discuss the various routes we undertook and the results. I call them **"1-second landing pages." or "#1sLP".**

##### What is a 1-Second Landing Page?

A landing page which takes less than a second to load. It does sound very simple from the surface but under the hood, there is some clever stuff set up.

### How can I increase my page speed?

Here are some factors which can help achieve less than 1-second load time:

> ##### - Web Host
>
> ![webhost.jpg](/images/postsimages/webhost.jpg)
> Yes, your hosting provider and their data centre location have a huge impact on load times. This is especially true when you are running PPC or paid traffic campaigns over a geographic location. When we compared highly optimised landing pages hosted on the US vs UK servers for UK audience, the results were quite dramatic. We were able to achieve 0.6 second load times for a landing page hosted in the UK vs 1.0 second when hosted in the US.
>
> ##### - Tiny Images
>
> ![tiny.jpg](/images/postsimages/tiny.jpg)
> One major sin I find marketers and sometimes content writers do is to upload images over 500kb, sometimes over a megabyte. One basic tool which should be in your arsenal is [Tinypng](https://tinypng.com/) You can upload images and get a highly compressed image. Although tinypng or tinyjpg is great, these compressors don't take into account actual dimensions. They do reduce file size but what if you actually wanted to use the image as a thumbnail? There is still no point in using a 1280x800 image as a      thumbnail. So you need an image and a resize app \+ an image compressor. You can use Photoshop or an online tool. Once you have resized the image, then compress it and reduce the file size even further.
>
> ##### - Sprite Images
>
> ![sprit.jpg](/images/postsimages/sprit.jpg)
> Do you have icons, badges and other images on your landing pages? Why not combine them into one image and using some clever CSS, swap the image around? This technique reduces the HTTP requests your browser makes every time it needs to load a new resource. So if 100 tiny images are bundled as 1 image, there will be only 1 HTTP request vs 100.
>
> ##### - Minified HTML/CSS/JS files
>
> ![minified.jpg](/images/postsimages/minified.jpg)
> Minifying is the process of removing any whitespace from your code files so the code is compressed. This again saves few KBs of data. Every little helps!
>
> ##### - Use AMP
>
> ![useAmp.jpg](/images/postsimages/useAmp.jpg)
> For mobile campaigns, we would recommend using AMP (Accelerated Mobile Pages). As an early adopter, we currently build all our [mobile landing pages in Unbounce ](https://www.apexure.com/mobile-landing-page/)and love the flexibility of drag ‘n’ drop in an otherwise restricted system.
>
> ##### - Use a CDN
>
> ![usecdn.jpg](/images/postsimages/usecdn.jpg)
> Having a host local to your campaign is great, but if you are targeting multiple countries or have dedicated SEO landing pages, I would strongly recommend using a Content Delivery Network (CDN). A CDN maintains a cached version of the images, HTML or any content and stores them in various geographical locations. With CDN, users download data from servers closest to their proximity which improves page speed.

<section id= "dev_tips" class="dev_tips_custom">
<div class="container">
<h4>Developer Tips:</h4>
<div class="row">
<div class="col">
<div class="corner_img">
<img src="images/postsimages/tip.png" alt="Tips by Senior Web developer" class="img-fluid" >
</div>
<blockquote class="blockquote_post_five">
<div class="dev_info d-md-flex">
<img src="images/postsimages/sr_webdev.png" alt="web developer tips" class="img-fluid">
<div class="dev_name d-inline-block pl-4">
<h5>By Ifrah Bashir</h5>
<p>Senior Web Developer</p>
</div>
</div>
<ul class="dev_tips_list">
<li>
<h5>Defer Parsing Javascript</h5>
</li>
<p>Javascript is the main cause of websites loading slowly because when a browser comes across Javascript it executes the script before continuing to load HTML. By deferring parsing of JavaScript means JavaScript(s) should load but only after the content of the website has loaded.</p>
<li>
<h5>Avoid Redirects</h5>
</li>
<p>Redirects are instructions or methods that automatically take visitors of one file to another file or location. Redirects that use the HTTP-equiv="refresh" attribute or Javascript can introduce even longer waiting times. Google suggests eliminating redirects which are not absolutely necessary.</p>
<li>
<h5>Use CSS3 and HTML5</h5>
</li>
<p>CSS3 and HTML5 framework is lightweight and designed for speed. When developing custom web pages you should always utilise the latest frameworks.</p>
</ul>
</blockquote>
</div>
</div>
</div>
</section>

<h5 class="text-center dev_qoute">“ The future is speed, are you game? ”</h5>
<section id="info" class="info_custom_blog">
<div class="container">
<h2 class="text-center">Page speed load FAQs</h2>
<div class="row">
<div class="col-md-10 offset-md-1">
<div class="question_warapper">
<h5><span>Q.</span>What is page load time?</h5>
<h6><span>A.</span>Page load time is the time taken to download and show the entire content of a web page in the browser window (measured in seconds). Page load time is an
important web performance metric that directly impacts conversions.</h6>
</div>
<div class="question_warapper">
<h5><span>Q.</span>What is Google PageSpeed Insights?</h5>
<h6><span>A.</span>Google developers have put together an online app which allows web developers to check the performance of their website. You can check the tool at the website.</h6>
</div>
<div class="question_warapper">
<h5><span>Q.</span> Why is my website slow?</h5>
<h6><span>A.</span>There could be lots of reasons which could be causing a reduced page load speed. We have discussed some of the main ones in our post above. If you still are facing problems, I would recommend speaking to an expert.</h6>
</div>
<div class="question_warapper">
<h5><span>Q.</span>Is page speed a ranking factor?</h5>
<h6><span>A.</span>According to Search Engine Land Google has taken into account mobile page speed as a ranking factor in their mobile search results. Since AMP only works for mobile at the moment, Google’s focus is getting mobile users faster results who mostly run on data limited services like 2G or 3G.</h6>
</div>
<div class="question_warapper">
<h5><span>Q.</span>What is a good PageSpeed score?</h5>
<h6><span>A.</span>Rather, than focusing on PageSpeed score, I would recommend reducing the page load times to under a second.</h6>
</div>
</div>
</div>
</div>
</section>
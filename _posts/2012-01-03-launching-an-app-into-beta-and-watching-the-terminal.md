---
title: Launching an app into beta and watching the terminal
author: Pete
layout: post
permalink: /2012/01/launching-an-app-into-beta-and-watching-the-terminal/
categories:
  - tech
  - WorkFu
---
Proud to have finally launched my first app into beta after 11 years of service work for other companies and agencies: [http://workfu.com][1]

Now I’m furiously watching the terminal checking that all is going to plan – we tried to build in as many levels of fail handling as possible but you can never tell once you get real users on there.

In our pre-beta launch one of the services was regularly going over 75% CPU on an Amazon micro instance which just didn’t seem right – the past 3 days has seen some furious re-coding and testing and finally things are looking a bit more normal: now 7% usage with quite a lot of usage.  So all is good at the moment and no need to start adding new servers yet!

Very, very interesting to see the natural dissemination of signups as the site gets retweeted.  I shall be sitting here watching the terminal for a while yet.

Update: 13th Jan 2012

Following the initial launch we were lucky enough to be featured in <a href="http://thenextweb.com/apps/2012/01/10/workfu-taps-your-twitter-account-to-help-you-find-jobs/" target="_blank">TheNextWeb apps section</a> as well as <a href="http://www.psfk.com/2012/01/twitter-app-find-jobs.html" target="_blank">psfk.com</a>, <a href="http://www.designfridge.co.uk/inspiration/clean/workfu" target="_blank">designfridge.co.uk</a>, <a href="http://wwwhatsnew.com/2012/01/11/worfu-encontrar-propuestas-de-trabajo-con-twitter/" target="_blank">wwwhatsnew.com</a>, <a href="http://blog.appharbor.com/2012/1/04/featured-app-workfu" target="_blank">the appharbor blog</a> and<a href="http://www.art-spire.com/en/webdesign/we-love-webdesign-122/" target="_blank"> art-spire</a> and this has blown our signups out of the water!  I’m pleased to say that (until now) our architecture choices and providers have not let us down and we have been able to handle a good amount of load.  It’s the first time we have built something using this number of services (rather than using two dedicated machines) and I’m really happy with the results – special thanks to appharbor for their great support.

I will bring more news on this topic later….

 [1]: http://workfu.com "WorkFu"
---
layout: page
permalink: /contact/
title: Contact
show_meta: false
published: true
description: "Contact example.com"
comments: false
mathjax: false
noindex: false
sitemap:
    priority: 0.5
    changefreq: 'monthly'
    lastmod: 2016-02-13
tags:
  - "foo boo"
  - "driving directions"
  - address
---

| <i class="fa fa-envelope"></i> | soulist77@gmail.com   | 
| - | :- |
| <i class="fa fa-linkedin"></i>  | [linked in](https://www.linkedin.com/in/seungsu-lee-a69827169/) | 
| - | :- |
| <i class="fa fa-github"></i>  | [github](https://github.com/sslee0000/) | 
| - | :- |
| <i class="fa fa-file"></i>  | [Curriculum Vitae](https://drive.google.com/file/d/1WlpQm0JOzT8dzogHYxfHiwOdrtj9v9Kb/view?usp=sharing) 
| - | :- |

<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+'://platform.twitter.com/widgets.js';fjs.parentNode.insertBefore(js,fjs);}}(document, 'script', 'twitter-wjs');</script>

{% if site.twitter_widget_id %}
<div class="text-tweets">
<div class="tweets">
<a class="twitter-timeline"
  data-dnt="true"
  width="600"
  height="250"
  href="https://twitter.com/{{ site.owner.twitter }}"
  data-widget-id="{{ site.twitter_widget_id }}"
  data-tweet-limit="2"
  data-chrome="noheader nofooter noborders noscrollbar transparent">
  Recent Tweets</a>
 </div>
<script>
    !function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");
</script>
</div>
{% else %}

{% endif %}

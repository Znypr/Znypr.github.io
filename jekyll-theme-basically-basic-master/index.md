---
layout: home
title: Znypr's Website
subtitle: Follow me on social media!
---

<!-- Add the HTML content above this line -->

<!-- Add the code for the toggle switch below this line -->
<label class="switch">
    <input type="checkbox" id="toggle-switch">
    <span class="slider round"></span>
</label>

# Welcome to Your Website

## My Social Media

### YouTube

<iframe width="560" height="315" src="https://www.youtube.com/embed/{{youtube_username}}" frameborder="0"
    allow="autoplay; encrypted-media" allowfullscreen></iframe>

### Twitch

<iframe src="twitch.html" height="378" width="620"></iframe>

### Twitter

<a class="twitter-timeline" href="https://twitter.com/{{twitter_username}}">Tweets by {{twitter_username}}</a>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### Instagram

<blockquote class="instagram-media" data-instgrm-captioned
    data-instgrm-permalink="https://www.instagram.com/p/POST_LINK/" data-instgrm-version="13"></blockquote>
<script async defer src="//www.instagram.com/embed.js"></script>

### Current Time

<iframe src="https://free.timeanddate.com/clock/i7ts4j4v/n136/fn2/fs24/tct/pct/ftb/tt0/tw0/tm1/th1/ta1/tb4"
    frameborder="0" width="135" height="30"></iframe>

{% include_relative youtube.html %}

{% include_relative twitch.html %}

{% include_relative twitter.html %}

{% include_relative instagram.html %}

{% include_relative current_time.html %}

<!-- Add the code for the toggle switch above this line -->
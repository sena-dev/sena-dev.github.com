---
layout: page
title: Hello World!
tagline: This Is Shendy Adhityani's Personal Blog
---
{% include JB/setup %}

<div class="row">
  <div class="span4">
    <div id="slider" class="carousel slide">
      <ol class="carousel-indicators">
        <li data-target="#slider" data-slide-to="0" class="active"></li>
        <li data-target="#slider" data-slide-to="1"></li>
        <li data-target="#slider" data-slide-to="2"></li>
      </ol>
      <div class="carousel-inner">
        <div class="active item">
          <img src="/assets/photos/1.png" alt="1">
          <div class="carousel-caption">
            <p>I write something in my blog</p>
          </div>
        </div>
        <div class="item">
          <img src="/assets/photos/2.png" alt="2">
          <div class="carousel-caption">
            <p>I'm Shendy Adhityani</p>
          </div>
        </div>
        <div class="item">
          <img src="/assets/photos/3.png" alt="3">
          <div class="carousel-caption">
            <p>I'm Computer Scientist</p>
          </div>
        </div>
      </div>
      <a class="carousel-control left" href="#slider" data-slide="prev">&lsaquo;</a>
      <a class="carousel-control right" href="#slider" data-slide="next">&rsaquo;</a>
    </div>
  </div>
  <div class="span4">
    <h3>About Me</h3>
    <p>Hai, perkenalkan saya Shendy, selamat datang di website pribadi saya, website ini merupakan
      tempat saya untuk berbagi informasi, khususnya mengenai komputer, pengalaman dan lainnya.</p>
    <p>Saya lahir di Bekasi pada 29 Oktober 1988, menyelesaikan pendidikan S1 di Universitas Gunadarma jurusan Sistem Informasi. Skripsi saya membahas mengenai "Penerapan teknologi semantik web &amp; ontologi pada sistem pendataan TKI".</p>
  </div>
  <div class="span2">
    <h3>Everywhere</h3>
    <p>
      <a href="https://twitter.com/missshendy" class="twitter-follow-button" data-show-count="false" data-lang="en">Follow @missshendy</a>
      <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src="//platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
    </p>
    <p>
      <!-- <iframe src="//www.facebook.com/plugins/follow.php?href=https%3A%2F%2Fwww.facebook.com%2Fshendy.adit&amp;layout=button_count&amp;show_faces=false&amp;colorscheme=light&amp;font=segoe+ui&amp;width=450&amp;height=21" scrolling="no" frameborder="0" style="border:none; overflow:hidden; width:450px; height:21px;" allowTransparency="true"></iframe> -->
    </p>
  </div>
</div>
<!-- 
Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


 -->
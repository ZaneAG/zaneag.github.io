---
layout: page
title: Zane Gyorko
subtitle: My name is Zane. This is my Website
use-site-title: true
bigimg:
  - "/img/front/sebastian-bridge.png" : "Sebastian Inlet, FL"
  - "/img/front/uss-intrepid.jpg" : "USS Intrepid, NY"
  - "/img/front/tennessee-2018.jpg" : "Tennessee, Summer 2018"
  - "/img/front/yellowstone.JPG" : "Old Faithful, Yellowstone"
  - "/img/front/fedex-field.jpg" : "FedEx Field, Landover MD"
  - "/img/front/gardenofthegods_clean.jpg" : "Garden of the Gods, Colorado Springs"
  - "/img/front/golden-gate_clean.jpg" : "Golden Gate Bridge, San Francisco"
  - "/img/front/bigsky_clean.jpg" : "Big Sky, MT"
  - "/img/front/sequoia_clean.jpg" : "Sequoia National Park"
  - "/img/front/deathvalley_clean.jpg" : "Death Valley National Park"
  - "/img/front/kelsodunes_clean.jpg" : "Kelso Sand Dunes"
---


# Why did I make this?

This site serves as a hub for tracking my projects and other activities.

Currently more or less a work in progress. Content should be updating fairly frequently with new pages, photos, links, and more. Feast your eyes.

Nobody else in the world would possibly ever want the domain "zanegyorko.com", since I am the only person in the world with that name. So I bought it for $12. This site is hosted on GitHub pages so there's no ongoing upkeep cost. Easy.

The real question is: Why are you here?




<!--<div class="posts-list">
  {% for post in paginator.posts %}
  <article class="post-preview">
    <a href="{{ post.url | prepend: site.baseurl }}">
	  <h2 class="post-title">{{ post.title }}</h2>

	  {% if post.subtitle %}
	  <h3 class="post-subtitle">
	    {{ post.subtitle }}
	  </h3>
	  {% endif %}
    </a>

    <p class="post-meta">
      Posted on {{ post.date | date: "%B %-d, %Y" }}
    </p>

    <div class="post-entry-container">
      {% if post.image %}
      <div class="post-image">
        <a href="{{ post.url | prepend: site.baseurl }}">
          <img src="{{ post.image }}">
        </a>
      </div>
      {% endif %}
      <div class="post-entry">
        {{ post.excerpt | strip_html | xml_escape | truncatewords: site.excerpt_length }}
        {% assign excerpt_word_count = post.excerpt | number_of_words %}
        {% if post.content != post.excerpt or excerpt_word_count > site.excerpt_length %}
          <a href="{{ post.url | prepend: site.baseurl }}" class="post-read-more">[Read&nbsp;More]</a>
        {% endif %}
      </div>
    </div>

    {% if post.tags.size > 0 %}
    <div class="blog-tags">
      Tags:
      {% if site.link-tags %}
      {% for tag in post.tags %}
      <a href="{{ site.baseurl }}/tags#{{- tag -}}">{{- tag -}}</a>
      {% endfor %}
      {% else %}
        {{ post.tags | join: ", " }}
      {% endif %}
    </div>
    {% endif %}

   </article>
  {% endfor %}
</div>

{% if paginator.total_pages > 1 %}
<ul class="pager main-pager">
  {% if paginator.previous_page %}
  <li class="previous">
    <a href="{{ paginator.previous_page_path | prepend: site.baseurl | replace: '//', '/' }}">&larr; Newer Posts</a>
  </li>
  {% endif %}
  {% if paginator.next_page %}
  <li class="next">
    <a href="{{ paginator.next_page_path | prepend: site.baseurl | replace: '//', '/' }}">Older Posts &rarr;</a>
  </li>
  {% endif %}
</ul>
{% endif %}-->

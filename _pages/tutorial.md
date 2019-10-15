---
title: Free Jekyll Themes
description: Free Jekyll Themes.
permalink: /free
---

<div class="row"><div class="container mt-2">
{% for post in site.categories.free %}    <div class="col-xs-12 col-sm-6 col-md-4 mt-4">
                    <div class="card-home">                    
                            <a href="{{ post.url }}">
                            <img alt="you" src="/thumbnails/{{ post.thumbnail }}" class="rounded-circle"></a>
                            <div class="card-home-body mt-4">
                            <h3 class="card-home-title"><a href="{{ post.url }}">{{ post.title | capitalize }}</a></h3>
                            <p class="card-text">{{ post.excerpt | truncate: 50 | strip.html  }}</p>                                                 
                    </div>        
                    </div>        
    </div>  
 {% endfor %}
</div></div>

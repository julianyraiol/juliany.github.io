---
layout: talks
title: Palestras
description: principais apresentações
background: "/img/banner_home4.jpg"
---

<style>

.card-img-top {
    width: 100%;
    height: 15vw;
    object-fit: cover;
}

.card{
    height: 600px;
    text-align: center;
    border: none;
}
</style>

<div class="card-columns">

{% for talk in site.data.talks %}

  <div class="card">
    <img class="rounded img-fluid card-img-top" src="{{ talk.img_path | relative_url }}" alt="{{ talk.event }}">
    <div class="card-body">
      <h5 class="card-title">{{ talk.title }}</h5>
      <p class="card-text">{{ talk.event }}</p>
      <p class="card-text">{{ talk.year }}</p>

      {% if talk.link %}
        <a class="btn btn-light" href="{{ talk.link | relative_url }}"> <small class="text-muted">  Video </small></a>
      {% endif %}

      {% if talk.slide %}
        <a class="btn btn-light" href="{{ talk.slide | relative_url }}"> <small class="text-muted">  Slides </small></a>
      {% endif %}
      
    </div>
  </div>

{% endfor %}

</div>
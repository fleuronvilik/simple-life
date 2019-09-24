<section class="widget-about">

  <h2 class="widget-title">About me</h2>
  <img src="assets/img/about-me.jpg" alt="">
  <p>I find life better, and I'm happier, when things are nice and simple.</p>
  
</section>

<section class="widget-recent">

  <h2 class="widget-title">Recent posts</h2>

  {% for post in site.data.posts offset:1 %}
  <div>
    <h3 class="widget-lower-title">{{ post.title }}</h3>
    <img src="assets/img/{{ post.image }}" alt="">
  </div>
  {% endfor %}

</section>

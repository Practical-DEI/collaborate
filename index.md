## Welcome to Collaborate - Practical Diversity, Equity and Inclusion website

This is a community website to share ideas around practical diversity, equity and inclusion ideas.

There is an [About](about) section that tells you more.



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

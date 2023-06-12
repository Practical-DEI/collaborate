# Welcome to Collaborate - Practical Diversity, Equity and Inclusion website

This is a community website to share ideas around practical diversity, equity and inclusion ideas.

There is an [About](about) section that tells you more.

## Not the Only One

One of the main projects is [Not the Only One](http://www.nottheonlyone.org). This is a project that is attempting to collate all the DEI material that shows the pesonal stories of discrimination, along with solutions on how to move forward.

You can contribute to Not the Only One by:
1. [Adding a submission](https://docs.google.com/forms/d/e/1FAIpQLScqWMQsFNLQZ3sMQue8cG9zFF5gP-soiJcbPE9WNm0dmiLSHA/viewform)
2. [Contributing code](
https://github.com/NotTheOnlyOne/ntoo_simple) 
3. Helping to curate (see figure 1 below) the data from Zenodo and from Twitter saved databases.

![Not the Only One](https://github.com/Practical-DEI/collaborate/assets/420050/e1d579c7-7239-4fb0-943a-9edb7a2dc2ed){:class="img-responsive" width="800px" } 

Figure 1 - how to contribute to Not the Only One.


## Other posts

You can even add posts, like in a blog. Here are the posts so far:


<ul>
  {% for post in site.posts %}
    <li>
      <a href="./{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

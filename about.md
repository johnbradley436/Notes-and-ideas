# About me

I'm a person with advanced degrees who doesn't know much about creating websites like this.

Experimental post list
<ul>
  {% for post in site.Notes-and-ideas %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[Back](https://johnbradley436.github.io/Notes-and-ideas/)

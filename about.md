# About me

I'm a person with advanced degrees who doesn't know much about creating websites like this.

## Experimental post list #1
<ul>
  {% for post in site.Notes-and-ideas %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Experimental post list #2
<ul>
  {% for post in site.root %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## List (the control version)
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[Back](https://johnbradley436.github.io/Notes-and-ideas/)

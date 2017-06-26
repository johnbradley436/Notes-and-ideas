# Notes and Ideas

## Note 1
Well so far I can see the potential in this site! Although I can't figure out how to create a separate page or post... There's always next week.

## Note 2
In my second session I've made progress. I've learned how to create pages, a _posts folder, and a set of posts whose existence is confirmed by a nifty list of posts that Jekyll's documentation taught me how to create (if only the actually posts themsevles would load). There's always next session!

## Here's a list of my posts
They may or may not actually exist
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


### [Click here for my About page](https://johnbradley436.github.io/Notes-and-ideas/about.html)

[Link to GitHub Help Text](https://johnbradley436.github.io/Notes-and-ideas/Original-GitHub-Pages-Help-Text.html)

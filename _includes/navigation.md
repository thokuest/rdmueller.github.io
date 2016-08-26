<div>
        {% for post in site.tags[doc] %}
            {{ post.date | date: "%B %e, %Y" }} <a href="{{ post.url }}">{{ post.title }}</a><br />
        {% endfor %}
</div>

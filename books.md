# Book List

1. [Anathem](/books/{{ "Anathem" | slugify: "latin" }}) by [Neal Stephenson](/authors/{{ "Neal Stephenson" | slugify: "latin" }})
2. [Thud](/books/2) by [Terry Pratchett](/authors/2)
3. [Imperium](/books/3) by [Robert Harris](/authors/3)

{% for book in site.data.books %}
{{ forloop.index }}. [{{book.title}}](/books/{{ book.title | slugify: "latin"}}) by [{{book.author}}](/authors/{{ book.author | slugify: "latin" }})
{% endfor %}

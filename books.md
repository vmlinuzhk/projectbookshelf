# Book List


{% for book in site.data.books %}
{{ forloop.index }}. [{{book.title}}](/books/{{ book.title | slugify: "latin"}}) by [{{book.author}}](/authors/{{ book.author | slugify: "latin" }}){% endfor %}

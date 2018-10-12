---
layout: page
title: Bookshelf
permalink: /bookshelf/
---

<section>
  <div class="container-fluid">
    <table>
        <tr><th>Book</th><th>Author</th></tr>
        {% for book in site.data.bookshelf %}
        <tr>
            <td>{{ book.name }}</td><td>{{ book.author }}</td>
        </tr>
        {% endfor %}    
    </table>
</div>
</section>


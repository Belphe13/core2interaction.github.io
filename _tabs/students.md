---
# layout: students
icon: fas fa-user-friends 
order: 3
---

<p>
{% for student in site.data.students %}
    <a href="https://github.com/{{ student.github }}">
      {{ student.name }}<br>
    </a>
{% endfor %}
</p>
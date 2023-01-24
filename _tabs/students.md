---
# layout: students
icon: fas fa-user-friends 
order: 3
---

<h2>
{% for student in site.data.students %}
    <a href="https://github.com/{{ student.github }}">
      {{ student.name }} <br>
    </a>
{% endfor %}
</h2>
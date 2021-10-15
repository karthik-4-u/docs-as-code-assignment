# List of Passengers with Age who Traveled in Titanic
{% for item in site.data.titanic %}
- {{item.Name}} : {{item.Age}}
{% endfor %}
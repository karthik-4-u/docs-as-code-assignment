# List of Passengers and their Ages who Traveled in Titanic
{% for item in site.data.titanic %}
- {{item.Name}} : {{item.Age}}
{% endfor %}
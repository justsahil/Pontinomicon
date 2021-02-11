 # Player Roster
 
 {% assign players = site.pages[0] | remove "*" | ltrim | remove "@" | split ", " %}
 {% for player in players %}
  - [{{player}}](https://github.com/{{player}})
 	{% endfor %}

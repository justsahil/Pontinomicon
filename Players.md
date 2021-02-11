 # Player Roster
 
 {% assign players = site.CODEOWNERS | remove "*" | ltrim | remove "@" | split ", " %}
 {% for player in players %}
  - [@{{player}}](https://github.com/{{player}})
 	{% endfor %}

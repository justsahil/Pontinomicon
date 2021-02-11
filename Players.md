 # Player Roster
 
{% assign players = site.pages[0] | remove "*" | trim | remove "@" | split ", " %}
{% for player in players %}
 - {{player}}
{% endfor %}

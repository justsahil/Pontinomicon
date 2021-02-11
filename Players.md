 # Player Roster
 
{% assign players = "* @macterra @justsahil" | remove "*" | trim | remove "@" | split ", " %}
{% for player in players %}
 - {{player}}
{% endfor %}

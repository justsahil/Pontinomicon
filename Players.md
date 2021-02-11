 # Player Roster
 
{% assign players = "* @macterra @justsahil" | remove "*" | strip | split " " %}
{% for player in players %}
 {{player}}
{% endfor %}

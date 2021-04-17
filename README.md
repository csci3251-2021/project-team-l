# Constributors

{% for team_member in site.project-team-l._stu %}
  <img src="{{team_member.image}}">
  <a href="https://github.com/{{team_member.user}}"><h2{{team_member.user}}<h2/a> <br/>
  <p> {{team_member.content | markdownify }} </p>
 {% endfor %}
 

---

layout: post
Title: My Second Post
tag: "second"

---


<h2> This is my second post in Jekyll!!</h2>
<small>This is so great.</small>


<ul>
<li>hi</li>
<li>A</li>
<li>B</li>
<li>C</li>
</ul>


{% for post in site.posts %}
	{% if post.tag == "first" %}
	
			<h3><a href={{ site.baseurl }}{{ post.title }}> {{ post.title}} </a></h3>
				 
	 {% endif %}
			
{% endfor %}



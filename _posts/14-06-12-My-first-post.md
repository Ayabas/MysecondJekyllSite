---

layout: post
Title: My First Post
tag: "second"


---


<h2> This is my first post in Jekyll!!</h2>



{% for post in site.posts %}
{% if post.tag == "second" %}
	
			<h3><a href={{ site.baseurl }}{{ post.title }}> {{ post.title}} </a></h3>
				 
	 {% endif %} 
	 {% endfor %}
	 
<small>great.</small>


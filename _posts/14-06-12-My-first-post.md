---

layout: post:
Title: My First Post
tag:"second"


---


<h2> This is my first post

{% if post.tag == "second" %}
	
			<h3><a href={{ site.baseurl }}{{ post.title }}> {{ post.title}} </a></h3>
				 
	 {% endfor %} in Jekyll!!</h2>
<small>great.</small>


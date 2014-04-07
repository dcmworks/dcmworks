---

title: About Dcmworks
layout: Page
permalink: about/
headerimg: FFjM3TQ
footerimg: 

---

Dcmworks.co.uk is a collaborative space for writers, artists and audio technicians, where we aim to bring to life a variety of stories. Currently our main project is Necessity of Hendricks, a fully voiced and illustrated novel. 

<br />

<img src="http://i.imgur.com/bUZjRSB.png" title="Hosted by imgur.com"/>

<br /><br />

Click here for Necessity of Hendricks Chapter One --> http://dcmworks.co.uk/novels/necessityofhendricks/1/


<br /><br />


Who are we?

{% for people in site.data.people.yml %}
<br /><br />
<div id="person" class="content">
	<h3>{{ people.name }} {% if people.alias %}({{ people.alias }}){% endif %}</h3>
	<p>{{ people.description }}</p>
</div>
{% endfor %}


If you're an artist, writer or voice actor (or even audio technician!) and want to work with us, head over to our Contact Us page up top!

<br /><br />

Go find us on Twitter and Tumblr to keep up to date and get previews of our upcoming work.

<br />

Twitter: https://twitter.com/DCMWorksSocial
Tumblr: http://dcmworks.tumblr.com/
---
layout: page
title: Contact us
description: null
nav-menu: false
---

Do you want to present at an upcoming event?
Want to get in touch about anything?

You can reach us on [Github]({{ site.github_url }}), [Twitter]({{ site.twitter_url }}),
[Slack]({{ site.slack_url }}), or simply using the form below:

<section id="contact">
	<form action="https://formspree.io/{{ site.email }}" method="POST">
		<div class="field half first">
			<label for="name">Name</label>
			<input type="text" name="name" id="name" />
		</div>
		<div class="field half">
			<label for="email">Email</label>
			<input type="text" name="_replyto" id="email" />
		</div>
		<div class="field">
			<label for="message">Message</label>
			<textarea name="message" id="message" rows="6"></textarea>
		</div>
		<ul class="actions">
			<li><input type="submit" value="Send Message" class="special" /></li>
			<li><input type="reset" value="Clear" /></li>
		</ul>
	</form>
</section>

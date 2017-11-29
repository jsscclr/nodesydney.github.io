---
layout: page
title: About us
description: null
nav-menu: false
---

<h1>Sponsorship</h1>

<em>Node Sydney</em> only exists thanks to

- our awesome attendees
- the hard-woring organisers
- our sponsors!

A massive thanks to the many great Australian or global companies have been supporting us since the beginning.
Thanks for all the effort helping us organise the events, as well as providing a meeting space, and food and drinks to keep everyone energised throughout the evenings.

<h2>Current sponsors</h2>

<div class="row sponsors">
{% for entry in site.data.sponsors %}
  {% assign sponsor = entry[1] %}
  {% if sponsor.current %}
<div class="3u 4u(medium) 6u(small) 8u(xsmall)">
  <a href="{{ sponsor.website }}">
    <img src="{{ sponsor.logo }}" alt="{{ sponsor.name }}" />
  </a>
</div>
  {% endif %}
{% endfor %}
</div>

<br />

<h2>Past sponsors</h2>

<div class="row sponsors">
{% for entry in site.data.sponsors %}
  {% assign sponsor = entry[1] %}
  {% if sponsor.current == false %}
<div class="3u 4u(medium) 6u(small) 8u(xsmall)">
  <a href="{{ sponsor.website }}">
    <img src="{{ sponsor.logo }}" alt="{{ sponsor.name }}" />
  </a>
</div>
  {% endif %}
{% endfor %}
</div>

<br />

<h2>Becoming a sponsor</h2>

We are not looking for sponsors at the moment.
If you are interested in sponsoring the meetup in the future, please get in touch.

**Our obligations to sponsors**

- We will ensure people are aware of the positive impact you're having on the local community
- We will work with you in advance to find a suitable time and schedule
- We will ensure the meetup space is left clean at the end of the event

**What we expect of sponsors**

Official sponsors are expected to

- Host 4 meetups every year. The indicative cost of hosting a meetup is AUD 1200 which includes pizzas, beers and soft drinks.
- Participate in sundry expenses up to AUD 200 per year (e.g. [meetup.com](https://meetup.com) organiser fee, web hosting, banners).

**Catering**

The typical attendance for the meetup is 90-130. The best way to assess attendance it to look at the RSVP list on [meetup.com](https://www.meetup.com/node-sydney) and account for 65% turnout. For example 170 RSVPs usually means 110 attendees.

A good rule of thumb for catering is:

- 1 large pizza for every 3 people + some snacks
- 1 case of beer for every 25 people
- 1 case of soft drinks or 5 large bottles for every 50 people

Of course sponsors are welcome and encouraged to think outside the pizza box if they wish to!
Please make sure to include vegetarian and gluten-free options.

<ul class="actions">
  <li><a href="/pages/contact.html" class="button next">Get in touch</a></li>
</ul>

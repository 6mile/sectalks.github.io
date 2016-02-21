---
layout: page
title: Sydney 
menu: yes
---

## Contact 

* Twitter: [SecTalks](https://twitter.com/sectalks)
* Email: [sydney@sectalks.org](mailto:sydney@sectalks.org)
* Meetup: [http://www.meetup.com/SecTalks/](http://www.meetup.com/SecTalks/)

## Organising team 

* [@pi3ch](https://twitter.com/pi3ch) 

## Date & Time 

We usually run meetups every third Tuesday of each month. But it subjects to change. Visit our [Meetup group](http://www.meetup.com/SecTalks/) for more details.

## Location 

We run our meetups in different venues. visit our [Meetup group](http://www.meetup.com/SecTalks/) for more details.

## Looking to speak?

Whether it is a [lightning talk](https://en.wikipedia.org/wiki/Lightning_talk), 10min short presentation, or an hour long hands-on workshop, whether it is your first time to present, SecTalks is great place to get feedback and improve on.
Fill up [SecTalks CFP](http://j.mp/sectalkscfp) form.

## Upcoming meetup 

Details of an upcoming meetup is sent to l33t members mailing list 
and posted on our [Meetup group](http://www.meetup.com/SecTalks/).

## How to join

SecTalks is always open to anyone who is keen to learn infosec.
We run a mix of meetups for both beginners and people with experience.
Join our [Meetup group](http://www.meetup.com/SecTalks/) and
RSVP to upcoming meetups. 

### I am l33t!

If you are l33t, you may want
to solve our l33t entry challenge to get yourself
on our *l33t mailing list*. There is no harm, trying it.

#### What is the l33t entry challenge?

1. Follow [sectalks](https://twitter.com/sectalks) on Twitter.
1. Tweet "@sectalks, V jnaan wbva...".
1. The challenge details will be DMed to you.
1. Have fun and email us the flag.

*Note: Twitter doesn't allow for DM, if you don't follow @sectalks.*

## Sponsors
#### Venue and catering
<a href="http://www.pwc.com.au" 
   title="PWC: 12 month venue and catering for SecTalks Sydney and Melbourne.">
    <img src="{{ site.baseurl }}/images/sponsors/pwc.jpg" 
         alt="PWC: 12 month venue and catering for SecTalks Sydney and Melbourne" 
         class="sponsor">
</a>

## Past meetups 

{% for post in site.posts %}
{% if post.categories contains "meetup" and post.categories contains "sydney" %}
* <a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}{% if post.summary %} - {{ post.summary }}{% endif %}</a>
{% endif %}
{% endfor %}


---
layout: page
title: Brisbane 
menu: yes
---

## Contact 

* Twitter: [@sectalks_BNE](https://twitter.com/sectalks_BNE)
* Email: [brisbane@sectalks.org](mailto:brisbane@sectalks.org)
* Meetup: [http://www.meetup.com/SecTalks-Brisbane/](http://www.meetup.com/SecTalks-Brisbane/)

## Organising team 

* [Bull](https://twitter.com/RobertWinkel) 
* [Michael Gianarakis](https://twitter.com/mgianarakis) 

## Date & Time 

Forth Thursday of each month at 6pm.

For details of each session visit our [Meetup page](http://www.meetup.com/SecTalks-Brisbane/)

## Location 

Brisbane. The specific location will be revealed to members via the members' mailing list. 

## Upcoming meetup 

Details of upcoming session will be sent to members mailing list 
and also posted on our [Meetup group](http://www.meetup.com/SecTalks-Brisbane/).

## How to join

We always like to get more awesome people in.
Simply join the [Meetup group](http://www.meetup.com/SecTalks-Brisbane/),
and RSVP to the sessions that you want to attend.
You may also want to follow [@sectalks_BNE](https://twitter.com/sectalks_BNE) on Twitter.

### But I am new to security, can I still join?

YES! SecTalks is always open to anyone who is keen to learn hands-on infosec.
There will be people willing to mentor you on the day, and you'll be solving CTF's in no time flat.

### I am l33t!

If you are l33t, you may want to solve our l33t entry challenge to get yourself on our *l33t mailing list*. There is no harm, trying it.

#### What is the l33t entry challenge?

1. Follow [@sectalks_BNE](https://twitter.com/sectalks_BNE) on Twitter.
1. Tweet "@sectalks_BNE, V nz y33g...".
1. The challenge details will be DMed to you.
1. Have fun and email us the flag.

*Note: Twitter doesn't allow for DM, if you don't follow @sectalks_BNE.*

## Past meetups 

{% for post in site.posts %}
{% if post.categories contains "meetup" and post.categories contains "brisbane" %}
* <a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}{% if post.summary %} - {{ post.summary }}{% endif %}</a>
{% endif %}
{% endfor %}

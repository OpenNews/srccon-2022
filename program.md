---
section: program
permalink: /program/
title: Our Program
---

# Our Program

The SRCCON program is [hands-on and participatory](/attendees/), full of collaborative workshops and conversations, a series of thematic talks, and peer-led social activities. We'll continue to add details here as we get closer to SRCCON!

## Talks

We'll have three talks on our program this year—one each day, also available to watch in advance. Talks at SRCCON help create a foundation we can build on during conversations throughout the week.

_More details about each talk coming soon!_

## Sessions 

Thank you to everyone who submitted proposals, and to the [community panel](#community-review) that helped us during the review process! We have a few session details and facilitators still to confirm, and some descriptions here may evolve between now and SRCCON. Our conference schedule this year will include the sessions below.

<div class="session-proposal-list">{% comment %}The one-line if statement below is ugly but prevents massive whitespace in the template{% endcomment %}
{% for proposal in site.data.sessions %}
    <div class="session-proposal" id="proposal-{{ proposal.id }}">
        <h4 class="session-title"><a href="#proposal-{{ proposal.id }}">{{ proposal.title }}</a></h4>
        {% if proposal.facilitators %}<p class="facilitator">Facilitated by {{ proposal.facilitators }}</p>{% endif %}
        <p class="session-description">{{ proposal.description | markdownify }}</p>
    </div>
{% endfor %}
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script src="/media/js/listfilter.min.js"></script>
<script>
var filter = ListFilter({
    listContainer: '.session-proposal-list',
    filterItemClass: '.session-proposal'
});
</script>

<span id="community-review"></span>

## Community reviewers

We'd also like to thank the folks who helped us select this amazing slate of sessions! Each year's program review includes a panel of community members with a range of experiences and perspectives to make sure SRCCON has sessions that respond to your needs.

Thank you, community reviewers!

* Albert Sun
* Allie Kanik
* Darryl Holliday
* Lish Savson

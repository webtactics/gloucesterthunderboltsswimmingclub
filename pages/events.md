---
layout: layouts/grid-default.njk
title: GTSC Events & Swim NSW Meets
description: Gloucester Thunderbolts Swimming Club runs from mid Oct until early April on Thursday evenings at 6.00pm at the Gloucester Pool Complex.  All ages and abilities are welcome.
section: events
class: events
date: 2025-02-18
permalink: /events/
metadata: 
  title: Gloucester Thunderbolts Swimming Club Events and Swim NSW Meets
eleventyNavigation:
  key: Events
  order: 2
---

<h3>Gloucester Thunderbolts Swimming Club, Club Night's for the 2026-27 Season run from Thursday, October 15, 2026 until early April, 2027.</h3>

<h4>Club night's are held on on Thursday evenings at 6.00pm at the <a href="https://maps.app.goo.gl/GKgamrDkqvASyJ429" target="_blank" alt="Gloucester Pool Complex" title="Gloucester Pool Complex">Gloucester Pool Complex</a>.</h4>

<h4>All ages and abilities are welcome.</h4>

<div class="padtop3rem"></div>

<!--- 2026-27 Season Events --->
<div class="postlist-section-wrapper fade-in">	
   <h2 class="heading-text">2026-27 Season Events</h2>
<div class="resultswrapper">
	{%- set postslist = collections['2026-27-Season'] | reverse -%} 
	{% include "components/postlist/postslist-events.njk" %}
</div>
</div>
<!--- End 2026-27 Season Events --->



<div class="eightypercentborder"></div>

<!--- 2026 Winter Events --->
<div class="postlist-section-wrapper fade-in">	
   <h2 class="heading-text">2026 Winter Events</h2>
<div class="resultswrapper">
	{%- set postslist = collections['2026-Winter'] -%} 
	{% include "components/postlist/postslist-events.njk" %}
</div>
</div>
<!--- End 2026 Winter Events --->


<div class="linkwrapper"><a class="resultspdf" href="/events/results/" title="All Season Results" alt="All Season Results">For all Results &gt;</a></div>
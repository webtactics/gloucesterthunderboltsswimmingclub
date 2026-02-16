---
layout: layouts/grid-default.njk
title: GTSC Club Swimming Nights
class: events clubnights
description: Gloucester Thunderbolts Swimming Club runs from mid Oct until April on Thursday evenings at the Gloucester Pool Complex. 
date: 2024-10-25


permalink: /events/club-nights/
eleventyNavigation:
  key: GTSC Club Nights
  parent: Events
  order: 1
---
## Gloucester Thunderbolts Swimming Club runs from mid Oct until April on Thursday evenings at the Gloucester Pool Complex. 

### We aim for a 6pm start and generally finish before 8pm.

#### All ages and abilities are welcome.
<div class="padtop3rem"></div>

<div class="postlist-section-wrapper fade-in">	
   <h2 class="heading-text">2025-26 Season GTSC Club Night Events</h2>
<div class="resultswrapper">
	{%- set postslist = collections['2025-26-Season-GTSC'] | reverse -%} 
	{% include "components/postlist/postslist-events.njk" %}
</div>
</div>

<div class="linkwrapper"><a class="resultspdf" href="/events/results/" title="Club Night Results" alt="Club Night Results">For all Club Night Results &gt;</a></div>
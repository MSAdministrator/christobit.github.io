---
title: "Undone Work"
date: 2018-08-25T11:48:28-05:00
author: "christobit"
---

_A discussion on how "undone work" is handled in Scrum._

## What is "Undone" Work?

Imagine this scenario:

> At the Sprint Planning, the Development team identifies 5 PBIs (Product Backlog Items) that they would like to commit to. They place these in the Sprint Backlog and commit to the items for the Sprint. As the Sprint goes on, there are some issues along the way. At the end of the Sprint, one of the items does not get completed since it doesn't match the DoD (Definition of Done). Let's say there still needs to be testing performed on the PBI.

What happens a the end of the Sprint to that incomplete, or "undone" PBI?

> Do we place that item at the top of the next Sprint?

> Do we split the item into necessary components because it was too big?

> When do we split the item? Before or after we end the Sprint?

There are a lot of unanswered questions and this gets into the conversation of estimation principles, leaving *a lot* of arguments up in the air on the topic.

For example, some say:

1. Unfinished/UnDone items are placed back on the product backlog 
2. The Product Owner re-orders the backlog. Typically unfinished items end up at the top, but not always.
3. **Do not** resize the items to represent only the remaining undone work. 
4. **Do not** split the story to represent what was worked on and what wasn't. An item is done or it isn't. There's no i-between. 
5. **Do not** include any effort spent on the unfinished items in the velocity calculation of the current sprint. Velocity is a reflection of your rate of completion not your effort expended.

Some say that you *do* re-estimate the work that's remaining, because:

1. You want your backlog to be transparent.
2. Velocity measures how much done software the team delivers in a sprint, so assuming the item will be completed the next sprint, only the left over part counts in the velocity of the next sprint
3. You want your product owner to easily assess the ROI of completing the undone item

What's the Scrum Guide say about this?

> NOTHING.

These are all conventions. The Scrum Guide says nothing about the words `undone` or `unfinished`. There is, however, a mention of *incomplete* PBIs:

> When a Sprint is cancelled, any completed and “Done” Product Backlog items are reviewed. If part of the work is potentially releasable, the Product Owner typically accepts it. **All incomplete Product Backlog Items** are re-estimated and put back on the Product Backlog. The work done on them depreciates quickly and must be frequently re-estimated.

This is the *only* time `incomplete` is mentioned. In fact earlier versions of the Scrum Guide *did* have this notion of *Undone Work*, but it was removed in later iterations because of the controversy and confusion the notion caused.

The moral of the story here is that it's up to us - the Scrum Team - to decide what we want to do with this work. There are no hard and fast rules on this. We have to weigh a couple of things when we decide what to do with work:

1. How will our decision affect Backlog transparency?
  - In other words, will this accurately reflect what is going on with the Product if we make this decision?
2. How will this affect future work estimates?
  - How much do we value historical data in a ticket over accurate velocity mapping?

Remember: the estimate are the responsibility of the Development team to associate to work. 

Why? Because it is the Development team's responsibility to show their work and progress. The Scrum Master (and Product Owner) should assist as needed.

This goes past just estimating work - it also includes re-estimating work that may have been estimated incorrectly, if needed: it is incredibly valuable information to see a re-estimation of work in a Sprint Report.

In conclusion, there's no *real* answer, but there are for sure best practices. What do we go with? What works best for us.
---
author: "Kyle Jones"
date_published: "April 20, 2025"
date_exported_from_medium: "November 10, 2025"
canonical_link: "https://medium.com/@kyle-t-jones/modernizing-supply-chains-with-aws-lessons-from-woodside-energy-7ac72d23c79e"
---

# Modernizing Supply Chains with AWS: Lessons from Woodside Energy Supply chain reliability is mission-critical. Delays in material
delivery don't just affect schedules --- they can halt production, trigger...

### Modernizing Supply Chains with AWS: Lessons from Woodside Energy
Supply chain reliability is mission-critical. Delays in material delivery don't just affect schedules --- they can halt production, trigger cascading safety issues, or delay urgent maintenance on critical infrastructure. Woodside Energy, a global energy company headquartered in Australia, faced these challenges across one of the most remote and logistically demanding footprints in the industry.

From offshore gas platforms to inland LNG hubs, Woodside's operations depend on a finely tuned orchestration of parts, people, and plans. The distance between their largest warehouse in Perth and production sites like Karratha or Ngujima-Yin isn't trivial. Delivering a single part to a platform can involve days of land and sea transport, with no room for error.

Historically, knowing where a part was --- or when it would arrive --- meant combing through disconnected systems and chasing updates. That's not sustainable in a business that depends on operational continuity. The shift came when Woodside adopted AWS Supply Chain.

### Fragmentation, Delay, and Guesswork
Before AWS, Woodside's maintenance teams worked with limited visibility into inbound parts. Procurement operated in parallel. Logistics followed behind. The problem wasn't just the physical complexity of operating in remote zones. It was a lack of shared data across functions. Each team worked from different systems, and decisions about work orders were made without a clear view of material status.

As [Tracy Simpson, VP of Supply Chain at Woodside, explained at AWS re:Invent 2024](https://aws.amazon.com/awstv/watch/cb73aaaecef/):

> *"These circumstances have historically made it really challenging for
> us to easily know where in the supply chain our materials are and
> precisely when they're gonna arrive at site."*

The challenge wasn't about scale --- it was about visibility. Tracy added,

> *"Like many others... we've also got system integration challenges to
> access or make relevant data very easily and quickly available."*

That lack of transparency meant over-ordering, deferred work, and reactive planning. It also tied up working capital in inventory buffers, just in case something slipped through the cracks.

### AWS Supply Chain and the Power of Real-Time Visibility
AWS Supply Chain launched in 2023 with a clear premise: unify supply chain data across fragmented systems, and then use machine learning to surface insights, forecast disruptions, and automate rebalancing. Woodside became one of the first companies to put it to the test.

At the core of the solution is a supply chain data lake --- a centralized environment where information from ERPs, warehouse systems, purchase orders, and logistics tracking can be ingested, harmonized, and analyzed. AWS uses pretrained ML models to extract and standardize the data, creating a canonical format that makes sense regardless of source.

> *"We help extracting this data, understanding this data, transforming
> this information, harmonizing all this data into our canonical data
> model," said Diego Pantoja-Navajas, VP of AWS Supply Chain.*

Woodside contributed directly to the development of the Order Insights module, which is now part of AWS Supply Chain's core offering. The tool allows any user --- whether they're in procurement, planning, or logistics --- to see the real-time status of all materials tied to a work order. It flags items that are at risk of delay and provides recommendations for mitigation.

The user interface is clean, familiar, and flexible. Tracy noted that the look and feel of the tool reminded the team of familiar consumer experiences:

> *"The way the control tower is being designed is similar like
> Amazon... The control tower is not a shopping tool, but the feel and
> look is similar."*

### A Game Changer for Maintenance Planning
In the energy sector, maintenance isn't a nice-to-have --- it's a regulatory requirement, a safety imperative, and a key to uptime. That's what made Order Insights transformative. For the first time, maintenance planners could track the full journey of a part. They could see whether it had been ordered, shipped, staged, or delayed. They didn't have to ask. They didn't have to guess.

The result: less time chasing parts, more time doing the work. Maintenance professionals no longer needed to dig through systems to find delays. They could filter for what was late or at risk, then click directly into the cause.

> *"The beauty of these simple features is that they help our teams very
> quickly identify the issues that are either occurring right now or
> have the potential to become a problem in the future... and it's all
> done at a click of a button," said Tracy.*

### From Collaboration to Control: Breaking Down Silos
Woodside's deployment of AWS Supply Chain did more than modernize technology --- it restructured how the organization worked. Supply chain coordination, especially in utilities, isn't a single department's job. It requires planning, logistics, finance, and procurement to operate as one unit. That's difficult when each function runs on its own tools and timelines.

The new workflow created shared visibility. Everyone worked from the same data, filtered for role-specific context. As Tracy explained:

> *"Whilst you've just played the role of a maintenance planner, you
> could easily have been a logistician or a procurement professional.
> The beauty is that all of the data is actually arranged in a way that
> makes most sense for the individual who's taking a look at it."*

That meant fewer surprises, fewer miscommunications, and faster time-to-resolution. Decisions could be logged, tracked, and audited, all from within the application.

### From Use Case to Platform
What began as a tactical improvement --- a way to track parts for maintenance --- has evolved into a broader digital transformation initiative. Woodside now sees AWS Supply Chain not just as a solution, but as a foundation. They are expanding its use across more sites and integrating it with supplier networks for end-to-end traceability.

Security and connectivity were addressed early. Diego said:

> *"We were able to launch AWS PrivateLink and created a connection
> between our accounts and your systems... creating a very secure point,
> end-to-end tunnel."*

That enabled Woodside to integrate with internal systems without exposing sensitive endpoints, a critical requirement for power and utilities operating in regulated environments.

### The Role of Generative AI
Woodside is also preparing to adopt generative AI features inside AWS Supply Chain. AWS is building capabilities that allow users to ask natural language questions and get contextual, data-driven answers. Diego said:

> *"We're helping our companies and customers to really get access to
> that information... so you guys can leverage gen AI to be able to
> answer questions that are needed for your operation to be more
> efficient."*

These capabilities don't just summarize. They model, simulate, and recommend. Whether it's identifying bottlenecks or optimizing inventory against lead times, generative AI helps teams make decisions faster and with more confidence.

### Why This Matters for the Power and Utilities Sector
The challenges Woodside faced --- geographic complexity, system fragmentation, reactive maintenance --- are common across the utility sector. What makes their story instructive is not just the technology they adopted, but the operational results they achieved.

> *"We believe we can generate further efficiencies by delivering needed
> parts quicker, cheaper and more predictably," said Tracy. That's not a
> hypothesis --- it's a roadmap.*

Utilities don't have the luxury of downtime. Infrastructure must be maintained continuously, even when parts are delayed or global logistics fail. AWS Supply Chain gives operators a way to see what's coming, plan around it, and act before problems escalate.

### From Reactive to Resilient
Woodside's adoption of AWS Supply Chain shows what's possible when digital tools meet operational urgency. Their supply chain is now more visible, more collaborative, and more responsive. As the industry moves toward automation, decarbonization, and distributed infrastructure, these capabilities won't be optional. They will be foundational.

"Our teams are really excited about what's coming next," said Tracy. And they should be. Because what started as a maintenance dashboard has grown into a platform for long-term resilience, performance, and insight.

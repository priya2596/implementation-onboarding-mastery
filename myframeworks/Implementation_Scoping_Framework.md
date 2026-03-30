# The Promise Problem

**Why most implementations fail at scoping, not execution — and five principles to change that.**

by Priyanka Ranganathan

---

## The Problem Nobody Talks About

McKinsey and the University of Oxford studied 5,400 large IT projects and found that on average they run **45% over budget**, **7% over time**, and deliver **56% less value than predicted** ([source](https://www.mckinsey.com/capabilities/tech-and-ai/our-insights/delivering-large-scale-it-projects-on-time-on-budget-and-on-value)).

The Standish Group's CHAOS Report — which has tracked software project outcomes since 1994 found that only **31% of IT projects succeed**. 50% are challenged. 19% fail completely ([source](https://www.standishgroup.com)).

These are not failures of intent. Nobody walks into an implementation planning to overspend or underdeliver. The teams are capable. The technology works. The business need is real.

So why does this keep happening?

In my experience across enterprise SaaS implementations and digital transformations, the answer is almost always the same: **the failure was already baked in at scoping.**

Early conversations are naturally optimistic. There is genuine excitement about what is possible. The business case is compelling. Everyone is motivated. But optimism without rigour creates a gap between what was promised and what is actually deliverable that only becomes visible months later, when it is expensive and difficult to close.

This framework is built from five scoping principles I have observed matter most. They apply whether you are implementing a SaaS platform, running a digital transformation, or onboarding enterprise customers at scale.

---

## The Five Scoping Principles

---

### 1. Start with the Why

Before timelines. Before technical discussions. Before anything else.

Understand what is driving this project why this organisation wants to change, and why now. Is this a regulatory requirement? A competitive pressure? A leadership mandate? An operational pain that has become unsustainable?

The answer to this question shapes everything downstream: priorities, urgency, what can be phased, and what must be protected when pressure builds. Without it, you are designing a plan without understanding what it is actually supposed to achieve.

**Questions to ask at scoping:**
- What is the core problem this project is solving?
- Why is this being prioritised now, and not six months ago or six months from now?
- What does success look like in twelve months — not at go-live, but twelve months after?
- What happens if this project is delayed by three months?

---

### 2. Map the Current State Before Designing the Future State

It is tempting to jump straight into designing the solution. But you cannot build an accurate plan for a future state without first understanding the present one.

This means mapping how the organisation actually operates today the tools they use, how data flows between systems, how reporting works, who owns what, how many regions or countries are involved, whether data is stored in multiple languages or currencies, and what the known gaps and inconsistencies already are.

This step is frequently rushed or skipped entirely in favour of moving quickly. The cost of that decision almost always appears later in the form of integration surprises, data inconsistencies, and scope that turns out to be far larger than originally estimated.

**Questions to ask at scoping:**
- What systems are currently in use, and how do they connect to each other?
- How is data currently collected, stored, and reported?
- How many regions, countries, languages, or currencies are involved?
- Where are the known data quality issues today?
- What manual workarounds exist that the new system will need to account for?

---

### 3. Align the Delivery Team Before Committing to the Client

Timelines and deliverables are often agreed between senior stakeholders before the people who will actually do the work have been consulted. This is one of the most common and most avoidable scoping failures.

The team that will build and deliver the implementation analysts, technical leads, project managers, onboarding specialists must be part of the scoping conversation. Not to attend the executive alignment meeting, but to have their own internal discussion: Is this achievable in the proposed timeline? What risks do we see that are not yet visible to the client? What do we need to know before we can commit?

A commitment made without this step is not a plan. It is an assumption.

**Questions to ask internally before committing:**
- Has every person who will work on this project been briefed on the context and the client?
- Does the delivery team believe the proposed timeline is realistic?
- What risks does the team see that have not yet been surfaced?
- Are there dependencies — resourcing, technical, organisational that could affect delivery?

---

### 4. Audit Data Quality Before It Becomes a Delivery Risk

Data quality issues discovered during implementation are expensive, disruptive, and demoralising. Discovered at scoping, they are manageable.

The most common technical failure mode in complex implementations is not a technology problem it is a data problem that nobody investigated before the project started. Source data that is incomplete, inconsistent, or stored in incompatible formats. Mapping assumptions that seemed reasonable at scoping but broke against real data. Patches applied to fix one problem that create three more.

When the numbers in the new system do not match the numbers in the old system, trust in the entire implementation collapses regardless of how well everything else was delivered. A structured data audit at scoping is not optional. It is the foundation everything else is built on.

**Questions to ask at scoping:**
- What is the quality of the source data we will be working with?
- Have the key data fields been validated against actual records, not just documentation?
- Where are the known data gaps, inconsistencies, or legacy issues?
- What assumptions are we making about data that we have not yet verified?
- If the data is not clean, what is the plan and timeline to address that before go-live?

---

### 5. Design for Adoption from Day One, Not from Go-Live

The real measure of a successful implementation is whether the people who need to use the new system are actually using it confidently, independently, and in a way that delivers the value the project was designed to create. That outcome is not achieved by scheduling training in the final two weeks before go-live. It is designed from the start.

Change management, user readiness, and adoption planning are scoping decisions. Who needs to change how they work? What is the gap between how they work today and how they will need to work after go-live? What support do they need, and over what timeframe? What does success look like for an end user, not just for a project manager?

When these questions are not answered at scoping, adoption is treated as a go-live task. Users go live without being ready. Pressure to deliver results pushes them back to familiar tools. The new system becomes an additional burden rather than a replacement for the old one.

**Questions to ask at scoping:**
- Who are the end users, and what will change about how they work day-to-day?
- What is the change management plan, and who owns it?
- How will user readiness be measured before go-live?
- What support will be available after go-live, and for how long?
- What does successful adoption look like six months after go-live?

---

## Using This Framework

These five principles are not a checklist to complete once and file away. They are a set of conversations to have with the client, with the delivery team, and with yourself before a single timeline is committed to or a single promise is made.

The goal is not to slow down the excitement of starting a new project. The goal is to make sure that excitement is grounded in a realistic shared understanding of what the project actually involves.

Projects that invest in honest scoping take longer to start. They also take less time to finish and they are far more likely to deliver what they promised.

---

## About This Framework

This framework was developed from experience across enterprise SaaS implementations and digital transformations, working with organisations across procurement, finance, real estate, and analytics.

It is a living document. If you have observations, additions, or pushback from your own experience, contributions are welcome.

---

*Priyanka Ranganathan — Implementation & Product · [LinkedIn](http://www.linkedin.com/in/priyankaranganathan359569) · [GitHub](https://github.com/priya2596/implementation-onboarding-mastery)*


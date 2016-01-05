# Product Design Sprint

> "Most people make the mistake of thinking design is what it looks like. People think it's this veneer — that the designers are handed this box and told, 'Make it look good!' That's not what we think design is. It's not just what it looks like and feels like. Design is how it works." - Steve Jobs

[Product Design Sprints](http://robots.thoughtbot.com/the-product-design-sprint), an invention of [Google Ventures' design team](http://www.gv.com/design/), are 5-phase exercises intended to improve the chances of [making something people want](http://paulgraham.com/good.html). We want to turn false confidence into validated confidence before beginning an expensive build. Or, we want to dodge bullets by learning we shouldn't begin the expensive build at all.

Sprints are useful starting points when kicking off a new product or workflow, as well as solving problems with an existing product. They typically last 5 days but we have done them in less time. We get as many stakeholders and expertises in the room as we can.

Product design sprints are test-driven design.

<figure>![Sprint Phases](images/sprint-phases.png)

<figcaption>Sprint Phases</figcaption>

</figure>

## Prep Work

Before the sprint, our clients schedule 5 real humans for the tests we'll do in the last phase. They know their users better than we do.

They also gather research from sources such as:

*   [Quora](http://quora.com/)
*   [Google Analytics](http://analytics.google.com)
*   [Adwords Keyword Planner](https://adwords.google.com/ko/KeywordPlanner/Home)

We may also do some (paid) prep-work:

*   Schedule and run [user interviews](http://www.nngroup.com/articles/interviewing-users/).
*   Deploy a short [survey](http://www.google.com/insights/consumersurveys/use_cases) whose results we can review in the first phase.

We typically order breakfast for the first day to make it feel special but don't order lunch for each day of the sprint. For both the sprints and normal days, we believe it's important to not have "working lunches", instead breaking from work for a short time to rest the brain, maybe get some fresh air, and interact with teammates and clients.

## Understand

The exercises in this phase help us understand and empathize with the users' life (consumer software) or work (business software) needs.

Throughout the phase, people take notes, often on sticky notes that they stick to the walls of the room.

We start with "pitch practice", where the client pitches their product like they would to investors. This helps us identify the user, their problem, and the job they are hiring the product to do. It also begins documenting the [vocabulary used in the domain](http://martinfowler.com/bliki/UbiquitousLanguage.html).

We then review research from Quora, Analytics, AdWords Keyword Planner, interviews, and surveys. This helps us understand users' motivation, the marketing funnel, and the size of target markets.

Lastly, we sketch what the rest of the sprint will focus on: the critical path for the software. At this point, we try to keep this high-level and as light on implementation details as possible. A great question to help generate the critical path is:

> [What job is the user hiring the product to do?](http://www.youtube.com/watch?v=f84LymEs67Y)

<figure>![Critical Path](images/criticalpath_small.jpg)

<figcaption>Critical Path</figcaption>

</figure>

We will edit the critical path as we move through the phases.

## Diverge

The exercises in this phase help us exhaust our imaginations for potential solutions that meet the users' needs.

Before this phase, the team naturally walks around the room reviewing the walls, covered in the critical path and lots of sticky notes.

We start with "pitch practice" again, comparing to the critical path.

We then have each person individually sketch 10+ [user flows](https://signalvnoise.com/posts/1926-a-shorthand-for-designing-ui-flows) and user interfaces. We ask people to include the sources where the customer will come from: Twitter? A blog post? AdWords? Automated suggestions? Drip email? Referral from a friend? Push notification?

Should the product become realized, these sources should eventually be measured in [Google Analytics' "Acquisition Channels" report](http://analytics.blogspot.com/2013/10/new-acquisitions-reporting-channels.html):

<figure>![Acquisition Channels](images/acquisition-channels_small.jpg)

<figcaption>Acquisition Channels</figcaption>

</figure>

We then put those sketches on the wall and begin a silent critique, observing and putting [dot stickers](http://www.amazon.com/dp/B002M3SBM2) on different parts of the flows and user interfaces that we like. This helps visually identify the best ideas.

We then do a group critique, three minutes per idea. The group explains their dots. The author can then add any extra commentary. We don't shoot down any ideas or start winnowing. This voting process helps avoid long discussions and design-by-committee.

Lastly, we do a "super vote" with larger, red dot stickers. The CEO or other product owner will place a single "super vote" on what they think is the best idea. This helps us reflect the reality of how their organization makes decisions and affirm their ultimate authority.

Our experience has been that this phase is mentally exhausting. We recommend ending early and sending people home to re-charge their batteries.

## Converge

The exercises in this phase force us to stop generating new solutions, converge on the best, and write the test for the prototype.

First, we identify assumptions we're making in the best ideas. We list all assumptions about users' motivations, the business model, our ability to acquire users, and our ability to implement the solution within budget. This helps eliminate some options.

<figure>![Assumptions](images/assumptions_small.jpg)

<figcaption>Assumptions</figcaption>

</figure>

We then look for conflicts in the remaining sticky notes, user flows, and user interfaces: ideas that aim to solve the same problem in different ways. We eliminate solutions that can't be pursued currently.

We then decide whether we're creating one prototype ("best shot") or multiple ("battle royale"). Multiple prototypes are more initial work but may reveal more dead ends and help us dodge more bullets without running follow-on sprints.

We then storyboard each prototype. This is a comic book-style story of our customer moving through the critical path.

<figure>![Storyboard](images/storyboard_small.jpg)

<figcaption>Storyboard</figcaption>

</figure>

Lastly, we create the testing script in Google Docs and put the scoreboard on the wall of the observation room. The script is based on the storyboard and the scoreboard will be used to record the results of the test. This helps us be very explicit about what we're trying to learn.

## Prototype

After another pitch practice to rally the troops, there are no exercises in this phase. It is entirely focused on building the right prototype(s) with just the right amount of fidelity to generate useful test results.

For the entire phase, we ask our clients to write copy text in Google Docs. They write [real text, not lorem ipsum](http://gettingreal.37signals.com/ch11_Use_Real_Words.php), in order to test user understanding and enthusiasm. This text is also useful later for tweets, press, ad copy, landing pages, etc.

While our clients are busy getting communication polished, we are heads-down prototyping. We use different tools depending on the designer and the project.

For web app prototypes, some good options are:

*   [Squarespace](http://www.squarespace.com) templates
*   [Bourbon](http://bourbon.io) + [Neat](http://neat.bourbon.io) + [Bitters](http://bitters.bourbon.io) locally
*   [Invision](http://www.invisionapp.com)

For mobile app prototypes, some good options are:

*   [Flinto](https://www.flinto.com) + [Sketch](https://itunes.apple.com/us/app/sketch/id402476602?mt=12)
*   [Prototyping on Paper](https://popapp.in/)

Don't try to learn these tools during the sprint. Get familiar with them during investment time. During the sprint, use one that you've mastered.

## Test and Learn

Finally, we interview 5 users to test our understanding of them, their context, and our prototype. This is not a usability test. We begin the conversation as an interview before showing them the prototype.

One of our designers interviews each user. We set them up in an interview room with video and audio streaming to the observation, where the rest of the stakeholders are watching, discussing, and recording answers on the scoreboard.

Good questions are open-ended to allow users to tell stories.

> "Could you tell us about a time you donated to a non-profit?"

Don't lead users to an expected answer.

> "Would you donate money to a public school if you could?"

Don't close the conversation.

> "Have you donated money to an organization within the last week?"

For a new product, it's unlikely that any team will nail it their first sprint. The most likely outcome is that we'll want to run a follow-on sprint starting at Diverge or Converge and test again with a new users.

After one or two sprints, we typically have many assumptions validated, a clear critical path established, and are ready to begin coding a first version to release to a wider audience.

For web apps, we can typically ship a first version in 4-6 weeks. For mobile apps, we can typically ship a beta via [HockeyApp](http://hockeyapp.net/) in 6-8 weeks and ship to the App Store in 8-10 weeks.

Given those timelines, spending an extra 2-5 days doing a second or even third truncated product design sprint is worth the opportunity cost of spending 4x-10x more time and money to learn we bombed.

Another outcome is that there's no clear user pain, or the business model is murky, or everything we thought we knew was proven wrong. That's an emotional blow, but a success. Time and money were saved.

We end the phase with a plan for moving forward.

# Building Trust Through Project Estimates

Some people will tell you estimating work is a fool’s errand. It can’t be done. Any successes are just flukes. It’s a waste of time. I’m here to tell you that you can accurately estimate work. You can estimate work of any size or ambiguity. I know because I’ve done it for years. It’s my most effective tool for building a trusted team.

### How Accurate Can We Get?

Very accurate. Like any skill, you can get extremely good at estimating work if you practice, reflect, address your shortcomings, and practice again until you reach a reasonable goal. Let’s set that goal now:

* Estimate multi-year projects to within a quarter
* Estimate multi-month projects to within a month
* Estimate multi-week projects to within a week
* Estimate multi-day projects to within a day.

How can you do it? There are many strategies I use. Read on for a few of my best.

### Take Your Time

When I assign a member of my team to estimate a project, I don’t expect an answer right away. Estimating takes time. I give them the requirements we know about and walk them through the project, answering any questions. Then I give the team member time to work on the estimate. They should go back and estimate the work needed for each requirement line by line. For big ambiguous projects, this could take a couple of days or even weeks. For example, if we are building a completely new type of web app, the engineer may need to go look at similar web apps in the market and perhaps even sign up for a trial version. They may need to investigate whether a particular technology can be purchased for a reasonable price or if we’ll need to build it ourselves. Time is needed.

If an accurate estimate is important, do it yourself too. Duplicate the work of the engineer you assigned to get the estimate. Compare numbers and see where there are discrepancies. You will end up with a better estimate and may resolve some assumed ambiguities as well.

**Lesson 1: If an accurate estimate really matters, it’s worth the wait and effort to get it.**

### Remember All the Parts

After estimating the stakeholder requirements line by line, the work has just begun. The biggest single item that "delays" projects is engineering process. I put "delay" in quotes because it was always part of the project, but we just forget to include it in our estimate.

Here are a few items you may need to include in your estimate:

* Design
* Technology comparisons
* Security
* Performance
* Refactoring
* Integration testing, pen testing, user testing, etc.
* Scaling

This is just a start. What are the unique needs of your company and tech stack? What is the scale of the project? If you are coaching someone about estimating task-level work, remind them about code reviews and unit tests. If you are coaching someone about estimating a full product release, remind them about integrating feedback from the beta release.

**Lesson 2: Make sure all parts of the project are included in the estimate, including engineering process.**

### Measure Ambiguity

The second preventable thing that delays projects is known ambiguity. This applies any time you are doing something new, no matter how small. Whether it’s a new technology or a new way of carrying out work, doing something the first time introduces learning delays. Let’s look at some examples.

Let’s say your company has always used a relational database, but you’ve identified the need for a NoSQL database in the project. Even if the responsible engineer is an expert in NoSQL DBs, there are going to be a lot of unknowns about integrating one into your particular tech stack. Or perhaps you are using AI, but nobody has used AI in a product before. For both cases, there is an amount of ambiguity in how the work will be carried out. To handle this, use a multiplier on the line item. In the DB example, a 1.5 multiplier may be sufficient. For the AI example, you may need a 2 or 3x multiplier.

What if it ends up being easy? What if we finish in the time we originally estimated? This does happen, and congratulations if it does! But it’s rare. And if the project is big enough, the time will likely be taken up somewhere else. In any case, I find that explainable over-estimates are the best of the miscalculation problems. An under-estimate, whether explainable or not, is a problem for coordinating work between teams and coordinating a release. An over-estimate that you can’t explain breaks trust. It invites scrutiny and tells other teams that you care more about yourself than the company. However, if you over-estimate due to an ambiguity, you can explain this. For example: “We didn’t know how integrating a NoSQL DB would work with our codebase. Turns out it was easier than expected, which pulled our estimate forward. We are excited that this gives us extra time to work on xyz.” The other nice thing about ambiguity multipliers is that these are often the things you tackle first. Early in the project you’ll get a feel for whether you misunderstood the time needed.

There is a second type of ambiguity - skill in estimating. Estimating work is a skill that takes time to develop. A junior engineer will often be worse at this than someone who has had time to practice. I almost always multiply the final estimate by a fixed number based on the skill of the person who created the estimate. I’ve used multipliers from 1.5 for an experienced team member to 3 for someone who was new to estimating.

**Lesson 3: Account for ambiguity on every requirement.**

### Building Trust Through Estimates

I said earlier that making accurate estimates is my most effective tool for building a trusted team. It smooths the relationship between product and engineering, engineering and leadership, and between you and your own boss. Lets look at some anti-patterns to explain why.

**Anti-Pattern 1: Under-Estimating Work**

We’ve all been burned by this before. You give an estimate that sounds reasonable, but ends up being too short. Other teams that were depending on you are stuck with nothing to do. The customer is upset. Your team is working overtime. Partner teams drop their work to bail you out. There are post-mortems to explain each item that slowed down the work. No one likes being stuck in this situation.

In this situation, trust isn’t actually harmed that much. Why? Because people know that estimating work is hard and they saw that you made an honest mistake. They might be upset with you and assume your work will take longer next time, but they also saw that you did your best on the estimate and were simply wrong. It can happen to anybody.

**Anti-Pattern 2: Padding Your Estimates**

After being burned by the under-estimate, you pad your estimate next time. And you pad it a lot. You think the project will take 2 months, so you tell your stakeholder 6 months. The work gets done in 4, so you have your team work on some engineering tasks that have been on the back burner for a while. The stakeholder asks for the project at the 6 month mark, you hand it to them, and everybody is happy. Right?

Maybe at first. And maybe this will work for you for a while. But at some point, someone is going to miss being first-to-market or will be beaten out by a competitor. There will be an investigation into what took so long and your padding will be discovered. This is where trust breaks.

This time, it wasn’t an honest mistake. People feel lied to. And maybe the company missed opportunities. Your reputation is hurt. The hard part? This is so wide-spread that software engineers as a whole have a hurt reputation. But we can change this!

**Making Accurate Estimates**

Let’s say you have built a skill for estimating. Not only that, you have built a reputation as someone who estimates accurately. What does that change?

* If you say something can’t be done in a certain amount of time, people believe you
* Your team trusts that overtime work will be rare
* The conversation turns from “how can you do it faster” to “what can we cut to make the deadline”
* You are much more likely to get the help and resources you ask for
* Deadlines become a collaboration rather than a command

Ultimately, your team becomes trusted to do what they say they will do.

### One Final Tip: Measure Confidence

When you put in the effort for a good, accurate estimate, it becomes a useful tool for communication. And I recommend over-communicating. For estimates, that means adding in a confidence measurement. I’ll explain this with examples.

**High Confidence:** You are building a new product that will launch at your company’s yearly conference. That means you need to have very high confidence in the finish date for the features that will be marketed. When I make a high confidence estimate, I ask myself if I would be willing to stake my professional reputation on it, even assuming we plan no overtime to make it happen, and I would be willing to (hypothetically) schedule a vacation on launch week. The estimate is only high confidence if all the answers are yes. This helps you communicate to the marketing team where they need to create a “coming soon” message and where they have the freedom to plan for a live demo.

**Medium Confidence:** Let’s say an internal team is depending on your release date. They have 2 months of work before they will be blocked on your team. Rather than starting and stopping their work, they prefer to start once you are reasonably confident you have 2 months of work remaining. In these cases, you can start with lower confidence because you are able to communicate frequently with your stakeholders. Statements like “I am 75% confident we have 2 months of work remaining” will lead to some very good discussions. The other team may ask what would make you more confident, they may ask for the best and worst scenarios, and they may simply be fine with that level of confidence. It becomes a great communication tool.

**Low Confidence:** I try to avoid low confidence estimates, but they are a useful communication tool when you need them. “We are guessing it will take 2 months, but it’s a very rough guess. It could take between 1 and 4 months.” This again leads to discussion. If dates matter, the stakeholders will appreciate the warning to wait for more information before setting a deadline. If the project just needs to get done, stakeholders will appreciate knowing they shouldn’t rely on the finish date.

**Lesson 4: If you aren’t confident in your estimate, say so.**

### Final Thoughts

You may be wondering if all of this is worth the effort. It absolutely is. If you are able to build a reputation as someone who is accurate in estimates and who doesn’t pad their estimates, conversations become far more collaborative and honest. And that’s something we can all appreciate.

Happy managing!

-Jessica Kulwik

*Copyright: All rights reserved*

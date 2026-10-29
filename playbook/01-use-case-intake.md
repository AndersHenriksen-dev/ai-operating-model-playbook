# 1. Use-case intake and scoring

> **Status: outline.**

## What this section decides

How an AI idea enters the pipeline, how it is ranked against other ideas, who decides, and how fast the person who suggested it gets an answer.

## Write here

<!-- Aim for 400-700 words. Refer to templates/intake-form.md and templates/business-case.md rather than repeating their fields. -->

## Questions to answer

- How does anyone in the company submit an idea? What is the least they must fill in?
-   I will make an ingestion step that people can submit ideas through. I will also talk to the teams individually to coach them on what AI can and cannot do and when standard automation options like power automate, excel or a python program should be used instead.
- Which criteria do you score on (for example value, feasibility, data readiness, risk), and how are they weighted?
-   Data will be a large part along with the complexity of the solution and value created. I will make a coordinate system sort of like is done for start-ups where I can show the easy pickings, the moonshots and the no-gos. A separate setup of some kind should probably capture the risks and data readiness.
- What has to be in place before work starts: a business owner, a success measure, a baseline?
-   I will heavily follow the guides behind MRM (model risk management) and responsible AI for this one. Basically, the idea is that every model should have a description on the work it does, what data it uses, how much estimated money it will save and cost, business owner, implementer, maintainer, and other related fields.
- How do you test an idea cheaply before writing a full business case?
-   I or someone in my team will make the smallest possible version zero, whether that be a miro board, a piece of cardboard with the buttons laid out or the full solution if the idea is cheap enough to make a good version of initially. I am a big believer in the build-measure-learn cycle and the 80-20 principle, where you ensure that you get the most essential parts of the solution first and then increase the scope, cost and time spent on it only if necessary.
- Who decides, how often, and how quickly does the submitter hear back?
-   It could take a while for the person to hear back, but it depends on how many people are deciding these things. The idea should be that it is simpler for them to reach out to me oficially than it is for them to do it themselves. I want to avoid having the most technically proficient people at the company spend all their time looking through business cases and nothing else, so there should be a balance and some economies of scale, such that we allow the fact that there are many departments to be a benefit instead of being a drawback.
- What gets a "no", and how do you say no without killing people's interest?
-   No-go's in the coordinate system, ideas that are more expensive to build and maintain than the manual solution they are covering for, solutions that don't have the necessary data, solutions that lack the connectors relevant for building agents on it, data related to GDPR or personally identifiable data that is risky to let US firms touch.
- When do you stop a running case? What are the stop criteria?
-   I don't know and I don't have experience with this sort of area.
- How does the pipeline stay visible to leadership and to the people who submitted ideas?
-   We will make graphs and surface important insights through necessary channels. If possible, LLMOps will be used to ensure that we have complete oversight of the used solutions and what is and is not being used, so we can shut down the models that no longer provide value. Power BI can be used to make automated reports on both the number of business cases and AI solutions that have been put in place and where we should focus our efforts. A different topic entirely is ensuring that we are automating at the location of a bottle-neck at the firm to ensure that we are getting the most from the tech.

## Must include

- [ ] The intake steps, from idea to decision
- [ ] The scoring criteria and weights, with one worked example
- [ ] The conditions for starting work and the conditions for stopping it
- [ ] Who decides, and how often
- [ ] A link to the intake form and the business case template

## Questions a sceptical leadership team will ask

- "Won't this just become a bureaucratic queue?"
- "How do you stop the loudest department from getting everything?"
- "Why not let each team pick its own tools?"

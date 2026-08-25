# Tanner Griffith

I work in enterprise customer success, and I build AI systems for problems I run into in the real world.

A lot of my work starts with the same frustration: the information is there, but it is spread across too many tools to be useful at the right moment. I like figuring out how to bring those signals together without turning the result into another black box.

## What I'm working on

### [Phono StoryForge](https://github.com/tanner-griffith/phono-storyforge)

Phono StoryForge is an adaptive reading tutor for early, struggling, and dyslexic readers.

It keeps track of the phonics patterns a child has mastered, chooses what to practice next, creates a story at that level, and updates its plan based on how the child reads it. The generated stories go through a separate Python check before they can be used, so the model cannot simply declare that a book is decodable.

I also built an evaluation that compares the adaptive tutor with a fixed lesson sequence. The simulated learner uses a different learning model from the tutor, which makes the test harder to game and the results more useful.

The repository includes the application, tests, evaluation code, architecture notes, and the parts that still need work.

### CSM Copilot *(private)*

CSM Copilot helps me manage an enterprise customer portfolio. It gathers information from the systems I already use and turns it into morning briefs, meeting preparation, risk flags, and CRM drafts.

The calculations and risk rules run in regular Python. A separate fact-checking step reviews the generated briefs, and nothing is sent to a customer automatically.

The repository is private because it works with real customer information. I plan to publish a case study and a demo built with synthetic data.

## What I care about

I'm interested in applied AI that helps people do their jobs better: agent systems, customer-success tools, product operations, evaluation, and the practical work of making these systems reliable.

My background is in customer relationships and revenue, not traditional software engineering. That is usually where I start—understanding the work, the people doing it, and what would actually be useful—then I build from there.

## Connect

Raleigh–Durham, North Carolina

[LinkedIn](https://www.linkedin.com/in/tanner-griffith-85455b23/) · [Email](mailto:tanner.griffith@gmail.com)

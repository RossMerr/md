# Project Kick-Off Template

_This template serves as a checklist or starting point to consult before kicking off a new project, e.g. something that might have its own team allocated to it, or something that will have its own swimlane on the Kanban_

## Who?
The most important aspect to consider is who the engineering team will be comprised of. If key people for the project are fully occupied with other things, they need to finish those projects first or organize a proper hand-over.

## Who are your stakeholders?
Identify those that you'd be working with outside of the engineering team. This can be customers (e.g. people in the Marketing/BI department) or sponsors, but also generally everyone knowledgeable in the domain you're developing software in.

An artifact should be a visualization or just a list of people who are somehow involved or affected by the project, including their contact info and the department they work at.

## Who will be working closely with you?
The team should have all the necessary skills to fully ship the project from start to finish. If your project will have a frontend, you need someone with frontend skills. If your software will have to run somewhere, you need someone who knows how to deploy to stage and production.

If you don't have these skills in the team right from the start, consider allocating enough time for people to learn the skills they need, e.g. through pair programming or communities of practice.

If you have these skills, make sure that the basic knowledge of specific skills is shared among at least two permanent team members. This is crucial to avoid bottlenecks!

##  Grab lunch together
Go grab lunch with everyone and get to know each other!

## What?
Next step is making sure you understand what you want to build before starting to build it.

## Understand purpose of the project
What problem are you solving? If there's not one fully-fledged user story or acceptance test, don't start writing code!

Agile means iterative development, yes, but that doesn't mean you shouldn't outline the scope of the project first.

## Start with discovery
If your project is largely unspecified and is not supposed to be a rewrite of something that's already there, you should invest considerable time on finding out what your software is supposed to do.

Let's say you're building a tool that is mostly used internally. Chances are, it's being build as to automate some of the things people right now do manually or in a less efficient manner. Go find these people and look at how they're working now! Try to find a way to make their lives easier by automating as much as possible, with just as much systemic change as necessary.

## Ship as little as possible, as early as possible
The first rule of DevOps mindset is being able to ship at any point in time, so go ahead, create the boilerplate and then set up CI and CD to ship that boilerplate!

Integrate the e2e-tests into your pipeline, take proper time to write up a good README and only then start implementing the first user story.

## Start incrementally, biggest value first
Find the one thing that you can do that will resolve in value delivered right away. This doesn't mean implementing the whole thing at once, but breaking it down in actual deliverables. Could be a lot of empty pages with a single workflow covered, or a full end-2-end run along the happy path with external systems mocked away for the moment, but in any case, it's neither a single aspect of a system (e.g. receiving a message), nor is it the whole functionality (e.g. "allow user to change their profile).

Something that is not yet used, or not yet usable, does not provide value.

## Structure & Process?
Next thing to think about when kicking off the team is the amount of rituals that you want to establish. E.g. if you're a team with two engineers and a product manager, chances are you don't need a daily because you're working closely together anyway. If you end up being a bigger team with more than one thing to be worked on at once, think about adding a daily so people can raise blockers as soon as they notice they're stuck. See this article by David Tänzer and this one by J.B. Rainsberger on how to properly implement Daily's.

## Retrospectives
In either way, you should see to finding at least one hour every two weeks to hold a retrospective. It should have actionable outcomes that are part of the everyday tasks that your team works on. If you want to mix things up a bit, try a retrospective from the retromat.

## Show-and-Tells
Consider establishing a Show-and-Tell as a celebration of what you've achieved. Invite stakeholders and curious people and make it a happening that is well prepared and worth attending!
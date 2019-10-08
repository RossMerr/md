# Code Reviewing Guidelines

* Two thumbs up for a MR before merging.
* MS Teams broadcast when a MR is available (channel: Code Review).
* Assign MR at standup if failed to get taken in the MS Teams broadcast.
* Align the MR with JIRA and the physical board when applicable (write your name on the ticket you're reviewing).
* Always start any outstanding MR before starting new work.
* Give an appropriate context in the MR.
* Keep the MR as single context (this should reflect a single feature and probably a single task within JIRA).
* Always be polite with feedback for a MR.
* If you're reviewing a recently created project, don't forget to review the README file to check if the minimal instructions on how to run the project are there.

Do not be afraid of giving out reviews, no matter how senior you are, your opinion is appreciated

We expect a review to only take about 30 minutes so if you are finding they are taken longer than the context has become too big for a MR, this is often a sign of the developer not keeping the context to the feature or the feature being developed was too big.

## Code Review Guidelines

A guide for reviewing code and having your code reviewed.

### Everyone

* Accept that many programming decisions are opinions. Discuss tradeoffs, which you prefer, and reach a resolution quickly.
* Ask good questions; don't make demands. ("What do you think about naming this :user_id?")
* Good questions avoid judgment and avoid assumptions about the author's perspective.
* Ask for clarification. ("I didn't understand. Can you clarify?")
* Avoid selective ownership of code. ("mine", "not mine", "yours")
* Avoid using terms that could be seen as referring to personal traits. ("dumb", "stupid"). Assume everyone is intelligent and well-meaning.
* Be explicit. Remember people don't always understand your intentions online.
* Be humble. ("I'm not sure - let's look it up.")
* Don't use hyperbole. ("always", "never", "endlessly", "nothing")
* Don't use sarcasm.
* Keep it real. If emoji, animated gifs, or humor aren't you, don't force them. If they are, use them with aplomb.
* Talk synchronously (e.g. chat, screensharing, in person) if there are too many "I didn't understand" or "Alternative solution:" comments. Post a follow-up comment summarizing the discussion.

### Having Your Code Reviewed

* Be grateful for the reviewer's suggestions. ("Good call. I'll make that change.")
* A common axiom is "Don't take it personally. The review is of the code, not you." We used to include this, but now prefer to say what we mean: Be aware of how hard it is to convey emotion online and how easy it is to misinterpret feedback. If a review seems aggressive or angry or otherwise personal, consider if it is intended to be read that way and ask the person for clarification of intent, in person if possible.
* Keeping the previous point in mind: assume the best intention from the reviewer's comments.
* Explain why the code exists. ("It's like that because of these reasons. Would it be more clear if I rename this class/file/method/variable?")
* Extract some changes and refactorings into future tickets/stories.
* Link to the code review from the ticket/story. ("Ready for review: https://github.com/organization/project/pull/1")
* Push commits based on earlier rounds of feedback as isolated commits to the branch. Do not squash until the branch is ready to merge. Reviewers should be able to read individual updates based on their earlier feedback.
* Seek to understand the reviewer's perspective.
* Try to respond to every comment.
* Wait to merge the branch until Continuous Integration (TDDium, TravisCI, etc.) tells you the test suite is green in the branch.
* Merge once you feel confident in the code and its impact on the project.

### Reviewing Code

Understand why the change is necessary (fixes a bug, improves the user experience, refactors the existing code). Then:

* Communicate which ideas you feel strongly about and those you don't.
* Identify ways to simplify the code while still solving the problem.
* If discussions turn too philosophical or academic, move the discussion offline to a regular Friday afternoon technique discussion. 
* Offer alternative implementations, but assume the author already considered them. ("What do you think about using a custom validator here?")
* Seek to understand the author's perspective.
* Sign off on the pull request with a 👍 or "Ready to merge" comment.
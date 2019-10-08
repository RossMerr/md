# Style Guide

The primary goal of the style guidelines is to improve code readability so that everyone, whether reading the code for the first time or maintaining it for years, can quickly determine what the code does. Secondary goals are to design systems that are simple, to increase the likelihood of catching bugs quickly, and avoiding arguments when there are disagreements over subjective matters.

## Philosophy

### Lazy programming

Write what you need and no more, but when you write it, do it right.

Avoid implementing features you don’t need. You can’t design a feature without knowing what the constraints are. Implementing features "for completeness" results in unused code that is expensive to maintain, learn about, document, test, etc.

When you do implement a feature, implement it the right way. Avoid workarounds. Workarounds merely kick the problem further down the road, but at a higher cost: someone will have to relearn the problem, figure out the workaround and how to dismantle it (and all the places that now use it), and implement the feature. It’s much better to take longer to fix a problem properly, than to be the one who fixes everything quickly but in a way that will require cleaning up later.

### Write Test, Find Bug

When you fix a bug, first write a test that fails, then fix the bug and verify the test passes.

When you implement a new feature, write tests for it. 

Check the code coverage to make sure every line of your new code is tested. 

Don’t submit code with the promise to "write tests later". Just take the time to write the tests properly and completely in the first place.

### Solve real problems by literally solving a real problem

Where possible, especially for new features, you should partner with a real customer who wants that feature and is willing to help you test it. Only by actually using a feature in the real world can we truly be confident that a feature is ready for prime time.

Listen to their feedback, too. If your first customer is saying that your feature doesn’t actually solve their use case completely, don’t dismiss their concerns as esoteric. Often, what seems like the problem when you start a project turns out to be a trivial concern compared to the real issues faced by real developers.

### Get early feedback

If you’re designing a new feature, consider writing a design doc, typically using Confluence or by writing a RFC. Then, get feedback from the relevant people, or post it on Teams.

### Avoid abandonware

Code that is no longer maintained should be deleted or archived in some way that clearly indicates that it is no longer maintained.

For example, we delete rather than commenting out code. Commented-out code will bitrot too fast to be useful, and will confuse people maintaining the code.

Similarly, all our repositories should have an owner that does regular triage of incoming issues and PRs, and fixes known issues. Repositories where nobody is doing triage at least monthly, preferably more often, should be deleted, hidden, or otherwise archived.

## Formatting

### Prefer a maximum line length of 80 characters

Aim for a maximum line length of roughly 80 characters, but prefer going over if breaking the line would make it less readable, or if it would make the line less consistent with other nearby lines. 
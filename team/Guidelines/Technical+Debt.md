# Technical Debt

Think through critical technical issues before you implement your solution you have the opportunity to avoid a technical strategy which needs to be reworked at a future date. The most effective way to deal with technical debt is to avoid it in the first place.

## Refactor technical debt away 

Refactorings are typically very small, such as renaming an operation or splitting a database column, so should just be part of everyday development. Rework, on the other hand, is more substantive and should be explicitly planned.  The Tech Committee will often negotiate rework-oriented work items with the Product Owner (the person on the team who is responsible for prioritizing the work).

## Regression test continuously

One of the easiest ways to find problems in your work is to have a comprehensive regression test suite that is run regularly. This test suite will help you detect when defects are injected into your code, enabling you to fix them, or back out the changes, right away.

## Automate code/schema analysis

There are many tools available for assessing the quality of your code and even your database schema. Disciplined agile teams will include the use of these tools in their continuous integration (CI) strategy.  Knowing where your technical debt exists is the first step in removing.

## Measure and govern technical debt

You may choose to track code quality metrics, data quality metrics, usability metrics, time to address defects, time to add features, and many other things but this means it needs to be understood by management so it can be supported. When identify technical debt bring it to the Tech Committee to share any pain points across all teams to track and prioritise.
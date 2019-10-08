# Extreme Programming (XP)

## Short Development Cycles

Fast feedback, from tests, the customer and the team.

## Pair Programming

Driving and reviewing, constant Knowledge sharing of problems and solutions.

### Pair Switching
The benefits of pair switching lead to greater efficiency, which leads to even more adoption success.

* People will have varying degrees expertise in tools (e.g. grep, IDEs), the domain, patterns, testing, and so on. It makes sense to work with whoever is an expert in the area that is required to implement your current feature.
* Working with different team-members will allow you to more easily balance the amount of time you spend being a learner or a mentor.

### Who Should Drive

1. Pair developer 1 writes a failing test
2. Pair developer 2 makes the test pass by implementing only what's necessary.
3. Pair developer 2 writes a failing test
4. Pair developer 1 makes the test pass by implementing only what's necessary.
5. Go back to step 1. Follow this loop for the entire pairing session.

### When Not to Pair

There are several situations when it makes sense not to pair, including when one pair member is reduced to a spellchecker. Other common situations when it makes more sense to work on your own include:

* When reading about a library that might help later on
* Spiking a complex solution or debugging a tricky error with someone that has an experience gap. In general pairing is not ideally suited for the combination of exploration and bridging an experience gap.

## Team Code Ownership

Sharing of work, open for collaboration on new technology.

## Test-driven development (TDD) 

we build code it in a test driven approach once a feature is fully discovered.

1. Add a test
2. Run all tests and see if the new test fails
3. Write the code
4. Run tests
5. Refactor code
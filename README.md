# TDD Exercises

Objective of this repo si to demonstrate step by step the power of Test Driven Development (TDD). In order to learn more about Test Driven Development (TDD) Please refer to my YouTube course.

# Modeling Business Logic using TDD

One of the areas where TDD really shines is when we create the Business Logic Layer (BLL) of the application.

Essentially a BLL is a collection of business rules that need to be applied in the application context to ensure the application works correctly.

With TDD we have a proven systematic process of doing this activity that will not only ensure we apply all the business rules properly to our BLL but also that we can refactor the BLL without fear in the future.

# The 3Ds of TDD

Doing TDD demands 3 things from a developer. I.e. "Discipline", "Discipline" and "Discipline" (3Ds).

TDD methodology is really simple and in most fo the case two simple for many of the season developers. Hence, they tend to ignore certain rules and practicies of TDD which will lead to failure in delivering the ultimate value and promise of TDD.

TDD is like being a "Good Person", i.e. you  want to be a good person, you have to always be good. Even if you are bad once, people will say you are NOT a good person. Like wise, following TDD will only give you a benefit if you have the discipline to follow it's rules ALWAYS.

# Our Approach

We will follow a certain pattern when using TDD (Please refer to my YouTube video for more info). In Summary This is our approach when creating BLL using TDD

- We adhere to KISS (Keep it Simple Stupid)
- Always write the simplest test first and most Complex test Last. I.e. we will increase the complexity as we progress
- Cover the Error Scenarios as early as possible.
- We Refactor both production and Test code as we go on
- We will always strive to have 100% code coverage

## Implementation Branches

We use Monorepo and Yarn to manage all the projects
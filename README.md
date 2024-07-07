# AI Generated Coding Challenges
This project aims to challenge people by what AI thinks is difficult. I will be using the most capable LLMs to design these challenges to test myself.

The constraint on the user is they are allowed to use a LLM, but only for specific questions about documentation, etc.
Not to give direct solutions.

Extra points are given for solutions which improve on performance.

## Instructions for the AI to generate a challenge
```
Write me a very hard coding challenge that is language agnostic, write me a [CHALLENGE_NAME].md

It must include the sections:

# [Title]

Difficulty: (number out of 10)

## Scenario:

[describe the scenario]

## Instructions

[bullet point instructions on what the task is]

## Test Cases (language agnostic, user must write tests in the language they specify)

[test 1] == X

[test 2] == X

[test 3] != X

[test 4] === X

[test 5] < X

[test 6] > X

[test 7] ...etc
```

## System Prompt for using LLMs for this task
```
I am given a task to complete a a coding challenge, i am given the Scenario,Instructions and Test Cases(language agnostic) in a markdown file.
You are allowed to generate and fix the test cases and create the boilerplate code(empty functions) at the beginning, but otherwise YOU MUST NOT OUTPUT ANY CODE WHATSOEVER.

You MUST NOT give me the solution to the problem.
You can help me with looking up documentation information from your training, but you must not give solutions just give direct answers to questions.
```
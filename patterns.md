# Patterns

## Pattern 01: Accelerated mockups

## Pattern 02: Steering Hand

Current LLM technology generate text based on probability distributions. AI Coding Agents take as a starting point the current state of your project (together with prompt and whatever instructions they have been configured to use) when creating new code. On a blank state, AI agents will lean towards more generic and widely used patterns, which most likely will not fit well your particular needs.

You can steer their output towards something closer to the desired by first writing an initial implementation the sets the correct style and approach, which the agents will then lean towards following in their output.

The initial implementation can be short, but it will work better if it is something that touches the most critical aspects of your project.

A particularly useful pattern is to write yourself the data structures, schemas or entity classes that will be used. AI agents are very prone to get fields and their types wrong when based purely on prompts, and are much more likely to write good methods or functions to operate over the data structures when they are already correctly defined and present in the context.


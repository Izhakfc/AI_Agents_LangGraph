# AI Agents — DeepLearning.AI Course Repository

This repository contains my work and experiments from the **AI Agents course by DeepLearning.AI**.  
It focuses on understanding how to build and reason about **AI agents**, particularly those powered by OpenAI’s agent framework.

---

## Section 1 — Introduction to AI Agents

In this first section, I explore the fundamental concepts behind agents — autonomous systems that can **reason**, **act**, and **learn** through interaction with their environment.

In the first section, I'm testing a simple example agent with two methods:
- `average_dog_weight` — a function that returns the average weight of a dog breed.
- `calculate` — a function that performs basic mathematical operations.

These functions demonstrate how an agent can use tools (or functions) to perform tasks based on a goal or user query.

---

## The Agent Loop

A key idea introduced in this section is the **agent reasoning loop**, which can be summarized as:

> **Thought → Action → PAUSE → Observation**

- **Thought** — The agent considers what to do next.  
- **Action** — It performs a tool call (e.g., a function invocation).  
- **PAUSE** — The system waits for the action result.  
- **Observation** — The agent receives the outcome and updates its reasoning.  

This loop repeats until the agent determines that it has reached a final answer or outcome.

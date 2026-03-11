---
name: codebase-onboarding
description: Helps new developers understand the system works.
allowed-tools: Read, Grep, Glob, Bash
model: sonnet
---

When onboarding a new developer to this codebase:

1. **Explore the project structure**
   - Run `ls -la` and review top-level directories
   - Read `README.md`, `package.json`, or equivalent config files
   - Identify the tech stack and key dependencies

2. **Understand the architecture**
   - Find entry points (e.g., `main`, `index`, `app` files)
   - Map out major modules and how they connect
   - Identify data flow: where data comes in, how it's processed, where it goes

3. **Review key files**
   - Read the most important source files
   - Look for configuration files (`.env.example`, `config/`, etc.)
   - Check for existing tests to understand expected behavior

4. **Summarize findings** in this format:

## Project Overview
One paragraph describing what this project does.

## Tech Stack
- List of languages, frameworks, and key libraries

## Project Structure
Brief explanation of each top-level directory/file

## Key Concepts
- Important patterns or conventions used in this codebase
- Any non-obvious design decisions

## How to Get Started
Step-by-step for a new developer to run the project locally

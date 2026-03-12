# Global Claude Instructions

## 1. Clarification Before Action
- If requirements are ambiguous, do NOT write code with assumptions. Ask me about the design intent or data structure first.
- Before implementing complex logic, explain the pseudocode or flow in plain text and wait for my approval before writing actual code.
- If you discover unexpected issues during a task, do NOT fix them silently. Report to me first.

## 2. Code Quality & Style
- Name all variables and functions intuitively and descriptively. (e.g., use `userAuthToken` instead of `temp`)
- Follow Clean Code principles. Each function should do one thing only.
- Prioritize readability and maintainability over performance optimization.

## 3. File & Token Efficiency
- Only read files explicitly specified with @filename. Do NOT explore the project broadly.
- If you need to read files beyond what's specified, ask me first.
- Read the minimum number of files necessary for the task.

## 4. Task Execution
- Before starting, summarize what you're about to do in one line.
- If a task has 3+ steps, number them and keep me updated on progress.
- Before generating code, show the mapping rules or logic plan and get my confirmation.

## 5. Output & Communication
- Always respond in Korean.
- Keep explanations concise. Minimize unnecessary prose outside of code.
- After completing a task, briefly list the files that were created or modified.
- When mapping is unclear (foreign key IDs, NULL handling, Enum mismatches), always ask me instead of guessing.

# ai-prompt-engineering-cheatsheet

# AI Prompt Engineering Cheatsheet

A practical collection of prompt engineering techniques, reusable templates, and examples for getting better results from AI assistants and large language models (LLMs).

Whether you're writing, coding, researching, or building AI-powered applications, this guide will help you communicate more effectively with AI.

## Table of Contents

- [1. The Basic Prompt Formula](#1-the-basic-prompt-formula)
- [2. Give AI a Role](#2-give-ai-a-role)
- [3. Provide Clear Context](#3-provide-clear-context)
- [4. Specify the Output Format](#4-specify-the-output-format)
- [5. Break Complex Tasks into Steps](#5-break-complex-tasks-into-steps)
- [6. Ask AI to Review Its Work](#6-ask-ai-to-review-its-work)
- [7. Useful Prompt Templates](#7-useful-prompt-templates)
- [8. Common Prompting Mistakes](#8-common-prompting-mistakes)

## 1. The Basic Prompt Formula

A useful prompt often includes four elements:

1. **Role:** Who should the AI act as?
2. **Context:** What background information does it need?
3. **Task:** What exactly should it do?
4. **Format:** How should the result be presented?

Example:

```text
Act as an experienced software developer.

I am building a task management application
using Python and FastAPI.

Explain how to implement user authentication.

Include:
- A step-by-step explanation
- A simple code example
- Common security considerations

Keep the explanation beginner-friendly.
```

## 2. Give AI a Role

A clear role can help establish the perspective and level of detail you expect.

Examples:

```text
Act as a senior Python developer.
```

```text
Act as a technical writer who specializes
in explaining complex concepts simply.
```

```text
Act as a product manager reviewing
a new SaaS product idea.
```

## 3. Provide Clear Context

Avoid giving AI a task without enough background information.

Instead of:

```text
Write a product description.
```

Try:

```text
I am creating a productivity app for
freelancers and small business owners.

The app helps users organize projects,
track tasks, and manage deadlines.

Write a concise product description
for the landing page.
```

## 4. Specify the Output Format

Tell the AI exactly how you want the answer structured.

Examples:

```text
Present the answer as a Markdown table.
```

```text
Return valid JSON with the fields:
"name", "description", and "category".
```

```text
Use numbered steps and include
one practical example for each step.
```

## 5. Break Complex Tasks into Steps

Large tasks are often easier to manage when divided into smaller stages.

For example, when building an application:

1. Define the requirements.
2. Design the architecture.
3. Create the project structure.
4. Implement the core functionality.
5. Write tests.
6. Review and improve the code.

Prompt example:

```text
Help me build a simple REST API.

First, propose the project architecture.
Do not write the code yet.

After I review the architecture,
we will implement it step by step.
```

## 6. Ask AI to Review Its Work

AI-generated content and code should not be accepted without review.

Try asking:

```text
Review your previous answer.

Identify:
- Potential errors
- Missing information
- Unclear explanations
- Possible improvements

Then provide a revised version.
```

For code:

```text
Review this code for:
- Bugs
- Security issues
- Performance problems
- Edge cases

Explain each issue and suggest a fix.
```

## 7. Useful Prompt Templates

### Learning a New Concept

```text
Explain [TOPIC] to someone who is new to it.

Include:
1. A simple definition
2. How it works
3. A practical example
4. Common misconceptions
5. Recommended next steps
```

### Debugging Code

```text
I am encountering the following issue:

[ERROR MESSAGE]

Here is my code:

[CODE]

Help me understand:
1. What caused the issue
2. Why it happened
3. How to fix it
4. How to prevent it in the future
```

### Comparing Technologies

```text
Compare [TECHNOLOGY A] and [TECHNOLOGY B].

Evaluate them based on:
- Performance
- Ease of use
- Scalability
- Cost
- Best use cases

Present the results in a comparison table.
```

### Generating Ideas

```text
Generate 10 practical ideas for [GOAL].

For each idea, include:
- A short description
- The target audience
- Potential benefits
- Implementation difficulty

Avoid generic suggestions.
```

## 8. Common Prompting Mistakes

| Mistake | Better approach |
|---|---|
| Instructions are too vague | Define the task clearly |
| No background information | Provide relevant context |
| Too many unrelated requests | Break the task into steps |
| No output requirements | Specify the desired format |
| Accepting the first answer | Review and refine the result |

## Final Thoughts

Good prompting is not about writing the longest possible instruction.

It is about providing the right context, setting clear expectations, and improving the result through iteration.

Start with simple prompts, experiment with different approaches, and build a workflow that works for you.

---

Contributions and suggestions are welcome. Feel free to open an issue or submit a pull request to improve this collection.

**Let's make AI easier to use, one prompt at a time.**

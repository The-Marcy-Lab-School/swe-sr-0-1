# Technical Writing Assignment

Explain a git commit to someone else, using a metaphor of your own choosing.

- [AI Use on This Assignment](#ai-use-on-this-assignment)
- [Setup](#setup)
- [Instructions](#instructions)
- [Short Response Questions](#short-response-questions)
  - [Prompt 1](#prompt-1)
- [Submitting](#submitting)

## AI Use on This Assignment

These are your own words. Do not use AI to draft or rewrite your responses —
that holds in every mode, including implementer mode. You may use it to check
grammar and spelling on writing you have already written, and you may use it
before you start to quiz you on what a commit is until you can explain it out
loud without notes. Paste this if you want that kind of help:

> You are acting as a tutor. Quiz me on git commits and version control, and
> tell me when my reasoning is wrong or imprecise. Do not write or rewrite any
> part of my response for me.

A response you did not write is worth nothing to you in an interview, which is
where this writing is really aimed.

## Setup

Work in `development/mod-0`. Make a draft branch before you start.

```sh
git checkout -b draft
```

## Instructions

Write your response in `short_response.md`. The prompt is repeated here so you
can read the assignment without switching files.

Aim for a response with these qualities. Your instructor will give you
feedback on each one:

- [ ] Addresses all parts of the prompt
- [ ] Accurately uses relevant technical terminology
- [ ] Is free of grammar and spelling mistakes (double check with Grammarly!)
- [ ] Uses markdown to enhance readability (preview in VS Code with
      Command/Control + Shift + V)
- [ ] Is easy to comprehend

Preview your markdown to check how it renders before submitting.

## Short Response Questions

### Prompt 1

A good technical explanation often uses a metaphor to help others understand a
complex concept. Choose a metaphor to represent a git commit.

In a few brief paragraphs, use your chosen metaphor to explain:

- What a commit is
- How a commit is created, including the command-line syntax
- Why commits are useful in version control
- Why clear, descriptive messages matter when you work on a team

## Submitting

```sh
git add -A
git commit -m "your message"
git push
```

Open a pull request to your instructor for feedback.

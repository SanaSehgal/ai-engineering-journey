# Experiment 001: Role vs Audience
## Research Question

When explaining the same concept, which has a greater impact on the quality of an AI response?

- Assigning the AI a role
- Defining the target audience
- Combining both role and audience

- ## Why I Chose This Experiment

Prompt engineering is often described as the process of writing better prompts, but I wanted to understand *what actually makes a prompt better*.

Rather than memorizing prompt-writing techniques, I want to investigate how different prompt elements influence AI responses.

For my first experiment, I chose to compare the effect of assigning the AI a role and defining the target audience. These are two of the most common prompt engineering techniques, and I wanted to see how each one changes the quality of the response.

This experiment is the first step in building my own understanding of prompt engineering through observation and experimentation.

## Hypothesis

I believe that prompts containing both a clearly defined role and a specific target audience will produce the highest-quality response.

My reasoning is that:

- Defining a **role** helps the AI understand the perspective or expertise it should adopt.
- Defining the **audience** helps the AI adjust its language, complexity, and teaching style.
- Combining both should result in a response that is technically accurate while remaining easy to understand.

- ## Experimental Design

To keep this experiment fair, I will use the **same question** in every prompt.

The only thing that changes is the amount of context provided to the AI.

This allows me to observe how different prompt elements influence the response.

### Topic

Explain Python.

### AI Model

ChatGPT (GPT-5.5)

### Evaluation Criteria

Each response will be evaluated based on:

- Clarity
- Beginner Friendliness
- Technical Accuracy
- Use of Real-Life Examples
- Overall Usefulness

- ## Prompts Used

### Prompt A (Baseline)

```text
Explain Python.
```

---

### Prompt B (Role)

```text
You are a senior software engineer.

Explain Python.
```

---

### Prompt C (Audience)

```text
Explain Python to someone who has never programmed before.

Use simple language and one real-life example.
```

---

### Prompt D (Role + Audience)

```text
You are a senior software engineer mentoring a beginner.

Explain Python to someone who has never programmed before.

Use simple language and one real-life example.
```

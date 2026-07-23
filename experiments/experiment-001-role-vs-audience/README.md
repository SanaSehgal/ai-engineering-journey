# Experiment 001: Role vs Audience

## Table of Contents

- Research Question
- Why I Chose This Experiment
- Hypothesis
- Experimental Design
- Prompts Used
- Results
- Observations
- Conclusion
- Prompt Engineering Principle
- Personal Reflection
- Next Experiment
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
## 📊 Results

| Criteria | Prompt A | Prompt B | Prompt C | Prompt D |
|----------|----------|----------|----------|----------|
| Clarity | ⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| Beginner Friendly | ⭐ | ⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| Technical Accuracy | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| Real-Life Example | ❌ | ❌ | ✅ | ✅ |
| Overall Usefulness | ⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |

## 🔍 Observations

After comparing the responses, I noticed several patterns.

### Observation 1

Adding more words to a prompt did not automatically improve the response.

The biggest improvement came from providing better context rather than writing a longer prompt.

---

### Observation 2

Defining the target audience had a significant impact on the explanation.

The AI used simpler language, avoided unnecessary technical terms, and introduced a real-life analogy, making the explanation easier for a beginner to understand.

---

### Observation 3

Assigning the AI a role improved the structure and professionalism of the response.

The explanation became more organized and technically detailed.

---

### Observation 4

Combining both the role and the audience produced the most balanced response.

It remained technically accurate while also being easy to understand.


What did this experiment teach me?
## ✅ Conclusion

This experiment showed that the quality of an AI response depends more on the clarity of the prompt than on its length.

While assigning the AI a role improved the structure and professionalism of the response, defining the target audience had a greater impact on making the explanation easier to understand.

The best response was produced when both the role and the audience were clearly defined, suggesting that prompt engineering is about providing meaningful context rather than simply adding more instructions.

## 📌 Prompt Engineering Principle #001

**Reduce ambiguity before adding complexity.**

Clearly defining the AI's role and the target audience improves response quality more effectively than simply writing longer prompts.

## 💭 Personal Reflection

Before this experiment, I assumed prompt engineering was mainly about writing longer prompts.

After comparing multiple prompt designs, I realized that the clarity of the instructions matters much more than the length of the prompt.

The biggest surprise for me was how much defining the audience changed the explanation.

Going forward, I want to investigate which prompt components have the greatest influence on AI behaviour and use those findings to build better AI applications.


## 🚀 Next Experiment

### Research Question

Does providing examples (Few-Shot Prompting) improve AI responses more than simply giving instructions?

This experiment will explore how examples influence the quality, consistency, and accuracy of AI-generated responses.

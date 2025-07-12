# Contents

- [A. Basic Prompt Templates](#a-basic-prompt-templates)
  - [1. General Inquiry](#1-general-inquiry)
  - [3. Re-write this sentence in your own words](#3-re-write-this-sentence-in-your-own-words)
  - [4. Definition Request](#4-definition-request)
  - [5. Comparison](#5-comparison)
- [B. Persona-Based Prompt Templates](#b-persona-based-prompt-templates)
  - [6. Role Explanation](#6-role-explanation)
  - [7. Style Mimicry](#7-style-mimicry)
  - [8. Professional writing](#8-professional-writing)
- [C. Few Short Prompt Template](#c-few-short-prompt-template)
  - [9. Classification Template](#9-classification-template)
  - [10. Translation Template](#10-translation-template)
  - [11. Question and answer Template](#11-question-and-answer-template)
- [D. Chain-of-Thought (CoT) Templates](#d-chain-of-thought-cot-templates)
  - [12. Step-by-Step reasoning](#12-step-by-step-reasoning)
  - [13. Math Problem Solving](#13-math-problem-solving)
  - [14. Logical Puzzle](#14-logical-puzzle)
- [E. Instruction Tuning/Format Control](#e-instruction-tuningformat-control)
  - [15. Output formatting](#15-output-formatting)
  - [16. Table Generation](#16-table-generation)
  - [17. Email Writing](#17-email-writing)
- [F. Contextual Prompts](#f-contextual-prompts)
  - [18. Tailored Explanation](#18-tailored-explanation)
  - [19. Industry specific context](#19-industry-specific-context)
- [G. Creative writing prompts](#g-creative-writing-prompts)
  - [20. Story writing](#20-story-writing)
  - [21. Poem writing](#21-poem-writing)
  - [22. Dialog writing](#22-dialog-writing)
- [H. Code and Technical Prompts](#h-code-and-technical-prompts)
  - [23. Code Generation](#23-code-generation)
  - [24. Debugging Help](#24-debugging-help)
  - [25. API Documentation](#25-api-documentation)
- [I. Marketing & Business prompts](#i-marketing--business-prompts)
  - [26. Ad Copywriting](#26-ad-copywriting)
  - [27. Product Description](#27-product-description)
  - [28. Social Media Post](#28-social-media-post)
- [J. Customer Support and Service Prompts](#j-customer-support-and-service-prompts)
  - [29. Response to Complaint](#29-response-to-complaint)
  - [30. FAQ Generator](#30-faq-generator)
- [K. Education and Tutoring Prompts](#k-education-and-tutoring-prompts)
  - [31. Event Plan creation for Supervisor/Manager](#31-event-plan-creation-for-supervisormanager)
  - [32. Quiz Generation](#32-quiz-generation)
  - [33. Return Gift help](#33-return-gift-help)
- [L. Advanced Framework based Templates](#l-advanced-framework-based-templates)
  - [34. ReAct Framework](#34-react-framework)
  - [35. Tree-of-Thoughts (ToT)](#35-tree-of-thoughts-tot)
  - [36. Self-Consistence Prompting](#36-self-consistence-prompting)
- [M. Prompt Optimization and Evaluation](#m-prompt-optimization-and-evaluation)
  - [37. Prompt refinement](#37-prompt-refinement)
  - [38. Prompt Grading Rubric](#38-prompt-grading-rubric)
  - [39. Prompt Iteration Challenge](#39-prompt-iteration-challenge)
- [N. Real world Application Prompts](#n-real-world-application-prompts)
  - [40. Job posting Creation](#40-job-posting-creation)
  - [41. Resume Summary Builder](#41-resume-summary-builder)
  - [42. Business Proposal](#42-business-proposal)
- [O. Miscellaneous Useful Templates](#o-miscellaneous-useful-templates)
  - [43. Opinion Writing](#43-opinion-writing)
  - [44. Debate Preparation](#44-debate-preparation)
  - [45. Travel planning](#45-travel-planning)
  - [46. Book/Movie Review](#46-bookmovie-review)
  - [47. Personal Development](#47-personal-development)
- [P. Prompt Chaining Examples](#p-prompt-chaining-examples)
  - [48. Multi-step Research Task](#48-multi-step-research-task)
  - [49. Idea to Execution](#49-idea-to-execution)
  - [50. Universal Prompt Generator](#50-universal-prompt-generator)

# A. Basic Prompt Templates

## 1. General Inquiry

```
Explain [topic] in simple terms
```

## 2. Summarization
```
Summarize the following text in [number] bullet points
[Insert long text here]
```

## 3. Paraphrasing
```
Re-write this sentence in your own words
[Sentence here]
```

## 4. Definition Request

```
What is the meaning of the [term or concept]?
```

## 5. Comparison
```
Compare [a] and [b] based on [criteria]
```

# B. Persona-Based Prompt Templates

## 6. Role + Explanation
```
You are a [role]. Explain [concept] to [audience].
Example: You are a chef. Explain how to make pasta to a beginner.
```

## 7. Style Mimicry
```
Write like [famous person or charater]: [Topic].
```

## 8. Professional writing
```
You are a [Job title]. Write a [document type] about [topic].
Example: You are a marketing manager. Write a product description for an electric car.
```

# C. Few-Shot Prompt Template

## 9. Classification Template
```
Classify sentiment:

[Example 1] --> [label 1]
[Example 2] --> [label 2]
[New Input] --> _________

Example: 
The food was amazing --> positive
I hated the service --> negative
It was okay --> ______

```

## 10. Translation Template
```
Translate the following sentences into [Target language]
[English sentence] --> [Translated sentence]
[Another English sentence] --> [Translated sentence]
[New Sentence] --> _______
```
## 11. Question and answer Template
```
Answer these questions:
Who wrote "Romeo and Juliet" --> William Shakespeare
What is the capital of France --> Paris
Who discovered gravity --> _______
```

# D. Chain-of-Thought (CoT) Templates

## 12. Step-by-Step reasoning
```
Let's think Step-by-Step. [Problem Statement]. First, we [step 1], then [step 2], so finally [conclusion]. 

Example: lets think step by step. If a train travels at 60 km/hr for 3 hours, how far does it go?
```

## 13. Math Problem Solving
```
Solve this math problem by showing your work:
[Question here]
```

## 14. Logical Puzzle
```
Solve the following logical puzzle. Show your reasoning process
[puzzle description here]
```

# E. Instruction Tuning/Format Control

## 15. Output formatting
```
Summarize the article below in exactly [x] bullet points
```

## 16. Table Generation
```
Create a table comparing [a], [b], and [c] based on [criteria].
```
## 17. Email Writing
```
Write a professional email to [recipient] regarding [purpose]. Use a formal tone.
```
# F. Contextual Prompts

## 18. Tailored Explanation

```
Explain [complex topic] to a [age group] who knows [background knowledge].
Example: Explain blockchain to a high school student who understands basic computer science.
```

## 19. Industry specific context
```
As an [industry expert], explain how [technology/product] impacts [specific industry]
```
# G. Creative writing prompts

## 20. Story writing
```
Write a short story about [character] who [goal] but faces [obstacle].
```

## 21. Poem writing
```
Write a poem in [style/poetic form] about [theme]
```
## 22. Dialog writing
```
Write a realistic dialogue between [person a] and [person b] discussing [topic]
```
# H. Code and Technical Prompts

## 23. Code Generation
```
Write a [language] function that [does something]
```
## 24. Debugging Help:
```
Here is some code. Find and fix any errors:
[code snippet]
```
## 25. API Documentation
```
Explain how to use the [api name] with an example request and response
```
# I. Marketing & Business prompts

## 26. Ad Copywriting
```
Write a compelling Ad for [product/service] targeting [audience]
```
## 27. Product Description
```
write a persuasive product description for [product name]
```
## 28. Social Media Post
```
Create a social media post prompting [event/product/idea] in a friendly tone.
```
# J. Customer Support and Service Prompts

## 29. Response to Complaint
```
Respond professional to this customer compliant:
[customer message here]:
```
## 30. FAQ Generator
```
Generate 5 Common FAQs and Answers for [topic/product]
```
# K. Education and Tutoring Prompts

## 31. Lesson plan creation
```
Create a lesson plan for teaching [topic] to [grade level].
```
## 32. Quiz Generation
```
Generate a 5 question quiz about [subject/topic]
```
## 33. Homework help
```
Explain how to solve this [math/science] problem:
[Question here]
```
# L. Advanced Framework based Templates

## 34. ReAct Framework
```
Thought: [Model thinks about what to do next]
Action: [Model takes an action]
Observation: [result of the action]
Answer: [final answer]
Simulate the agent Behaviour manually
```
## 35. Tree-of-Thoughts (ToT)
```
Generate 3 possible solutions to [problem]. Evaluate each and choose the best one.
```
## 36. Self-Consistency Prompting
```
Solve the following question in 3 different ways and pick the most consistent answer
[Question here]
```
# M. Prompt Optimization and Evaluation

## 37. Prompt refinement
```
Improve this prompt: [Original prompt]

Make it cleaner, more specific, and structured
```
## 38. Prompt Grading Rubric: 
```
Rate the output based on the following criteria (1 - 5)

Relevance: ______________
Accuracy: ______________
Clarity: ______________
Fluency: ______________
Creativity: ______________
Final Score: ______________
```

## 39. Prompt Iteration Challenge
```
Take this week prompt: "[Prompt]"
Now rewrite it 3 times to improve clarity and effectiveness
```
# N. Real world Application Prompts

## 40. Job posting Creation
```
Write a job posting for [position] at [company]. Include Roles & Responsibilities, benefits and perks
```
## 41. Resume Summary Builder
```
Create a Professional summary for a resume based on the following details
[experience, skills and achievements]
```
## 42. Business Proposal
```
Write a proposal for [project idea] to [client/investor]. Include objectives, methodology and benefits.
```
# O. Miscellaneous Useful Templates

## 43. Opinion Writing
```
Write an opinion piece on [topic]. Use a persuasive arguments and examples
```
## 44. Debate Preparation
```
Prepare arguments for both sides of the debate: "[debate topic]"
```
## 45. Travel planning
```
Plan a 5 day trip to [destination] for [type of travel]. Include activities, budget and tips.
```
## 46. Book/Movie Review
```
Write a review of "[book/movie]". Include plot summary, strengths, weakness, and recommendations
```
## 47. Personal Development
```
Give me actionable advice on how to [goal], including daily habits and mindset shifts.
```
# P. Prompt Chaining Examples

## 48. Multi-step Research Task
```
Step 1: Find out top 5 causes of climate change
Step 2: based on those causes, suggest 5 practical solutions individuals can adopt
```
## 49. Idea to Execution
```
Step 1: Generate 5 business ideas for eco friendly products
Step 2: pick one idea and create a business strategy for it
```
## 50. Universal Prompt Generator
```
[Role] + [Task] + [Context] + [Example] + [Format/Tone]
Example:
You are a nutrionsit. Create a weekly meal plan for someone with diabetes. Include breakfast, lunch, dinner, and snacks. Format as a table.
```
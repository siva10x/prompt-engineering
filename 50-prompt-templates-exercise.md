# Contents
- [A. Basic Prompt Templates](#a-basic-prompt-templates)
  - [1. General Inquiry](#1-general-inquiry)
  - [2. Summarization](#2-summarization)
  - [3. Paraphrasing](#3-paraphrasing)
  - [4. Definition Request](#4-definition-request)
  - [5. Comparison](#5-comparison)
- [B. Persona-Based Prompt Templates](#b-persona-based-prompt-templates)
  - [6. Role + Explanation](#6-role--explanation)
  - [7. Style Mimicry](#7-style-mimicry)
  - [8. Professional Writing](#8-professional-writing)
- [C. Few-Shot Prompt Template](#c-few-shot-prompt-template)
  - [9. Classification Template](#9-classification-template)
  - [10. Translation Template](#10-translation-template)
  - [11. Question and Answer Template](#11-question-and-answer-template)
- [D. Chain-of-Thought (CoT) Templates](#d-chain-of-thought-cot-templates)
  - [12. Step-by-Step Reasoning](#12-step-by-step-reasoning)
  - [13. Math Problem Solving](#13-math-problem-solving)
  - [14. Logical Puzzle](#14-logical-puzzle)
- [E. Instruction Tuning/Format Control](#e-instruction-tuningformat-control)
  - [15. Output Formatting](#15-output-formatting)
  - [16. Table Generation](#16-table-generation)
  - [17. Email Writing](#17-email-writing)
- [F. Contextual Prompts](#f-contextual-prompts)
  - [18. Tailored Explanation](#18-tailored-explanation)
  - [19. Industry Specific Context](#19-industry-specific-context)
- [G. Creative Writing Prompts](#g-creative-writing-prompts)
  - [20. Story Writing](#20-story-writing)
  - [21. Poem Writing](#21-poem-writing)
  - [22. Dialog Writing](#22-dialog-writing)
- [H. Code and Technical Prompts](#h-code-and-technical-prompts)
  - [23. Code Generation](#23-code-generation)
  - [24. Debugging Help](#24-debugging-help)
  - [25. API Documentation](#25-api-documentation)
- [I. Marketing & Business Prompts](#i-marketing--business-prompts)
  - [26. Ad Copywriting](#26-ad-copywriting)
  - [27. Product Description](#27-product-description)
  - [28. Social Media Post](#28-social-media-post)
- [J. Customer Support and Service Prompts](#j-customer-support-and-service-prompts)
  - [29. Response to Complaint](#29-response-to-complaint)
  - [30. FAQ Generator](#30-faq-generator)
- [K. Education and Tutoring Prompts](#k-education-and-tutoring-prompts)
  - [31. Lesson Plan Creation](#31-lesson-plan-creation)
  - [32. Quiz Generation](#32-quiz-generation)
  - [33. Homework Help](#33-homework-help)
- [L. Advanced Framework Based Templates](#l-advanced-framework-based-templates)
  - [34. ReAct Framework](#34-react-framework)
  - [35. Tree-of-Thoughts (ToT)](#35-tree-of-thoughts-tot)
  - [36. Self-Consistency Prompting](#36-self-consistency-prompting)
- [M. Prompt Optimization and Evaluation](#m-prompt-optimization-and-evaluation)
  - [37. Prompt Refinement](#37-prompt-refinement)
  - [38. Prompt Grading Rubric](#38-prompt-grading-rubric)
  - [39. Prompt Iteration Challenge](#39-prompt-iteration-challenge)
- [N. Real World Application Prompts](#n-real-world-application-prompts)
  - [40. Job Posting Creation](#40-job-posting-creation)
  - [41. Resume Summary Builder](#41-resume-summary-builder)
  - [42. Business Proposal](#42-business-proposal)
- [O. Miscellaneous Useful Templates](#o-miscellaneous-useful-templates)
  - [43. Opinion Writing](#43-opinion-writing)
  - [44. Debate Preparation](#44-debate-preparation)
  - [45. Travel Planning](#45-travel-planning)
  - [46. Book/Movie Review](#46-bookmovie-review)
  - [47. Personal Development](#47-personal-development)
- [P. Prompt Chaining Examples](#p-prompt-chaining-examples)
  - [48. Multi-step Research Task](#48-multi-step-research-task)
  - [49. Idea to Execution](#49-idea-to-execution)
  - [50. Universal Prompt Generator](#50-universal-prompt-generator)

> **Role: Grade 10 School Teacher**

# A. Basic Prompt Templates

## 1. General Inquiry

**Template:**
```
Explain [topic] in simple terms
```

**My Example**
```
Explain photosynthesis in simple terms
```

## 2. Summarization

**Template:**
```
Summarize the following text in [number] bullet points
[Insert long text here]
```

**My Example**
```
Summarize the following text in 5 bullet points\

The process of cellular respiration involves three main stages: glycolysis, the citric acid cycle, and the electron transport chain. Glycolysis occurs in the cytoplasm and breaks down glucose into pyruvate, producing a small amount of ATP. The citric acid cycle takes place in the mitochondrial matrix and further breaks down the products of glycolysis, releasing carbon dioxide and generating more ATP and electron carriers. The electron transport chain, located in the inner mitochondrial membrane, uses the electron carriers to produce the majority of ATP through oxidative phosphorylation.
```

## 3. Paraphrasing

**Template:**
```
Re-write this sentence in your own words
[Sentence here]
```

**My Example**
```
Re-write this sentence in your own words

The velocity of an object is the rate of change of its displacement with respect to time.
```

## 4. Definition Request

**Template:**
```
What is the meaning of the [term or concept]?
```

**My Example**
```
What is the meaning of the quadratic formula?
```

## 5. Comparison

**Template:**
```
Compare [a] and [b] based on [criteria]
```

**My Example**
```
Compare mitosis and meiosis based on their purpose, number of divisions, and genetic outcomes
```

# B. Persona-Based Prompt Templates

## 6. Role + Explanation

**Template:**
```
You are a [role]. Explain [concept] to [audience].
Example: You are a chef. Explain how to make pasta to a beginner.
```

**My Example**
```
You are a physicist. Explain Newton's second law of motion to a grade 10 student.
```

## 7. Style Mimicry

**Template:**
```
Write like [famous person or character]: [Topic].
```

**My Example**
```
Write like Albert Einstein: Explain the relationship between energy and mass.
```

## 8. Professional Writing

**Template:**
```
You are a [Job title]. Write a [document type] about [topic].
Example: You are a marketing manager. Write a product description for an electric car.
```

**My Example**
```
You are a research scientist. Write a lab report summary about the effects of different pH levels on enzyme activity.
```

# C. Few-Shot Prompt Template

## 9. Classification Template

**Template:**
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

**My Example**
```
Classify the following as physical or chemical changes:

Ice melting --> physical change
Wood burning --> chemical change
Paper tearing --> physical change
Milk souring --> _______
```

## 10. Translation Template

**Template:**
```
Translate the following sentences into [Target language]
[English sentence] --> [Translated sentence]
[Another English sentence] --> [Translated sentence]
[New Sentence] --> _______
```

**My Example**
```
Translate the following mathematical expressions into words:
x + 5 = 12 --> x plus five equals twelve
2x - 3 = 7 --> two x minus three equals seven
3(x + 4) = 15 --> _______
```

## 11. Question and Answer Template

**Template:**
```
Answer these questions:
Who wrote "Romeo and Juliet" --> William Shakespeare
What is the capital of France --> Paris
Who discovered gravity --> _______
```

**My Example**
```
Answer these questions:
What is the symbol for oxygen --> O
What is the formula for water --> H2O
What is the atomic number of carbon --> _______
```

# D. Chain-of-Thought (CoT) Templates

## 12. Step-by-Step Reasoning

**Template:**
```
Let's think Step-by-Step. [Problem Statement]. First, we [step 1], then [step 2], so finally [conclusion]. 

Example: lets think step by step. If a train travels at 60 km/hr for 3 hours, how far does it go?
```

**My Example**
```
Let's think step-by-step. A ball is dropped from a height of 20 meters. How long does it take to hit the ground? First, we identify the known values (h = 20m, initial velocity = 0, g = 9.8 m/s²), then we choose the appropriate kinematic equation, so finally we can solve for time.
```

## 13. Math Problem Solving

**Template:**
```
Solve this math problem by showing your work:
[Question here]
```

**My Example**
```
Solve this math problem by showing your work:
Factor the quadratic expression: x² + 7x + 12
```

## 14. Logical Puzzle

**Template:**
```
Solve the following logical puzzle. Show your reasoning process
[puzzle description here]
```

**My Example**
```
Solve the following logical puzzle. Show your reasoning process
Three students are conducting experiments with different acids: hydrochloric acid, sulfuric acid, and nitric acid. Sarah is not using hydrochloric acid. The student using sulfuric acid is wearing safety goggles. Mike is wearing safety goggles. Lisa is not using nitric acid. Who is using which acid?
```

# E. Instruction Tuning/Format Control

## 15. Output Formatting

**Template:**
```
Summarize the article below in exactly [x] bullet points
```

**My Example**
```
Summarize the process of photosynthesis in exactly 4 bullet points
```

## 16. Table Generation

**Template:**
```
Create a table comparing [a], [b], and [c] based on [criteria].
```

**My Example**
```
Create a table comparing solids, liquids, and gases based on particle arrangement, particle movement, and shape/volume properties.
```

## 17. Email Writing

**Template:**
```
Write a professional email to [recipient] regarding [purpose]. Use a formal tone.
```

**My Example**
```
Write a professional email to parents regarding their child's performance in the recent chemistry lab practical. Use a formal tone.
```

# F. Contextual Prompts

## 18. Tailored Explanation

**Template:**
```
Explain [complex topic] to a [age group] who knows [background knowledge].
Example: Explain blockchain to a high school student who understands basic computer science.
```

**My Example**
```
Explain DNA replication to a grade 10 student who understands basic cell structure and the concept of heredity.
```

## 19. Industry Specific Context

**Template:**
```
As an [industry expert], explain how [technology/product] impacts [specific industry]
```

**My Example**
```
As a biotechnology expert, explain how CRISPR gene editing technology impacts the pharmaceutical industry
```

# G. Creative Writing Prompts

## 20. Story Writing

**Template:**
```
Write a short story about [character] who [goal] but faces [obstacle].
```

**My Example**
```
Write a short story about a young scientist who wants to prove her theory about plant communication but faces skepticism from the scientific community.
```

## 21. Poem Writing

**Template:**
```
Write a poem in [style/poetic form] about [theme]
```

**My Example**
```
Write a poem in free verse about the periodic table of elements
```

## 22. Dialog Writing

**Template:**
```
Write a realistic dialogue between [person a] and [person b] discussing [topic]
```

**My Example**
```
Write a realistic dialogue between a student and teacher discussing why understanding the concept of significant figures is important in scientific measurements
```

# H. Code and Technical Prompts

## 23. Code Generation

**Template:**
```
Write a [language] function that [does something]
```

**My Example**
```
Write a Python function that calculates the area of a circle given its radius
```

## 24. Debugging Help

**Template:**
```
Here is some code. Find and fix any errors:
[code snippet]
```

**My Example**
```
Here is some code. Find and fix any errors:
def calculate_velocity(distance, time):
    velocity = distance / time
    return velocity

result = calculate_velocity(100, 0)
print(result)
```

## 25. API Documentation

**Template:**
```
Explain how to use the [api name] with an example request and response
```

**My Example**
```
Explain how to use a scientific calculator API for trigonometric functions with an example request and response
```

# I. Marketing & Business Prompts

## 26. Ad Copywriting

**Template:**
```
Write a compelling Ad for [product/service] targeting [audience]
```

**My Example**
```
Write a compelling ad for a science tutoring program targeting grade 10 students struggling with chemistry concepts
```

## 27. Product Description

**Template:**
```
write a persuasive product description for [product name]
```

**My Example**
```
Write a persuasive product description for a digital microscope designed for high school biology classes
```

## 28. Social Media Post

**Template:**
```
Create a social media post promoting [event/product/idea] in a friendly tone.
```

**My Example**
```
Create a social media post promoting our upcoming science fair in a friendly tone.
```

# J. Customer Support and Service Prompts

## 29. Response to Complaint

**Template:**
```
Respond professional to this customer complaint:
[customer message here]:
```

**My Example**
```
Respond professionally to this parent complaint:
"My child says the math homework is too difficult and spends 3 hours every night struggling with it. This is affecting their sleep and stress levels."
```

## 30. FAQ Generator

**Template:**
```
Generate 5 Common FAQs and Answers for [topic/product]
```

**My Example**
```
Generate 5 common FAQs and answers for grade 10 students about preparing for the chemistry unit test
```

# K. Education and Tutoring Prompts

## 31. Lesson Plan Creation

**Template:**
```
Create a lesson plan for teaching [topic] to [grade level].
```

**My Example**
```
Create a lesson plan for teaching the law of conservation of energy to grade 10 students.
```

## 32. Quiz Generation

**Template:**
```
Generate a 5 question quiz about [subject/topic]
```

**My Example**
```
Generate a 5 question quiz about quadratic equations for grade 10 students
```

## 33. Homework Help

**Template:**
```
Explain how to solve this [math/science] problem:
[Question here]
```

**My Example**
```
Explain how to solve this physics problem:
A car accelerates from rest to 25 m/s in 10 seconds. What is its acceleration?
```

# L. Advanced Framework Based Templates

## 34. ReAct Framework

**Template:**
```
Thought: [Model thinks about what to do next]
Action: [Model takes an action]
Observation: [result of the action]
Answer: [final answer]
Simulate the agent Behaviour manually
```

**My Example**
```
Thought: The student is struggling with balancing chemical equations
Action: I'll provide a step-by-step method for balancing equations
Observation: The student successfully balanced a simple equation
Answer: The student now understands the basic principle of conservation of mass in chemical reactions
Simulate the agent behavior manually
```

**My Example 2**
```
You are an AI-powered customer support agent for [Company/Product].  
When a customer asks a question, follow this Reasoning and Action framework:  

Question: {customer question}
Thought: (Think through what the question is asking. Identify if you need to retrieve external information or if you already know the answer.)
Action: (If needed, perform an action — like lookup, search knowledge base, or retrieve from product FAQ. If no action is needed, write "None.")
Observation: (State what you found from the action, if any. If no action, write "N/A.")
Thought: (Reflect on the observation. Is it enough to answer the question? Do you need more info?)
Action: (Optional: If further action is needed, perform it.)
Observation: (Result of the second action, if any.)
Answer: (Finally, state the final, complete answer to the customer.)
```

## 35. Tree-of-Thoughts (ToT)

**Template:**
```
Generate 3 possible solutions to [problem]. Evaluate each and choose the best one.
```

**My Example**
```
Generate 3 possible solutions to help students remember the order of operations in mathematics. Evaluate each and choose the best one.
```

## 36. Self-Consistency Prompting

**Template:**
```
Solve the following question in 3 different ways and pick the most consistent answer
[Question here]
```

**My Example**
```
Solve the following question in 3 different ways and pick the most consistent answer
What is the molarity of a solution containing 58.5g of NaCl dissolved in 500mL of water?
```

# M. Prompt Optimization and Evaluation

## 37. Prompt Refinement

**Template:**
```
Improve this prompt: [Original prompt]

Make it cleaner, more specific, and structured
```

**My Example**
```
Improve this prompt: "Tell me about cells"

Make it cleaner, more specific, and structured
```

## 38. Prompt Grading Rubric

**Template:**
```
Rate the output based on the following criteria (1 - 5)

Relevance: ______________
Accuracy: ______________
Clarity: ______________
Fluency: ______________
Creativity: ______________
Final Score: ______________
```

**My Example**
```
Rate the student's explanation of photosynthesis based on the following criteria (1 - 5)

Scientific Accuracy: ______________
Clarity of Explanation: ______________
Use of Scientific Terminology: ______________
Completeness: ______________
Organization: ______________
Final Score: ______________
```

## 39. Prompt Iteration Challenge

**Template:**
```
Take this weak prompt: "[Prompt]"
Now rewrite it 3 times to improve clarity and effectiveness
```

**My Example**
```
Take this weak prompt: "Explain math stuff"
Now rewrite it 3 times to improve clarity and effectiveness
```

# N. Real World Application Prompts

## 40. Job Posting Creation

**Template:**
```
Write a job posting for [position] at [company]. Include Roles & Responsibilities, benefits and perks
```

**My Example**
```
Write a job posting for a laboratory technician at a high school. Include roles & responsibilities, benefits and perks
```

## 41. Resume Summary Builder

**Template:**
```
Create a Professional summary for a resume based on the following details
[experience, skills and achievements]
```

**My Example**
```
Create a professional summary for a resume based on the following details
5 years teaching experience, expertise in chemistry and biology, developed innovative lab experiments, improved student test scores by 20%, certified in laboratory safety
```

## 42. Business Proposal

**Template:**
```
Write a proposal for [project idea] to [client/investor]. Include objectives, methodology and benefits.
```

**My Example**
```
Write a proposal for implementing a new science laboratory equipment program to the school board. Include objectives, methodology and benefits.
```

# O. Miscellaneous Useful Templates

## 43. Opinion Writing

**Template:**
```
Write an opinion piece on [topic]. Use a persuasive arguments and examples
```

**My Example**
```
Write an opinion piece on the importance of hands-on laboratory experiments in science education. Use persuasive arguments and examples
```

## 44. Debate Preparation

**Template:**
```
Prepare arguments for both sides of the debate: "[debate topic]"
```

**My Example**
```
Prepare arguments for both sides of the debate: "Should genetic engineering be used to enhance human capabilities?"
```

## 45. Travel Planning

**Template:**
```
Plan a 5 day trip to [destination] for [type of travel]. Include activities, budget and tips.
```

**My Example**
```
Plan a 5 day educational field trip to the local science center and natural history museum for grade 10 students. Include activities, budget and tips.
```

## 46. Book/Movie Review

**Template:**
```
Write a review of "[book/movie]". Include plot summary, strengths, weakness, and recommendations
```

**My Example**
```
Write a review of "The Martian" focusing on its scientific accuracy. Include plot summary, strengths, weaknesses, and recommendations for use in science class
```

## 47. Personal Development

**Template:**
```
Give me actionable advice on how to [goal], including daily habits and mindset shifts.
```

**My Example**
```
Give me actionable advice on how to improve student engagement in science classes, including daily habits and mindset shifts.
```

# P. Prompt Chaining Examples

## 48. Multi-step Research Task

**Template:**
```
Step 1: Find out top 5 causes of climate change
Step 2: based on those causes, suggest 5 practical solutions individuals can adopt
```

**My Example**
```
Step 1: Identify the top 5 most common misconceptions students have about atomic structure
Step 2: Based on those misconceptions, create 5 targeted teaching strategies to address them
```

## 49. Idea to Execution

**Template:**
```
Step 1: Generate 5 business ideas for eco friendly products
Step 2: pick one idea and create a business strategy for it
```

**My Example**
```
Step 1: Generate 5 creative lab experiment ideas for teaching chemical reactions
Step 2: Pick one experiment and create a detailed lesson plan with safety procedures and learning objectives
```

## 50. Universal Prompt Generator

**Template:**
```
[Role] + [Task] + [Context] + [Example] + [Format/Tone]
Example:
You are a nutritionist. Create a weekly meal plan for someone with diabetes. Include breakfast, lunch, dinner, and snacks. Format as a table.
```

**My Example**
```
You are a grade 10 science teacher. Create a study guide for the upcoming unit test on ecosystems. Include key terms, important concepts, and practice questions. The guide should be comprehensive but easy to follow, helping students who struggle with biology concepts. Format as a structured document with clear headings and bullet points.
```
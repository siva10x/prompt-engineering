# RTCFR Prompt Engineering Technique Notes

## 📌 What is RTCFR?
**RTCFR** is a structured framework for writing high-quality, reliable prompts for AI language models. It stands for:

- **R** → Role  
- **T** → Task  
- **C** → Context  
- **F** → Few Shots (Examples)  
- **R** → Report/Tone  

This technique ensures clarity, precision, and consistency in AI-generated responses.

## 📖 Components Explained

### 🟢 **R → Role**
**Define the role you want the AI to adopt.**  
Helps tailor the model’s behavior and perspective.

**Example:**  
- *You are a senior Python developer.*  
- *You are a friendly English grammar tutor for grade 6 students.*


### 🟢 **T → Task**
**Clearly state what you want the AI to do.**  
Be direct and action-oriented.

**Example:**  
- *Explain the concept of recursion with a simple example.*  
- *Create a motivational Instagram caption.*


### 🟢 **C → Context**
**Provide relevant background information.**  
Helps the AI generate relevant, accurate, and on-topic outputs.

**Example:**  
- *The audience is beginner programmers with no prior experience.*  
- *The target users are small business owners looking to automate support tasks.*


### 🟢 **F → Few Shots (Examples)**
**Give a few sample inputs and expected outputs (if needed).**  
Demonstrates the kind of response you expect.  
*Optional but highly useful for complex or stylistic prompts.*

**Example:**  

**Input:** `Convert "I eating now" to correct English.`  
**Output:** `I am eating now.`


### 🟢 **R → Report / Tone**
**Specify the tone or style of the response you need.**  
Ensures consistency in personality and delivery.

**Example:**  
- *Use a warm and encouraging tone.*  
- *Keep the explanation concise and professional.*  
- *Sound like a witty, playful social media manager.*


## 📑 RTCFR Prompt Template  

```
You are a [ROLE].  
Your task is to [TASK].  
[CONTEXT]  
Here are some examples:  
[FEW SHOTS]

Use a [TONE/REPORT] tone in your response.
```


## 📊 Example RTCFR Prompt  

**Prompt:**  
```
You are an experienced career coach.  
Your task is to write a LinkedIn post to inspire fresh graduates looking for their first job.  
Context: The job market is competitive, and many students feel anxious about starting their careers.  
Here’s an example:  
"Your first job doesn’t define your entire career. Every role is a stepping stone."  

Use a positive and motivational tone.
```

## ✅ Benefits of RTCFR

- Reduces ambiguity  
- Increases response accuracy  
- Controls tone and style  
- Enhances AI alignment to your intent  
- Easy to adapt for varied use cases (marketing, code, content creation, teaching, etc.)


## 📌 When to Use RTCFR?
- When you need precise, reliable AI outputs  
- For professional content, copywriting, educational explanations, or code generation  
- While creating reusable prompt templates for teams or products  
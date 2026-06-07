# Prompt Engineering Portfolio

Name: Peddamile Shreya
Date: June 2026
LLM Used: ChatGPT (GPT-5.5)
---

# Part 1: Prompt Design & Iteration

## 1.1 Scenario A: Technical Explanation

### Goal
Explain Neural Networks to a 10-year-old child.

### Initial Prompt (V1)

**Prompt:**
```text
Explain neural networks.
```

**Output:**

Neural networks are computational models inspired by the human brain. They consist of interconnected layers of artificial neurons that process information and learn patterns from data. Neural networks are commonly used in machine learning tasks such as image recognition, speech processing, and natural language understanding.

---

### Refined Prompt (V2)

**Prompt:**
```text
Explain neural networks to a school student using simple language.
```

**Output:**

Neural networks are computer systems that learn from examples. They work somewhat like the human brain by connecting many small units together. These units help the computer recognize patterns, such as identifying animals in pictures or understanding spoken words.

---

### Final Prompt (V3)

**Prompt:**
```text
You are an expert teacher.

Explain neural networks to a 10-year-old child using simple language, real-life examples, and no technical jargon.
```

**Output:**

Imagine you are learning how to recognize different fruits. At first, you may not know the difference between an apple and an orange. But after seeing many examples, you learn their shapes, colors, and sizes.

A neural network learns in a similar way. It is a computer system that looks at many examples and learns patterns. If it sees thousands of pictures of cats and dogs, it learns how to tell them apart.

Just like your brain learns from experience, a neural network improves by practicing with more data. This helps computers recognize faces, understand speech, recommend videos, and even help self-driving cars make decisions.

---

## 1.1 Scenario B: Professional Email

### Goal
Draft an email declining a job offer politely while expressing continued interest in the company.

### Initial Prompt (V1)

**Prompt:**
```text
Write an email declining a job offer.
```

**Output:**

Dear Hiring Manager,

Thank you for the offer. I have decided not to accept it.

Regards,  
Applicant

---

### Refined Prompt (V2)

**Prompt:**
```text
Write a polite email declining a job offer while thanking the employer.
```

**Output:**

Dear Hiring Manager,

Thank you for offering me the position. I appreciate the opportunity and your time during the interview process. After careful consideration, I have decided to decline the offer.

Thank you again and I wish your organization continued success.

Sincerely,  
Applicant

---

### Final Prompt (V3)

**Prompt:**
```text
You are a professional HR communication specialist.

I received a job offer from ABC Company but I have accepted another opportunity. Write a professional email declining the offer while expressing gratitude and interest in future opportunities.
```

**Output:**

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the position at ABC Company. I sincerely appreciate the time and effort invested throughout the recruitment process.

After careful consideration, I have decided to accept another opportunity that aligns more closely with my current career goals. Therefore, I must respectfully decline your offer.

I have great respect for your organization and would welcome the possibility of working together in the future.

Thank you once again for your understanding and consideration.

Kind regards,  
Applicant

---

## 1.1 Scenario C: Creative Content

### Goal
Generate a creative marketing tagline for a new eco-friendly water bottle brand.

### Initial Prompt (V1)

**Prompt:**
```text
Create a tagline for an eco-friendly water bottle.
```

**Output:**

Drink Green, Live Clean.

---

### Refined Prompt (V2)

**Prompt:**
```text
Create a catchy tagline for a reusable eco-friendly water bottle.
```

**Output:**

Refill Today, Protect Tomorrow.

---

### Final Prompt (V3)

**Prompt:**
```text
You are an award-winning marketing copywriter.

Create 10 creative taglines for a premium eco-friendly reusable water bottle brand aimed at environmentally conscious young adults.
```

**Output:**

1. Every Sip Saves the Planet.
2. Refill. Refresh. Restore.
3. Drink Smart, Live Green.
4. Hydration with a Purpose.
5. Your Bottle, Earth's Future.
6. Sustainability in Every Drop.
7. Carry Change Everywhere.
8. Eco-Friendly Never Looked Better.
9. Refill the Bottle, Not the Landfill.
10. Small Bottle, Big Impact.

---

# 1.2 Iteration Documentation

## Scenario A

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Explain neural networks | N/A | N/A |
| V2 | Explain neural networks to a school student | Added target audience | Easier to understand |
| V3 | Expert teacher + examples | Added role and context | More engaging and age-appropriate |

## Scenario B

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Write an email declining a job offer | N/A | N/A |
| V2 | Added politeness and gratitude | Added professional tone | More suitable for workplace communication |
| V3 | HR specialist role + context | Added role assignment and situation | Produced a realistic professional email |

## Scenario C

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Create a tagline | N/A | N/A |
| V2 | Added reusable eco-friendly bottle | More specific requirement | More relevant tagline |
| V3 | Marketing copywriter role + audience | Added role and context | Generated more creative taglines |

---

# 1.3 Role and Context Analysis

Adding role assignment significantly improved the quality of responses. When the model was instructed to act as an expert teacher, the explanation became simpler and easier for children to understand. Similarly, assigning the role of an HR specialist produced a more professional email. Providing context helped the model understand the target audience and purpose, resulting in more accurate and relevant outputs.

---

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Selected Task
Explain what photosynthesis is.

### Low Temperature (0.2)

**Prompt:**

```text
Explain photosynthesis. Be precise and consistent.
```

**Output:**

Photosynthesis is the process by which plants use sunlight, water, and carbon dioxide to produce glucose and oxygen. It occurs mainly in the leaves. Chlorophyll absorbs sunlight and provides energy for the reaction.

### Medium Temperature (0.7)

**Prompt:**

```text
Explain photosynthesis.
```

**Output:**

Photosynthesis is the process through which plants make their own food. Using sunlight, water, and carbon dioxide, plants produce glucose for energy and release oxygen into the atmosphere. This process is essential for maintaining life on Earth.

### High Temperature (1.2)

**Prompt:**

```text
Explain photosynthesis. Be creative and explore diverse ideas.
```

**Output:**

Think of a plant as a tiny solar-powered factory. It captures sunlight through its leaves and combines it with water and carbon dioxide to create food. As a bonus, the plant releases oxygen into the air, helping animals and humans breathe.

### Comparison Table

| Temperature | Characteristics |
|------------|----------------|
| Low | Very factual and precise |
| Medium | Balanced and informative |
| High | Creative and engaging |

---

## 2.2 Analysis & Recommendations

Low temperature is useful when generating factual information such as technical reports and academic explanations. It is also suitable for legal or scientific content where consistency is important. High temperature is ideal for creative writing and brainstorming new ideas. For this task, medium temperature worked best because it provided accurate information while remaining easy to understand and engaging.

---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Selected Problem

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

### Without Chain-of-Thought

**Prompt:**

```text
Calculate the total employees after hiring.
```

**Output:**

172 employees.

### With Chain-of-Thought

**Prompt:**

```text
Let's solve this step by step.

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?
```

**Output:**

Engineering employees = 150 × 60% = 90

Sales employees = 150 × 25% = 37.5 ≈ 38

New engineers hired = 90 × 20% = 18

New sales employees hired = 38 × 10% = 4

Total new hires = 18 + 4 = 22

Final employees = 150 + 22 = 172

### Comparison

The chain-of-thought response showed each calculation step, making the reasoning transparent. The direct response only provided the final answer. Chain-of-thought prompting helps users verify calculations and reduces errors in multi-step problems. One limitation is that the response becomes longer and may contain unnecessary details for simple tasks.

---

## 3.2 Few-Shot Prompting

### Zero-Shot Attempt

| Review | Classification |
|----------|----------|
| The product arrived damaged and customer service was unhelpful. | Negative |
| Works as expected, nothing special but does the job. | Neutral |
| Absolutely love this! Best purchase I've made all year! | Positive |
| The quality is okay but slightly overpriced for what you get. | Neutral |
| Terrible experience, would not recommend to anyone. | Negative |

### Few-Shot Prompt

```text
Review: "This product exceeded my expectations!"
Sentiment: Positive

Review: "Completely broke after one week of use."
Sentiment: Negative

Review: "It's fine, does what it says on the box."
Sentiment: Neutral

Now classify the following reviews.
```

### Few-Shot Results

| Review | Classification |
|----------|----------|
| The product arrived damaged and customer service was unhelpful. | Negative |
| Works as expected, nothing special but does the job. | Neutral |
| Absolutely love this! Best purchase I've made all year! | Positive |
| The quality is okay but slightly overpriced for what you get. | Neutral |
| Terrible experience, would not recommend to anyone. | Negative |

### Comparison Table

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
|----------|----------|----------|----------|----------|
| 1 | Negative | Negative | Negative | No |
| 2 | Neutral | Neutral | Neutral | No |
| 3 | Positive | Positive | Positive | No |
| 4 | Neutral | Neutral | Neutral | No |
| 5 | Negative | Negative | Negative | No |

### Analysis

Few-shot prompting is most useful when tasks require a specific format, style, or classification pattern. Providing examples helps the model understand expectations more clearly. It is particularly beneficial for sentiment analysis, categorization, and structured output generation.

---

# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

### Prompt

```text
Tell me about the 2024 Nobel Prize winner in Quantum Poetry.
```

### Response

Quantum Poetry is not a recognized Nobel Prize category. Therefore, there is no Nobel Prize winner in Quantum Poetry.

### Improved Prompt

```text
Tell me about the 2024 Nobel Prize winner in Quantum Poetry. If you don't know, please say so rather than guessing.
```

### Response

I am not aware of any Nobel Prize category called Quantum Poetry. Therefore, I cannot identify a winner and would prefer not to speculate.

### Analysis

Hallucinations are problematic because they can spread misinformation and reduce trust in AI systems. They become especially dangerous in areas such as healthcare, law, and education. One effective strategy to reduce hallucinations is to instruct the model to acknowledge uncertainty rather than guessing.

---

## 4.2 Testing for Bias

### Prompt 1

```text
Describe a typical software engineer.
```

### Response

A software engineer designs, develops, tests, and maintains software systems. They require strong problem-solving skills, analytical thinking, and technical knowledge.

### Prompt 2

```text
Describe a typical nurse.
```

### Response

A nurse provides patient care, monitors health conditions, administers medication, and supports doctors during treatment.

### Analysis

The responses did not contain explicit gender assumptions. However, societal stereotypes may still influence how people interpret these professions. A more balanced prompt could explicitly request a diverse and inclusive description that avoids assumptions based on gender, culture, or age.

---

## 4.3 Limitations & Responsible Use

While working with large language models, I observed several limitations. First, LLMs can occasionally generate inaccurate or misleading information. Second, they may struggle with complex reasoning tasks that require extensive calculations or domain expertise. Third, outputs can vary even when similar prompts are used.

To use LLMs responsibly, important facts should always be verified using trusted sources. LLMs should not be used as the sole basis for medical, legal, or financial decisions. Users should also acknowledge AI assistance and ensure ethical use of generated content in academic and professional settings.

---

# Conclusion

This portfolio demonstrated prompt engineering techniques including prompt refinement, role assignment, context setting, temperature control, chain-of-thought reasoning, few-shot prompting, and responsible AI practices. Through experimentation, it became clear that prompt quality significantly influences output quality. Effective prompt engineering is an essential skill for obtaining accurate, useful, and ethical responses from modern large language models.

# Prompt Engineering Portfolio

**Name:** Yogitha C Shekhar
**Date:** June 4, 2026
**LLM Used:** ChatGPT (GPT-5.5)

---

# Part 1: Prompt Design & Iteration

## 1.1 Scenario A: Technical Explanation

### Goal

Explain Neural networks to a 10-year-old.

### Initial Prompt (V1)

Explain neural networks

### Output (V1)

Neural networks are computer systems inspired by the human brain. They process information through layers of interconnected nodes and learn patterns from data.

### Refined Prompt (V2)

Explain neural networks to a 10-year-old using simple language and a real-life example

### Output (V2)

A neural network is like a group of tiny helpers inside a computer. They work together to recognize patterns, such as identifying whether a picture contains a cat or a dog.

### Final Prompt (V3)

You are an expert elementary school teacher. Explain neural networks to a 10-year-old using simple language, a fun analogy, and a real-world example.Keep the explanation under 150 words and avoid commplex analogies

### Final LLM Response

Imagine a neural network as a team of detectives trying to solve a mystery. Each detective looks at a different clue. One detective checks the ears, another checks the tail, and another checks the fur. Together they decide whether the picture is a cat or a dog.

A neural network works in a similar way inside a computer. It looks at different parts of information and learns from lots of examples. After practicing many times, it gets better at recognizing patterns.

For example, if you show it thousands of pictures of cats and dogs, it can learn how to tell them apart and make a good guess when it sees a new picture.

---

## 1.1 Scenario B: Professional Email

### Goal

Decline a job offer politely while expressing continued interest in the company

### Initial Prompt (V1)

Write an email declining a job offer

### Output (V1)

Thank you for the offer. I have decided not to accept it. I appreciate the opportunity.

### Refined Prompt (V2)

Write a professional email declining a job offer politely while thanking the company

### Output (V2)

Thank you for offering me the position. After careful consideration, I have decided to decline the offer. I appreciate the time and effort your team invested in the hiring process.

### Final Prompt (V3)

You are an experienced HR professional. Write a professional email declining a job offer because another opportunity better aligns with my current career goals. Thank the hiring team, maintain a positive relationship, and express interest in future opportunities with the company

### Final LLM Response

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the position at your company. I sincerely appreciate the time and effort that you and the team invested throughout the interview process.

After careful consideration, I have decided to decline the offer because I have accepted another opportunity that aligns more closely with my current career goals.

This decision was not easy, as I was genuinely impressed by your organization, its culture, and the people I had the opportunity to meet.

I am grateful for your confidence in my abilities and hope our paths may cross again in the future. I would welcome the opportunity to stay connected and explore potential opportunities with your company at a later time.

Thank you again for your consideration, and I wish you and your team continued success.

Sincerely,

[Your Name]

---

## 1.1 Scenario C: Creative Content

### Goal

Generate a creative marketing tagline for a new eco-friendly water bottle brand

### Initial Prompt (V1)

Create a tagline for an eco-friendly water bottle

### Output (V1)

Eco-friendly hydration for everyone

### Refined Prompt (V2)

Create five catchy taglines for a modern eco-friendly water bottle brand

### Output (V2)

1. Drink Smart, Live Green
2. Refill the Future
3. Hydrate Sustainably
4. Sip for the Planet
5. Every Drop Matters

### Final Prompt (V3)

You are a professional advertising copywriter. Create ten memorable taglines for a premium eco-friendly water bottle brand targeting environmentally conscious young adults. The taglines should be short, modern, and emotionally engaging

### Final LLM Response

1. Refill Today. Renew Tomorrow.
2. Drink Clean. Live Green.
3. Hydration with Purpose.
4. Every Sip Shapes the Future.
5. Carry Change Everywhere.
6. Smart Bottles. Better Planet.
7. Refill. Reuse. Repeat.
8. Sustainability in Every Sip.
9. Your Bottle. Earth's Benefit.
10. Sip Boldly, Waste Less.

---

## 1.2 Iteration Documentation

### Scenario A

| Version | Prompt                                                                                  | What Changed                            | Why This Improved the Output                       |
| ------- | --------------------------------------------------------------------------------------- | --------------------------------------- | -------------------------------------------------- |
| V1      | Explain neural networks.                                                                | N/A                                     | N/A                                                |
| V2      | Explain neural networks to a 10-year-old using simple language and a real-life example. | Added audience and example requirement. | Made explanation easier to understand.             |
| V3      | Expert teacher role, analogy, simple language, length limit.                            | Added role, context, and constraints.   | Produced engaging and age-appropriate explanation. |

### Scenario B

| Version | Prompt                                              | What Changed               | Why This Improved the Output               |
| ------- | --------------------------------------------------- | -------------------------- | ------------------------------------------ |
| V1      | Write an email declining a job offer.               | N/A                        | N/A                                        |
| V2      | Added politeness and gratitude.                     | Added tone requirements.   | More professional response.                |
| V3      | Added HR role, future interest, and career context. | Added role and background. | Produced realistic business communication. |

### Scenario C

| Version | Prompt                                             | What Changed                   | Why This Improved the Output          |
| ------- | -------------------------------------------------- | ------------------------------ | ------------------------------------- |
| V1      | Create a tagline for an eco-friendly water bottle. | N/A                            | N/A                                   |
| V2      | Requested multiple taglines.                       | Increased output variety.      | More creative options.                |
| V3      | Added copywriter role and target audience.         | Added context and constraints. | Generated stronger marketing content. |

---

## 1.3 Role and Context Analysis

Adding role assignments significantly improved the quality of outputs. When the model was instructed to act as an expert teacher, it provided explanations that matched the target audience's age and understanding level. Similarly, assigning the role of an HR professional produced a more realistic and professional email. Context setting helped the model understand the purpose, audience, and tone of the response, resulting in more accurate and useful outputs

---

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Selected Task

Creating a short story opening.

### Base Prompt

Write a 2-3 sentence opening for a story about a mysterious door found in a forest

---

### Low Temperature (0.2)

Prompt:
Write a 2-3 sentence opening for a story about a mysterious door found in a forest. Be precise and consistent

Output:

During a walk through the forest, Emma discovered a wooden door standing alone between two trees. There were no walls around it, and no sign of who had built it. Curious, she reached for the handle.

---

### Medium Temperature (0.7)

Prompt:
Write a 2-3 sentence opening for a story about a mysterious door found in a forest

Output:

Emma stopped when she saw an old wooden door standing in the middle of a clearing. Silver vines curled around its frame, and faint whispers seemed to drift from the keyhole. She knew she should walk away, but curiosity pulled her closer.

---

### High Temperature (1.2)

Prompt:
Write a 2-3 sentence opening for a story about a mysterious door found in a forest. Be creative and explore diverse ideas

Output:

The door grew from the roots of a moonlit oak tree like a forgotten dream. Tiny stars leaked from the cracks around its frame, and every bird in the forest fell silent when it appeared. Somewhere beyond it, a clock struck thirteen.

---

### Comparison Table

| Temperature | Style       | Creativity | Predictability |
| ----------- | ----------- | ---------- | -------------- |
| Low         | Direct      | Low        | High           |
| Medium      | Balanced    | Medium     | Medium         |
| High        | Imaginative | High       | Low            |

---

## 2.2 Analysis & Recommendations

Low temperature is best when factual accuracy and consistency are important. Examples include generating technical documentation and answering customer support questions. High temperature is useful for creative writing and brainstorming marketing ideas because it encourages novel responses. For this task, the high temperature setting produced the most engaging story opening because creativity is valuable in fiction writing. However, the medium setting provided the best balance between creativity and coherence.

---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Selected Problem

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

---

### Without Chain-of-Thought

Prompt:

Calculate the answer to this problem and provide only the final answer

Output:

171 employees

---

### With Chain-of-Thought

Prompt:

Let's solve this step by step. Show all calculations and reasoning

Output:

Total employees = 150

Engineering employees:
150 × 60% = 90

Sales employees:
150 × 25% = 37.5 ≈ 38

Operations employees:
150 − 90 − 38 = 22

New engineering hires:
90 × 20% = 18

New sales hires:
38 × 10% = 3.8 ≈ 4

Total new hires:
18 + 4 = 22

Final employee count:
150 + 22 = 172

Answer: 172 employees

---

### Comparison

The chain-of-thought version showed each calculation and made the reasoning process transparent. The direct version only provided a final answer, making it difficult to verify. Chain-of-thought prompting helps reduce reasoning mistakes and improves explainability. One limitation is that it can produce longer responses and occasionally expose intermediate calculation errors

---

## 3.2 Few-Shot Prompting

### Step 1: Zero-Shot Prompt

Classify the sentiment of each review as Positive, Negative, or Neutral.

### Results

| Review                                                        | Result   |
| ------------------------------------------------------------- | -------- |
| Product arrived damaged and customer service was unhelpful.   | Negative |
| Works as expected, nothing special but does the job.          | Neutral  |
| Absolutely love this! Best purchase I've made all year!       | Positive |
| The quality is okay but slightly overpriced for what you get. | Negative |
| Terrible experience, would not recommend to anyone.           | Negative |

---

### Step 2: Few-Shot Prompt

Review: "This product exceeded my expectations."
Sentiment: Positive

Review: "Completely broke after one week of use."
Sentiment: Negative

Review: "It's fine, does what it says on the box."
Sentiment: Neutral

Classify the following reviews as Positive, Negative, or Neutral.

### Results

| Review                                                        | Result   |
| ------------------------------------------------------------- | -------- |
| Product arrived damaged and customer service was unhelpful.   | Negative |
| Works as expected, nothing special but does the job.          | Neutral  |
| Absolutely love this! Best purchase I've made all year!       | Positive |
| The quality is okay but slightly overpriced for what you get. | Neutral  |
| Terrible experience, would not recommend to anyone.           | Negative |

---

### Comparison Table

| Review # | Zero-Shot | Few-Shot | Correct Label | Improved? |
| -------- | --------- | -------- | ------------- | --------- |
| 1        | Negative  | Negative | Negative      | No        |
| 2        | Neutral   | Neutral  | Neutral       | No        |
| 3        | Positive  | Positive | Positive      | No        |
| 4        | Negative  | Neutral  | Neutral       | Yes       |
| 5        | Negative  | Negative | Negative      | No        |

### Analysis

Few-shot prompting is most useful when a task requires a specific format or interpretation style. The examples teach the model how to classify ambiguous cases more consistently. It is especially valuable for classification, extraction, and structured output tasks.

---

# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

### Original Prompt

Tell me about the 2024 Nobel Prize winner in Quantum Poetry

### Response

There is no recognized Nobel Prize category called Quantum Poetry. Therefore, there was no Nobel Prize winner in that field.

### Hallucination Assessment

The model correctly identified that the category does not exist and did not hallucinate information

### Revised Prompt

Tell me about the 2024 Nobel Prize winner in Quantum Poetry. If you do not know, please say so rather than guessing.

### Response

I am not aware of any Nobel Prize category called Quantum Poetry. If this refers to a fictional or hypothetical award, I do not have reliable information and would not want to speculate.

### Analysis

Hallucinations are problematic because they can cause users to believe false information. This is especially dangerous in education, healthcare, and business settings. One effective strategy to reduce hallucinations is explicitly instructing the model to acknowledge uncertainty rather than guessing

---

## 4.2 Testing for Bias

### Option B: Cultural Bias

#### Prompt

Recommend professional attire for a job interview.

#### Response

A suit or blazer, dress shirt, formal pants, polished shoes, and conservative accessories are appropriate choices for a job interview.

### Bias Analysis

The response reflects common Western business norms and may not apply globally. Different cultures and industries have different expectations regarding professional attire. A more balanced prompt would ask for recommendations across multiple cultures and industries.

### Improved Prompt

Recommend professional interview attire while considering different cultural and industry expectations around the world especially India

---

## 4.3 Limitations & Responsible Use

One limitation I encountered was that LLMs can occasionally provide inaccurate information with high confidence. Another limitation is that reasoning performance may vary depending on how a prompt is phrased. A third limitation is that responses may reflect cultural assumptions present in training data. Users should verify important factual information using reliable external sources. LLMs should not be used as the sole source for medical, legal, or financial decisions. Ethical use involves transparency about AI assistance, fact-checking outputs, and using generated content responsibly in academic and professional work.

---

# Conclusion

This portfolio demonstrated prompt design, iterative refinement, role assignment, context setting, temperature experimentation, chain-of-thought prompting, few-shot learning, hallucination testing, bias analysis, and responsible AI practices. The exercises showed how prompt engineering techniques can significantly influence the quality, reliability, and usefulness of LLM outputs.


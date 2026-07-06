## Question 1

**Answer:**  
AI Copilot has access to current Kestra plugin documentation.

**Explanation:**  
AI Copilot generates more accurate Kestra workflows because it has access to the latest Kestra plugin documentation, while ChatGPT does not automatically have this product-specific context.

---

## Question 2

**Answer:**  
Vague, generic, or fabricated — the model guesses from training data.

### Without RAG

```
Kestra 1.1 introduced several exciting new features, focusing on improving the user experience, enhancing Kestra's capabilities for complex workflows, and simplifying integration.

Here are 5 major features released in Kestra 1.1:

1. Conditional Triggers
2. Secret Management (Env/File Storage)
3. Namespace-Level Defaults
4. Flow-Level inputs and outputs
5. New ForEach Task with value Support
```

### With RAG

```
Kestra 1.1 introduced several major features.

Here are at least 5 with brief descriptions:

1. New Filters
2. No-Code Dashboard Editor
3. Multi-Agent AI Systems
4. Fix with AI
5. Human Task
6. Improved Air-Gapped Support
```

**Explanation:**  
The response of the non-RAG workflow relies only on its training data and produces a plausible answer without Kestra documentation. The RAG workflow retrieves the actual release notes from Kestra's documentation, resulting in an accurate and up-to-date answer.

---

## Question 3

**Answer:**  
60–100 tokens.

**Example:**

```
outputTokenCount: 83
```

---

## Question 4

**Answer:**  
2–5x more.

**Examples:**

**Short summary**

```
outputTokenCount: 83
```

**Long summary**

```
outputTokenCount: 198
```

---

## Question 5

**Answer:**  
2–4x more.

**1-sentence version**

```
outputTokenCount: 46
```

**3-sentence version**

```
outputTokenCount: 98
```

---

## Question 6

**Answer:**  
Use traditional task-based workflows for predictability and auditability.

**Explanation:**  
Traditional task-based workflows provide consistent, repeatable, and auditable results, which is essential for production environments with strict compliance requirements.
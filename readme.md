# Qwen3-8B Question Answering Flow
This project illustrates a flowchart for a question-answering system powered entirely by Qwen3-8B, a Large Language Model (LLM). The system is designed to handle natural language questions with reasoning, translation, domain classification, and specialized response generation all handled by Qwen3-8B.

## 🧠 Overview
All tasks in this flow are performed using the Qwen3-8B model. It processes the input, validates its format, classifies its domain, and generates answers accordingly.

## 🔄 Process Flow
1. Input Question
The user submits a natural language question.

2. Reasoning
Qwen3-8B evaluates the question and performs reasoning to understand its intent and structure.

3. Format Validation

- If the question is in the correct format, Qwen3-8B generates an answer directly.

- If the question is not in the correct format, it proceeds to:

  - Remove command & translate the question into a suitable form.

  - Classify the domain to determine whether it relates to investment or other topics.

4. Domain-Specific Handling

- If the question is related to investment, Qwen3-8B uses investment-specific knowledge.

- Otherwise, Qwen3-8B draws from its broader knowledge base (a "mixture of experts" approach).

5. Answer Generation
All answers, regardless of the flow path, are generated by Qwen3-8B.

## 🧰 Model Used
Qwen3-8B
A powerful LLM capable of handling reasoning, translation, domain classification, and answering all within a unified model.

## 🖼️ Diagram
Refer to the included image for a visual overview of the system architecture.
![image](https://github.com/user-attachments/assets/510f2068-123a-4c24-a120-b5fa848ad08a)


## 💡 Key Features
Single Model System: All tasks handled by Qwen3-8B, simplifying deployment and maintenance.

Flexible Input Handling: Can interpret, reformat, and classify a wide range of natural language questions.

Domain Awareness: Tailors answers based on topic-specific routing logic.

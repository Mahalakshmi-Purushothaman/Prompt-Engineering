# Prompt-Engineering

Prompt Engineering is the process of designing effective instructions (prompts) to guide AI models, such as ChatGPT, to generate the desired responses. It involves structuring input prompts in a way that enhances accuracy, relevance, and creativity in AI-generated outputs.

### With prompt engineering we can
  - write, refine and optimize prompts
  - enhance the interaction between human and AI
  - monitor and maintain prompts

### Why is Prompt Engineering Important?
 - Enhances AI Performance – A well-crafted prompt improves response quality.
 - Saves Time – Reduces the need for corrections and iterations.
 - Customizes AI Behavior – Directs AI towards specific tones, formats, or styles.
 - Increases Control – Ensures AI responses align with user expectations.

### Key Principles of Prompt Engineering
 - 1️⃣ Clarity and Specificity
    - Be explicit about what you want.
    - Example: ❌ Bad Prompt: "Write about Python."
               ✅ Good Prompt: "Explain Python’s object-oriented programming features with code examples."
 - 2️⃣ Contextual Information
    - Provide background details for better responses.
    - Example: ❌ Vague Prompt: "Give me a marketing strategy."
               ✅ Detailed Prompt: "Suggest a digital marketing strategy for a startup selling eco-friendly water bottles."
  - 3️⃣ Structured Output Requests
    - Specify format (bullet points, code snippets, step-by-step guides).
    - Example: Prompt: "Generate a Markdown README for a Python web scraping project, including installation, usage, and example code."
  - 4️⃣ Using Examples (Few-shot Prompting)
    - Providing examples improves AI accuracy.
    - Example: Prompt: "Translate the following sentences to Spanish: 'Hello, how are you?' → 'Hola, ¿cómo estás?'. Now translate: 'Good morning, friend!'"
  - 5️⃣ Step-by-Step Breakdown (Chain-of-Thought Prompting)
    - Asking the AI to explain its reasoning improves accuracy.
    - Example: Prompt: "Solve the math problem 24 × 17 using a step-by-step approach."

### Prompt Engineering Techniques
  - ✅ Zero-shot Prompting - No examples provided; No demonstration from human. Direct Instructions are given. AI generates a response based on prior knowledge.
    - Example: "Summarize this research paper in three sentences."
  - ✅ Few-shot Prompting - A few examples are given before the AI generates an output.
    - Example: "Translate the following:
                1. 'Good morning' → 'Buenos días'
                2. 'See you later' → 'Hasta luego'
                3. 'How are you?' →"
  - ✅ Chain-of-Thought (CoT) Prompting - enables complex reasoning capabilities through intermediate reasoning steps. You can combine it with few-shot prompting to get better results on more complex tasks that require reasoning before responding.
  - ✅ Zero-shot Chain-of-Thought (CoT) Prompting
  - ✅ Automatic Chain-of-Thought (CoT) Prompting - Auto-CoT consists of two main stages:
            Stage 1): question clustering: partition questions of a given dataset into a few clusters
            Stage 2): demonstration sampling: select a representative question from each cluster and generate its reasoning chain using Zero-Shot-CoT with simple heuristics
            The simple heuristics could be length of questions (e.g., 60 tokens) and number of steps in rationale (e.g., 5 reasoning steps). This encourages the model to use simple and accurate demonstrations.
  - ✅ Meta Prompting - focuses on the structural and syntactical aspects of tasks and problems rather than their specific content details.
            Structure-oriented: Prioritizes the format and pattern of problems and solutions over specific content.
            Syntax-focused: Uses syntax as a guiding template for the expected response or solution.
            Abstract examples: Employs abstracted examples as frameworks, illustrating the structure of problems and solutions without focusing on specific details.
            Versatile: Applicable across various domains, capable of providing structured responses to a wide range of problems.
            Categorical approach: Draws from type theory to emphasize the categorization and logical arrangement of components in a prompt.
  - ✅ Role-based Prompting - Assigning a role to AI for more tailored responses.
    - Example: "You are a cybersecurity expert. Explain the importance of encryption in online transactions."
  - ✅ Multi-turn Prompting - Using follow-up prompts to refine AI responses.
    - Example: User: "Explain quantum computing in simple terms."
                AI: "(Gives a basic explanation)"
                User: "Now explain its real-world applications."
### Real-World Applications of Prompt Engineering
  - Content Creation – Generating blogs, reports, and documentation.
  - Chatbots & Virtual Assistants – Enhancing AI-driven customer service.
  - Programming Help – Debugging and writing code snippets.
  - Data Analysis – Summarizing insights from large datasets.
  - Education – Creating study guides, quizzes, and explanations.
### Best Practices
  - Clear Instruction
  - Specify Format
  - Limit Scope
  - Avoid leading the answer
### LLM Settings
  - Temperature
  - Top P
  - Max Length
  - Stop Sequences
  - Frequency Penalty
  - Presence Penalty
### Prompt Examples
  - Text Summarization
  - Information Extraction
  - Question Answering
  - Text Classification
  - Conversation
  - Code Generation
  - Reasoning

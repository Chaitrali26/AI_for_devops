# Introduction to AI for devops

Today, we will learn about traditional AI, Gen AI, LLM, AI Landscape etc. we will see devops usecase for both traditional AI and Gen AI aswell.

## AI Landscape:
- The AI Landscape refers to the ecosystem of artificial intelligence technologies, models, applications, and their categorization based on functionality and use cases.
- Key components of AI landscape:
    1. Traditional AI
    2. Generative AI
    3. LLMs
    4. Multimodel AI
    5. Edge AI
    6. AI for Specialized Applications like healthcare, finance, autonomous system and more

## What is Traditional AI?
- AI has been around since 1950s. The term Artificial Intelligence was officially coined at the Dartmouth Conference. This conference is considered the official starting point for AI as a field of study.

- `Definition`: 
    -   Traditional AI is based on rule-based systems, decision trees, expert systems, and algorithms designed to perform specific tasks or solve problems within predefined parameters. 
    -   It operates through explicit instructions, often designed and coded by humans.
- Primary usecase of traditional AI is **to predict**. 
    - EX-1: Climate prediction has been around since a long time.
    - Ex-2: Predicting system failures before they occur.
        - `How It Works`:
            -   It uses log-based anomaly detection and pattern recognition (e.g. time-series forecasting).   
- Hence, we can say that `traditional AI` relies on `structured data, pre-defined rules, and predictive models trained on historical data to make decisions or recognize patterns.`. 
- It excels at classification, forecasting, and anomaly detection

## What is Generative AI?

- `Definition`: 
    -   Generative AI refers to a category of models and systems that can generate **new** data, such as text, images, or sound, by learning patterns from existing data.
- Primary usecase of Gen AI is **to generate**
    - Ex: ChatGPT
        - `How it works?`:
            - Generative AI models learn from large datasets and generate outputs that mimic the patterns in the data. Unlike traditional AI, it doesn't simply rely on rules but can adapt and `create new content`, making it more flexible and creative.

## What is LLM?
- LLM are part of Gen AI which deals with text generation. It uses machine learning to understand and generate human language, trained on massive datasets to perform tasks like text analysis, translation, and content creation
- Primary usecase of LLM is **to understand and generate human-like text**
    - Ex: GPT (OpenAI), PaLM (Google), and Llama (Meta) are popular examples of LLMs. 
        - `How it works?`:
            - They are trained on vast amounts of text data using deep learning (Transformer models), allowing them to learn patterns and relationships in language.


## Usecases of traditional AI and GenAI for Devops
- Tradtional AI:
    - 1. Incident Detection & Prediction
        - Ex: If CPU usage suddenly spikes beyond a threshold, AI predicts a potential issue. The system alerts DevOps teams to take preventive action.

- Gen AI:
    - AI-Powered Incident Resolution & RCA
        - When an alert is triggered in Prometheus or Datadog, AI analyzes logs and suggests possible fixes.
        -  AI-powered bots (like StackStorm + GPT) generate incident reports with resolution steps.
        - Benefit: Reduces Mean Time to Resolution (MTTR) and enhances reliability.

## Conclusion:
AI is rapidly transforming the DevOps ecosystem by automating workflows, enhancing predictive capabilities, and streamlining incident resolution. Traditional AI had helped us with anomaly detection and failure prediction, enabling proactive system monitoring, while Generative AI (Gen AI) and LLMs empower DevOps teams with automated troubleshooting, configuration generation, and intelligent documentation. As AI models evolve, integrating multimodal AI, Edge AI, and specialized AI will further enhance system efficiency, reducing operational overhead and improving reliability. By leveraging both predictive and generative AI, DevOps teams can build smarter, more resilient, and highly scalable infrastructure for the future.
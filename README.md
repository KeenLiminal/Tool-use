# Prompt Engineering Tool Prompts
##### J.A.G, 2025
This repository contains a collection of tool-based user prompts tailored for prompt engineering use cases. Each prompt is designed to assist an AI during user interactions by guiding data input and providing clear instructions. These prompts include placeholders with descriptive text to indicate where users should input specific data.

## Table of Contents

- [Overview](#overview)
- [Prompt Engineering Use Cases](#prompt-engineering-use-cases)
  - [1. Web Search for Prompt Optimization](#1-web-search-for-prompt-optimization)
  - [2. Data Analysis for Prompt Effectiveness](#2-data-analysis-for-prompt-effectiveness)
  - [3. Content Policy Guidance for Prompt Compliance](#3-content-policy-guidance-for-prompt-compliance)
  - [4. Image Generation for Visual Prompting](#4-image-generation-for-visual-prompting)
  - [5. A/B Testing Prompts Using AI](#5-ab-testing-prompts-using-ai)
  - [6. Extracting Key Phrases for Prompt Optimization](#6-extracting-key-phrases-for-prompt-optimization)
  - [7. Web Search for Model-Specific Prompting Strategies](#7-web-search-for-model-specific-prompting-strategies)
  - [8. Reverse Engineering Prompts from AI Outputs](#8-reverse-engineering-prompts-from-ai-outputs)
  - [9. Multi-Turn Conversational Prompt Testing](#9-multi-turn-conversational-prompt-testing)
  - [10. Visualizing Prompt Effectiveness](#10-visualizing-prompt-effectiveness)
  - [11. File Processing for Data Extraction](#11-file-processing-for-data-extraction)
  - [12. Document Summarization](#12-document-summarization)
  - [13. Code Debugging and Analysis](#13-code-debugging-and-analysis)
  - [14. Sentiment Analysis of User Text](#14-sentiment-analysis-of-user-text)
  - [15. Text Translation Between Languages](#15-text-translation-between-languages)
  - [16. Generating a Chatbot Conversation Script](#16-generating-a-chatbot-conversation-script)
  - [17. Data Visualization from a Dataset](#17-data-visualization-from-a-dataset)
  - [18. Converting Natural Language to SQL Queries](#18-converting-natural-language-to-sql-queries)
  - [19. Document Tagging and Annotation](#19-document-tagging-and-annotation)
  - [20. Topic Modeling on a Collection of Documents](#20-topic-modeling-on-a-collection-of-documents)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository provides a set of pre-defined, tool-based prompts designed specifically for prompt engineering tasks. Each prompt includes descriptive placeholders to guide users in supplying the necessary data. Use these templates to optimize your AI interactions, gather performance insights, and refine your prompt designs.

## Prompt Engineering Use Cases

### 1. Web Search for Prompt Optimization

**Prompt:**

> "Using the **web** tool, search for `[TOPIC OR KEYWORDS RELATED TO PROMPT ENGINEERING]` on `[SPECIFIC WEBSITE OR SEARCH ENGINE]`. Summarize the most relevant findings about `[AREA OF FOCUS, e.g., 'response clarity' or 'user engagement']`."

**Example:**

- *"Search for 'prompt engineering best practices GPT-4' on a reliable AI blog. Summarize the most relevant findings about response clarity."*

---

### 2. Data Analysis for Prompt Effectiveness

**Prompt:**

> "Using the **code interpreter** tool, analyze the dataset `[UPLOAD OR LINK TO YOUR DATASET]` that contains AI-generated responses. Identify patterns in `[DESIRED METRICS, e.g., 'accuracy', 'relevance', 'user satisfaction']`."

**Example:**

- *"Analyze the dataset ./data/responses.csv for patterns in accuracy and relevance."*

---

### 3. Content Policy Guidance for Prompt Compliance

**Prompt:**

> "Using the **guardian_tool**, verify if this prompt `[INSERT YOUR PROMPT TEXT]` aligns with content moderation guidelines for `[NAME OF PLATFORM OR POLICY SOURCE]`. Highlight any potential issues."

**Example:**

- *"Verify if the prompt 'Generate a detailed report on trending political hashtags' aligns with Twitter's content guidelines."*

---

### 4. Image Generation for Visual Prompting

**Prompt:**

> "Using the **dalle** tool, generate an image of `[SCENE OR SUBJECT]` for `[PURPOSE, e.g., 'testing multimodal capabilities']`. Provide one or two variations if possible."

**Example:**

- *"Generate an image of a futuristic cyberpunk library for testing multimodal prompting. Provide two variations."*

---

### 5. A/B Testing Prompts Using AI

**Prompt:**

> "Using the **code interpreter** tool, run an A/B test on these two prompts: `[INSERT PROMPT A]` and `[INSERT PROMPT B]`. Compare their performance based on `[PERFORMANCE METRICS, e.g., 'accuracy', 'user satisfaction']` and show a summary of the findings."

**Example:**

- *"Run an A/B test on 'Prompt A: Summarize the latest tech news' and 'Prompt B: Provide a structured summary of the latest tech news' to compare accuracy and user satisfaction."*

---

### 6. Extracting Key Phrases for Prompt Optimization

**Prompt:**

> "Using the **code interpreter** tool, process the text data `[UPLOAD OR LINK TO TEXT DATA]` containing AI-generated responses. Extract the most common key phrases to refine `[SPECIFIC AREA OF THE PROMPT OR GOAL]`."

**Example:**

- *"Process the text data ./logs/responses.txt to extract common key phrases for refining the research prompt on climate change."*

---

### 7. Web Search for Model-Specific Prompting Strategies

**Prompt:**

> "Using the **web** tool, research effective prompting strategies for `[NAME OF AI MODEL, e.g., GPT-4]`. Summarize the top three best practices that apply to `[YOUR USE CASE, e.g., 'customer support queries']`."

**Example:**

- *"Research effective prompting strategies for GPT-4. Summarize the top three best practices for customer support queries."*

---

### 8. Reverse Engineering Prompts from AI Outputs

**Prompt:**

> "Using the **code interpreter** tool, analyze the AI-generated outputs from `[LINK OR UPLOAD OUTPUT DATA]`. Infer potential prompt structures that may have produced these outputs, focusing on `[SPECIFIC FEATURES, e.g., 'tone', 'style', 'level of detail']`."

**Example:**

- *"Analyze outputs from ./logs/ai_outputs.json and infer prompt structures focusing on formal tone and detailed responses."*

---

### 9. Multi-Turn Conversational Prompt Testing

**Prompt:**

> "Using the **code interpreter** tool, simulate a multi-turn conversation with the prompt `[INSERT YOUR MULTI-TURN SCENARIO]`. Record the AI responses and evaluate `[CRITERIA, e.g., 'coherence', 'consistency']` over `[NUMBER OF TURNS, e.g., 5 turns]`."

**Example:**

- *"Simulate a multi-turn conversation for an HR chatbot scenario over 5 turns and evaluate response coherence."*

---

### 10. Visualizing Prompt Effectiveness

**Prompt:**

> "Using the **code interpreter** tool, create a visualization (e.g., a heatmap or bar chart) from `[UPLOAD OR LINK TO PROMPT-RESPONSE DATA]`. Show how different prompt variations affect `[METRIC, e.g., 'completion time', 'relevance', 'overall score']`."

**Example:**

- *"Create a heatmap based on ./data/prompt_test_results.csv showing the impact of prompt variations on user satisfaction scores."*

---

### 11. File Processing for Data Extraction

**Prompt:**

> "Using the **code interpreter** tool, extract `[TYPE OF DATA, e.g., 'email addresses', 'phone numbers']` from the file located at `[FILE PATH OR URL]`. Save the extracted data into a new file `[OUTPUT FILE PATH]`."

**Example:**

- *"Extract email addresses from ./data/user_data.txt and save them into ./data/emails.csv."*

---

### 12. Document Summarization

**Prompt:**

> "Using the **code interpreter** tool, summarize the document located at `[UPLOAD OR LINK TO DOCUMENT]` into a concise summary of `[NUMBER OF SENTENCES OR WORDS]` that captures the main points."

**Example:**

- *"Summarize the document ./reports/annual_report.pdf into a 5-sentence summary highlighting key findings."*

---

### 13. Code Debugging and Analysis

**Prompt:**

> "Using the **code interpreter** tool, analyze the following code snippet `[INSERT CODE SNIPPET]` for potential errors or improvements. Provide suggestions for debugging or refactoring."

**Example:**

- *"Analyze the code snippet provided in ./code/snippet.py and list potential improvements for performance and error handling."*

---

### 14. Sentiment Analysis of User Text

**Prompt:**

> "Using the **code interpreter** tool, perform sentiment analysis on the text `[INSERT TEXT SAMPLE]`. Classify the sentiment as `[Positive, Negative, or Neutral]` and explain the reasoning briefly."

**Example:**

- *"Analyze the sentiment of the text 'I love using this tool, it makes my life easier' and classify it as Positive."*

---

### 15. Text Translation Between Languages

**Prompt:**

> "Using the **translate_tool**, translate the text `[INSERT TEXT HERE]` from `[SOURCE LANGUAGE]` to `[TARGET LANGUAGE]`. Ensure the translation retains the original meaning and tone."

**Example:**

- *"Translate the text 'Hello, how are you?' from English to Spanish."*

---

### 16. Generating a Chatbot Conversation Script

**Prompt:**

> "Using the **code interpreter** tool, generate a conversation script for a chatbot designed for `[SPECIFIC APPLICATION, e.g., 'customer support']`. Use the scenario `[INSERT SCENARIO DESCRIPTION]` and provide at least `[NUMBER OF TURNS]` dialogue turns."

**Example:**

- *"Generate a 5-turn conversation script for a customer support chatbot handling a billing inquiry."*

---

### 17. Data Visualization from a Dataset

**Prompt:**

> "Using the **code interpreter** tool, create a visualization (e.g., scatter plot, line graph, or bar chart) from the dataset `[UPLOAD OR LINK TO DATASET]` that displays `[SPECIFIC METRICS OR DATA COLUMNS]`."

**Example:**

- *"Generate a bar chart from ./data/sales.csv showing monthly sales figures."*

---

### 18. Converting Natural Language to SQL Queries

**Prompt:**

> "Using the **code interpreter** tool, convert the natural language query `[INSERT QUERY TEXT]` into an SQL query that retrieves data from the table `[TABLE NAME]`. Ensure the query considers `[SPECIFIC CONDITIONS OR FILTERS]`."

**Example:**

- *"Convert the query 'Show me all orders placed in 2024 with a total above $100' into an SQL query for the 'orders' table."*

---

### 19. Document Tagging and Annotation

**Prompt:**

> "Using the **code interpreter** tool, analyze the document located at `[UPLOAD OR LINK TO DOCUMENT]` and tag it with `[SPECIFIC TAGS, e.g., 'important', 'to-review']` based on its content. Output the tagged document in `[FORMAT, e.g., JSON or Markdown]`."

**Example:**

- *"Tag the document ./docs/project_overview.txt with tags such as 'summary', 'important', and 'action-required' and output the results as JSON."*

---

### 20. Topic Modeling on a Collection of Documents

**Prompt:**

> "Using the **code interpreter** tool, perform topic modeling on the document collection `[UPLOAD OR LINK TO DOCUMENTS]`. Extract the top `[NUMBER]` topics and provide a brief description for each topic along with their corresponding probabilities."

**Example:**

- *"Perform topic modeling on ./data/articles.json to extract the top 5 topics and their probabilities."*

---

## Contributing

Contributions are welcome! Please fork this repository, make your changes, and open a pull request. If you have ideas for new prompts or improvements to existing ones, feel free to share them.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

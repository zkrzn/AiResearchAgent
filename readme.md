# AI Research Agent

This project implements an AI research agent that leverages the power of language models to conduct detailed research on any given topic and provide factual and data-backed results. The agent utilizes the LangChain framework, which includes various tools and functionalities to support the research process.

## Getting Started

To set up the project, follow these steps:

1. Install the required dependencies by running the following command:
   ````
   pip install -r requirements.txt
 ````

2. Set up the environment variables by creating a `.env` file and adding the following variables:
   ````python
   OPENAI_API_KEY=<your_openai_api_key>
   BROWSERLESS_API_KEY=<your_browserless_api_key>
   SERP_API_KEY=<your_serp_api_key>
   HUGGINGFACEHUB_API_TOKEN=<your_huggingfacehub_api_token>
    ````

3. Run the application using the following command:
   ````python
   streamlit run main.py
 ````

## Tools

The project provides the following tools to aid in the research process:

### 1. Search Tool

The search tool allows you to perform targeted searches for answering questions about current events and data. It is used by asking specific questions and expects targeted queries as input.

### 2. Scrape Website Tool

The scrape website tool enables you to extract data from a website and optionally summarize the content based on a given objective. It takes a URL as input and scrapes the website, providing the extracted text. If the content is too large, the tool can automatically summarize it based on the objective.

### Usage

To use the AI research agent, simply enter your research goal in the provided input field and click the "Research" button. The agent will then generate a response based on the given objective and the tools available.

## Guidelines for AI Research

When using the AI research agent, please adhere to the following guidelines:

1. Conduct thorough research to gather as much information as possible about the objective.
2. If there are relevant links and articles, scrape them to gather additional information.
3. Consider conducting additional searches and scrapes based on the collected data to enhance the research quality. Limit this process to a maximum of three iterations.
4. Only provide facts and data that have been gathered; avoid making things up.
5. Include all reference data and links in the final research output to support your findings.
6. Remember to include all reference data and links in the final research output.

Please note that the AI research agent aims to provide data-backed results but relies on the available information and tools. It is essential to critically evaluate the generated responses and verify the information independently.

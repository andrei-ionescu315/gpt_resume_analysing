# ResumeGPT - GPT-Powered Resume Auto Analysis

ResumeGPT leverages the power of Langchain and OpenAI to automate the process of resume analysis. This tool enables recruiters to efficiently process large volumes of resumes, automatically extract important features, and generate a matching score based on a predefined job description.

## Overview

The processing flow of ResumeGPT includes the following steps:

1. **Resume Vectorization**: Resume information is vectorized using the language understanding capabilities of OpenAI. These vectors are then stored in a Faiss vector database.

2. **Information Extraction**: Predefined elements are extracted from the Faiss vector database using a question-answering approach. The answers are collected and stored in a DataFrame.

3. **Comprehensive Analysis**: Using the Language Learning Model (LLM) from Langchain, the tool conducts a comprehensive analysis of the resume features and job requirements to generate a matching score. This score can be used to rank the candidates.


# ATS Resume LLM App

This is a Streamlit-based application that evaluates resumes based on a given job description (JD) using Google's Gemini-Pro language model. The app acts like an Application Tracking System (ATS), offering insights into resume improvements by identifying matching percentages, missing keywords, and generating a profile summary.

## Features

- **Job Description Matching**: Analyze the resume text to find the degree of match with the job description.
- **Missing Keywords**: Identify important keywords missing from the resume that may improve its ranking.
- **Profile Summary Generation**: Create a concise summary based on JD relevance.
- **PDF Upload**: Allows users to upload a PDF resume for evaluation.

## Requirements

- `streamlit`
- `google-generativeai`
- `dotenv`
- `PyPDF2`

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ATS-Resume-LLM-App.git
   cd ATS-Resume-LLM-App

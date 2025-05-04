This is an AI-powered solution that extracts key fields from mortgage transcripts, specifically those relevant to a 1003 loan application form. Built with a Django REST API backend and a Streamlit frontend, this tool helps automate the manual process of identifying borrower details from natural language inputs.

Features
- Extracts field_name, field_value, and confidence_score using OpenAI or Gemini API
- Validates inputs with robust error handling (empty, non-string, malformed)
- RESTful API built using Django
- Frontend built with Streamlit for easy interaction and testing
- Tested for both valid and invalid inputs (positive + negative test cases)
- Easy to deploy on Render or Streamlit Cloud

Use Case
Mortgage companies can use this tool to automatically pre-fill forms from customer call transcripts or chat logs, reducing processing time and errors in loan origination.


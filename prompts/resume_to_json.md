# Resume to JSON Generator

## Goal
Convert an unstructured resume into a structured JSON object
that can be reused programmatically.

## Prompt Template
Extract information from the resume below and return **only valid JSON**
using the following schema exactly:

{
  "name": "",
  "email": "",
  "phone": "",
  "skills": [],
  "experience": [
    {
      "role": "",
      "company": "",
      "duration": "",
      "responsibilities": []
    }
  ],
  "education": []
}

Rules:
- Use null if information is missing
- Do not add explanations
- Output must be valid JSON

Resume:
[paste resume here]

## Expected Output
A clean JSON object matching the schema.

## Improvement Notes
- Add strict field validation
- Add optional fields for certifications

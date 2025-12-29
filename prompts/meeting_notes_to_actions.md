# Meeting Notes to Action Items Generator

## Goal
Extract clear, actionable tasks from unstructured meeting notes.

## Prompt Template
From the meeting notes below, extract action items.
Return the output using this format only:

- Action:
- Owner:
- Deadline:

Rules:
- If owner or deadline is missing, write "Not specified"
- Do not summarize discussion
- Only list actions

Meeting Notes:
[paste meeting notes here]

## Expected Output
A clean list of actionable tasks.

## Improvement Notes
- Add priority levels
- Add follow-up questions for missing info

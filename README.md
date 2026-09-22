# student-feedback-ai-automation
# AI Student Feedback Automation

An AI-powered student feedback automation built with **n8n** and **OpenRouter**.

## What it does

The workflow receives student feedback through an n8n form, sends the feedback to an AI model for processing, and returns a structured response.

The AI produces:

* A summary of the student's feedback
* A category for the feedback
* A recommended next step

## Workflow

```text
Student Feedback Form
        ↓
OpenRouter AI
        ↓
Final Output
```

## Technologies

* n8n
* OpenRouter
* AI/LLM
* n8n Form Trigger

## AI Instructions

The AI is instructed to summarize the feedback, identify its category, and suggest a useful next step. It is also instructed not to invent information and to request more information when the user's input is unclear.

## Testing

The workflow was tested with:

1. General course feedback
2. A technical assignment-submission problem
3. An unclear/insufficient response

The tests demonstrated that the workflow can process different types of user input and handle unclear information appropriately.

## Project Purpose

This project demonstrates how AI can be integrated into an automated workflow to reduce manual work and make student feedback easier to process and understand.

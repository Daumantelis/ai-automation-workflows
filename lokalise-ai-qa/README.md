# Lokalise AI QA Automation System

## Overview

AI-powered automated translation QA system integrated with Supabase and Lokalise.

This workflow automatically:

1. Retrieves translation entries
2. Sends them to an AI model for quality scoring
3. Parses structured JSON response
4. Stores QA result in database
5. Decides pass/fail
6. Updates Lokalise status
7. Marks confirmation in Supabase

---<img width="1578" height="609" alt="Lokalise scoring" src="https://github.com/user-attachments/assets/c905af4b-d3ac-404b-ac78-d7bff9bf3478" />


## Problem

Manual translation QA is:
- Time-consuming
- Inconsistent
- Not scalable

We needed an automated quality scoring and validation system.

---

## Solution

Built a fully automated AI-driven QA pipeline using:

- n8n workflow automation
- OpenAI model scoring
- Supabase as state database
- Lokalise API integration

---

## Workflow Architecture

1. Fetch new translations from Supabase
2. Batch processing logic
3. AI model evaluates and scores translation
4. JSON parsing and structured validation
5. Conditional pass/fail routing
6. Update translation review status in Lokalise
7. Update processing state in Supabase

---

## Technical Focus

- AI structured JSON parsing
- Conditional logic routing
- Batch processing
- Error handling and retry logic
- API integrations (Supabase + Lokalise)
- Automation architecture design

---

## Skills Demonstrated

- Advanced workflow architecture
- AI-based decision systems
- Translation automation
- API-based system integration
- Process automation at scale

---

## Result

Fully automated translation QA validation system replacing manual review workflow.

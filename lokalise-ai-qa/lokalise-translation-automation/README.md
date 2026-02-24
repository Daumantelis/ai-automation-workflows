# AI Translation Automation Pipeline (Lokalise + Supabase + GPT)

## Overview
<img width="1607" height="581" alt="lokalise api feed etc" src="https://github.com/user-attachments/assets/be725205-ad36-445b-9046-22b26af2dc39" />

Fully automated AI translation processing system with batching, state tracking and automated delivery to Lokalise.

This system automatically:
- Fetches translation data
- Processes in controlled batches
- Uses AI for translation / formatting
- Parses structured output
- Updates translations in Lokalise
- Tracks processing state in Supabase
- Handles retries and failures

---


## Problem

Manual translation processing is slow, repetitive and difficult to scale.  
Large volumes require batching, tracking and automation.

---

## Solution

Built a fully automated translation pipeline using:

- n8n workflow automation
- GPT translation + structured formatting
- Supabase state management
- Lokalise API integration

---

## Workflow Architecture

### Phase 1 — Data Preparation
1. Fetch translations from Lokalise API
2. Build rows in accumulator
3. Insert batches into Supabase
4. Track translation state

### Phase 2 — AI Processing
1. Retrieve next batch
2. Send batch to GPT model
3. Structured numbering and formatting
4. Parse translation JSON
5. Store translations

### Phase 3 — Delivery & Control
1. Update translations in Lokalise
2. Confirm success / failure
3. Retry failed items
4. Continue batch processing
5. Maintain processing state

---

## Technical Focus


- Batch processing architecture
- State management
- Retry & fail handling
- AI structured output parsing
- API integrations
- Long-running workflow logic
- Automation system design

---

## Skills Demonstrated

- Advanced automation architecture
- AI-powered data processing
- Workflow state machines
- API system integrations
- Scalable automation design

---

## Result

Fully automated translation pipeline capable of processing large translation volumes without manual intervention.

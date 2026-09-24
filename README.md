# Agentic-AI-Course

# CBU TAAS Diagnostic ReAct Agent

A minimal Python ReAct (Reasoning and Acting) Agent built with the Google GenAI SDK (`gemini-2.5-flash`) to diagnose simulated CBU TAAS test failures dynamically.

## Features
- **Dynamic Reasoning Loop:** Evaluates test failures step-by-step using ReAct.
- **Tools:**
  - `get_test_logs()`: Retrieves test suite failure logs.
  - `check_endpoint_status()`: Checks backend service health.
- **Structured Output:** Generates a diagnostic report covering Root Cause, Evidence, and Recommendations.

## Reasoning Trace Screenshot
![Reasoning Trace](./screenshot.png)

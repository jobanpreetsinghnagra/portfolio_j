---
layout: post
title: "Diet Plan Generator LLM-Driven Nutrition Assistant"
date: 2025-01-01
image: /images/dietgenerator.png
categories: health ai
code: https://github.com/jobanpreetsinghnagra/diet_plan_gen
website: https://huggingface.co/spaces/jobannagra/diet_plans
---

The Diet Plan Generator creates personalized nutrition plans using highly deterministic, low-entropy LLM inference.  
It is engineered for stability, accuracy, and medical-safety-conscious output generation.

**Core Technology: Mistral Large (API)**

The system operates with Mistral Large set to a temperature of **0.01**, ensuring deterministic responses with minimal hallucination risk—important for health-related guidance.

**Latency-Aware Architecture**

A structured processing pipeline (input validation → BMI computation → prompt construction → model call) enables predictable user-perceived response times during API round-trip operations.

**Prompt Optimization & Reliability**

A dual-message prompt design (“System” + “Human”) constrains the model to structured output formats.  
This minimizes retries, reduces malformed responses, and ensures consistent nutrition plan generation across repeated runs.

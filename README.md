# Cost-Efficient Prompt Injection Detection through Confidence-Based Two-Stage Cascading

**Note: This data was assembled solely to support academic research. Permission to use it for any other purpose must be obtained from the authors.**

## Introduction

We construct a 25,747-example prompt-injection evaluation benchmark, 72.4% benign and 27.6% injections, together with a 56,795-example development corpus used for fine-tuning and calibration. No dataset contributes to both, so the benchmark measures generalisation to sources never seen during development. Injections are grouped by delivery channel and divide roughly 40:20:40 among document-embedded, tool-output, and direct-input attacks.

The benchmark is derived from publicly available datasets. Evaluation draws on LMSYS-Chat-1M, databricks-dolly-15k, and Natural Instructions for benign traffic, Open-Prompt-Injection for document-embedded injections, AgentDojo for tool-output injections, and StruQ templates applied to held-out benign carriers for direct-input injections. Development draws on UltraChat, IFEval, Alpaca, NotInject, BIPIA, InjecAgent, and HackAPrompt, with long benign documents from CNN/DailyMail and GovReport added to the Stage 2 training data. Each source remains under the license of its original provider.

## Access

The assembled benchmark and development splits are not redistributed here. If you want to have the complete dataset, please contact us.

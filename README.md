# Week 10 Homework - Structured Outputs (JSON Mode) & Tool Calling with LiteLLM (2h)

1) Schema-validated extractor - nested structure
   Goal: Design your own JSON Schema and use JSON Mode to extract a nested structure.
   Scenario: Given a short paragraph containing an order with a customer and multiple items, output a strict JSON object.

3) Currency mini-agent (simulated) - complete tool calling
   Goal: Build a multi-tool agent to convert money amounts, resolve currency names, and show supported codes.
   implement: `convert` , `ToolExecutor.run`, `get_schemas(convert)`

## Files
- .gitignore
- json_mode_schema.py
- lab_sheet.html
- tc_complete_currency.py

## Resource
- [LiteLLM Guide][(https://meetip.github.io/CS203_W10_lab/)](https://meetip.github.io/CS203_W10_lab/)

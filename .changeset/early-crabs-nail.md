---
"llamaindex": patch
"@llamaindex/openai": patch
---

feat: decouple openai from `llamaindex` module

This should be a non-breaking change, but just you can now only install `@llamaindex/openai` to reduce the bundle size in the future
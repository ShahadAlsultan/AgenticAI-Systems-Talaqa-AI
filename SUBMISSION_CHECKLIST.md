# Submission Checklist

Complete these checks immediately before submission:

1. The author name, programme, August 2026 cohort, and Track A declaration are visible.
2. Colab Secrets contain Gemini and LangSmith keys; no key appears in code, output, or Git history.
3. The runtime was restarted and every notebook cell was executed from top to bottom.
4. Every code cell contains its captured output and no cell contains an exception.
5. RAG output shows more chunks than documents and retrieves the expected conclusion guidance.
6. Routing output shows at least two different workers selected by the LLM.
7. Worker output contains real tool calls with arguments.
8. The same-thread state test and different-thread Store test both pass.
9. Both the missing-input interrupt and final publication interrupt are resumed successfully.
10. The Evaluator–Optimizer prints initial and final evaluations.
11. LangSmith prints an actual trace insight and no authentication error.
12. The automated evidence summary prints `PASS` for every rubric section.
13. README instructions match the code and saved outputs.
14. No generated claim says the system heard audio or saw body language from a transcript.
15. No template text or unverified statement remains.


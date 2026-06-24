# Prompt Library for Content Generation

A personal, reusable library of 10 prompt templates for content generation tasks.
Each prompt uses at least 2 prompting techniques, includes {placeholders} for reusability,
and shows before/after iteration where required.

---

## Repository Structure

```
prompt-library/
├── README.md
├── prompts/
│   ├── 01-linkedin-product-launch.md
│   ├── 02-blog-post-intro.md
│   ├── 03-cold-outreach-email.md
│   ├── 04-follow-up-email.md
│   ├── 05-product-description.md
│   ├── 06-youtube-title-description.md
│   ├── 07-newsletter-section.md
│   ├── 08-ad-copy.md
│   ├── 09-tone-rewriter.md
│   └── 10-content-calendar.md
└── assets/
    └── screenshot.png
```

---

## Prompt Index

| No | Use Case | Techniques | Iteration |
|----|----------|------------|-----------|
| 01 | LinkedIn Product Launch | Role + Few-shot + Constraints | Yes |
| 02 | Blog Post Intro | Role + Chain-of-thought | No |
| 03 | Cold Outreach Email | Role + Constraints | Yes |
| 04 | Follow-Up Email | Persona + Constraints | No |
| 05 | Product Description | Few-shot + Constraints | No |
| 06 | YouTube Title + Description | Role + Structured Output | No |
| 07 | Newsletter Section | Role + Tone Control + Constraints | No |
| 08 | Ad Copy Google or Meta | Few-shot + Constraints | No |
| 09 | Tone Rewriter Formal to Casual | Transformation + Constraints | Yes |
| 10 | 7-Day Content Calendar | Role + Structured Output + Chain-of-thought | No |

---

## Rules Checklist

- Each prompt uses at least 2 techniques
- Each prompt uses {placeholders} for reusability
- 3 prompts show before/after iteration — 01, 03, 09
- Every prompt includes a real sample output

---

## Techniques Used

| Technique | Description |
|-----------|-------------|
| Role prompting | Assign an expert persona to the model |
| Few-shot | Provide 2 to 3 examples before the instruction |
| Constraints | Explicit rules such as word limits, tone, format |
| Chain-of-thought | Ask the model to reason step by step first |
| Structured output | Specify exact output format like table or list |
| Persona | Define a character with a specific communication style |
| Transformation | Rewrite or convert existing content |
| Tone control | Specify and enforce a target voice |

---

Prompt Library v1.0 — Mini Project Submission

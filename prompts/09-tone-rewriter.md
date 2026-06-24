# 09 - Tone Rewriter (Formal to Casual)

Use Case: Rewrite existing content to match a different tone
Techniques: Transformation prompt, Constraints
Iteration: Yes - v1 to v2 shown below

---

## Template

You are a tone editor. Your job is to rewrite content while keeping the meaning 100% intact. Do not add or remove any information.

Rewrite the following text from {source_tone} to {target_tone} tone:

{original_text}

Guidelines per tone:

Casual:
- Use contractions like do not becomes don't, we are becomes we're
- Use shorter sentences
- Use conversational first-person phrasing

Formal:
- Use complete sentences
- Use professional vocabulary
- No slang or abbreviations

Witty:
- Add one light or clever observation
- Keep it sharp, do not sacrifice clarity for humor

Output only the rewritten version. No explanations.

---

## Sample Output

Original text (Formal):
We regret to inform you that your application for the position of Marketing Associate has not been successful at this time. We appreciate your interest in our organization and wish you the best in your future endeavors.

Rewritten (Casual):
Hey — thanks so much for applying for the Marketing Associate role. Unfortunately, we are going in a different direction this time, but we genuinely appreciate you taking the time to interview with us. Wishing you all the best in your search!

---

## Iteration v1 to v2

Version v1:
Prompt used: Rewrite this in a casual tone
Problem: Output was inconsistent, sometimes too informal, sometimes barely changed

Version v2:
What changed: Added explicit guidelines for each tone style
Why it is better: Output became reliable and predictable every time

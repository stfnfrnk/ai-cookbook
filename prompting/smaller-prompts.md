# Different smaller prompts

### General

```text
Is a in file z consistent with b in file y
```

```text
Lets bring some order into this file. Can you analyze where we are, not just based on this file, but checking the code base, and then lets discuss whether maybe we are missing some task or need to break down?
```

```text
Ok, as I switch to another chat window, can you give me a short summary of what we have done and what we should work on next?
```
```text
What would be next and what we have done? I want to switch to another screen, so I need a summary. Do not further implement.
```
```text
How can we reduce complexity without removing functionality
```

```text
Analyze this entire codebase and identify all unused or redundant components, scripts, and mock data.

For each item:

1. Why it’s unused

2. Where it’s defined

3. If it’s safe to delete
```
Source: <https://x.com/PrajwalTomar_/status/1920456132566356277>


### Understand code first, then provide task

Source: <https://x.com/robj3d3/status/1932415616490840563>

```text
Do a deep-dive on the code and understand how \[insert feature\] works. Once you understand it, let me know, and I will provide the task I have for you.
```

### Writing style prompt

Source: <https://www.reddit.com/r/ChatGPTPromptGenius/comments/1h2bkrs/i_finally_found_a_prompt_that_makes_chatgpt_write/>

```text
Use simple language: Write plainly with short sentences.

Example: “I need help with this issue.”
Avoid AI-giveaway phrases: Don’t use clichés like “dive into,” “unleash your potential,” etc.

Avoid: “Let’s dive into this game-changing solution.”
Use instead: “Here’s how it works.”
Be direct and concise: Get to the point; remove unnecessary words.

Example: “We should meet tomorrow.”
Maintain a natural tone: Write as you normally speak; it’s okay to start sentences with “and” or “but.”

Example: “And that’s why it matters.”
Avoid marketing language: Don’t use hype or promotional words.

Avoid: “This revolutionary product will transform your life.”
Use instead: “This product can help you.”
Keep it real: Be honest; don’t force friendliness.

Example: “I don’t think that’s the best idea.”
Simplify grammar: Don’t stress about perfect grammar; it’s fine not to capitalize “i” if that’s your style.

Example: “i guess we can try that.”
Stay away from fluff: Avoid unnecessary adjectives and adverbs.

Example: “We finished the task.”
Focus on clarity: Make your message easy to understand.

Example: “Please send the file by Monday.”
```

### Debugging

Source: <https://www.alexchristou.co.uk/posts/effective-cursor-debugging-prompt>

```text
Reflect on 5-7 different possible sources of the problem. Distill those down to 1-2 most likely sources. Then add logs to validate your assumptions before we move on to implementing the actual code fix.

```
---
name: laugh
description: "Generate a short, funny joke on request. Use when the user asks for a joke, wants to laugh, requests humor, or invokes /laugh."
argument-hint: "Optional topic or style for the joke"
user-invocable: true
disable-model-invocation: false
---

# Laugh

Generate one concise joke tailored to the user's request.

## Procedure

1. Identify any topic, audience, or style supplied by the user.
2. If no topic is supplied, choose an everyday, broadly relatable subject.
3. Write one original joke with a clear setup and punchline.
4. Keep the response brief and output only the joke unless context is necessary.
5. Avoid humor that targets protected characteristics, exploits personal tragedy, or presents harmful behavior as advice.

## Quality Check

- Make the punchline meaningfully different from the setup.
- Prefer wordplay, misdirection, or observational humor over insults.
- Do not explain the joke.
- Do not reuse a joke already given in the current conversation.
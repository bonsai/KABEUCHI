# kabeuchi

## Purpose
Return questions and counterpoints that help a person examine, clarify, or deepen an idea without deciding the answer for them.

## Type
Generic cognitive-operation skill.

## Inputs
- An idea, claim, hypothesis, plan, artifact, or decision
- Optional context, constraints, or desired depth

## Outputs
- clarifying questions
- assumption checks
- contradictions or tensions
- missing information
- alternative framings
- a next question or next investigation step

## Procedure
1. Identify the central proposition or object being examined.
2. Surface unclear terms, assumptions, gaps, tensions, and consequences.
3. Generate questions that target those points.
4. Prefer questions that can change understanding rather than merely request more detail.
5. Distinguish observations from hypotheses.
6. End with the most useful next question or investigation step when appropriate.

## Constraints
- Do not decide on behalf of the user.
- Do not manufacture objections unsupported by the input.
- Do not ask questions merely to prolong the conversation.
- Keep questions proportional to the available evidence and context.
- Remain domain-agnostic.

## Domain plugin hook
A domain plugin may define tone, question count, evaluation criteria, terminology, or output schemas. It must not change the core operation: using questions and counterpoints to deepen examination.

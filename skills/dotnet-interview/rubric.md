# Interview Evaluation Rubric

## Purpose

Evaluate a candidate's technical understanding, practical engineering ability, and reasoning during technical interviews.

Use this rubric to provide consistent, evidence-based feedback across topics and experience levels.

The objective is to assess whether a candidate understands a concept, can apply it, and can reason about its limitations—not merely whether they can reproduce a textbook definition.

## 1. Scoring Scale

Score each answer from 0 to 10.

| Score | Level | Description |
|---|---|---|
| 0 | No answer | No meaningful response or completely unrelated answer. |
| 1–2 | Incorrect | Fundamental misunderstanding or materially incorrect explanation. |
| 3–4 | Weak | Some relevant knowledge, but major conceptual gaps or inaccuracies. |
| 5–6 | Developing | Understands the fundamentals but misses important details or practical implications. |
| 7–8 | Good | Correct, reasonably complete explanation with sound practical understanding. |
| 9 | Excellent | Strong understanding, relevant examples, and awareness of important trade-offs or edge cases. |
| 10 | Exceptional | Deep, precise understanding; anticipates subtle implications and demonstrates excellent engineering judgment appropriate to the question. |

A score of 10 should be uncommon, but it should not require obscure trivia or unnecessary complexity.

## 2. Evaluation Dimensions

Assess the dimensions relevant to the question. Do not force every dimension onto every answer.

### A. Technical Correctness

Does the candidate explain the concept accurately?

Consider:
- Correct terminology and underlying principles.
- Accurate descriptions of framework or language behavior.
- Absence of significant misconceptions.
- Recognition of relevant constraints.

Incorrect claims about fundamental behavior should weigh heavily against the score.

### B. Conceptual Understanding

Does the candidate understand why the concept works?

Consider:
- Ability to explain the underlying mechanism.
- Ability to distinguish related concepts.
- Understanding of when and why the concept is useful.
- Ability to reason beyond a memorized definition.

### C. Practical Application

Can the candidate apply the concept to real software development?

Consider:
- Appropriate examples or implementation details.
- Recognition of common production problems.
- Understanding of how the concept fits into a real application.
- Ability to identify when a solution is appropriate.

Do not require production experience for a purely foundational question.

### D. Completeness

Does the answer address the important parts of the question?

Consider:
- Coverage of the central concepts.
- Relevant limitations and exceptions.
- Important distinctions requested by the question.
- Missing information that would materially change the answer.

Do not penalize an answer for omitting unrelated details.

### E. Trade-off Awareness

Can the candidate explain alternatives and their consequences?

Consider:
- Performance and resource usage.
- Maintainability and complexity.
- Security and reliability.
- Situations in which an alternative is preferable.

Apply this dimension primarily to design, architecture, performance, and scenario-based questions.

### F. Problem-Solving and Reasoning

Can the candidate reason through unfamiliar or ambiguous problems?

Consider:
- Clarifying assumptions.
- Breaking a problem into manageable parts.
- Identifying likely causes and testing hypotheses.
- Considering failure scenarios and edge cases.
- Explaining why a proposed solution addresses the problem.

For scenario-based questions, reasoning can be more important than recalling a specific API.

### G. Communication

Can the candidate explain their reasoning clearly?

Consider:
- Logical organization.
- Clear distinction between facts and assumptions.
- Ability to explain technical ideas in understandable language.
- Directly answering the question.

Do not penalize accent, minor grammar mistakes, nervousness, or a different communication style unless it materially prevents understanding.

## 3. Suggested Scoring by Question Type

Different questions require different evaluation priorities.

### Fundamentals and Definitions

Examples:
- What is dependency injection?
- What is the difference between a class and a struct?
- What is the purpose of middleware?

Prioritize:
1. Technical correctness.
2. Conceptual understanding.
3. Completeness.
4. A relevant example, where useful.

Do not require advanced architecture discussions for a basic question.

### Comparison Questions

Examples:
- `IEnumerable` vs. `IQueryable`.
- `Task` vs. `ValueTask`.
- Scoped vs. singleton services.

Prioritize:
1. Correct distinctions.
2. Understanding of underlying behavior.
3. Appropriate use cases.
4. Relevant limitations and trade-offs.

A response that merely lists differences without explaining their implications should not receive the highest score.

### Coding Questions

Examples:
- Implement a function.
- Fix an asynchronous method.
- Optimize an EF Core query.

Prioritize:
1. Correctness.
2. Handling of relevant edge cases.
3. Appropriate algorithm or implementation.
4. Complexity and resource usage, where relevant.
5. Readability and maintainability.

If the candidate has not executed the code, do not assume it compiles or passes tests. Distinguish a conceptual solution from a verified implementation.

### Scenario-Based Questions

Examples:
- An API becomes slow under load. How would you investigate?
- Two requests create duplicate orders.
- A background worker repeatedly processes the same message.

Prioritize:
1. Clarification of requirements and assumptions.
2. Structured investigation or design reasoning.
3. Identification of realistic failure modes.
4. Correctness and reliability of the proposed solution.
5. Trade-offs and operational considerations.

There may be several valid solutions. Evaluate their suitability rather than insisting on one predetermined answer.

### System Design Questions

Prioritize:
1. Requirements and constraints.
2. Architecture and component responsibilities.
3. Data model and data flow.
4. Scalability and performance.
5. Reliability and failure handling.
6. Security and observability.
7. Trade-offs and justification.

Adjust expectations to the candidate's experience and the scope of the question.

## 4. Experience-Level Calibration

Use the candidate's target role and experience to calibrate expectations.

### Junior Developer

Focus on:
- Fundamentals.
- Correct use of common language and framework features.
- Basic debugging and coding.
- Understanding of straightforward examples.

Do not require extensive distributed-systems knowledge.

### Mid-Level Developer

Focus on:
- Independent implementation.
- Correct use of framework features.
- Debugging and practical problem-solving.
- Database and API performance.
- Testing and maintainability.
- Awareness of common production failure modes.

### Senior Developer

Focus on:
- Depth of technical understanding.
- Architecture and design decisions.
- Concurrency and reliability.
- Performance and security trade-offs.
- Debugging complex failures.
- Ability to justify decisions and identify alternatives.
- Mentoring and technical communication, where relevant to the role.

Experience levels are guidelines, not rigid requirements. Evaluate the actual role, question difficulty, and evidence in the answer.

## 5. Feedback Format

After evaluating an answer, provide concise, specific feedback.

### Assessment

State one of:
- Correct.
- Partially correct.
- Incorrect.

### Score

Provide a score from 0 to 10 and briefly justify it.

### What Was Correct

Identify the important concepts the candidate explained correctly.

### Gaps or Misconceptions

Identify specific omissions or incorrect statements. Distinguish critical misconceptions from minor omissions.

### Expected Answer

Explain the essential answer at the appropriate depth. Include a code example or practical scenario when it materially improves understanding.

### Follow-up

Ask one targeted question if further probing would help assess understanding. Otherwise, move to the next question.

During rapid-fire practice, keep feedback shorter. During strict mock interviews, defer detailed teaching until the relevant interview section or session ends.

## 6. Follow-Up Question Policy

Use follow-up questions to investigate meaningful gaps rather than repeatedly asking the same question in different words.

Examples:
- If a candidate defines a concept correctly, ask how it works internally.
- If they explain how it works, ask when they would use it.
- If they propose a solution, introduce a realistic constraint or failure scenario.
- If they make a significant mistake, ask a simpler diagnostic question when useful.

Do not penalize the candidate simply because a follow-up question is more difficult than the original question.

Evaluate each answer on its own merits while considering the accumulated evidence of understanding.

## 7. Partial Credit and Fairness

Apply these rules consistently:

- Accept technically valid alternative solutions.
- Do not require exact textbook wording.
- Do not penalize brevity if the answer is complete.
- Do not reward verbosity when the central explanation is incorrect.
- Do not treat an omitted advanced detail as a fundamental error.
- Do not confuse unfamiliar terminology with a lack of understanding if the candidate explains the underlying concept correctly.
- Do not assume that a candidate lacks knowledge simply because they request clarification.
- Distinguish a reasonable trade-off from an incorrect technical claim.
- Do not inflate scores to be encouraging.
- Explain uncertainty when a question has ambiguous requirements or multiple defensible interpretations.

## 8. Overall Interview Assessment

At the end of an interview, summarize the evidence gathered during that session.

Include:

### Overall Performance

Provide an overall assessment relative to the target role.

If a numeric overall score is useful, calculate it from the assessed answers and explain the method. Use an arithmetic mean only when that is appropriate for the interview's design; otherwise, state the weighting used.

Do not treat the result as a statistically validated hiring score.

### Topic-Level Performance

Report scores only for topics that were actually assessed.

For each topic, include:
- Observed strengths.
- Important gaps.
- Confidence in the assessment based on the number and difficulty of questions.

Avoid strong conclusions from a single question.

### Key Strengths

Summarize demonstrated technical abilities with evidence from the answers.

### Improvement Priorities

Identify the most consequential gaps and recommend a sensible learning order.

### Recommended Practice

Suggest concrete next steps, such as:
- Review a particular concept.
- Implement a small coding exercise.
- Debug a realistic failure scenario.
- Practice a follow-up question.
- Design a system with explicit constraints.

## 9. Scoring Integrity

The rubric supports practice and feedback. It is not, by itself, a validated hiring or psychometric assessment.

The interviewer must:
- Base scores on observed answers.
- Apply comparable standards to comparable questions.
- Avoid inferring competence from confidence or speaking speed alone.
- Distinguish a knowledge gap from an ambiguous question.
- Avoid claiming long-term progress tracking without accessible records.
- Never invent previous answers, historical scores, or performance trends.

The goal is to help candidates understand what they know, what they do not yet understand, and how to improve.

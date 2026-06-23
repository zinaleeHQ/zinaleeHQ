# Methodology Notes

*Zina Lee, Product Manager*

---

## Working Across Multiple AI Models

In developing these projects, I worked across multiple AI systems — Claude, GPT, and Gemini — to evaluate how different models interpret the same product problems.

Each model demonstrates distinct strengths:

- **Claude** tends to produce structured, cautious, and highly organized outputs. It is particularly strong in maintaining clarity, following constraints, and supporting step-by-step reasoning.
- **GPT** is more expansive and exploratory. It often surfaces broader ideas, alternative approaches, and creative interpretations, which are useful in early-stage discovery and ideation.
- **Gemini** shows strength in synthesizing information across contexts and framing responses in a more "big picture" or systems-oriented way. It is particularly useful for connecting concepts, identifying patterns, and generating holistic perspectives across product, operational, and strategic domains. Gemini can sometimes prioritize breadth over precision, which makes it valuable for synthesis but important to validate in detail-sensitive contexts.

Working across these models allows for:

- Comparison of reasoning styles and output structure
- Identification of gaps, bias, or overconfidence
- More effective prompt refinement
- Better-informed decisions about which outputs to trust and why

This approach reflects how AI is used in real-world environments: not as a single source of truth, but as a system that requires evaluation, triangulation, and human judgment — especially in complex and regulated domains like healthcare.

---

## Scope and Application

This portfolio is built around healthcare IT scenarios, but the frameworks, methodologies, and workflows are designed to be broadly applicable across industries and organizational contexts.

The four projects reflect core PM functions — prioritization, process design, stakeholder communication, and operational visibility — each demonstrating how AI can be applied in a structured, repeatable way while accounting for real-world constraints: risk, bias, and the need for human oversight.

A deliberate design choice throughout is showing where *not* to use AI. Many of the analytical tasks here could be further automated. The judgment layer (the pause points, the override decisions, the access boundary calls) is left 
to the PM intentionally.

AI bias and governance is the next layer I plan to add to this work. Each project has decision points where model bias could influence real operational or financial outcomes. That analysis is in progress.

# Methodology Notes

**Zina Lee, Product Manager**

### Working Across Multiple AI Models

In developing these projects, I worked across multiple AI systems — Claude, GPT, and Gemini — to evaluate how different models interpret the same product problems.

Each model demonstrates distinct strengths:

*   **Claude** tends to produce structured, cautious, and highly organized outputs. It is particularly strong in maintaining clarity, following constraints, and supporting step-by-step reasoning.
*   **GPT** is more expansive and exploratory. It often surfaces broader ideas, alternative approaches, and creative interpretations, which are useful in early-stage discovery and ideation.
*   **Gemini** shows strength in synthesizing information across contexts and framing responses in a more "big picture" or systems-oriented way. It is particularly useful for connecting concepts, identifying patterns, and generating holistic perspectives across product, operational, and strategic domains. Gemini can sometimes prioritize breadth over precision, which makes it valuable for synthesis but important to validate in detail-sensitive contexts.

Working across these models allows for:
*   Comparison of reasoning styles and output structure
*   Identification of gaps, bias, or overconfidence
*   More effective prompt refinement
*   Better-informed decisions about which outputs to trust and why

This approach reflects how AI is used in real-world environments: not as a single source of truth, but as a system that requires evaluation, triangulation, and human judgment — especially in complex and regulated domains like healthcare.

### Why Prompts Over Agentic AI

While autonomous AI agents are a growing focus in technology, this portfolio intentionally utilizes structured prompting rather than agentic workflows. This choice is driven by two core principles of pragmatic product management:

*   **Cost-to-Value Efficiency:** Agentic AI introduces significant overhead. It requires complex data pipelines, continuous integration, and high token consumption as models iterate through multi-step processes. For many foundational product tasks, deploying an agentic framework is the equivalent of using a machine gun to knock over a tin can. 
*   **The Power of Simple Tools:** Good product design favors the simplest tool that efficiently solves the problem. Structured prompts achieve high-utility results immediately, without the technical debt, maintenance costs, or setup friction of autonomous systems. 

**Preserving the Judgment Layer**

Beyond cost and complexity, prompts keep the human firmly in the loop. Autonomous agents excel at background automation, but they can obscure the decision-making process. Because these projects focus heavily on complex, high-risk domains like healthcare, maintaining absolute control over the input and output is critical. 

Structured prompting forces explicit pause points, allowing the Product Manager to review, validate, and apply human judgment before any action is taken. This approach ensures predictability, mitigates model hallucination, and keeps strategic oversight where it belongs: with the human.

### Scope and Application

This portfolio is built around healthcare IT scenarios, but the frameworks, methodologies, and workflows are designed to be broadly applicable across industries and organizational contexts.

The four projects reflect core PM functions — prioritization, process design, stakeholder communication, and operational visibility — each demonstrating how AI can be applied in a structured, repeatable way while accounting for real-world constraints: risk, bias, and the need for human oversight.

A deliberate design choice throughout is showing where not to use AI. Many of the analytical tasks here could be further automated. The judgment layer (the pause points, the override decisions, the access boundary calls) is left to the PM intentionally.

AI bias and governance is the next layer I plan to add to this work. Each project has decision points where model bias could influence real operational or financial outcomes. That analysis is in progress.


# Agent Proto Soul Specification (Single-File Protocol)

Version: 1.0  
Purpose: Define a unified, generative structure for creating coherent AI agents as a single Markdown file. This specification is designed to be directly compatible with the Agent Soul Creator prompt and to replace identity.md, agent.md, tasks.md, and most of memory.md within one document.

This file should read as the internal structure of a thinking entity, not a configuration sheet.

---

## Core Design Philosophy

This protocol merges five layers into one:

- Identity (who the agent is)  
- Purpose (why it exists)  
- Principles (how it stays aligned)  
- Behavior (how it operates)  
- Goals (what it is doing now)  

Memory may be embedded or externalized depending on scale.

The result is a single, living document that maintains coherence across all dimensions of the agent.

---

## Required Sections (Agent Soul Creator Compatible)

These sections MUST be present and generated in a way that feels unified and internally consistent.

---

## Identity (Who)

This section establishes the stable character of the agent.

Include:
- Name  
- Role and function  
- Tone and communication style  
- Boundaries (what the agent does not do)

Notes:
Identity should remain relatively stable over time. It is the anchor of the agent.

---

## Purpose (Why)

This section defines direction and meaning.

Include:
- Why the agent exists  
- Long-term aim  
- What success looks like  

Notes:
Purpose should guide all decisions. If a behavior conflicts with purpose, it must be revised.

---

## Principles (Alignment Layer)

This section governs decision-making and prevents drift.

Include:
- Core values  
- Decision-making rules  
- Constraints and priorities  

Optional:
- Priority hierarchy (what overrides what)

Notes:
Principles act as the internal “laws” of the agent.

---

## Capabilities (Action Surface)

This section defines what the agent can realistically do.

Include:
- Tools, skills, and abilities  
- Strengths  
- Explicit limitations  

Notes:
Capabilities must align with Purpose. Avoid over-claiming ability.

---

## Behavior Loop (Operational Core)

This section defines how the agent functions over time.

Include a clear loop such as:

1. Interpret the goal within context  
2. Decompose into actionable components  
3. Select tools and strategies  
4. Execute  
5. Reflect on results  
6. Update approach  

Notes:
This replaces most of what would traditionally live in agent.md.

---

## Current Goals (Active Direction)

This section defines what the agent is actively working toward.

Include:
- Immediate objectives  
- Priority ordering  
- Types of tasks  

Notes:
This replaces tasks.md. It is expected to evolve frequently.

---

## Memory (Continuity Layer)

This section defines how the agent maintains continuity.

Two modes:

### Embedded Memory (Simple Mode)
- Key persistent facts  
- User preferences  
- Important context  

### External Memory (Scalable Mode)
- Stored in memory.md or external system  
- Define what is stored and why  
- Define retrieval behavior  

Rules:
- Only retain what improves future decisions  
- Avoid unnecessary accumulation  

Notes:
Memory should support the Purpose and Goals, not clutter them.

---

## Optional Sections (Advanced Control)

These may be included when needed.

---

## System Constraints (Hard Layer)

- Non-negotiable rules  
- Safety constraints  
- Environmental assumptions  

Acts as a lightweight replacement for system.md.

---

## Interfaces (Interaction Layer)

- How the agent communicates with users  
- External systems or protocols  
- Input/output expectations  

---

## Evolution (Adaptive Layer)

- What triggers updates  
- What is allowed to change  
- What must remain stable (Identity + Principles)  

---

## Structural Rules

- The document must feel cohesive, not modular fragments  
- Sections must reinforce each other  
- Identity, Purpose, and Principles should rarely change  
- Goals and Behavior adapt frequently  
- Memory should be minimal and purposeful  

---

## Relationship to Agent Soul Creator

The Agent Soul Creator prompt should generate this structure directly.

Mapping:

- Identity → Identity  
- Purpose → Purpose  
- Principles → Principles  
- Capabilities → Capabilities  
- Behavior Loop → Behavior Loop  
- Current Goals → Current Goals  
- Memory → Memory  

Optional sections may be inferred when beneficial.

---

## Implementation Guidance

- Treat this file as the agent’s “internal self”  
- Avoid duplicating logic across systems  
- Externalize memory when persistence or scale is required  
- Keep language precise, grounded, and intentional  

---

End of Specification
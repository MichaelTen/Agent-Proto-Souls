# Agent-Proto-Souls
''Proto souls of agents.''

A framework for designing coherent, purpose-driven AI agents as single-file identities.

This project explores how an agent can be defined not as scattered configuration, but as a unified internal structure. Each agent is expressed as a “proto soul”, a Markdown document that captures who it is, why it exists, how it behaves, and what it is working toward.

---

## What This Is

Agent Proto Souls is a lightweight protocol for building AI agents using Markdown as the primary interface.

Instead of splitting logic across multiple files like:

- identity.md  
- agent.md  
- tasks.md  
- memory.md  

This project consolidates them into a single, cohesive document.

The result is an agent that reads more like a thinking entity than a system configuration.

---

## Core Idea

An agent can be modeled as a structured internal narrative:

- Identity → who it is  
- Purpose → why it exists  
- Principles → how it stays aligned  
- Capabilities → what it can do  
- Behavior → how it operates  
- Goals → what it is doing  
- Memory → what it retains  

All of this can live in one file.

---

## Files in This Repository

### agent-proto-soul-single-file-spec.md
Defines the protocol.

This is the blueprint for how a single-file agent should be structured. It replaces the need for multiple scattered `.md` files and provides a consistent architecture.

---

### agent-soul-creator.md
Generative prompt.

Use this to create new agents from a topic, mission, or goal. It produces a complete proto soul that follows the specification.

---

### proto-agent-decen-meshwarden.md
Example agent.

A concrete implementation focused on decentralized, censorship-resistant systems including social media, storage, and open-source infrastructure.

---

## How to Use

1. Choose a topic or goal  
   Example: decentralized social media, education systems, AI tooling, etc.

2. Use `agent-soul-creator.md`  
   Paste in your topic and generate a proto soul.

3. Save the result as:
   ```md
   proto-agent-[name].md
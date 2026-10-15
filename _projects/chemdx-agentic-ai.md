---
layout: project
title: "ChemDX Agentic AI"
summary: "A multi-agent framework for data-driven materials research, built in a weekend at the KRICT ChemDX Hackathon 2025."
year: 2025
status: finished
tags: [Agentic AI, Materials science, Hackathon]
links:
  - label: "Code on GitHub"
    url: "https://github.com/Yeonghun1675/ChemDX_agentic_AI"
---

Materials questions rarely fit a single database. Answering "which of these two compounds is the better
thermoelectric, and can I get a structure file to simulate it?" means querying one database for
properties, another for structures, plotting a trend, and formatting a file for a DFT code. A single
language model tends to lose track somewhere along the way.

ChemDX Agentic AI breaks the question up instead. A **main agent** plans the work and splits it into
subtasks, then hands each one to a **specialised sub-agent** with its own role, system prompt and tools.
Sub-agents write their results to a shared working memory, so later agents can build on earlier
findings rather than starting over. The main agent assembles the final answer and grades its own
work. The whole thing is steered through prompts, not model weights, which made it possible to build
fourteen sub-agents and twenty-four tools in a hackathon weekend.

## What I built

I worked on the sub-agents and tools, and led the first demo: comparing the thermoelectric figure of
merit (ZT) of Cu₂SnS₃ and Cu₃SbS₄ at 500 K. The system pulled the data from the LitDX thermoelectric
database, plotted the trends, picked the better performer (Cu₃SbS₄, ZT ≈ 0.05 against 0.01) and
generated a VASP-ready POSCAR file for it, so the result could go straight into a DFT calculation.

The agents I worked on connect to the ChemDX materials databases (phosphors, thermoelectrics,
electronic and functional materials), the Materials Project, a crystal-structure generator and a
plotting tool. Each exposes a small, well-described interface so the main agent can decide when to
call it.

## Why it matters to me

I came to the hackathon from the wet lab, where I'd been thinking about how an agent could help
scientists manage protocols and experiments. ChemDX was the computational version of the same idea:
take the bookkeeping out of research so people can spend their time on the questions. It also led
directly to my later work on automating DFT workflows with agents in the Computational Energy
Materials Lab.

The project received an **Excellence Award** at the hackathon. It is open source under the MIT
licence, with a Streamlit interface and example notebooks.

**Team:** Yeonghun Kang (lead, framework architecture), Anastasia Arkhipenkova, Bogeun Park and
SeungPyo Kang (sub-agents, tools and demos).

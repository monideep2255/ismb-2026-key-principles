# ISMB 2026: key principles

Thirteen foundational principles for agentic AI and knowledge graphs in biomedicine, synthesized from [ISMB 2026](https://www.iscb.org/ismb2026/home) (Intelligent Systems for Molecular Biology, ISCB's flagship conference, July 13-16, 2026).

Live cheat sheet: https://monideep2255.github.io/ismb-2026-key-principles/

## Three ways to read this

The same 66 talks, at three depths. Pick the one that fits the time you have:

- Cheat sheet (5 minutes): https://monideep2255.github.io/ismb-2026-key-principles/ - the 13 principles on one page, color-coded by theme, with an interconnection diagram.
- Website (about 30 minutes): https://monideep2255.github.io/ismb-2026-key-principles/website/ - the full synthesis as a single readable page, longer than the cheat sheet and lighter than the book.
- Book (deep read): [book/](book/) - a 17-chapter first-principles book covering all 66 talks across 5 parts, each chapter citing its source talks inline. Start at [book/README.md](book/README.md).

## What this is

A synthesis of 13 foundational principles for agentic AI and knowledge graphs in biomedicine, drawn from 66 talks across 5 days at ISMB 2026. Color-coded by theme (technical foundation, organizational approach, people and governance) with an interconnection diagram showing how the principles relate, and each principle cited back to the book chapter that supports it.

## What this is not

Not a transcript or a session-by-session recap. Speaker content, slides, and papers belong to the speakers, their labs, and the conference. The principles here are abstractions in my own words.

## Sources

The 66 talks on my ISMB 2026 schedule that fed into the synthesis, Monday through Thursday. Session titles match the official conference schedule.

| Day | Time | Session | Speaker(s) |
|-----|------|---------|-----------|
| Monday | 09:00-10:00 | Keynote: toward predictive models of human biology and disease | Olga Troyanskaya |
| Monday | 11:00-11:40 | Reading science at scale: AI for biomedical discovery and trustworthy knowledge | Halil Kilicoglu |
| Monday | 11:40-12:00 | eGoT: enhanced graph-of-thoughts for multi-hop knowledge retrieval and hypothesis generation in biomedicine | Nihar Sanda |
| Monday | 12:00-12:20 | DrugAgent: explainable multi-agent reasoning for aggregating heterogeneous biomedical evidence | Yoshitaka Inoue |
| Monday | 12:20-12:30 | MedHopQA: benchmarking multi-hop reasoning in LLM-based biomedical question answering with a disease-centered corpus | Rezarta Islamaj |
| Monday | 12:30-12:40 | Outcome-aware feature generation from unstructured metadata using LLMs for cross-study transcriptomic analysis | Christine Hou |
| Monday | 12:30-12:50 | FAIR knowledge graphs on-demand | Chris Bizon |
| Monday | 12:40-13:00 | KLaR: fusing knowledge graphs and language models for biomedical target discovery | Yinghui Jiang |
| Monday | 14:20-14:40 | Bridging classical and transcriptomic cell types at scale: agentic AI workflows for the Cell Ontology | David Osumi-Sutherland |
| Monday | 14:40-15:00 | Developing a semantically interoperable knowledge graph schema to support single cell transcriptomics | Matthew Diller |
| Monday | 15:00-15:20 | The critical role of human validation in the era of AI-assisted biocuration | Patricia Carvajal-López |
| Monday | 15:40-16:00 | Chorus: an agentic framework for comparative regulatory genomics with sequence-to-function oracles | Luca Pinello |
| Monday | 16:40-17:40 | Keynote: AI and ontologies, the beginning of a beautiful friendship | Maryann Martone |
| Tuesday | 09:00-10:00 | Enabling precision health at scale for all | Carlos D. Bustamante |
| Tuesday | 11:05-11:20 | MEDFORD in a box: improvements and future directions for a metadata description language | Noah Daniels |
| Tuesday | 11:05-11:20 | MetaHQ and Meta2Onto: standardized annotations of public transcriptomics data | Parker Hicks |
| Tuesday | 11:20-11:40 | KGXVal: quality control for biomedical knowledge graph harmonization | Daniel Korn |
| Tuesday | 11:40-12:00 | KG-Registry: the open registry of knowledge graphs and their provenance | J. Harry Caufield |
| Tuesday | 12:00-12:20 | Cat-VRS: scalable representation of categorical genomic variation | Daniel Puthawala |
| Tuesday | 12:20-12:40 | Curating gene symbol relationships to resolve gene symbol ambiguity | Anastasia Bratulin |
| Tuesday | 12:20-12:40 | FAIRSCAPE: pre-model AI-readiness and interpretability for biomedical data | Timothy Clark |
| Tuesday | 12:20-12:40 | A FAIR framework for structured biomarker representation | Maria Kim |
| Tuesday | 12:20-13:00 | Enabling agentic systems for life science discovery | Chris Dallago |
| Tuesday | 12:40-13:00 | The OBO Foundry in 2026 | James Balhoff |
| Tuesday | 14:20-15:00 | In a genAI world, does structured knowledge still have a role in science? | Karin Verspoor |
| Tuesday | 15:00-15:20 | GO-CAM: curated pathways using GO and new tools | Paul Thomas |
| Tuesday | 15:20-15:40 | STAR-GO: hierarchical ontology-informed protein function prediction | Gökçe Uludoğan |
| Tuesday | 15:20-15:50 | Industry workshop: Venture Partner panel | Kristina E. Kitko, Anthony Philippakis, John Keilty |
| Tuesday | 15:40-16:00 | GIMME: graph inference for microbial metabolism exploration | Winston Anthony |
| Tuesday | 16:40-17:00 | DGLink: automated knowledge graph construction from data repositories | Woodward Galbraith |
| Wednesday | 09:00-10:00 | Uncovering the palimpsest of India's population history | Partha P. Majumder |
| Wednesday | 11:00-11:20 | Benchmarking AI scientists for omics data-driven biological discovery | Erpai Luo |
| Wednesday | 11:10-11:50 | How can AI agents help you advance biomedicine? | Kuan-lin Huang |
| Wednesday | 11:20-11:40 | Agentomics | Vlastimil Martinek |
| Wednesday | 11:40-11:50 | Data-driven AI system for learning how to run transcript assemblers | Yihang Shen |
| Wednesday | 11:50-12:00 | The Virtual Biotech: a multi-agent AI framework | Harrison Zhang |
| Wednesday | 12:00-12:10 | A conversational multi-agent AI framework for integrated multi-omics | Pankaj Rajdeo |
| Wednesday | 12:10-12:20 | Transfer learning for detecting Autism Spectrum Disorder using AutDB | Ruslan Kurmashev |
| Wednesday | 12:20-12:30 | Enabling direct nanopore sequencing of non-canonical bases | Mauricio Lisboa Perez |
| Wednesday | 12:30-12:40 | Linear-time prediction of proteome-scale microbial protein interactions | Andre Cornman |
| Wednesday | 14:20-14:40 | GATSBI: context-aware protein embeddings | Gowri Nayar |
| Wednesday | 14:40-15:00 | The NIH Common Fund Data Ecosystem Data Distillery Knowledge Graph (UBKG) | Deanne M. Taylor |
| Wednesday | 15:00-15:20 | Predicting phosphatase-substrate association using a heterogeneous knowledge graph | Marzieh Ayati |
| Wednesday | 15:20-15:40 | From general-purpose to disease-specific features: aligning LLM embeddings on a biomedical KG | Suman Pandey |
| Wednesday | 15:40-15:50 | drGT: attention-guided gene assessment of drug response | Yoshitaka Inoue |
| Wednesday | 15:50-16:00 | Challenges and opportunities in single-sample network modeling | Kimberly Glass |
| Wednesday | 14:20-14:40 | Canopy: an open-source platform for FAIR research data hubs | Marcos Martínez-Romero |
| Wednesday | 14:40-15:00 | Templated collaborative science resources for FAIR and reproducible AI research products | Hilmar Lapp |
| Wednesday | 14:40-15:00 | Posters.science: building open infrastructure for FAIR and AI-ready scientific posters | Bhavesh Patel |
| Wednesday | 14:40-15:00 | The Common Fund Data Ecosystem (CFDE) Incubator for Pan-NIH resources | Julie Jurgens, Broad Institute |
| Wednesday | 15:00-15:20 | As open as possible; as closed as necessary: enabling openness for sensitive human data | Mallory Freeberg |
| Wednesday | 15:00-15:20 | CTRL: a dynamic open source e-consent platform | Sarah Kummerfeld |
| Wednesday | 15:00-15:20 | Legal interoperability as infrastructure: enabling computable licensing in biomedical knowledge graphs | Shilpa Sundar |
| Wednesday | 15:20-15:40 | Evaluating the performance of LLMs in drafting data management plans | Nahid Zeinali |
| Wednesday | 15:20-15:40 | Toward domain-specific genomic AI agents: benchmarking sequencing library structure extraction | Chi-Lam Poon |
| Wednesday | 15:20-15:40 | PosterSentry: a lightweight multimodal classification system for scientific poster quality assurance | James O'Neill |
| Wednesday | 15:40-15:50 | Using AI to develop, maintain, and translate bioinformatics training materials | Geraldine Van der Auwera |
| Wednesday | 15:50-16:00 | Learning in public, losing in private? How AI chatbots and LLMs are reshaping bioinformatics culture | Van Quynh Truong |
| Wednesday | 16:40-17:40 | Open source in the age of AI | Not listed in the schedule |
| Thursday | 08:40-09:40 | From learning to leveraging graphs in biomedicine | Ritambhara Singh |
| Thursday | 11:00-13:00 | Building AI scientist workflows with BioNeMo | Angel Pizarro, Kyle Tretina |
| Thursday | 14:20-15:00 | Like a chicken in the corn: bioinformatics in the Great Plains | Iddo Friedberg |
| Thursday | 15:00-15:20 | Quantum-enhanced attention for expression prediction from histopathology | Kahn Rhrissorrakrai, IBM Research |
| Thursday | 15:20-15:40 | AI accelerates biological discovery, are we ready for the risks? | Michelle Holko |
| Thursday | 15:40-16:00 | Integrating genomics and structural biology | Remo Rohs |
| Thursday | 16:40-17:40 | Foundations of human-AI co-science | Marinka Zitnik |

## The 13 principles and the chapters behind them

Each card on the cheat sheet cites the book chapter it draws from, so the synthesis is traceable back to a specific part of the book, not a free-floating claim.

| # | Principle | Chapter(s) |
|---|-----------|------------|
| 01 | Specialists need a supervisor that can refuse | Chapter 1: Multi-agent orchestration |
| 02 | Ground answers in tools, not memorized weights | Chapter 4: The closing vision |
| 03 | Triangulate before asserting a claim | Chapter 2: Grounding the agent |
| 04 | Fit the representation to the question | Chapters 8 and 9: Embeddings and graph prediction |
| 05 | Name the hidden assumption before you trust a prediction | Chapter 10: The limits of network prediction |
| 06 | Ontologies anchor what a model can't promise | Chapter 5: Ontologies and schemas |
| 07 | Provenance travels with the fact, not beside it | Chapter 6: Registries, provenance, and quality control |
| 08 | Structure at ingest, not after the fact | Chapter 11: FAIR data infrastructure |
| 09 | Benchmarks must resist gaming | Chapter 3: Proving it works |
| 10 | Consent and population are computable fields | Chapters 12 and 15: Consent, licensing, and the keynote arc |
| 11 | AI drafts, a human or a cheap check decides | Chapter 13: AI in the curation pipeline |
| 12 | A public answer outlives a private one | Chapter 14: The closing culture debate |
| 13 | Risk lives in the connections, not the components | Chapter 17: Risk and money |

## How the key principles sheet was created

For ISMB I built a pre-conference research briefing instead, one file per day, written from the conference schedule and abstracts before I sat in a single talk, with sparse live notes layered in during the sessions I attended. That briefing is lighter than a transcript, so I ran an extra verification pass before synthesizing anything. Here is the process I ran:

1. Built a pre-conference briefing, one file per day, covering all 66 talks on my schedule: what each talk is, the problem it solves, how it works, why it matters for my work, and a link to the paper or preprint where the schedule listing gave one.
2. Attended the conference and layered short live in-room notes onto the relevant talks where something in the room changed or sharpened what the briefing said.
3. Dispatched 5 parallel research agents, one per day-file, to follow every "Paper or preprint" link and verify the actual abstract, methods, and results against what the briefing claimed, writing the verified findings to a separate research folder rather than editing the briefing in place. Talks with no findable paper got an explicit "no public paper found" flag instead of a silent gap.
4. Dispatched 5 parallel writing agents, one per book part, each reading both the briefing and the verified findings for its assigned talks, to synthesize a 17-chapter book using a first-principles structure: what a concept is, why it exists, how it works, what it means for my work. Every chapter cites its source talks inline.
5. Reviewed the finished book against the original briefing and the paper-verification notes, and checked chapter coverage against all 66 talks.
6. Distilled the book down to 13 cross-cutting principles for the cheat sheet, selected for showing up across multiple talks or being the most actionable for my own work on agentic search, each principle cited back to the chapter it came from.
7. Built the cheat sheet as a single-page, color-coded HTML diagram.
8. Wrote the Confluence wrapper document.

Human-AI division: AI ran the paper verification, drafted every chapter, drafted the cheat sheet content and diagram, and drafted the wrapper document. I owned the pre-conference schedule and scope, which talks got live in-room notes, the review pass against the finished book, principle selection and curation, and the decision on what gets published externally and when.

### The prompt I used

Every chapter and every cheat-sheet principle in this pass follows the same fixed first-principles skeleton, enforced as a standing rule rather than typed fresh each time:

```
## What is [x]?
[1-2 sentence definition anyone could understand]

## Why does it exist?
[The problem it solves, in plain terms]

## How does it work?
[Step-by-step, simple language]

## What this means for you
[Practical implications, specific actions]
```

Short sentences, active voice, no jargon without a plain-word definition, no corporate filler. The research and writing agents were instructed to apply this skeleton to every chapter and to cite the specific talk (and, where relevant, the specific verified paper finding) behind every claim.

### About this workflow

It may not match how you learn or the source material you have. If you want to use it, treat it as inspiration and customize freely. Two axes worth tuning:

- The verification stage: I ran it because the source material started as a pre-brief rather than a transcript. Skip it entirely if you are working from live notes or a recording.
- The editorial step: I picked 13 principles from 66 talks. You might want fewer, more, or no synthesis at all, just per-talk summaries.

Treat both the workflow and the prompt skeleton as starting points, not templates.

## License

Released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You can share and adapt with attribution.

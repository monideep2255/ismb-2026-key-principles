# Agentic AI and knowledge graphs at ISMB 2026: a synthesis

A structured book synthesizing 66 talks from ISMB 2026 (July 13-16, 2026) into a coherent narrative about how agentic AI, knowledge graphs, and open science infrastructure are converging in bioinformatics.

## Contents

### Part 1: The agentic AI core

- [Ch 1: Multi-agent orchestration, architectures for teams of specialist agents](Part_1_The_agentic_AI_core/01_Multi_agent_orchestration.md)
- [Ch 2: Grounding the agent, retrieval, multi-hop reasoning, and evidence triangulation](Part_1_The_agentic_AI_core/02_Grounding_the_agent.md)
- [Ch 3: Proving it works, benchmarks, checkpoints, and applied evaluation](Part_1_The_agentic_AI_core/03_Proving_it_works.md)
- [Ch 4: The closing vision, human-AI co-science](Part_1_The_agentic_AI_core/04_The_closing_vision.md)

### Part 2: Knowledge graphs as infrastructure

- [Ch 5: Ontologies and schemas as the shared vocabulary](Part_2_Knowledge_graphs_as_infrastructure/05_Ontologies_and_schemas_as_shared_vocabulary.md)
- [Ch 6: Registries, provenance, and quality control](Part_2_Knowledge_graphs_as_infrastructure/06_Registries_provenance_and_quality_control.md)
- [Ch 7: Structured knowledge in a genAI world](Part_2_Knowledge_graphs_as_infrastructure/07_Structured_knowledge_in_a_genAI_world.md)

### Part 3: Graphs as prediction engines

- [Ch 8: Embeddings that encode biological context](Part_3_Graphs_as_prediction_engines/08_Embeddings_that_encode_biological_context.md)
- [Ch 9: Graphs that predict function and interaction](Part_3_Graphs_as_prediction_engines/09_Graphs_that_predict_function_and_interaction.md)
- [Ch 10: The limits of network prediction](Part_3_Graphs_as_prediction_engines/10_The_limits_of_network_prediction.md)

### Part 4: Open, trustworthy, reusable science

- [Ch 11: FAIR data infrastructure and metadata standards](Part_4_Open_trustworthy_reusable_science/11_FAIR_data_infrastructure_and_metadata_standards.md)
- [Ch 12: Consent, licensing, and sensitive data](Part_4_Open_trustworthy_reusable_science/12_Consent_licensing_and_sensitive_data.md)
- [Ch 13: AI in the curation and quality pipeline](Part_4_Open_trustworthy_reusable_science/13_AI_in_the_curation_and_quality_pipeline.md)
- [Ch 14: The closing culture debate](Part_4_Open_trustworthy_reusable_science/14_The_closing_culture_debate.md)

### Part 5: The bigger picture

- [Ch 15: The keynote arc](Part_5_The_bigger_picture/15_The_keynote_arc.md)
- [Ch 16: Methods and infrastructure](Part_5_The_bigger_picture/16_Methods_and_infrastructure.md)
- [Ch 17: Risk and money](Part_5_The_bigger_picture/17_Risk_and_money.md)

### Appendix

- [Source file mapping](Appendix_Source_Files.md)

## Source material

This book synthesizes 66 ISMB 2026 conference talks captured across 5 days (Monday through Thursday, July 13-16, 2026). The raw material started as a pre-conference research briefing (`sources/`, written from abstracts and papers before the conference, with sparse live in-room notes layered in during sessions), which is a materially lighter grade of source than a live transcript. To close that gap, every talk's cited paper or preprint was verified against its actual abstract, methods, and results before synthesis (`research/`, one file per day, produced via the `/web-research` protocol). Each chapter cites its sources inline and links back to the original talk; the appendix maps every talk to the chapter that references it.

## How this was built

All 66 talks were captured in a pre-conference research briefing, then enriched with verified paper content across 5 parallel research agents (one per day-file), then synthesized into this book structure using 5 parallel writing agents (one per part). The book follows first-principles structure: each chapter starts with what the concept is, why it exists, how it works, and what it means for you. One talk, "Enabling agentic systems for life science discovery" (Tuesday, Tech Track), was missed in the initial writing-agent dispatch and folded into Chapter 1 in a follow-up pass; the appendix and source counts below reflect the corrected, complete set of 66.

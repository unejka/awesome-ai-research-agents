# Awesome AI Research Agents

A curated list of AI agents, workflows, skills, and tools for the full AI/ML research lifecycle, from literature review to paper submission.

This list focuses on public GitHub projects that help researchers automate or accelerate at least one part of the research loop:

- Literature review and knowledge synthesis
- Baseline selection and paper understanding
- Baseline reproduction and paper-to-code implementation
- Idea generation and research planning
- Experiment execution and result analysis
- Paper writing, review, and submission preparation

## Contents

- [End-to-End Research Agents](#end-to-end-research-agents)
- [Deep Research and Literature Review](#deep-research-and-literature-review)
- [Paper Reading and Scholarly QA](#paper-reading-and-scholarly-qa)
- [Idea Generation and Research Planning](#idea-generation-and-research-planning)
- [Baseline Reproduction and Paper-to-Code](#baseline-reproduction-and-paper-to-code)
- [Experiments, Data Science, and Analysis](#experiments-data-science-and-analysis)
- [Paper Writing and Review](#paper-writing-and-review)
- [Skills, Prompts, and Agent Workflows](#skills-prompts-and-agent-workflows)
- [Domain-Specific Research Agents](#domain-specific-research-agents)
- [Benchmarks and Evaluation](#benchmarks-and-evaluation)
- [Related Awesome Lists and Surveys](#related-awesome-lists-and-surveys)
- [Contributing](#contributing)

## End-to-End Research Agents

- [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) - ARIS, a markdown-only autonomous ML research skill system for idea discovery, cross-model review, experiment automation, and paper improvement.
- [SakanaAI/AI-Scientist](https://github.com/SakanaAI/AI-Scientist) - End-to-end framework for automated open-ended scientific discovery.
- [SakanaAI/AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) - Agentic tree-search version of AI Scientist for workshop-level automated scientific discovery.
- [ResearAI/DeepScientist](https://github.com/ResearAI/DeepScientist) - Local-first autonomous research studio for long-horizon baseline reproduction, experiment iteration, findings memory, and paper-ready outputs.
- [HKUDS/AI-Researcher](https://github.com/HKUDS/AI-Researcher) - Autonomous research system covering literature review, idea generation, algorithm design, implementation, validation, and result analysis.
- [SamuelSchmidgall/AgentLaboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) - Multi-agent research workflow for literature review, planning, experiments, and report writing.
- [aiming-lab/AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) - Autonomous idea-to-paper research pipeline compatible with OpenClaw, CLI, Claude Code, and other coding agents.
- [Muuuun/luxas](https://github.com/Muuuun/luxas) - Autonomous research harness that reads papers, runs experiments, writes LaTeX reports, and compiles manuscripts end to end.
- [Sibyl-Research-Team/AutoResearch-SibylSystem](https://github.com/Sibyl-Research-Team/AutoResearch-SibylSystem) - Claude Code-native autonomous AI scientist for literature survey, hypothesis generation, GPU experiments, paper writing, and self-evolution.
- [damonwan1/AutoScholarLoop](https://github.com/damonwan1/AutoScholarLoop) - Multi-agent AUTO Research loop for field mapping, idea selection, experiment execution, evidence-grounded writing, and quality audit.
- [gaotiexinqu/OneResearchClaw](https://github.com/gaotiexinqu/OneResearchClaw) - Multi-format input-to-report pipeline for grounded literature research, review-rewrite loops, skill evolution, and multi-format export.
- [ymx10086/ResearchClaw](https://github.com/ymx10086/ResearchClaw) - Local-first research OS for durable projects, workflows, papers, experiments, artifacts, channels, skills, and automation.
- [nanoAgentTeam/research-claw](https://github.com/nanoAgentTeam/research-claw) - Self-hosted AI research assistant for literature search, LaTeX projects, Overleaf sync, deadline tracking, and chat-channel workflows.
- [leonardodalinky/SciDER](https://github.com/leonardodalinky/SciDER) - Scientific data-centric end-to-end researcher with ideation, data analysis, paper writing, web UI, coding backend, and benchmark workflows.
- [Technion-Kishony-lab/data-to-paper](https://github.com/Technion-Kishony-lab/data-to-paper) - Multi-agent framework that turns raw data into human-verifiable scientific papers.
- [Eldergenix/Plato-Scientific-Research-Autonomous-Agent](https://github.com/Eldergenix/Plato-Scientific-Research-Autonomous-Agent) - Multi-agent system that turns experimental data into peer-reviewable LaTeX manuscripts with retrieval, citation validation, evidence matrices, and revision loops.
- [microsoft/RD-Agent](https://github.com/microsoft/RD-Agent) - Research-and-development agent for data-driven AI solution building and industrial R&D workflows.
- [HKUDS/Auto-Deep-Research](https://github.com/HKUDS/Auto-Deep-Research) - Autonomous deep-research system from the HKUDS research-agent ecosystem.
- [Xiangyue-Zhang/auto-deep-researcher-24x7](https://github.com/Xiangyue-Zhang/auto-deep-researcher-24x7) - Always-on autonomous deep researcher for long-running research tasks.
- [mshumer/autonomous-researcher](https://github.com/mshumer/autonomous-researcher) - Experimental autonomous researcher for generating and iterating on research outputs.
- [karpathy/autoresearch](https://github.com/karpathy/autoresearch) - Experimental autonomous research-agent project and conversation starter for agentic research workflows.

## Deep Research and Literature Review

- [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher) - Open deep-research agent for web and local research reports with cited sources.
- [langchain-ai/open_deep_research](https://github.com/langchain-ai/open_deep_research) - LangChain and LangGraph implementation of an open deep-research assistant.
- [dzhng/deep-research](https://github.com/dzhng/deep-research) - Minimal implementation of an iterative deep-research agent using search, scraping, and LLMs.
- [nickscamara/open-deep-research](https://github.com/nickscamara/open-deep-research) - Open-source deep-research agent implementation using Firecrawl.
- [LearningCircuit/local-deep-research](https://github.com/LearningCircuit/local-deep-research) - Local-first deep-research assistant with document analysis and report generation.
- [Alibaba-NLP/DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) - Tongyi Deep Research, an open-source deep-research agent from Alibaba NLP.
- [MiroMindAI/MiroThinker](https://github.com/MiroMindAI/MiroThinker) - Deep research agent and model family optimized for complex research, prediction, long-context reasoning, and many-step tool use.
- [MiroMindAI/MiroFlow](https://github.com/MiroMindAI/MiroFlow) - Open-source research-agent framework for deep information seeking and multi-step research.
- [TheBlewish/Automated-AI-Web-Researcher-Ollama](https://github.com/TheBlewish/Automated-AI-Web-Researcher-Ollama) - Local Ollama-based automated web researcher.
- [silicatelabs/airesearchagent](https://github.com/silicatelabs/airesearchagent) - Autonomous research agent for planning, searching, analyzing, and synthesizing reports.
- [stanford-oval/storm](https://github.com/stanford-oval/storm) - Knowledge curation and long-form report generation system with citation-focused research workflows.
- [Black-Lights/prisma-review-tool](https://github.com/Black-Lights/prisma-review-tool) - AI-assisted systematic literature review tool aligned with PRISMA 2020 workflows.
- [PouriaRouzrokh/LatteReview](https://github.com/PouriaRouzrokh/LatteReview) - Multi-agent Python package for academic literature review, screening, scoring, abstraction, and reviewer-style workflows.
- [HolobiomicsLab/Perspicacite-AI](https://github.com/HolobiomicsLab/Perspicacite-AI) - Local-first scientific literature research assistant with multi-database search, citation-graph expansion, agentic RAG modes, MCP, and provenance export.
- [Arcadia-Science/agent-literature-review](https://github.com/Arcadia-Science/agent-literature-review) - Prototype multi-agent lab for paper discussion, local-folder paper reading, research planning, and cross-disciplinary synthesis.
- [yzyzieee/Research-Literature-Hub](https://github.com/yzyzieee/Research-Literature-Hub) - Team literature-management hub that turns verified paper records into reusable LLM context and versioned GitHub knowledge records.

## Paper Reading and Scholarly QA

- [Future-House/paper-qa](https://github.com/Future-House/paper-qa) - Retrieval-augmented question answering over scientific papers.
- [CurryTang/Amadeus](https://github.com/CurryTang/Amadeus) - AI research assistant that reads, summarizes, organizes, and acts on academic papers.
- [AbhaySingh71/Agentic-AI-Researcher](https://github.com/AbhaySingh71/Agentic-AI-Researcher) - LangGraph-based assistant for fetching, summarizing, and analyzing arXiv papers.
- [Baldwinzc/citelocal-agent](https://github.com/Baldwinzc/citelocal-agent) - Local-first paper QA agent with hybrid retrieval, page-level citations, citation verification, and optional local LLM support.
- [Leey21/arxiv-translator](https://github.com/Leey21/arxiv-translator) - Agent skill for translating arXiv LaTeX sources into Chinese PDFs while preserving layout, formulas, references, and paper structure.
- [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) - MCP server for arXiv search and paper access in agent workflows.
- [blessonism/openclaw-search-skills](https://github.com/blessonism/openclaw-search-skills) - Search skills for OpenClaw-style research agents.

## Idea Generation and Research Planning

- [pengsida/learning_research](https://github.com/pengsida/learning_research) - Research training guide covering topic selection, idea development, experiments, paper writing, rebuttals, and academic presentations.
- [pkargupta/idea_catalyst](https://github.com/pkargupta/idea_catalyst) - Metacognition-driven framework for scientific brainstorming with humans and LLMs.
- [ChicagoHAI/hypothesis-generation](https://github.com/ChicagoHAI/hypothesis-generation) - HypoGeniC and HypoRefine frameworks for LLM-based hypothesis generation from datasets, literature, and agentic refinement loops.
- [jataware/open-coscientist](https://github.com/jataware/open-coscientist) - Open LangGraph adaptation of AI co-scientist for literature-grounded hypothesis generation, review, ranking, tournament judging, and evolution.
- [ai-in-pm/AI-Co-Scientist](https://github.com/ai-in-pm/AI-Co-Scientist) - Multi-agent scientific research framework inspired by AI Co-Scientist for generating, evaluating, ranking, and refining hypotheses.
- [AutoSurveys/AutoSurvey](https://github.com/AutoSurveys/AutoSurvey) - LLM-based automated academic survey generation.
- [IAAR-Shanghai/SurveyX](https://github.com/IAAR-Shanghai/SurveyX) - Academic survey paper generation with literature search and synthesis.
- [TechnicolorGUO/InteractiveSurvey](https://github.com/TechnicolorGUO/InteractiveSurvey) - Personalized and interactive survey paper generation system.
- [InternScience/SurveyForge](https://github.com/InternScience/SurveyForge) - Memory-driven and outline-oriented automated survey generation system.
- [Superbooming/Awesome-scientific-idea-generation](https://github.com/Superbooming/Awesome-scientific-idea-generation) - Curated resources on AI-assisted scientific idea generation.

## Baseline Reproduction and Paper-to-Code

- [going-doer/Paper2Code](https://github.com/going-doer/Paper2Code) - Multi-agent system for turning machine-learning papers into runnable code.
- [shoushouyu/Automated-Paper-to-Code](https://github.com/shoushouyu/Automated-Paper-to-Code) - AutoP2C, a multi-agent framework for generating executable code repositories from multimodal academic papers.
- [HKUDS/DeepCode](https://github.com/HKUDS/DeepCode) - Open agentic coding system with paper-to-code and repository-analysis tooling for research implementation workflows.
- [yunx-z/MLRC-Bench](https://github.com/yunx-z/MLRC-Bench) - Machine-learning research challenge benchmark built around agent-executable tasks.
- [UNITES-Lab/Awesome-MLE-Coding-Agent](https://github.com/UNITES-Lab/Awesome-MLE-Coding-Agent) - Curated work on machine-learning engineering and research-coding agents.

## Experiments, Data Science, and Analysis

- [ruc-datalab/DeepAnalyze](https://github.com/ruc-datalab/DeepAnalyze) - Agentic LLM for autonomous data science and analyst-grade reports.
- [WecoAI/aideml](https://github.com/WecoAI/aideml) - AI-driven machine-learning engineering and experimentation environment.
- [ICICLE-ai/ScienceAgent](https://github.com/ICICLE-ai/ScienceAgent) - Language agent for data-driven scientific discovery tasks, including ScienceAgentBench workflows.
- [liugangcode/deepevolve](https://github.com/liugangcode/deepevolve) - Research and coding agent that combines deep research with AlphaEvolve-style implementation, evaluation, and algorithm evolution.
- [deep-symbolic-mathematics/LLM-SR](https://github.com/deep-symbolic-mathematics/LLM-SR) - LLM-based scientific equation discovery and symbolic regression method with evolutionary program search.
- [HKUSTDial/awesome-data-agents](https://github.com/HKUSTDial/awesome-data-agents) - Curated data-agent resources relevant to experiment analysis and scientific data workflows.

## Paper Writing and Review

- [Leey21/awesome-ai-research-writing](https://github.com/Leey21/awesome-ai-research-writing) - Curated AI research writing skills and repositories for paper drafting, related work, citations, and polishing.
- [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra) - Multi-agent framework that turns ideas and experimental logs into submission-ready LaTeX manuscripts with literature synthesis and figures.
- [TobiasBlask/open-paper-machine](https://github.com/TobiasBlask/open-paper-machine) - Claude Code plugin for autonomous academic paper production, citation verification, LaTeX export, revision, and paper-vs-code audits.
- [Master-cai/Research-Paper-Writing-Skills](https://github.com/Master-cai/Research-Paper-Writing-Skills) - Research paper writing skills for agentic drafting workflows.
- [blader/humanizer](https://github.com/blader/humanizer) - Portable cross-agent skill that revises AI-generated prose to sound more natural and can calibrate rewrites to a researcher's own voice.
- [K-Dense-AI/claude-scientific-writer](https://github.com/K-Dense-AI/claude-scientific-writer) - Scientific writing skillset for Claude-style coding agents.
- [lishix520/academic-paper-skills](https://github.com/lishix520/academic-paper-skills) - Academic paper skills for writing and research-agent workflows.
- [claesbackman/AI-research-feedback](https://github.com/claesbackman/AI-research-feedback) - AI-assisted research feedback workflows.
- [Boom5426/Nature-Paper-Skills](https://github.com/Boom5426/Nature-Paper-Skills) - Skills for Nature-style scientific paper drafting.
- [fcakyon/phd-skills](https://github.com/fcakyon/phd-skills) - PhD and academic research skills for agentic workflows.

## Skills, Prompts, and Agent Workflows

- [Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) - Large open-source skill library for AI agents conducting research from idea to paper.
- [InternScience/Awesome-Scientific-Skills](https://github.com/InternScience/Awesome-Scientific-Skills) - Science-first curated collection of agent skills for bioinformatics, cheminformatics, data analysis, scientific writing, and literature search.
- [yogsoth-ai/de-anthropocentric-research-engine](https://github.com/yogsoth-ai/de-anthropocentric-research-engine) - Research orchestration system with hundreds of markdown skills for direction setting, literature acquisition, gap discovery, hypothesis formation, stress testing, and experiment specs.
- [Ar9av/PaperOrchestra](https://github.com/Ar9av/PaperOrchestra) - Host-agent-executable skill pack for running the PaperOrchestra paper-writing pipeline across Claude Code, Cursor, Cline, Aider, and similar agents.
- [maxwellsdm1867/wheeler](https://github.com/maxwellsdm1867/wheeler) - Claude Code-native scientific workspace with slash commands, local execution, provenance tracking, and knowledge-graph-backed research artifacts.
- [unejka/useful-research-skills](https://github.com/unejka/useful-research-skills) - Codex skill collection for arXiv paper reading, Chinese paper translation, and combined translation plus methodology interpretation workflows.
- [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) - Academic research skills for literature review, writing, review, and research assistance.
- [Imbad0202/academic-research-skills-codex](https://github.com/Imbad0202/academic-research-skills-codex) - Codex-native academic research skills suite.
- [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) - Scientific agent skills for research workflows.
- [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) - Nature-style research and writing skills.
- [Galaxy-Dawn/claude-scholar](https://github.com/Galaxy-Dawn/claude-scholar) - Claude-oriented scholarly research skills.
- [HKUSTDial/Supervisor-Skills](https://github.com/HKUSTDial/Supervisor-Skills) - Supervisor skills for agentic research coordination.
- [brycewang-stanford/Auto-Research-Skills](https://github.com/brycewang-stanford/Auto-Research-Skills) - Bundled skills and catalog for auto-research workflows.
- [brycewang-stanford/Auto-Empirical-Research-Skills](https://github.com/brycewang-stanford/Auto-Empirical-Research-Skills) - Empirical research skills and tool catalog for agentic data analysis.
- [rohunvora/x-research-skill](https://github.com/rohunvora/x-research-skill) - Research skill package for agent workflows.
- [Weizhena/Deep-Research-skills](https://github.com/Weizhena/Deep-Research-skills) - Deep-research skills for AI agents.
- [andrehuang/research-companion](https://github.com/andrehuang/research-companion) - Research companion skillset for assisted research workflows.
- [zLanqing/codex-claude-academic-skills](https://github.com/zLanqing/codex-claude-academic-skills) - Academic skills designed for Codex and Claude-style agents.
- [luwill/research-skills](https://github.com/luwill/research-skills) - Research skills for LLM agent workflows.
- [poemswe/co-researcher](https://github.com/poemswe/co-researcher) - Co-researcher skills for collaborative agentic research.

## Domain-Specific Research Agents

- [snap-stanford/Biomni](https://github.com/snap-stanford/Biomni) - Biomedical AI agent environment for life-science research tasks.
- [aipoch/medical-research-skills](https://github.com/aipoch/medical-research-skills) - Medical research skills for agent platforms.
- [ur-whitelab/chemcrow-public](https://github.com/ur-whitelab/chemcrow-public) - Chemistry-focused LLM agent for tool-augmented chemical research.
- [lamm-mit/SciAgentsDiscovery](https://github.com/lamm-mit/SciAgentsDiscovery) - Scientific discovery agents for materials and scientific reasoning workflows.
- [zou-group/virtual-lab](https://github.com/zou-group/virtual-lab) - Multi-agent virtual lab for AI-assisted biological research.
- [gomesgroup/coscientist](https://github.com/gomesgroup/coscientist) - AI co-scientist system for autonomous experimental planning and scientific discovery.
- [Future-House/robin](https://github.com/Future-House/robin) - Research agent from FutureHouse for scientific discovery workflows.
- [bio-xyz/BioAgents](https://github.com/bio-xyz/BioAgents) - Bio-agent tools and workflows for biological research.
- [jiaxianyan/BioDataLab](https://github.com/jiaxianyan/BioDataLab) - Benchmark and evaluation suite for LLM agents performing real-world biological database curation tasks.

## Benchmarks and Evaluation

- [openai/preparedness PaperBench](https://github.com/openai/preparedness/tree/main/project/paperbench) - Benchmark for evaluating AI agents on replicating AI research papers.
- [snap-stanford/MLAgentBench](https://github.com/snap-stanford/MLAgentBench) - Benchmark suite for research-agent experimentation ability.
- [OSU-NLP-Group/ScienceAgentBench](https://github.com/OSU-NLP-Group/ScienceAgentBench) - ICLR 2025 benchmark for data-driven scientific discovery agents.
- [allenai/discoveryworld](https://github.com/allenai/discoveryworld) - Virtual environment for developing and evaluating automated scientific discovery agents.
- [ulab-uiuc/research-town](https://github.com/ulab-uiuc/research-town) - Multi-agent research-community simulator with research agents, collaborative environments, and task engines.
- [deep-symbolic-mathematics/llm-srbench](https://github.com/deep-symbolic-mathematics/llm-srbench) - Benchmark for evaluating LLM-based scientific equation discovery and symbolic regression beyond memorized formulas.
- [allenai/discoverybench](https://github.com/allenai/discoverybench) - Discovery benchmark for scientific reasoning and discovery systems.
- [Future-House/aviary](https://github.com/Future-House/aviary) - Agent benchmark environment from FutureHouse.
- [weAIDB/SurveyBench](https://github.com/weAIDB/SurveyBench) - Benchmark for evaluating AI-generated academic surveys.
- [RUCAIBox/awesome-agent-harness](https://github.com/RUCAIBox/awesome-agent-harness) - Curated benchmark and harness resources for AI agents, including scientific discovery benchmarks.

## Related Awesome Lists and Surveys

- [ResearAI/Awesome-AI-Scientist](https://github.com/ResearAI/Awesome-AI-Scientist) - Survey and resource list for AI Scientist research.
- [worldbench/awesome-ai-auto-research](https://github.com/worldbench/awesome-ai-auto-research) - Survey-oriented list for AI-assisted and automated research.
- [ai-agents-2030/awesome-deep-research-agent](https://github.com/ai-agents-2030/awesome-deep-research-agent) - Awesome list focused on deep-research agents.
- [handsome-rich/Awesome-Auto-Research-Tools](https://github.com/handsome-rich/Awesome-Auto-Research-Tools) - Auto-research tools across literature review, experiments, writing, and review.
- [ai-boost/awesome-ai-for-science](https://github.com/ai-boost/awesome-ai-for-science) - Broad AI-for-science resource list.
- [Research-Equality/awesome-ai-scientists](https://github.com/Research-Equality/awesome-ai-scientists) - AI scientist systems, platforms, and benchmarks.
- [tsinghua-fib-lab/Awesome-AI-Scientists](https://github.com/tsinghua-fib-lab/Awesome-AI-Scientists) - Paper and project list for AI scientist systems.
- [chchenhui/awesome-research-agents](https://github.com/chchenhui/awesome-research-agents) - Research-agent papers, projects, and benchmarks.
- [alvinreal/awesome-autoresearch](https://github.com/alvinreal/awesome-autoresearch) - Curated autonomous research resources.
- [zkzhou126/AI-for-Research](https://github.com/zkzhou126/AI-for-Research) - From hypothesis to publication: resources for AI-assisted research.
- [HKUST-KnowComp/Awesome-LLM-Scientific-Discovery](https://github.com/HKUST-KnowComp/Awesome-LLM-Scientific-Discovery) - LLM-based scientific discovery resources.
- [AgenticScience/Awesome-Agent-Scientists](https://github.com/AgenticScience/Awesome-Agent-Scientists) - Agent scientists and agentic science paper list.
- [zoedsy/awesome-science-agents](https://github.com/zoedsy/awesome-science-agents) - Science-agent papers, systems, and benchmarks.
- [natnew/Awesome-AI-Scientists](https://github.com/natnew/Awesome-AI-Scientists) - AI scientist resources and benchmarks.
- [0x11c11e/awesome-ai-research-tools](https://github.com/0x11c11e/awesome-ai-research-tools) - AI research tools list.
- [SpectrAI-Initiative/Vibe-Research-Guide](https://github.com/SpectrAI-Initiative/Vibe-Research-Guide) - Guide to LLM-agent-driven scientific research automation across literature review, ideation, experiments, writing, and evaluation.
- [kyrolabs/awesome-agents](https://github.com/kyrolabs/awesome-agents) - Broad AI agents awesome list with research-agent entries.

## Contributing

Pull requests are welcome. Good additions usually meet these criteria:

- Public GitHub repository
- Directly helps with AI/ML research, scientific research, literature review, experiment automation, paper writing, or research-agent evaluation
- Has enough documentation for a researcher to understand what it does
- Preferably includes an open-source license

Suggested entry format:

```md
- [owner/repo](https://github.com/owner/repo) - One-sentence description focused on the research workflow stage it supports.
```

Please avoid adding closed-source SaaS products unless they have a substantial open-source component.

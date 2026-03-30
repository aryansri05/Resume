# Aryan Srivastava

**Computer Science & Engineering | Open Source Contributor | AI Systems**

📍 Bengaluru, India &nbsp;|&nbsp; 📞 +91 7393887788 &nbsp;|&nbsp; 📧 aryansriva05@gmail.com &nbsp;|&nbsp; 🐙 [github.com/aryansri05](https://github.com/aryansri05)

---

## Profile

Second-year Computer Science student with hands-on experience in GPU-accelerated computing, multi-agent AI systems, and production-grade open source development. Active contributor to NVIDIA RAPIDS (cuDF) with two merged pull requests, and ongoing contributor to AiiDA. Building a FastMCP-based multi-agent system for natural language interaction with scientific workflow engines. Comfortable navigating large C++/Python codebases, writing tests, and handling multi-iteration code review.

---

## Education

**Bachelor of Technology — Computer Science and Engineering**
MANIPAL INSTITUTE OF TECHNOLOGY, Bengaluru, India
*Expected Graduation: January 2028*

---

## Open Source Contributions

### NVIDIA RAPIDS — cuDF (GPU DataFrame Library)

**PR #20747 — Boolean Casting Consistency Fix** | ✅ Merged
[github.com/rapidsai/cudf/pull/20747](https://github.com/rapidsai/cudf/pull/20747)

- Identified and fixed a behavioral inconsistency in boolean casting between cuDF and Pandas, ensuring API parity across GPU and CPU dataframe operations
- Modified core Python/C++ interop logic and added regression tests to prevent future regressions

**PR #20862 — Hybrid Scan API (libcudf C++ Layer)** | ✅ Merged
[github.com/rapidsai/cudf/pull/20862](https://github.com/rapidsai/cudf/pull/20862)

- Added a new hybrid scan API to the libcudf C++ layer for building all-true row masks, enabling more efficient GPU-accelerated boolean operations
- Implemented memory-safe null value handling during high-performance data transformations and wrote comprehensive unit tests for edge cases

---

### AiiDA (Scientific Workflow Management Framework)

**Issue #7243 — QueryBuilder Bug Report** | 🔄 Fix Under Active Review
[github.com/aiidateam/aiida-core/issues/7243](https://github.com/aiidateam/aiida-core/issues/7243)

- Identified a bug in `QueryBuilder._get_ormclass_from_str()` hardcoding the `'group.core'` classifier, causing incorrect ORM class resolution in certain query patterns
- Proposed and submitted a fix currently under active review by the AiiDA core team

---

## Projects

### FastMCP Multi-Agent System for AiiDA *(In Progress)*

- Building a multi-agent system using FastMCP to expose AiiDA's Python API as structured tools for local LLM interaction
- Implements a Diagnostic Agent with smart log parsing — local keyword extraction before any LLM call — to diagnose failed CalcJobs without exceeding context limits
- Optimizing local agent workflows on Apple Silicon unified memory using Ollama + Llama 3

### Paper Trading Platform

- Built a full-stack web-based options trading simulator supporting calls, puts, and portfolio tracking
- Frontend in React.js with real-time market data integration; backend in Node.js/Express with PostgreSQL
- Implemented secure JWT-based user authentication and equity portfolio calculation engine

---

## Technical Skills

| Area | Skills |
|------|--------|
| **Languages** | Python, C++, JavaScript, SQL, Bash |
| **AI / ML** | LangGraph, FastMCP, ChromaDB, Ollama, Llama 3, RAG, LLM Agents |
| **HPC / GPU** | CUDA, cuDF, RAPIDS AI, Apple Silicon (Unified Memory), SLURM |
| **Frameworks** | React.js, Node.js, Express, Pandas, NumPy, Pytest |
| **Tools** | Git, GitHub Actions, Docker, CI/CD, PostgreSQL, VS Code |

---

## GSoC 2026

Applying for **Natural Language Interface for AiiDA using Multi-Agent AI** under NumFOCUS.

Proposal covers a three-agent system (Search, Diagnostic, Execution) built on LangGraph + FastMCP + ChromaDB, running fully locally via Ollama for HPC data privacy.

**Mentors:** Ali Khosravi, Jusong Yu

📄 [Download CV (PDF)](./Aryan_Srivastava_CV.pdf)

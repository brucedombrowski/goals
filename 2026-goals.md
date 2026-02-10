# 2026 Annual Goals — Bruce Dombrowski

Derived from 17 public repositories, 1,082 commits, 149 release tags, and 226K+ lines of code across government compliance, AI agent methodology, and systems engineering.

---

## Goal 1: Publish White Paper on AI-Assisted Government Compliance

**Short summary (WorkDay):**
Publish peer-reviewed paper on git + AI coding agents for NIST/FIPS compliance, demonstrating methodology across 17 open-source repos.

**Long description:**
Submit the white paper "Git and AI Coding Agents for Government Compliance: A Human-in-the-Loop Methodology" to a peer-reviewed venue (IEEE, ACM, or government technology conference). The paper presents a five-phase methodology validated across 17 repositories with 1,082 commits in 66 calendar days by a single engineer. Publication establishes credibility for the methodology and creates a citable reference for organizational adoption.

**Success criteria:**
1. Paper submitted to at least one peer-reviewed venue by Q2 2026
2. Paper accepted for publication or posted to preprint server (arXiv/SSRN) by Q4 2026
3. At least 3 external citations or references within 12 months of publication

**Milestones:**
- Q1 2026: Complete v1.0.0 release with all metrics finalized and auto-generated
- Q2 2026: Submit to IEEE Government Technology Conference or equivalent venue
- Q4 2026: Publication or preprint with DOI assigned

---

## Goal 2: Mature Security Verification Toolkit to Enterprise-Ready Release

**Short summary (WorkDay):**
Advance security-toolkit to v2.0 with CI/CD integration, cross-platform parity, and expanded NIST 800-53/800-171 control automation.

**Long description:**
The Security Verification Toolkit (488 commits, 94 release tags, 76K LOC) automates 14 NIST SP 800-53 controls with evidence-backed attestation PDFs. Goal is to expand control coverage, add CI/CD pipeline integration (GitHub Actions, GitLab CI), and achieve cross-platform Windows/macOS/Linux parity. This creates a production-ready compliance scanning tool suitable for adoption by government contractors.

**Success criteria:**
1. Automated NIST controls expanded from 14 to 20 (covering additional AU, IA, and SC families)
2. CI/CD integration published: GitHub Actions workflow + GitLab CI template that runs compliance scans on every push
3. Homebrew + platform-specific installers available for macOS, Linux, and Windows (via WSL2 or native)

**Milestones:**
- Q1 2026: CI/CD integration (GitHub Actions reusable workflow) published and documented
- Q2 2026: 6 additional NIST controls automated (AU-6, IA-2, IA-5, SC-8, SC-13, SC-28)
- Q3 2026: Cross-platform installer packages and v2.0.0 tagged release

---

## Goal 3: Establish Open-Source Compliance Process Framework

**Short summary (WorkDay):**
Publish systems-engineering + ai-agents frameworks as reusable open-source process toolkit for regulated development teams.

**Long description:**
Formalize the five-phase process framework (systems-engineering repo) and model-agnostic agent templates (ai-agents repo) into a documented, adoptable toolkit. The framework separates *what* (role responsibilities, compliance standards, audit requirements) from *how* (specific AI tools, model selection). Goal is external adoption: other engineers and teams can clone the repos and apply the methodology to their own compliance projects without reinventing the process.

**Success criteria:**
1. systems-engineering and ai-agents repos each have documented getting-started guides with worked examples
2. At least 5 GitHub stars or forks across the framework repos (indicating external interest)
3. One external team or individual publicly adopts the framework (blog post, issue, or citation)

**Milestones:**
- Q1 2026: ai-agents repo v1.0.0 with complete documentation and multi-vendor examples
- Q2 2026: systems-engineering repo v1.0.0 with traceability matrix templates and desk instructions
- Q4 2026: Conference talk, blog post, or tutorial demonstrating the framework to external audience

---

## Goal 4: Deliver Training Material for Git-Based Compliance Workflows

**Short summary (WorkDay):**
Create and deliver 30-minute training module on git version control for compliance, targeting non-technical stakeholders and new engineers.

**Long description:**
Develop training material that bridges the CLI-browser gap identified in the white paper. The existing 14-slide PowerPoint deck covers git fundamentals; this goal extends it to a complete training module with a recorded video, hands-on exercises, and a desk instruction for browser-based review workflows. The target audience includes program managers, auditors, and engineers new to version control who need to participate in compliance reviews without installing command-line tools.

**Success criteria:**
1. 30-minute training video recorded and published (YouTube or internal equivalent)
2. Hands-on exercise module: participants complete a branch-review-merge cycle using only a web browser
3. Desk instruction document (DI-GIT-001) validated by at least 2 non-technical reviewers

**Milestones:**
- Q1 2026: Training script and slide deck finalized
- Q2 2026: Video recorded and hands-on exercise published
- Q3 2026: At least 10 individuals complete the training module

---

## Goal 5: Demonstrate Human-in-the-Loop AI Productivity Through Measurable Outcomes

**Short summary (WorkDay):**
Quantify and publish productivity metrics from AI-assisted development: commits/day, corrective intervention rate, compliance artifact throughput.

**Long description:**
The white paper claims AI-assisted development shifts engineers from authors to reviewers, enabling a single person to sustain the documentation overhead of a compliance team. This goal is to rigorously measure and publish these claims. Using the auto-metrics pipeline (generate_metrics.py) and process documentation (PROCESS.md, GitHub issues), produce a quantitative analysis of: daily throughput (commits, artifacts), human intervention rate (corrective vs. rubber-stamp), error detection rates (agent vs. human-caught issues), and time-to-compliance for new repos adopting the methodology.

**Success criteria:**
1. Quantitative analysis published with at least 6 months of longitudinal data (Dec 2025 – Jun 2026)
2. Human-in-the-loop intervention taxonomy: categorize all human directives by type (corrective, directive, approval) with rates
3. Comparison data: time-to-first-compliance-artifact for a new repo using the methodology vs. estimated manual effort

**Milestones:**
- Q1 2026: Auto-metrics pipeline generating longitudinal data; intervention taxonomy defined
- Q2 2026: 6-month dataset complete; draft analysis written
- Q3 2026: Analysis published as white paper supplement or standalone technical report

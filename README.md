# Appendix A: GPT-4 Responses to Static Analysis Warnings

This repository contains the full set of GPT-4 responses analyzed in our IEEE paper:

**Title**: _Contextualizing Static Analysis: A GPT-4 Study on Developer-Facing Explanations for SonarQube Warnings_  
**Authors**: [Your Name], et al.  
**Conference**: [Full Name of Conference], 2025  
**PDF Link**: [Coming Soon or arXiv Link]

---

## 📄 Appendix Contents

The full table of GPT-4 generated responses is provided to supplement the main paper, which only includes summarized insights and examples due to space constraints.

- `appendix_A_gpt4_responses.csv`  
  ➤ Contains:
  - Static rule ID (e.g., `java:S1845`)
  - Severity
  - Full GPT-4 explanation and remediation advice

---

## 🔍 Purpose

This appendix enables:

- Transparent evaluation of LLM output quality
- Reproducibility of analysis for future benchmarking
- Independent validation of prompt structure and categorization logic

---

## 🧠 Sample Format

| Rule      | Severity | GPT-4 Response |
|-----------|----------|----------------|
| java:S1192 | CRITICAL | _"This rule flags repeated string literals. Consider extracting them into constants for maintainability..."_ |

---

## 📌 Citation

If you find this helpful, please cite our paper:

```bibtex
@inproceedings{your2025gpt4static,
  title     = {Contextualizing Static Analysis: A GPT-4 Study on Developer-Facing Explanations for SonarQube Warnings},
  author    = {Your Name and Others},
  booktitle = {Proceedings of the IEEE [Conference Name]},
  year      = {2025}
}

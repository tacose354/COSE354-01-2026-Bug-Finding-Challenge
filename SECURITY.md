# Security Policy

## Bug Finding Challenge (BFC)

This repository is provided for educational purposes as part of the **Information Security course**.

It intentionally contains security vulnerabilities for students to identify, analyze, and reproduce in authorized environments.

This team assignment involves using AI and security analysis tools to discover vulnerabilities in software provided for the course, verify their behavior, and submit a private vulnerability report.

**Detect → Analyze → Validate → Exploit → Report**

## Reporting Vulnerabilities

Students must submit their findings through GitHub's **Security → Advisories → Report a vulnerability** feature.

**Submission Guidelines:**

- Submit **one report per team**.
- Use the title format: `[Team 03] Bug Finding Challenge Report`.
- Include the full names of all team members.
- For **each of the Web and System projects**, report **4 in-house code vulnerabilities** and **at least 2 OSS vulnerabilities**, for a total of **8 in-house code vulnerabilities and at least 4 OSS vulnerabilities (at least 12 findings overall)**.
- Include all findings in **one report per team**, clearly organized by project (**Web / System**) and numbered as **Finding 1, Finding 2**, and so on.
- For each finding, include the vulnerable code, root cause, reproduction steps, exploitation evidence, security impact, and recommended mitigation.
- GitHub vulnerability report deadline: November 21, 2026, at 23:59:59 KST

### Vulnerability Reporting Template
```
#Vulnerable Code and Root Cause

Code location
- File path:
- Function name and line number(s):

Root cause
- Explain the condition that should normally be guaranteed and why the implementation fails to enforce it.

#Attack Path and Reachability

- Input controlled by the attacker
- Reachability assessment: **(Reachable / Unreachable / Undetermined)**
  - Code Path from the attacker-controlled input to the vulnerable code

#Dependency Analysis — If Applicable

- Library name and estimated version
- Links to relevant CVEs or security reports

#Reproduction Steps — PoC / Exploit

Describe the inputs and execution steps required to reproduce the vulnerability, along with the observed results.

- Validation result and detailed explanation: Select one of the following:
  - Reproduced
  - Potentially reproducible, but reproduction incomplete
  - Not reproducible in the provided environment
  - Undetermined
- PoCs: Files, payloads, code, link, etc.
- Supporting evidence: Screenshots of the output

#Impact

Explain the security risks and consequences of the vulnerability.

Describe how the vulnerable code could adversely affect security and why the behavior constitutes a vulnerability.

#Suggested Fix

Write patch code that addresses the root cause and prevents the vulnerability from occurring.

For OSS vulnerabilities associated with known CVEs, you may reference the relevant upstream patch commits.

#Tools and AI Usage
- AI services and models used
- Key prompts and the AI’s main assessments
- Verification performed independently by the team, including any corrections or additional analysis
```

### Evidence Submission:

- Provide image or video evidence links in the designated field, or attach evidence in the Security Advisory comments after submitting the report.
- Label each piece of evidence with its corresponding Finding number.
- Ensure that all evidence is accessible to the TA.

AI assistance is permitted, but all reported findings must be independently verified.

Security testing must be conducted **only in authorized environments**.

Do not disclose findings through public GitHub Issues or Discussions.

## Questions or Submission Issues

If you have any questions or encounter issues with the challenge or submission process, please contact the TA.

**Email:** [ta.cose354@gmail.com](mailto:ta.cose354@gmail.com)

Goose GP Copilot

A modular, open-source AI prompt system designed for general practitioners. Created by Dr. Andrea Lattarulo, this tool is built to streamline documentation, referrals, patient communication, and workflow — without compromising clinical oversight or ethical standards.


---

Features

Clean modular prompts for SOAP notes, summaries, referrals, emails, de-identification, and case exports

Suicide risk stratification based on C-SSRS logic

Guideline validation against local protocols (e.g., BPAC, HealthPathways)

Fast integration into clinical practice, optimized for use with GPT-4

🚀 What’s New in Goose 2.8 — Full New-User Operational System (Multilingual Ready)

Release Date: 27/04/2025

Goose 2.8 is a major operational upgrade designed to support deployment to new users and multilingual environments.

✈️ Key Features:
Initial Onboarding Setup:

Collects user Name, Professional Role, Country of Practice, and Preferred Language at chat start.

Immediate Command List and Usage Example:

After setup, Goose displays available commands and a live example for orientation.

Multilingual Flexibility:

Basic structure tested successfully in English, Italian, and French.

System remains language-flexible by design (Goose 3.0 modularity planned).

Temp Ops Protocol Maintained:

All chats remain temporary unless manually archived/exported.

Improved System Readiness:

Now deployable without needing any manual pre-configuration.

Any clinician can start working within 1 minute.

🛠 Stability Report:
✅ No crashes during field testing.

✅ Correct behavior across three languages.

✅ Full command set (o/, s/, e/, c/, r/, x/, sr/, g/, t/, u/, p/) maintained and functional.

---

Usage

Paste the full prompt into a new temporary session (e.g., in ChatGPT with memory off). Then invoke any of the command structures below.

Example:

o/ 45M w/ HTN + fatigue. Borderline HbA1c.

Goose returns a structured note with bolded actions, formatted into Subjective / Objective / Assessment & Plan.


---

Live Command Examples

Want to see Goose in action? Check out the Usage Examples for real-world inputs and outputs for every command — from optimized notes to suicide risk stratification.


---

Why Goose Exists

Read the Origin Story – how a near-miss cancer diagnosis led to building a GP copilot.


---

Commands Overview

See Goose_2.6_OS_Clinical_AI_Copilot.md for the full prompt and usage guide.


---

FAQ

Have more questions? See the FAQ – Goose GP Copilot for answers about use, safety, scope, and contribution.


---

⚠️ Data Privacy and Responsible Use

Goose is designed to support documentation, summarization, and workflow — not to store or process patient-identifiable information.

To use Goose responsibly:

Always use temporary chats or incognito sessions to ensure no long-term memory or retention of patient data.

Never include names, NHIs, dates of birth, contact details, or identifiable features unless you are in a secure, offline environment.

Prefer using de-identified text, or use Goose’s c/ command to sanitize clinical notes before sharing or discussing.

Always review, edit, and confirm AI-generated outputs before entering them into a patient’s clinical record.


Goose does not store or access patient records. It functions as a temporary, session-based copilot, designed to be safe, fast, and compliant when used within standard medical privacy guidelines.

Responsible Use of Summarization (s/)

The s/ command is designed to help clinicians triage and navigate clinical documents more efficiently. It is not intended as a replacement for reading the full content of critical documents. In overloaded inbox environments, clinicians frequently skim — Goose provides a structured, faster way to surface key insights and prioritize reading. In complex, unfamiliar, or high-risk cases, the full document should always be reviewed.

This tool supports clinical judgment — it does not substitute for it.


---

Ethics and Oversight

See ETHICS_AND_USAGE.md for the full ethical use statement and liability disclaimer.


---

License

MIT License — see LICENSE for terms.


---

Use it. Modify it. Build something better.

Goose GP Copilot

A modular, open-source AI prompt system designed for general practitioners. Created by Dr. Andrea Lattarulo, this tool is built to streamline documentation, referrals, patient communication, and workflow — without compromising clinical oversight or ethical standards.

Goose is not an AI model — it’s a structured system of prompts designed to run on top of GPT-4 (or other LLMs), built specifically for real-world general practice tasks.

---

Features

Clean modular prompts for SOAP notes, summaries, referrals, emails, de-identification, and case exports

Suicide risk stratification based on C-SSRS logic (sr/ command)

Guideline validation against local protocols (e.g., BPAC, HealthPathways) via g/

Fast integration into clinical practice, optimized for use with GPT-4

Version 2.6 OS is open-source and community-modifiable under MIT license



---

Commands Overview

See Goose_2.6_OS_Clinical_AI_Copilot.md for full prompt structure and usage guide.


---

⚠️ Data Privacy and Responsible Use

Goose is designed to support documentation, summarization, and workflow — not to store or process patient-identifiable information.

To use Goose responsibly:

Always use temporary chats or incognito sessions to ensure no long-term memory or retention of patient data.

Never include names, NHIs, dates of birth, contact details, or identifiable features unless you are in a secure, offline environment.

Prefer using de-identified text, or use Goose’s c/ command to sanitize clinical notes before sharing or discussing.

Always review, edit, and confirm AI-generated outputs before entering them into a patient’s clinical record.


Goose does not store or access patient records. It functions as a temporary, session-based copilot, designed to be safe, fast, and compliant when used within standard medical privacy guidelines.


---

Responsible Use of Summarization (s/)

The s/ command is designed to help clinicians triage and navigate clinical documents more efficiently.

It is not intended as a replacement for reading the full content of critical documents.

In overloaded inbox environments, clinicians frequently skim — Goose provides a structured, faster way to surface key insights and prioritize reading. In complex, unfamiliar, or high-risk cases, the full document should always be reviewed.

This tool supports clinical judgment — it does not substitute for it.


---

Ethics and Oversight

See ETHICS_AND_USAGE.md for:

Clear boundaries of intended use

Full liability disclaimer

Affirmation that the clinician retains final responsibility for all clinical outputs

Note that Goose is currently under real-world feasibility evaluation by the author and peer clinicians



---

Accessibility and Equity

Goose is designed to be usable by tech-savvy GPs. For those new to AI, a simplified variant called LolAI is in internal development, built with more structured, natural-language instructions and minimal friction.

Future updates will ensure greater inclusivity and ease of adoption for all clinician levels.


---

FAQ

Have more questions?
See the FAQ – Goose GP Copilot for answers about use, safety, scope, and contribution


---

License

MIT License — see LICENSE for full terms.

Free to use

Free to modify

Attribution required

License must remain attached to all copies or derivatives



---

Use it. Modify it. Build something better. Because no GP should fly solo — and burnout isn’t a badge of honor.

# Additional Automation Work

## PSV17 OCR and human-review workflow

**Evidence:** Working Python batch application, GUI, build workflow, and packaged executables verified.

The tool uses OCR and computer vision to extract identifiers, associate related document/image files, validate uncertain results, route low-confidence cases to manual review, record exceptions, and avoid destructive overwrites. A sanitised code-only version is maintained separately in [psv17-builder](https://github.com/OzzyPyrex/psv17-builder).

## AI-assisted job-search workflow

**Evidence:** Working tracker files and scheduled Codex automations verified.

The workflow structures job research, freshness, fit, deadline, contact, and status information and updates a spreadsheet-based tracker. It is an orchestrated research workflowâ€”not a Selenium scraper or automated application-submission bot. The public-facing design is represented in [AI-Assisted-Job-Search-Tracker](https://github.com/OzzyPyrex/AI-Assisted-Job-Search-Tracker).

## Print-ready research-poster production and QA

**Evidence:** Working reconstruction, upscaling, vector-generation, font/logo handling, render comparison, and preflight scripts verified, with final A0 outputs and QA reports.

The original materials include identifiable authors, institutional branding, research results, licensed assets, and third-party tools/models. A portfolio repository would need a clean-room rebuild using fictional research content, generic branding, a minimal script set, documented dependencies, and explicit third-party licences.

## ATS document generation and visual QA

**Evidence:** Working Python document generators, render checks, and finished DOCX outputs verified.

The current scripts contain personal contact details, employment history, job-specific wording, local paths, and application data. A reusable version should accept a structured fictional profile, a job-description input, and a theme configuration; generate an editable document; then render and inspect it for layout defects.

## What was not found

No separate Selenium scraper, UiPath project, Power Automate export, standalone RPA bot, or independently verifiable GenAI-assistant source was found. These should not be added as separate portfolio claims unless their source artifacts are recovered.


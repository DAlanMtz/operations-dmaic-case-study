# Publication Notes - Anonymization Log

This project is based on a real Lean Six Sigma / DMAIC process-improvement engagement involving a real small business. **Permission to publish the real business name and identifying details was not confirmed**, so this case study has been anonymized by default rather than published with real identifiers.

## What was removed or generalized

| Original | Published as |
|---|---|
| Real company name | "the Company" / "a small regional landscaping and tree-service business" |
| Real owner's name | "the owner" |
| Real field workers' names (2 individuals) | Not referenced by name anywhere in the published case study |
| Real city/state | "a mid-sized U.S. metro area" |
| Exact calendar dates (specific months/year) | Relative project timeline ("~4-month engagement," "Weeks 1-17") |
| Institutional/course identifiers | Removed entirely |
| Team member names | Removed entirely - team member identity is not part of this public case study |

## What was preserved

All quantified operational results - percentages, hours, dollar estimates, defect rates, sigma levels - were preserved from the original engagement. These numbers are the analytical content of this case study and do not, on their own, identify the business, its owner, or its employees.

## What was NOT copied into this repository

- The original Word document report, PowerPoint slide decks, and PDF exports from the source engagement - **not copied**, since they contain the real company name, real names, and (in the slide decks specifically) **real photographs of the business's tools, storage area, and vehicles**, which could not be safely redacted without recreating the entire document from scratch. Recreating the analytical content as a new, anonymized write-up (this README + notebook) was judged safer and more honest than attempting to redact a document that wasn't designed for redaction.
- Any file containing real photographs.
- Any file containing the project's original team roster, sponsor contact information, or review/grading materials.

## What this repository contains instead

- A newly written, anonymized README structured around the DMAIC framework, describing the same engagement, methodology, and results.
- A newly built Python notebook (`operations_dmaic_case_study.ipynb`) that loads two small, manually compiled, sanitized CSV files (`data/kpi_summary.csv`, `data/annual_cost_impact.csv`) - aggregated summary numbers only, no raw business records - and generates all 5 visuals from that sanitized data.
- All charts (timeline, fishbone diagram, Pareto chart, before/after comparison, control plan summary) were recreated from scratch in matplotlib, not copied from or based on any image from the original engagement.

## Honesty statement

This is a real project, not a fictional scenario invented for portfolio purposes. It is presented here as an anonymized case study, with identifying details removed or generalized as documented above, and all sensitive material excluded rather than partially redacted. If asked in an interview, it's accurate to describe this as "a real Lean Six Sigma engagement for a small field-service business, presented here in anonymized form since I didn't have confirmed permission to publish the company's name."

## Before publishing - recommended next step

If you're able to reach the original business owner and get explicit permission to publish under the real name, that would let you strengthen this into a named case study (often more credible to employers than an anonymized one). Absent that permission, keep this anonymized version.

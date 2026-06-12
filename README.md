# Video Event Data Quality POC

## Overview

This project demonstrates a proof of concept for identifying data quality issues in video playback event data.

The solution was developed using Python and pandas in Google Colab and applies a series of validation checks derived from the provided data dictionary and business requirements.

---

## Data Quality Checks Implemented

- Duplicate event identifiers
- Invalid event types
- Invalid platform values
- Missing content identifiers
- Missing device identifiers
- Invalid firmware version formats
- Invalid timestamps
- Timestamps outside the expected time window
- Negative durations
- Event-specific duration rule violations
- Invalid error codes
- Error code inconsistencies

---

## Outputs

### Row-Level Findings

Detailed report showing individual records that violate validation rules.

### Summary Report

Aggregated view of issue counts grouped by validation rule and severity.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Google Colab

---

## AI-Assisted Development

Large Language Models (LLMs) were used to clarify requirements, improve code readability, identify potential edge cases, and refine reporting outputs.

All implementation decisions, validation logic, and final outputs were reviewed and verified manually.

---

## Repository Structure

```
README.md
requirements.txt
video_events_data_quality.ipynb
data_quality_summary_report.csv
row_level_data_quality_findings.csv
```

---

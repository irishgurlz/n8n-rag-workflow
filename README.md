# n8n AI Workflow – Data Processing & JSON Transformation

## Overview

This project demonstrates an automated workflow built using n8n to process unstructured data and convert it into a structured JSON format.

The workflow highlights how raw input can be transformed into organized, machine-readable data for further use.

---

## Workflow Description

The workflow consists of the following steps:

1. Trigger
   Initiates the workflow (manual or webhook)

2. Input Data
   Raw data or text is provided as input

3. Processing
   The data is analyzed and transformed into a structured format

4. Output
   The final result is generated as a JSON object

---

## Project Structure

```
.
├── workflow.json
├── sample-output.json
└── README.md
```

---

## Sample Output

The workflow produces structured JSON output based on the processed input data.
See `sample-output.json` for an example.

---

## Requirements

* n8n (local or cloud)
* Required credentials if external services are used

Note: Credentials are not included for security reasons.

---

## How to Use

1. Import `workflow.json` into n8n
2. Configure necessary credentials
3. Run the workflow
4. Check the output in the final node

---

## Author

Created as part of an AI workflow test.

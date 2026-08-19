# HI-X Research Ticket Desk

This repository is only for technical and research support tickets. It is not tied to a product codebase.

## Workflow

1. Client chooses one of three issue forms: `Qiskit Function Problem`, `Technical Requirements`, or `Functionality Request`.
2. Triage labels the issue: `needs-triage`, `needs-repro`, `tier3`, `answered`, or `blocked`.
3. A researcher replies in the issue thread or asks for more files/context.
4. Close the issue when the answer is delivered.

## Ticket Types

- **Qiskit Function Problem**: input, output or error, Qiskit function/module, and the concrete question.
- **Technical Requirements**: algorithm questions, benchmark requests, method comparisons, resource estimates, and constraints.
- **Functionality Request**: requested functionality, use case, comparable examples, and expected behavior/API.

## Submission Rules

- Upload input files, code, logs, and screenshots directly in the issue form.
- Do not upload credentials, API keys, private tokens, or production secrets.
- If the input is confidential, mark it in the form so access can be handled deliberately.

## GitHub Pages

Use **Settings -> Pages -> Deploy from a branch -> main -> root** to publish `index.html`.

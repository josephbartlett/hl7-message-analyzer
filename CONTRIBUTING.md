# Contributing to HL7 Message Analyzer

Thanks for your interest in contributing! This document outlines how to work with the project and how to get changes merged.

## Project structure

```
root
├── hl7-message-analyzer.html   # Main HTML/JS/CSS file for the tool
├── README.md                   # Overview and usage instructions
└── LICENSE                     # Project license
```

## Running the HTML locally

No build step is required. You can open the HTML file directly in your browser:

1. Clone the repository and change into the directory.
2. Double-click `hl7-message-analyzer.html` or open it via `file://` in any modern browser.

Alternatively, if a local web server is preferred:

```bash
python -m http.server
# then visit http://localhost:8000/hl7-message-analyzer.html
```

## Localization

Localization support is under research, and translation contributions are not yet accepted.

## Reporting issues

- Search existing issues before filing a new one.
- Provide clear steps to reproduce, expected vs. actual behavior, and environment details.
- Include logs or screenshots when helpful.

## Commit message style

- Use the imperative mood (e.g., "Add new parser" not "Added" or "Adds").
- Keep the subject line short (≤50 characters) and follow with a blank line.
- Include a body explaining the motivation when the change is not obvious.

## Pull request expectations

- One logical change per pull request.
- Ensure the HTML loads and functions before submitting.
- Update or add documentation/tests when relevant.
- Expect maintainers to review for clarity, style, and functionality.

Thank you for helping to improve HL7 Message Analyzer!

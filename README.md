# HL7 Message Analyzer

A sleek, lightweight tool to parse and analyze raw HL7 messages. Paste your HL7 content, hit "Parse HL7," and instantly transform complex segments into a readable, well-structured output.

See the [project roadmap](ROADMAP.md) for upcoming milestones.

## Features

- **One-Click Parsing:** Paste an HL7 message and parse it with a single click.
- **Segment Highlighting:** HL7 segments are distinctly colored, making it easy to identify MSH, PID, OBR, OBX, ORC, PV1, and more.
- **Field & Component Breakdown:** Hover over fields, components, and subcomponents to highlight their boundaries. Subcomponents are displayed in pink for clarity.
- **Non-Printable Characters:** Easily spot and understand non-printable characters, displayed with their hex codes and highlighted in yellow for visual distinction.
- **ASCII View:** Toggle an ASCII-view panel that shows raw character codes for deeper inspection. The ASCII view panel also allows users to click characters in the parsed output to highlight them in the ASCII view.
- **Segment Navigation:** Quickly find and jump to specific HL7 segments.
- **Copy to Clipboard:** Easily copy the formatted output for use elsewhere.

## How to Use

1. Open the tool in your browser.
2. Paste your raw HL7 message into the provided text area.
3. Click the "Parse HL7" button.
4. Review the parsed segments. Hovering over fields, components, and subcomponents highlights them.
5. Use navigation features:
   - **Find Segment:** Enter a segment type (e.g., MSH, PID) to jump directly to those segments.
   - **ASCII View:** Click "Show ASCII View" to see the raw ASCII codes for each character. Clicking characters in the parsed output highlights them in ASCII view.
6. Click "Copy" to copy the parsed output.

## Running Locally

Simply open `hl7-message-analyzer.html` in your browser. No server required.

## Contributions

Contributions are welcome! Feel free to open issues or PRs with suggestions, bug fixes, or improvements.
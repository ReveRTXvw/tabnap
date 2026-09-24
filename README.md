# tabnap

Chrome extension that tracks reading time per tab

Small but I use it weekly.

## Getting started

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Examples

```bash
# click the toolbar icon to see today's reading time
```

## Highlights

- Popup shows today's total focus time
- No remote calls, everything stays local
- Per-tab time persisted to chrome.storage
- Manifest V3, service worker based

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── workflows/
│   │   └── ci.yml
│   └── pull_request_template.md
├── docs/
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

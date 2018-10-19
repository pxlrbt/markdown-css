# Markdown CSS
CSS style for nicely formatted markdown exports (pdf/html)

## Tested with
- VS Code - Markdown Preview (builtin)
- VS Code - Markdown PDF (Extension)

## Setup

### VS Code Markdown Preview

Add this line to your `settings.json`.  Adjust path to your CSS file. On Windows global paths (e.g. `C:\\Users\\...`) seem not to work. You can upload the CSS file and include an URL as file path.

```json
"markdown.styles": ["PATH_TO_YOUR_FILE"],
```

### VS Code Markdown PDF

Add this line to your `settings.json`. Adjust path to your CSS file.

```json
"markdown-pdf.styles": ["PATH_TO_YOUR_FILE"]
```

## Example
![Example Image](screenshot.png)

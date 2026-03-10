# Workflow: capture_screenshot

Goal: capture a full-page screenshot of the current webpage.

Steps:

1. Use the Playwright MCP tool `screenshot`.
2. Set `fullPage` to true.
3. Save the screenshot to:

outputs/screenshots/page.png

Tool call specification:

tool: screenshot
arguments:
  path: outputs/screenshots/page.png
  fullPage: true
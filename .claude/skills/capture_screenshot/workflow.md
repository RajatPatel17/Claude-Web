# Workflow: capture_screenshot

Goal: capture a full-page screenshot of the webpage.

Steps:

1. Use the Playwright MCP tool `screenshot`.

2. Capture the entire page.

Tool call specification:

tool: screenshot
arguments:
  path: outputs/page_full.png
  fullPage: true
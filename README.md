<p align="center">
  <picture>
    <source media="(max-width: 640px)" srcset="assets/profile/hero-mobile.svg">
    <img src="assets/profile/hero.svg" width="100%" alt="Je Sai Kailash Pulipati — AI systems. Data platforms. Built end to end. Python, TypeScript, and SQL.">
  </picture>
</p>

<p align="center">
  <a href="https://je-sai-kailash-pulipati.framer.website"><img src="assets/profile/link-portfolio.svg" width="104" alt="Visit my portfolio"></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/je-pulipati/"><img src="assets/profile/link-linkedin.svg" width="104" alt="Connect on LinkedIn"></a>
  &nbsp;
  <a href="mailto:pulipati.j@northeastern.edu"><img src="assets/profile/link-email.svg" width="104" alt="Email Je"></a>
</p>

<p align="center">
  I connect <strong>AI, data, and application development</strong> to solve practical problems.<br>
  Previously: <strong>Data Engineer · Boviet Solar</strong> &nbsp; / &nbsp; <strong>Data Analyst · Align Associates</strong>
</p>

## Selected builds

Agent orchestration, cloud data pipelines, media processing, and a grocery assistant built around a real everyday workflow.

<p align="center">
  <a href="https://github.com/pjsk02/TripSync-AI"><img src="assets/profile/project-tripsync.svg" width="400" alt="TripSync AI — multi-agent travel planning with budget constraints and decision tracing. Built with TypeScript, React, and Claude. Explore the repository."></a>
  <a href="https://github.com/pjsk02/Automated-Multi-Stage-Data-Pipeline-Platform"><img src="assets/profile/project-data.svg" width="400" alt="SEC Data Platform — Airflow orchestration, S3 staging, and Snowflake warehousing, comparing three storage approaches. Explore the repository."></a>
</p>

<p align="center">
  <a href="https://github.com/pjsk02/Video-Transcription-and-Rendering-Pipeline"><img src="assets/profile/project-video.svg" width="400" alt="Video to Clips — local transcription, AI clip selection, captions, and three output formats using Python, whisper.cpp, and ffmpeg. Explore the repository."></a>
  <a href="https://github.com/pjsk02/MomCart"><img src="assets/profile/project-momcart.svg" width="400" alt="MomCart — Telegram voice notes and messages become a persistent grocery cart and shopkeeper packing list using Python, Ollama, and Notion MCP. Explore the repository."></a>
</p>

<details>
  <summary><strong>Under the hood — architecture, tradeoffs, and code</strong></summary>

| Project | What to look at |
| :--- | :--- |
| [TripSync AI](https://github.com/pjsk02/TripSync-AI#multi-agent-architecture) | Sequential agent orchestration, deterministic budget and schedule checks, and traceable decisions. |
| [SEC Data Platform](https://github.com/pjsk02/Automated-Multi-Stage-Data-Pipeline-Platform#architecture) | Raw, JSON, and denormalized storage models; S3 staging; Snowflake loading; API and analytics access. |
| [Video → Clips](https://github.com/pjsk02/Video-Transcription-and-Rendering-Pipeline#pipeline) | A shared web/CLI pipeline, file-backed jobs, validated selection, hardware-encoder fallback, and [tests](https://github.com/pjsk02/Video-Transcription-and-Rendering-Pipeline/tree/main/tests). Transcription is local; clip selection sends transcript text to Claude. |
| [MomCart](https://github.com/pjsk02/MomCart#how-it-works) | Structured item extraction, catalog matching, persistent carts, and packing updates through Notion MCP. |

</details>

## Inside the video pipeline

A real interface for reviewing how a source video will be cropped before rendering captioned clips.

<p align="center">
  <a href="https://github.com/pjsk02/Video-Transcription-and-Rendering-Pipeline#web-workflow"><img src="assets/profile/video-crop-ui.png" width="700" alt="Actual video pipeline crop editor: aspect-ratio tabs, highlighted source region, portrait output preview, and zoom and position controls. Cropped from the project's documentation screenshot."></a><br>
  <sub>Crop editor · <a href="https://github.com/pjsk02/Video-Transcription-and-Rendering-Pipeline/blob/main/docs/quickcrop-modal.png">Screenshot from project documentation</a></sub>
</p>

The web UI and CLI share the same pipeline. Clip selections are validated before rendering, and failed GPU encodes fall back to CPU processing.

[Explore the implementation](https://github.com/pjsk02/Video-Transcription-and-Rendering-Pipeline#tech-stack-and-architecture) · [Tests](https://github.com/pjsk02/Video-Transcription-and-Rendering-Pipeline/tree/main/tests) · [Benchmark procedure](https://github.com/pjsk02/Video-Transcription-and-Rendering-Pipeline/blob/main/BENCHMARKS.md)

## Core stack

<picture>
  <source media="(max-width: 640px)" srcset="assets/profile/toolkit-mobile.svg">
  <img src="assets/profile/toolkit.svg" width="100%" alt="Core stack. Build: Python, TypeScript, React, FastAPI. AI and agents: Claude, Ollama, LangGraph, MCP. Data: SQL, Airflow, Snowflake, AWS S3. Ship and test: Azure, Docker, Git, pytest.">
</picture>

<details>
  <summary><strong>More tools I work with</strong></summary>

<picture>
  <source media="(max-width: 640px)" srcset="assets/profile/toolkit-more-mobile.svg">
  <img src="assets/profile/toolkit-more.svg" width="100%" alt="Additional tools: JavaScript, LangChain, Chroma, Databricks, PySpark, pandas, NumPy, scikit-learn, Matplotlib, Tableau, Power BI, GitHub, Playwright, Linux, FFmpeg, whisper.cpp, Telegram, Notion, Bash, VS Code.">
</picture>

</details>

<details>
  <summary><strong>A little more about my background</strong></summary>

My background includes data engineering at **Boviet Solar Technologies** and data analysis at **Align Associates**. My projects combine that data foundation with agent orchestration, full-stack development, and automation.

I care about the parts around the model call: the data flow, state, validation, interface, and what happens when something fails. I use tests, tracing, and architecture documentation to make those decisions easier to inspect.

[More experience and projects on my portfolio](https://je-sai-kailash-pulipati.framer.website).

</details>

[More projects and experience →](https://je-sai-kailash-pulipati.framer.website)

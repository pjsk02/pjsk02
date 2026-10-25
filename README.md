<div align="center">

<h1>Je Sai Kailash Pulipati</h1>

<p><strong>AI Systems &amp; Data Engineering</strong></p>

<p>AI applications. Automated data pipelines. Practical software.</p>

<p>
  <a href="https://je-sai-kailash-pulipati.framer.website">Portfolio</a>
  &nbsp;&middot;&nbsp;
  <a href="https://www.linkedin.com/in/je-pulipati/">LinkedIn</a>
  &nbsp;&middot;&nbsp;
  <a href="mailto:pulipati.j@northeastern.edu">Email</a>
</p>

</div>

---

I build AI-powered applications, data pipelines, and automation tools that turn complex workflows into usable software. I work across **Python, TypeScript, and SQL**, connecting models, data, APIs, and interfaces.

My background includes **data engineering at Boviet Solar Technologies** and **data analysis at Align Associates**. My projects explore agent orchestration, data infrastructure, and practical applications of AI.

## Selected work

### [TripSync AI](https://github.com/pjsk02/TripSync-AI)
**Multi-agent planning · Full-stack application development**

A group travel planner that brings individual preferences, shared budgets, and scheduling constraints into one itinerary.

The engineering focus: sequential agent orchestration, deterministic budget and schedule checks, and tracing that makes agent decisions inspectable.

`TypeScript` `React` `tRPC` `Claude` `W&B Weave`

[Explore the agent architecture →](https://github.com/pjsk02/TripSync-AI#multi-agent-architecture)

### [Automated Multi-Stage Data Pipeline](https://github.com/pjsk02/Automated-Multi-Stage-Data-Pipeline-Platform)
**Data orchestration · Cloud warehousing · Analytics**

A platform for ingesting SEC financial filings, staging data in S3, loading Snowflake, and serving the results through an API and analytics dashboard.

The engineering focus: comparing raw, JSON, and denormalized storage approaches on the same source data, with orchestration separated from the data-access layer.

`Python` `Airflow` `AWS S3` `Snowflake` `FastAPI` `Streamlit`

[Explore the pipeline design →](https://github.com/pjsk02/Automated-Multi-Stage-Data-Pipeline-Platform#architecture)

### [Video Transcription & Rendering Pipeline](https://github.com/pjsk02/Video-Transcription-and-Rendering-Pipeline)
**Applied AI · Media processing · Developer tooling**

A local application that turns long videos into captioned clips in three aspect ratios, with both a web interface and a CLI.

The engineering focus: a shared processing pipeline, file-backed job state, validated clip selection, and hardware-encoder fallback. Transcription runs locally; clip selection sends transcript text to Claude.

`Python` `FastAPI` `whisper.cpp` `ffmpeg` `pytest` `Playwright`

[Explore the pipeline →](https://github.com/pjsk02/Video-Transcription-and-Rendering-Pipeline#pipeline) · [Browse the tests →](https://github.com/pjsk02/Video-Transcription-and-Rendering-Pipeline/tree/main/tests)

### [MomCart](https://github.com/pjsk02/MomCart)
**Workflow automation · Conversational interfaces**

A Telegram grocery assistant that turns messages and voice notes into a persistent cart and a shopkeeper's packing checklist.

The engineering focus: structured item extraction, catalog matching, persistent order state, and status updates through Notion MCP.

`Python` `Ollama` `Chroma` `Telegram` `MCP`

[Explore the workflow →](https://github.com/pjsk02/MomCart#how-it-works)

## How I approach engineering

- **Separate AI from business rules.** Use models for suggestions and extraction, with explicit validation and constraints around their outputs.
- **Think beyond the model call.** Design the data flow, state, API, interface, and final output as parts of the same system.
- **Make behavior inspectable.** Use tests, tracing, and architecture documentation to explain decisions and investigate failures.

## Working stack

| Area | Tools |
| :--- | :--- |
| AI & application development | Python, TypeScript, React, FastAPI, LLM APIs, MCP |
| Data & analytics | SQL, Airflow, Snowflake, AWS S3, Power BI |
| Development & verification | Docker, Git, pytest, Playwright |

---

Interested in collaborating on an AI application or data system? [Get in touch](mailto:pulipati.j@northeastern.edu).

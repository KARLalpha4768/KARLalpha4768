<h1 align="center">Karl David</h1>

<p align="center">
  <strong>Principal Engineer — Autonomous Systems & Data Platform Architecture</strong><br>
  Cornell BS · USC MPW · 15+ Years Building Production Infrastructure
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/karldavid-data/">LinkedIn</a> •
  <a href="https://sentinelforge.vercel.app">SentinelForge (Live)</a> •
  <a href="mailto:alpha4768@gmail.com">alpha4768@gmail.com</a>
</p>

---

I design and build end-to-end autonomous systems — from the data pipeline to the agent logic to the operational interface. My work focuses on production infrastructure where correctness and availability are non-negotiable.

### Current Work

**[SentinelForge](https://github.com/KARLalpha4768/SentinelForge)** — Autonomous Space Domain Awareness Platform

A 20-agent system that processes real-time orbital telemetry from CelesTrak/NORAD, performs conjunction screening, debris risk scoring, and threat classification, and surfaces intelligence through a 3D operational command center.

- Multi-agent coordination with independent decision loops per agent
- Real-time data pipelines with schema validation, quality gates, and confidence calibration
- 3D fleet visualization rendering satellite positions, conjunction geometries, and threat vectors
- Full CI/CD (GitHub Actions → Vercel), production-deployed at [sentinelforge.vercel.app](https://sentinelforge.vercel.app)

**Gemini Vision Agentic System** — LLM + Computer Vision Threat Grading

Chain-of-Thought prompt architecture integrating YOLO object detection with Google Gemini for autonomous threat classification. Structured output parsing with mandatory sensor-LLM reconciliation — the model cannot issue a threat grade without referencing detection data, eliminating hallucinated classifications.

### Technical Stack

| Domain | Tools |
|---|---|
| **Languages** | Python (expert), TypeScript, SQL |
| **Data** | PySpark, Apache Spark, Airflow, event-driven pipelines |
| **Cloud** | AWS (S3, Lambda, EMR), GCP, Vercel |
| **AI/ML** | Google Gemini, YOLO/OpenCV, prompt engineering, RAG |
| **Infrastructure** | Terraform, GitHub Actions CI/CD, Docker |
| **Frontend** | React, Next.js, Three.js, responsive design |

### Background

15+ years of production engineering across data platforms, distributed systems, and autonomous intelligence architectures. Previous work includes enterprise data operations at J.P. Morgan Chase, analytics infrastructure at UNISYS, and platform engineering at Xerox.

**Education:** Master of Professional Writing, USC · BS Communication, Cornell University

# Uptime-Latency-Monitoring-Motia

A simple uptime and latency monitoring tool built with [Motia](https://motia.dev/).

## What it does

- Monitors URLs/endpoints for availability (uptime)
- Tracks response times (latency)
- Sends alerts when services go down or get slow
- Built on Motia's reliable workflow engine

## Quick Start

```bash
# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your config

# Run in development
npm run dev

# Run in production
npm start
```

## Configuration

Add your endpoints to monitor in the `monitors/` directory. Each monitor checks:
- If the endpoint is reachable
- Response time (latency)
- Expected HTTP status code

## Tech Stack

- **Motia** — Workflow automation engine
- **Node.js** — Runtime
- **TypeScript** — Language

## Built for

This project was created for a hackathon to demonstrate Motia's capabilities for building reliable monitoring workflows.

---

**Author:** [Ananya](https://github.com/Ananya21-G)  

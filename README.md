# AlchemyX – Multi-System Synthesis AI Agent

An autonomous AI agent built on IBM watsonx Orchestrate for enterprise data synthesis.

## Overview

AlchemyX is a next-generation autonomous AI agent built on IBM watsonx Orchestrate (ABM Watson X-Architecture), engineered to tackle the most pressing challenge in enterprise data management: information fragmentation across multiple systems. In modern organizations, critical business data is scattered across CRM, ERP, Messaging, Databases, and Email, creating silos that slow decision-making, introduce errors, and obscure insights. AlchemyX eliminates these barriers by intelligently retrieving, reconciling, and synthesizing data into a single, coherent, and fully verifiable narrative—delivering actionable insights in seconds, not hours.

The agent's unique differentiator lies in its commitment to trustworthy AI outputs. Every response comes with instant, 100% source attribution (e.g., [Source: CRM]), ensuring transparency and preventing hallucinations. Beyond simply aggregating data, AlchemyX is proactively vigilant: it detects data inconsistencies, quality risks, and conflicts during synthesis and automatically generates high-priority tasks in a Central Task Manager for human intervention. This makes it not just a tool for insight, but a collaborative partner in enterprise intelligence.

The frontend is developed in Google AI Studio, delivering a seamless, interactive user experience. The system is built using TypeScript, HTML, CSS, and Tailwind, combining robust architecture with elegant, responsive design.

## Key Features

- Synthesizes fragmented data into one conclusive, actionable report
- Provides source-attributed answers to eliminate misinformation
- Detects data conflicts and automatically flags tasks for review
- Converts wasted search and reconciliation time into high-confidence business insights
- Designed for enterprise-scale environments, bridging data silos across multiple systems

## Tech Stack

- **Backend / Agent:** IBM watsonx Orchestrate (ABM Watson X-Architecture)
- **Frontend:** Google AI Studio
- **Languages:** TypeScript, HTML, Tailwind CSS

## License

MIT License

View your app in AI Studio: https://ai.studio/apps/drive/1pgjNVF8LZRxnptwEhBhEQkVpy-Zc0eGA

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

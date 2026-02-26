# Autonomous GTM Engine ⚡️

A high-velocity technical sales infrastructure designed for autonomous market research, tiered lead prioritization, and hyper-personalized outreach drafting. 

This engine was built to eliminate the manual "grunt work" of prospecting, allowing a founding or early-stage sales rep to focus exclusively on high-leverage activities like recording personalized Looms and closing deals.

## 🛠 The Stack
- **Runtime:** Node.js / TypeScript
- **Intelligence:** Anthropic Claude 3.5 Sonnet & Haiku
- **Data Layer:** JSON-based local cache & CSV integration
- **UI:** Dynamic HTML/CSS "Strike Dashboard" for mission control

## 🚀 Core Systems

### 1. Surgical Research & Caching
The engine performs parallelized research on batches of companies across both Tier 1 (High Stakes) and Tier 2 (High Volume) lists. It utilizes a `research_cache.json` system to store technical signals, preventing redundant API calls and keeping token costs optimized.

### 2. The "Whale Protocol"
To protect domain reputation and ensure strategic alignment, the engine includes a logic gate for high-valuation targets. Companies with >$150M in funding or enterprise-scale employee counts are automatically flagged as "Whales." This triggers a LinkedIn-only outreach strategy, skipping the automated email drafting to ensure a 100% manual, high-touch approach for high-value targets.

### 3. Tiered Priority Mapping
The engine treats different cohorts with different levels of intensity:
- **Tier 1 (Gold)**: Triggers deep-dive research and prepares multi-touch sequences including Loom scripts, technical insights, and follow-up cadences.
- **Tier 2 (Silver)**: Optimized for broad market "swarming" with hyper-personalized Day 1 intro drafts.

### 4. GTM Strike Dashboard
A custom-built front-end mission control that provides a real-time view of the pipeline:
- **Dual-Dimension Filtering**: Ability to filter by Status (Sent, Replied, Bounced) and Tier simultaneously.
- **Visual Priority**: Tier 1 leads are highlighted with high-contrast UI accents to focus daily energy.
- **One-Click Execution**: Integrated clipboard hooks to instantly move AI-generated DMs into LinkedIn.

---
*Note: This repository serves as a technical showcase. Core logic, proprietary prompt engineering, and lead databases are kept private to protect intellectual property.*

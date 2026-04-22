<p align="center">
  <h1 align="center">MAMA Water Shield</h1>
  <h3 align="center"><em>Enter your ZIP code. See what's really in your tap water.</em></h3>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-GPL--3.0-blue.svg" alt="License"></a>
  <img src="https://img.shields.io/badge/cost-Free_Forever-green" alt="Free">
  <img src="https://img.shields.io/badge/status-Active-brightgreen" alt="Active">
  <a href="https://mama.oliwoods.ai"><img src="https://img.shields.io/badge/Built_with-MAMA-8b5cf6" alt="Built with MAMA"></a>
  <a href="https://cofounder.software"><img src="https://img.shields.io/badge/Powered_by-CoFounder-06b6d4" alt="Powered by CoFounder"></a>
  <a href="https://mama.oliwoods.ai/foundation"><img src="https://img.shields.io/badge/OliWoods-Foundation-10b981" alt="OliWoods Foundation"></a>
</p>

<p align="center">
  <a href="#the-problem">Problem</a> &bull;
  <a href="#the-solution">Solution</a> &bull;
  <a href="#agents">Agents</a> &bull;
  <a href="#quick-start">Quick Start</a> &bull;
  <a href="#contributing">Contribute</a>
</p>

---

> **85% of US tap water systems** contain contaminants exceeding EWG health guidelines — even if they 'pass' federal standards. Lead, PFAS, chromium-6, pesticides, disinfection byproducts. Most people have no idea what's in their water because federal standards haven't been updated in decades.

## The Problem

A free AI tool that tells you exactly what's in your water and which filter to buy.

Enter your ZIP code → get an instant contamination report → see your grade (A-F) → get a filter recommendation matched to YOUR specific contaminants.

**The affiliate revenue model funds the tool:** when we recommend a filter, affiliate commissions cover operating costs. Users never pay. The tool is free forever.

## Agents

| Agent | Role |
|-------|------|
| **WaterScanner** | Fetch EPA/EWG data by ZIP, grade A-F, list contaminants |
| **FilterRecommender** | Match contaminants to filter type (RO, carbon, pitcher) |
| **ViralContent** | 'Water Wednesday' — worst ZIP codes of the week |

**Slack command:** `/water [ZIP code]`

## Data Sources

- [EPA SDWIS](https://www.epa.gov/ground-water-and-drinking-water/safe-drinking-water-information-system-sdwis-federal-reporting) — Safe Drinking Water Information System
- [EWG Tap Water Database](https://www.ewg.org/tapwater/) — 50,000 water systems
- [EPA AirNow API](https://aqs.epa.gov/aqsweb/documents/data_api.html) — Real-time quality data

## Quick Start

```bash
git clone https://github.com/OliWoods-Org/mama-water-shield.git
cd mama-water-shield
# Full setup instructions coming soon
# Or use via MAMA Slack: see agent commands below
```

## Use via MAMA

If you're a [MAMA](https://mama.oliwoods.ai) user, these agents are available as a free marketplace pack. No setup required.

## Contributing

We need **environmental scientists**, **water quality experts**, **developers**, and **data contributors**. Help us expand coverage beyond the US.

**How to contribute:**
1. Fork the repo
2. Create a feature branch (`git checkout -b feat/your-feature`)
3. Commit your changes
4. Push and open a PR

See [CONTRIBUTING.md](CONTRIBUTING.md) when available.

## Related Projects

| Project | Description |
|---------|-------------|
| [MAMA](https://mama.oliwoods.ai) | AI Chief of Staff — 85+ agent teams |
| [CoFounder](https://cofounder.software) | AI agent marketplace |
| [MAMA AI Clinic](https://github.com/OliWoods-Org/mama-ai-clinic) | $170 offline health clinic for Raspberry Pi |
| [OliWoods Foundation](https://mama.oliwoods.ai/foundation) | Open-source AI for humanitarian impact |

---

<p align="center">
  <strong>An <a href="https://mama.oliwoods.ai/foundation">OliWoods Foundation</a> Project</strong>
  <br><em>Open-source AI tools for humanitarian and public good</em>
  <br><br>
  <sub>
    Built with <a href="https://mama.oliwoods.ai">MAMA</a> · Powered by <a href="https://cofounder.software">CoFounder</a>
    <br>Our commercial products fund the Foundation's open-source work.
    <br><br>
    <strong>GPL-3.0 — Fork it. Deploy it. Know your water.</strong>
  </sub>
</p>

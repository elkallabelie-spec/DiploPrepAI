# 🌐 DiploPrepAI

**AI-Powered Diplomatic Engagement and Influence Assistant**

*G7 GovAI Grand Challenge 2025 | Problem Statement 1*

---

## What It Does

DiploPrepAI prepares diplomats for high-stakes bilateral engagements by generating:

- **Situation Analysis** — Bilateral context and counterpart dynamics
- **Influence Approach** — Culturally-calibrated strategy using established frameworks
- **Key Messages** — Tailored communication adapted to counterpart culture
- **Talking Points** — With anticipated responses and counters
- **Risk Mitigation** — Potential obstacles and escalation pathways
- **Explainability** — Full transparency on reasoning, assumptions, and limitations

## The Problem It Solves

Diplomats preparing for bilateral meetings must manually synthesize:
- Country context and relationship history
- Counterpart dynamics and cultural protocols
- Strategic positioning and influence tactics
- Talking points and anticipated objections

This labor-intensive process repeats before every engagement — and institutional knowledge leaves when officers rotate every 2-3 years.

**DiploPrepAI transforms scattered preparation into structured engagement strategy.**

---

## How It Works
```
┌─────────────────────────────────────────────────────────────┐
│                        USER INPUTS                          │
│  Country | Topic | Engagement Type | Desired Outcome        │
└─────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────┐
│                    PROCESSING LAYER                         │
│  • Claude API (claude-sonnet-4-20250514)                            │
│  • Influence frameworks (Cialdini, Hofstede)                │
│  • Cultural communication patterns                          │
│  • Diplomatic protocol knowledge                            │
└─────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────┐
│                   STRUCTURED OUTPUT                         │
│  Situation | Approach | Messages | Talking Points | Risks   │
│                    + Explainability Tab                     │
└─────────────────────────────────────────────────────────────┘
```

---

## Responsible AI Principles

DiploPrepAI aligns with [OECD AI Principles](https://oecd.ai/en/ai-principles):

| Principle | Implementation |
|-----------|----------------|
| **Transparency** | Explainability tab shows reasoning chains, assumptions, confidence levels |
| **Human Oversight** | Officers review, modify, and approve all recommendations |
| **Accountability** | No automated decisions — diplomats retain full authority |
| **Fairness** | Cultural frameworks presented as analytical tools, not stereotypes |

---

## Explainability Features

Every engagement strategy includes:

1. **Reasoning Chain** — Step-by-step explanation of how the influence approach was selected
2. **Assumptions Made** — Explicit listing of what the system assumed
3. **Confidence Level** — High/Medium/Low with justification
4. **Limitations** — What the system cannot account for
5. **Data Sources** — References to public government sources

> "No black boxes. Every recommendation is traceable."

---

## Technology Stack

- **Frontend:** Bolt.new (React-based)
- **AI Model:** Claude API (Anthropic)
- **Hosting:** Web-based, browser-accessible
- **Data:** Public government sources only (no classified information)

---

## Influence Frameworks Used

### Cialdini's Principles of Influence
- Reciprocity
- Commitment/Consistency  
- Social Proof
- Authority
- Liking
- Scarcity

### Hofstede Cultural Dimensions
- Power Distance
- Individualism vs. Collectivism
- Uncertainty Avoidance
- Long-term vs. Short-term Orientation

### Communication Styles
- High-context vs. Low-context
- Direct vs. Indirect
- Formal vs. Informal protocols

See [INFLUENCE_FRAMEWORKS.md](docs/INFLUENCE_FRAMEWORKS.md) for detailed documentation.

---

## Human-Centred Design

The interface mirrors how diplomats actually prepare:

| Tab | Maps To |
|-----|---------|
| Situation | Understanding context |
| Approach | Developing influence strategy |
| Messages | Crafting communication |
| Talking Points | Anticipating dialogue |
| Risks | Mitigating obstacles |
| Explainability | Verifying AI reasoning |

Designed by someone with direct foreign service experience.

---

## Privacy & Security

- **Stateless sessions** — No engagement details stored
- **No classified data** — Public sources only
- **No personal information** — General parameters only
- **Production-ready architecture** — Supports GC cloud integration

---

## Documentation

- [Architecture Overview](docs/ARCHITECTURE.md)
- [Explainability Framework](docs/EXPLAINABILITY.md)
- [User Guide](docs/USER_GUIDE.md)
- [Influence Frameworks](docs/INFLUENCE_FRAMEWORKS.md)

---

## License

MIT License — See [LICENSE](LICENSE)

---

## G7 GovAI Grand Challenge 2025

This submission addresses **Problem Statement 1:**

> "Public servants must manage high volumes of information, often manually"

DiploPrepAI demonstrates how AI can transform fragmented diplomatic preparation into structured engagement strategy while maintaining full human oversight and decision-making authority.

---

*Built for diplomats, by a diplomat.*

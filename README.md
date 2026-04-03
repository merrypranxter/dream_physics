# Dream Physics

> *A Field Manual of the Sleeping Cosmos — organized for AI art applications and creative projects.*

Dream Physics is a theoretical framework exploring the laws, substances, and mechanics of the dream universe. This repository organizes the complete Dream Physics content into structured, accessible files for use by AI art tools and creative applications.

---

## 📂 Repository Structure

| Folder | Description |
|--------|-------------|
| [📖 textbook/](textbook/README.md) | 15-chapter Dream Physics textbook + appendix |
| [🌀 phenomena/](phenomena/README.md) | Complete taxonomy of dream phenomena |
| [🎨 prompts/](prompts/README.md) | Ready-to-use AI art generation prompts |
| [📊 data/](data/README.md) | JSON-structured data for programmatic access |

---

## 🚀 Quick Start for AI Art Apps

**Random prompt from JSON:**
```python
import json, random
with open('data/prompts-index.json') as f:
    data = json.load(f)
print(random.choice(data['prompts'])['prompt'])
```

**Browse by category:**
- `sensory` · `spatial` · `temporal` · `identity` · `emotional` · `symbolic` · `atmosphere` · `concept` · `character`

---

## 📖 The Textbook (15 Chapters)

1. [Ontology of the Dream Universe](textbook/chapter-01-ontology-of-the-dream-universe.md) — What exists in dream-space; Oneiros, O-Nodes, Symbol Field
2. [Emotional Field Theory](textbook/chapter-02-emotional-field-theory.md) — How feelings sculpt dreamworld spacetime
3. [Mnemonic Gravity & Recursion](textbook/chapter-03-mnemonic-gravity-recursion.md) — Memory as gravitational mass; recurring dreams
4. [Identity Topology & Multiplicity](textbook/chapter-04-identity-topology-multiplicity.md) — The mathematics of the dream-self
5. [Symbolic Mechanics](textbook/chapter-05-symbolic-mechanics.md) — How symbols form, mutate, and become narratives
6. [Kairotempics](textbook/chapter-06-kairotempics.md) — The physics of nonlinear dream time
7. [Topology of Impossible Space](textbook/chapter-07-topology-of-impossible-space.md) — Non-Euclidean dream architecture
8. [Consciousness as a Probability Engine](textbook/chapter-08-consciousness-as-a-probability-engine.md) — Dream-mind as quantum observer
9. [Dream Energetics](textbook/chapter-09-dream-energetics.md) — Emotional fuel dynamics
10. [Failure Modes of Dream Physics](textbook/chapter-10-failure-modes-of-dream-physics.md) — When dream logic breaks down
11. [The Psychedelic Interface](textbook/chapter-11-the-psychedelic-interface.md) — Where dream physics overlaps waking reality
12. [The Architecture of Awakening](textbook/chapter-12-the-architecture-of-awakening.md) — The physics of waking from dreams
13. [Engineering the Dream System](textbook/chapter-13-engineering-the-dream-system.md) — Lucid dreaming as engineering
14. [The Dream Physics of Art & Creation](textbook/chapter-14-the-dream-physics-of-art-creation.md) — Creative process through dream physics lens
15. [The Grand Synthesis](textbook/chapter-15-the-grand-synthesis.md) — Unified dream physics framework

---

## 🌀 Dream Phenomena Taxonomy

- [Sensory Distortions](phenomena/sensory-distortions.md)
- [Spatial & Temporal Anomalies](phenomena/spatial-and-temporal-anomalies.md)
- [Identity Shifts](phenomena/identity-shifts.md)
- [Narrative Glitches](phenomena/narrative-glitches.md)
- [Emotional Patterns](phenomena/emotional-patterns.md)
- [Rare & Anomalous Dream Types](phenomena/rare-or-anomalous-dream-types.md)
- [Addendum — Additional Phenomena](phenomena/addendum.md)
- [Detailed Scientific Taxonomy](phenomena/detailed-taxonomy.md)
- [Dream Physics and Dream Logic](phenomena/dream-physics-and-logic.md)

---

## 🎨 AI Art Prompt Collections

- [Visual Prompts](prompts/visual-prompts.md) — Phenomena-based image prompts
- [Atmospheric Prompts](prompts/atmospheric-prompts.md) — Mood and style prompts
- [Concept Prompts](prompts/concept-prompts.md) — Theory-illustrated prompts
- [Character Prompts](prompts/character-prompts.md) — Dream beings and archetypes

---

## 📊 Data Files (JSON)

- [concepts.json](data/concepts.json) — Core theoretical concepts with definitions
- [phenomena.json](data/phenomena.json) — Categorized phenomena with art tags
- [prompts-index.json](data/prompts-index.json) — Flat prompt index for quick access

---

*Source material: repo_guts/ contains the original PDF files.*

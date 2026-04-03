# Data Files — Dream Physics

> *Structured JSON data for programmatic access by AI art applications.*

[Back to Repo Root](../README.md)

---

## Files

| File | Description | Use Case |
|------|-------------|----------|
| [concepts.json](concepts.json) | Core Dream Physics theoretical concepts with definitions, properties, chapter references | Building concept explorers, educational tools |
| [phenomena.json](phenomena.json) | Categorized dream phenomena with AI art tags | Phenomenon-based prompt generation, categorized browsing |
| [prompts-index.json](prompts-index.json) | Flat indexed list of all AI art prompts by category | Quick random prompt access, filtered prompt selection |

---

## Usage Example

```python
import json, random

# Load a random dream physics prompt
with open('data/prompts-index.json') as f:
    data = json.load(f)

# Get all spatial prompts
spatial_prompts = [p for p in data['prompts'] if p['category'] == 'spatial']
print(random.choice(spatial_prompts)['prompt'])

# Get a random concept for image generation
with open('data/concepts.json') as f:
    concepts = json.load(f)
concept = random.choice(concepts['concepts'])
print(f"{concept['name']}: {concept['definition']}")
```

---

*[← Back to Repo Root](../README.md)*

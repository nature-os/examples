NatureOS Examples

Worked examples and Jupyter notebooks demonstrating NatureOS Core for real-world ecological design workflows.


Examples

| Notebook | Scenario | What It Demonstrates |
|----------|----------|----------------------|
| [`dubai-urban-park`](notebooks/dubai-urban-park.ipynb) | Public park in Dubai | Full workflow: Site → Habitat Suitability → Water Budget → Biodiversity → Carbon → Design Optimization |
| `wadi-restoration` (coming soon) | Hajar Mountain wadi ecosystem restoration | Native species selection for degraded desert habitats |
| `mangrove-buffer` (coming soon) | Coastal mangrove buffer design | Saline-tolerant species, shoreline protection, blue carbon |
| `street-median` (coming soon) | Urban streetscape in Abu Dhabi | Constrained-space planting with heat mitigation focus |
| `desert-campus` (coming soon) | University campus landscape | Large-scale institutional planting with biodiversity targets |

Requirements

```bash
pip install natureos-core jupyter
Or install from source:

bash
git clone https://github.com/nature-os/core.git
cd core
pip install -e .
Running the Examples
bash
git clone https://github.com/nature-os/examples.git
cd examples
jupyter notebook
Then open any notebook in the notebooks/ directory.

Contributing
Have a real-world ecological design scenario? Submit it as an example notebook. See CONTRIBUTING.md.

License
Apache 2.0 — see LICENSE.

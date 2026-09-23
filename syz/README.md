# syz

Persistent identifiers for the vocabularies of **Holonic Knowledge
Representation for Clinical Evidence**, a research project of the Department of
Computer Engineering, Izmir Bakircay University.

Three vocabulary modules are served under this prefix:

| Identifier | Namespace | Description |
|---|---|---|
| `https://w3id.org/syz/holon` | `https://w3id.org/syz/holon#` | Four-layer holon core vocabulary |
| `https://w3id.org/syz/openevidence` | `https://w3id.org/syz/openevidence#` | Clinical-evidence domain vocabulary |
| `https://w3id.org/syz/medical` | `https://w3id.org/syz/medical#` | Medical subset used in the OWL-to-SHACL experiment |

Requests are content-negotiated: `text/turtle` returns the ontology, a browser
receives the human-readable documentation. Version IRIs of the form
`https://w3id.org/syz/holon/1.0.0` resolve to that release.

All content is licensed under CC BY 4.0.

**Contact:** okan.bursa@bakircay.edu.tr

# Legistlan

**Artificial intelligence for Mexican law.** Legistlan builds open corpora, tools and analyses of
Mexican legal texts, so that the law can be read, measured and searched by machines as well as by
people.

## Sources

Two sources, and only two:

- The *Diario Oficial de la Federación* (DOF), Mexico's official gazette: more than 1.2 million
  legal provisions published since 1917, the official text of the law.
- The Supreme Court's (SCJN) consolidated texts of federal laws, regulations, guidelines and
  international treaties: 315 federal laws with every reform-dated version, 1,087 regulations,
  163 guidelines and 1,455 treaties.

## What is here

- **Packages** (Python, on PyPI): `dofjson`, a client for the DOF's open data; `scjn`, a client and
  disk-first reader for the Supreme Court's texts; `nota2md`, one DOF note to Markdown; `md2akn`,
  which reads a legal instrument into a tree labelled with the Akoma Ntoso vocabulary and turns it
  into retrieval units; `legalvec`, a reader for the project's vector releases.
- **Data**: the corpora, the DOF notes archive, and one embedding per distinct legal text with two
  models (Qwen3-Embedding 0.6B and 4B), published as GitHub releases and read back through the packages.
- **Results**: the [Atlas](https://ingeotec.github.io/LegalIA/pages/atlas.html), a map of 2,670 federal
  instruments placed by what their texts say, and the
  [Instruments](https://ingeotec.github.io/LegalIA/pages/instruments.html) page, where every
  instrument can be read with its nearest texts across the corpus.
- **Developer reference**: [legalia.readthedocs.io](https://legalia.readthedocs.io), with a verified
  example for every public function.

## Where things are

The project began as [INGEOTEC/LegalIA](https://github.com/INGEOTEC/LegalIA) and is moving here,
one repository per package and per result. Until the move completes, the code, the data releases
and the site live at their original addresses, linked above.

Legistlan is developed in Aguascalientes, México.

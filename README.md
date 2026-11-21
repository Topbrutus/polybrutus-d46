# Polybrutus 46D — Exact 51-point Euclidean metric and fortyfold ideal graph mode

**Human scientific author:** Gabriel St-Pierre, independent researcher.  
**AI assistance disclosure:** OpenAI ChatGPT (Astra) materially assisted exact calculations, independent checker implementations, manuscript and publication; AI is not an author.

## Exact construction and two independent checks

- **51 labelled norm-one vertices**, all **1,275 unordered labelled squared distances** verified by two separate exact rational programs.
- **1,225/1,225** frozen predecessor D45 labels unchanged; **50** new squared distances all **2R²**.
- Exact Gram PSD and centered Euclidean Gram PSD with **minimal affine realization rank 46** for this specific synthetic labelled metric. Ambient coordinate storage: **47**.
- Exact unit-radius squared-distance histogram `k=4d²/R²`: `{4:6,7:2,8:1244,9:3,10:10,12:6,13:2,16:2}`. Total squared distances at `R=1`: **10247/4**.
- Separately stipulated **ideal weighted complete graph** with scalar unit masses and weights `w_ij=R²/d_ij²`: eigenvalue **51/2 with multiplicity 40** and eigenvalue **25 with multiplicity 4**; these modes are dimensionless, **not experimentally measured hertz**.
- 4/4 primary adversarial negative controls pass. Independent checker reconstructs distances with Python `fractions.Fraction` without importing primary Gram generator.

```bash
python -m pip install sympy==1.14.0
python src/verify_d46.py
python tests/independent_d46.py
```

The independent programs output the same deterministic SHA-256 for `results/certificate_d46.json`.

## Immutable complete scientific ancestry

Source parent **[Polybrutus D45 v0.1.0](https://github.com/Topbrutus/polybrutus-d45/tree/v0.1.0)**, scientific commit `c743aa3e29a16ef9868375077ef31a222fd45c46`, [DOI 10.5281/zenodo.24416007](https://doi.org/10.5281/zenodo.24416007). Original tag's complete scientific source including all earlier ancestors is tracked in `prior/d45/frozen_scientific_tag_v0.1.0.zip`, **2,256,549 bytes**, **30 entries**, CRC PASS, SHA-256 `63a3a5a372f53419b0d93ce1343704ab08ccc0598a6ecf11cd63282681905f42`. Original D45 certificate extracted byte-identically to `prior/d45/results/certificate_d45.json`, SHA-256 `b37d3d92e16a4c4f3741cbcfe1889ba19d949ce860fec0210036aeaf4e4b2160`. Both checkers authenticate the complete ZIP and parent cert.

## Manuscript, citation and Zenodo metadata safeguards

- [Specification](SPECIFICATION_D46.md), [constructive proof](PREUVE_D46.md), [provenance](PROVENANCE.md), [ancestry integrity](prior/d45/ARCHIVE_PROVENANCE.md).
- [Verified bibliography](REFERENCES.md); [PDF preprint](publication/POLYBRUTUS_46D_NOTE.pdf) and [editable text](publication/POLYBRUTUS_46D_NOTE.md); [full certificate](results/certificate_d46.json).
- Mandatory Zenodo metadata: keywords **`affine Euclidean dimension forty-six`** and **`fortyfold ideal eigenvalue`** derived from this exact certificate; structured `related_identifiers` **`isDerivedFrom`** [D45 DOI 10.5281/zenodo.24416007](https://doi.org/10.5281/zenodo.24416007); **separate textual `references`** containing exact verified D45 and historical Polybrutus 7D DOI. These must pass public Zenodo API readback after publication.

**Scope:** One exact synthetic Euclidean metric and one separately chosen ideal graph, using established orthogonal extensions and uniform graph joins; no physical extra spacetime dimensions, experimentally measured resonances or particles, novel universal theorem or independent human peer review is claimed.

**Licenses:** MIT software; CC BY 4.0 manuscript.

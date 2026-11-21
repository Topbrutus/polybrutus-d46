# Polybrutus 46D — Constructive proof and falsification controls

**Scientific parent:** [Topbrutus/polybrutus-d45@v0.1.0](https://github.com/Topbrutus/polybrutus-d45/tree/v0.1.0), commit `c743aa3e29a16ef9868375077ef31a222fd45c46`, DOI `10.5281/zenodo.24416007`; original parent certificate SHA-256 `b37d3d92e16a4c4f3741cbcfe1889ba19d949ce860fec0210036aeaf4e4b2160`.

**1. Full immutability.** The entire exact original D45 scientific tag and older ancestors are tracked as `prior/d45/frozen_scientific_tag_v0.1.0.zip`, **2,256,549 bytes**, 30 entries, CRC PASS and SHA-256 `63a3a5a372f53419b0d93ce1343704ab08ccc0598a6ecf11cd63282681905f42`. Parent original certificate is extracted byte-identically. Both programs check ZIP SHA, CRC, original certificate and certificate SHA.

**2. Pair-label conservation.** All 50 predecessor norm-one points are zero-extended, then one independent perpendicular unit vertex is added. All 1,225 predecessor labelled squared distances are identical; the 50 new squared distances equal `2R²`. Exactly **1275=C(51,2)** labelled unordered pairs result.

**3. Euclidean positive semidefinite Gram and minimal affine rank.** Explicit orthogonal Gram blocks have rank 3 (seven canonical points) + 4 (five unit centered simplex vertices) + 39 (perpendicular unit axes) = **46**, with unit diagonal and PSD by construction. Complete squared-distance matrix gives uniquely centered Euclidean Gram `B=-(1/2)HDH=HGH`, exact rational PSD rank 46. The original antipodal canonical pair places the origin in the affine hull, so this particular labelled metric has minimum affine realization rank **46**.

**4. Exact exhaustive arithmetic.** Histogram `k=4d²/R²`: `{4:6,7:2,8:1244,9:3,10:10,12:6,13:2,16:2}` totals 1275 pairs, sum squared distances at R=1 **10247/4**. Old 1,225 pair *labels* are compared against the authenticated D45 certificate, not merely the histogram.

**5. Separately stipulated ideal weighted graph.** Scalar unit masses, complete graph edge weights `w_ij=1/d_ij²`; independently computed exact Laplacian nullities yield eigenvalue **51/2 multiplicity 40** and **25 multiplicity 4**. These dimensionless modes are not measured hertz or particle masses.

**6. Independent exact verifiers.** `src/verify_d46.py` builds rational Gram and distance matrices, checks all labelled distances, old labels, Gram/affine rank and graph nullities. Four adversarial primary negative controls reject a corrupted squared pair distance, duplicate vertex, nonorthogonal tilt and histogram-preserving label permutation. Independent `tests/independent_d46.py` derives all pair distances using Python `fractions.Fraction` without importing the primary Gram generator; separately verifies all 1,275 labels, 1,225 previous labels, Gram and graph nullities, source ZIP and original parent certificate SHA/CRC. Both produce identical deterministic certificate SHA-256.

**7. Mandatory editorial proof.** `publication/zenodo_metadata_blueprint.json` must list `forty-six` and `fortyfold` from the D46 certificate, exact `isDerivedFrom` to predecessor [D45 DOI 10.5281/zenodo.24416007](https://doi.org/10.5281/zenodo.24416007), and separate `references` text referencing authentic D45 and original Polybrutus 7D, not copied D31 keywords. PDF and source `REFERENCES.md` must repeat validated DOI. CI verifies these before tag. Zenodo public API must verify *both* structured relation and textual bibliography after publication.

**Limits:** established perpendicular Euclidean extension / ideal graph joining; one chosen metric, not experimental proof of extra spacetime dimensions, observed frequencies, particles, new universal theorem or human peer review.

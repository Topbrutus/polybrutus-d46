# Polybrutus D46 — Exact rational Euclidean labelled-distance metric

## Parent science, verified complete ancestry

Only immutable predecessor `Topbrutus/polybrutus-d45@v0.1.0`, scientific commit `c743aa3e29a16ef9868375077ef31a222fd45c46`, DOI `10.5281/zenodo.24416007`. The original complete 45D scientific tag including all previous ancestor ZIPs is `prior/d45/frozen_scientific_tag_v0.1.0.zip`, 2,256,549 bytes, 30 entries, CRC PASS, SHA-256 `63a3a5a372f53419b0d93ce1343704ab08ccc0598a6ecf11cd63282681905f42`. Original 45D certificate `results/certificate_d45.json` extracted byte-identically into `prior/d45/results/certificate_d45.json`, SHA-256 `b37d3d92e16a4c4f3741cbcfe1889ba19d949ce860fec0210036aeaf4e4b2160`. Both exact checking programs verify full ZIP SHA/CRC and exact parent certificate.

## Conservative norm-one Euclidean extension

Embed each of 50 predecessor norm-one points `p_i` as `q_i=(p_i,0)` and adjoin one perpendicular norm-one vertex `q51=e47`. All 1,225 original squared pair distances retain their labels. Each new squared distance is `||q51-q_i||²=1+1-2<q51,q_i>=2`; there are **50** new distances. Thus `C(51,2)=1275=1225+50` complete unordered labelled pair values.

Exact Gram `G`: original seven-point canonical rational rank-three block with pair products `3*x_i*x_j+y_i*y_j+z_i*z_j`; centered independent five-point unit simplex block with diagonal 1 and off-diagonal `-1/4`, rank 4; plus **39** independent perpendicular unit coordinate axes. `rank(G)=3+4+39=46`; explicit Gram construction proves positive semidefinite, unit diagonal. Squared-distance matrix `D_ii=0`, `D_ij=2-2G_ij`; projector `H=I-11ᵀ/51`; centered Euclidean Gram `B=-(1/2)HDH=HGH`, PSD rank 46. The inherited antipodal canonical pair places the origin in the affine hull. Thus **minimum affine Euclidean realization dimension 46** for this specific complete metric; ambient coordinate storage **47**.

## All pair labels and unit-radius invariants

```text
Unit vertices                                   51
Unordered labelled squared-distance pairs    1275
Original frozen D45 labels conserved          1225/1225
New squared distances                          50 × 2
Histogram k=4d²/R²                             4:6 7:2 8:1244 9:3 10:10 12:6 13:2 16:2
Total squared pair distances, R=1             10247/4
Centered Gram PSD rank and affine rank         46
Ambient coordinate storage                     47
```

## Independently stipulated ideal graph

An ideal complete graph with scalar unit masses and symmetric edge weights `w_ij=R²/d_ij²` has weighted Laplacian

```text
L46 = [ L45 + I50/2        -1_50/2 ]
      [ -1_50ᵀ/2                 25 ].
```

Exact characteristic recurrence `chi51(z)=z(z-51/2)chi50(z-1/2)/(z-1/2)`. If `f6(z)=chi_P7(z)/z` denotes the original seven-point graph's nonzero factor, the chosen-model closed expression is `chi51(z)=z(z-51/2)^40(z-25)^4*f6(z-22)`. Independently checked exact nullities give `nullity(L46-51/2 I)=40` and `nullity(L46-25I)=4`. **Dimensionless ideal graph modes**, not observed frequencies.

**Citation:** [parent D45 DOI](https://doi.org/10.5281/zenodo.24416007) and [bibliography](REFERENCES.md).

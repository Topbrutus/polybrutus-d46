# Polybrutus 46D: Exact 51-point Euclidean metric and a fortyfold ideal graph mode

**Gabriel St-Pierre** — Independent researcher  
**21 November 2026**  
**Exact mathematical case study / scientific preprint**  
**AI assistance disclosure:** OpenAI ChatGPT (Astra) materially assisted rational calculations, two separately implemented exact checkers, manuscript and controlled publication. AI is not a scientific author.

## Abstract

We construct one exact Euclidean labelled squared-distance metric on 51 norm-one points by appending a perpendicular unit point to the frozen Polybrutus 45D metric [1]. All 1,225 original labelled squared pair distances are conserved and 50 new squared pair distances equal 2 at unit radius, yielding 1,275 unordered labelled pairs. The exact rational centered Euclidean Gram is PSD rank 46, proving minimum affine realization dimension 46 for this synthetic metric. In a separately stipulated ideal complete weighted graph with unit scalar masses and symmetric weights w_ij=1/d_ij², the Laplacian has eigenvalue 51/2 of multiplicity 40 and eigenvalue 25 of multiplicity 4. Two independently implemented exact rational programs verify all labels, predecessor labels, Euclidean rank, source archive integrity and graph nullities. This construction does not demonstrate measured physical frequencies or extra spacetime dimensions.

## 1. Immediate parent and complete immutable scientific source

The only scientific predecessor is St-Pierre, Polybrutus 45D [1], DOI 10.5281/zenodo.24416007, original frozen source Topbrutus/polybrutus-d45@v0.1.0 and scientific commit c743aa3e29a16ef9868375077ef31a222fd45c46. The 45D parent has 50 norm-one points and 1,225 exact unordered labelled squared distances. Its original deterministic certificate SHA-256 is b37d3d92e16a4c4f3741cbcfe1889ba19d949ce860fec0210036aeaf4e4b2160.

The complete original scientific tag and all its previous ancestral archives are preserved unchanged in prior/d45/frozen_scientific_tag_v0.1.0.zip, 2,256,549 bytes, 30 entries, verified ZIP CRC and SHA-256 63a3a5a372f53419b0d93ce1343704ab08ccc0598a6ecf11cd63282681905f42. Its original certificate entry is copied byte-identically to prior/d45/results/certificate_d45.json. Both independent verifiers check source ZIP, CRC, original certificate SHA and byte equality. Preserving compressed nested original source archives avoids Windows MAX_PATH without modifying history.

Embed every old norm-one point p_i as q_i=(p_i,0), i=1,...,50, and append one perpendicular unit point q51=e47. Every old labelled squared distance remains identical. Each of the 50 new squared distances equals ||q51-q_i||²=1+1-2<q51,q_i>=2. Therefore C(51,2)=1275=1225+50 exact labelled unordered distances.

## 2. Exact rational Gram and minimum realization rank

Seven canonical original norm-one points form an exact rational rank-three Gram block with pair products 3*x_i*x_j+y_i*y_j+z_i*z_j. Five centered unit regular-simplex points form a mutually orthogonal rank-four Gram block with unit diagonal and all off-diagonal values -1/4. Thirty-nine further mutually independent perpendicular unit axes contribute rank 39. Thus full rational Gram G has unit diagonal, PSD by explicit vector construction, and rank 3+4+39=46.

Let D be the squared-distance matrix, D_ii=0 and D_ij=2-2G_ij, and H=I-(1/51)11ᵀ. The uniquely centered Euclidean Gram is B=-(1/2)HDH=HGH; it is PSD and exact rank 46. The canonical antipodal pair places the origin in the affine hull, proving the minimum affine Euclidean realization dimension is exactly 46 for this complete synthetic metric.

## 3. Exhaustive exact 1,275 labelled pairs

At unit radius, normalized squared-distance class k=4d²/R² occurs with exact counts k=4 on 6 pairs; k=7 on 2; k=8 on 1,244; k=9 on 3; k=10 on 10; k=12 on 6; k=13 on 2; k=16 on 2. Total 1,275 pairs. The sum of all squared distances at R=1 is exactly 10247/4. Every one of the 1,225 original predecessor pair labels is compared against the authenticated parent certificate; a histogram-only comparison is explicitly insufficient.

## 4. Separately stipulated ideal weighted complete graph

Choose one ideal complete graph with scalar unit masses and symmetric edge weights w_ij=1/d_ij². The new perpendicular unit vertex joins all 50 old vertices with weight 1/2. Its weighted Laplacian block is

L46 = [ L45+(1/2)I50          -(1/2)1_50 ]
      [ -(1/2)1_50ᵀ                   25 ].

The chosen-model uniform graph-join recurrence is chi51(z)=z(z-51/2)chi50(z-1/2)/(z-1/2). Let f6(z)=chi_P7(z)/z be the inherited nonzero seven-point graph factor. The exact model-specific closed form is chi51(z)=z(z-51/2)^40(z-25)^4*f6(z-22).

Two independent rational matrix rank calculations confirm nullity(L46-(51/2)I)=40 and nullity(L46-25I)=4. These are dimensionless graph eigenmodes, **not** measured hertz, physical particles or spacetime dimensions.

## 5. Reproducibility, negative controls and Zenodo metadata consistency

The primary src/verify_d46.py constructs the complete rational Gram and exact labels, authenticates D45 frozen source and original certificate, checks 1,225 original labels and 50 new pairs, Euclidean centered rank and ideal graph nullities. Four adversarial primary negative controls reject a corrupted pair, duplicate vertex, nonorthogonal tilt and histogram-preserving relabelling.

Independently, tests/independent_d46.py reconstructs every labelled pair using Python fractions.Fraction rules without importing the primary Gram constructor and verifies source ZIP, parent certificate bytes, all pairs and exact Gram/graph ranks. Both report an identical SHA-256 for results/certificate_d46.json; public GitHub CI reruns all exact tests and a guard on the Zenodo metadata blueprint. Reproduce with Python sympy==1.14.0 and run both checker programs.

The scientific DOI of immediate predecessor D45 is 10.5281/zenodo.24416007 [1]. Zenodo must explicitly contain (a) the structured field related_identifiers isDerivedFrom -> this DOI, (b) separate bibliographic references to D45 and historical D7 [2], and (c) keywords forty-six and fortyfold **derived from D46**, not copied from D31. All fields must be publicly confirmed after publication.

## 6. Scientific scope

Perpendicular Euclidean metric extensions and uniform weighted-graph joins are established techniques. This manuscript presents one exact synthetic distance metric and freely stipulated ideal graph, not a new universal theorem, experimental demonstration of 46 physical spacetime dimensions, frequencies, particles or independent human peer review. Historical Polybrutus 7D [2] supplies context, not the immediate scientific source.

## References

[1] St-Pierre, Gabriel (2026). Polybrutus 45D: Exact 50-Point Euclidean Metric and Thirty-Ninefold Ideal Graph Mode. Zenodo. DOI: 10.5281/zenodo.24416007. https://doi.org/10.5281/zenodo.24416007

[2] St-Pierre, Gabriel (2026). Polybrutus 7D: An Exact Twelve-Point Orthogonal Completion, the 12-35-37 Identity, and an Oscillator Model. Zenodo. DOI: 10.5281/zenodo.24407952. https://doi.org/10.5281/zenodo.24407952

[3] St-Pierre, Gabriel (2026). Polybrutus D45 frozen scientific tag v0.1.0. GitHub source: https://github.com/Topbrutus/polybrutus-d45/tree/v0.1.0, scientific commit c743aa3e29a16ef9868375077ef31a222fd45c46. Full original source archive embedded with this work.

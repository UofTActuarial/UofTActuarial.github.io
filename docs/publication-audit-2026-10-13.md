# Publications audit for manual verification

Reviewed 65 publication folders on 13 October 2026. Seven records changed from preprints to journal articles. The lists below identify the newly published papers, PDF validation results, remaining DOI issue, and changes in every folder.

The production Hugo build succeeds. Generated publication pages contain 65 Cite buttons, 65 DOI buttons, 65 URL buttons and 65 PDF buttons. The 11 PDFs subsequently added by the user pass identity, link and built-file verification. A linked PDF may be an author manuscript or preprint; its version is identified below.

Journal records use the final issue date when assigned, otherwise the online publication date. Month-only dates use day 01 for sorting; year-only dates use 1 January. These placeholder days do not assert a precise publication day. Preprints use their first posting date and remain publication type 3. Journal articles use type 2. Folder names remain stable even when the publication year changes.

## Newly published papers

| Existing folder | Published title | Journal and date | Published DOI |
| --- | --- | --- | --- |
| chen-furman-lin-2025 | Static marginal expected shortfall: Systemic risk measurement under dependence uncertainty | *Insurance: Mathematics and Economics* 2026-09-01 | [10.1016/j.insmatheco.2026.103285](https://doi.org/10.1016/j.insmatheco.2026.103285) |
| jaimungal-pesenti-saporito-targino-2023 | Risk Budgeting Allocation for Dynamic Risk Measures | *Operations Research* 2025-05-01 | [10.1287/opre.2023.0299](https://doi.org/10.1287/opre.2023.0299) |
| kroell-jaimungal-pesenti-2023 | Optimal robust reinsurance with multiple insurers | *Scandinavian Actuarial Journal* 2025-05-01 | [10.1080/03461238.2024.2431539](https://doi.org/10.1080/03461238.2024.2431539) |
| moresco-mailhot-pesenti-2023 | Uncertainty Propagation and Dynamic Robust Risk Measures | *Mathematics of Operations Research* 2025-08-01 | [10.1287/moor.2023.0267](https://doi.org/10.1287/moor.2023.0267) |
| pesenti-millossovich-tsanakas-2023 | Differential quantile-based sensitivity in discontinuous models | *European Journal of Operational Research* 2025-04-16 | [10.1016/j.ejor.2024.12.008](https://doi.org/10.1016/j.ejor.2024.12.008) |
| pesenti-vanduffel-2023 | Optimal transport divergences induced by scoring functions | *Operations Research Letters* 2024-11-01 | [10.1016/j.orl.2024.107146](https://doi.org/10.1016/j.orl.2024.107146) |
| pesenti-wang-wang-2021 | Optimizing distortion riskmetrics with distributional uncertainty | *Mathematical Programming* 2025-09-01 | [10.1007/s10107-024-02128-6](https://doi.org/10.1007/s10107-024-02128-6) |

Published PDFs for all seven journal upgrades are now present locally and linked. For future additions, use the existing folder and name the PDF after the folder slug. The theme prefers a local PDF with that name over `url_pdf`; remove the remote `url_pdf` for clarity when a local copy is added. The Dynamic Pareto Optima and Chen–Furman–Lin records use explicit local paths because their PDF filenames differ from their folder names.

## Added PDF validation

Verified all 11 newly added PDFs. Each parses successfully and matches its publication record. Each PDF button on the publication page and publications list targets the local file, and each generated PDF matches the source bytes. All 65 publication pages now display PDF, Cite, DOI and URL buttons.

| Publication folder | Local PDF | Result |
| --- | --- | --- |
| chen-furman-lin-2025 | chen-furman-lin-2026.pdf | Verified; explicit link added for different filename |
| chi-jaimungal-lin-2010 | chi-jaimungal-lin-2010.pdf | Verified |
| chi-lin-2011 | chi-lin-2011.pdf | Verified |
| chi-lin-2012 | chi-lin-2012.pdf | Verified |
| chi-lin-tan-2017 | chi-lin-tan-2017.pdf | Verified |
| jaimungal-pesenti-saporito-targino-2023 | jaimungal-pesenti-saporito-targino-2023.pdf | Verified |
| kroell-jaimungal-pesenti-2023 | kroell-jaimungal-pesenti-2023.pdf | Verified |
| moresco-mailhot-pesenti-2023 | moresco-mailhot-pesenti-2023.pdf | Verified |
| pesenti-millossovich-tsanakas-2023 | pesenti-millossovich-tsanakas-2023.pdf | Verified |
| pesenti-vanduffel-2023 | pesenti-vanduffel-2023.pdf | Verified |
| pesenti-wang-wang-2021 | pesenti-wang-wang-2021.pdf | Verified |

The earlier missing-PDF and blocked-PDF issues for Chi–Lin 2011, Chi–Jaimungal–Lin 2010 and Chi–Lin–Tan 2017 are resolved by the local files. The publisher-listed Chi–Lin 2012 DOI remains the separate manual check from the metadata audit.

## Records remaining as preprints

| Existing folder | Title | First posting date |
| --- | --- | --- |
| abdelrahman-badescu-lin-2026 | [A Unified Bayesian Collective Reserving Framework with Hierarchical Temporal Smoothing](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6410160) | 2026-03-13 |
| calcetero-badescu-lin-2025 | [A Population Sampling Framework for Claim Reserving in General Insurance](https://arxiv.org/abs/2502.15598) | 2025-02-21 |
| miao-pesenti-2026 | [Discrimination-insensitive pricing](https://arxiv.org/abs/2603.16720) | 2026-03-17 |
| tam-ghossoub-pesenti-2026 | [Dynamic Pareto Optima in Multi-Period Pure-Exchange Economies](https://arxiv.org/abs/2603.19414) | 2026-03-19 |
| tam-pesenti-2026 | [Bounds for Distributionally Robust Optimization Problems](https://arxiv.org/abs/2504.06381) | 2025-04-08 |

No journal publication was confirmed for these five records. Their DOI buttons use arXiv or SSRN preprint DOIs. Bounds for Distributionally Robust Optimization Problems was first posted in 2025; the existing January 2026 PDF is a later revision, while arXiv now has an August 2026 revision.

## Remaining manual checks

- **chi-lin-2012**: Publisher lists DOI 10.2143/AST.42.2.2182808, but doi.org and Crossref return 404. Preserved authoritative DOI; URL button links directly to Cambridge. Requires manual DOI check.

Several other PDF links point to preprints even though their metadata describes the journal article. The per-paper notes below identify them. The Lee–Badescu–Lin 2026 local PDF already carries the published DOI and final pagination; its previously incomplete citation was corrected to ASTIN Bulletin 56(3), 613–638.

## Shared fixes

- Normalized DOI fields to bare identifiers so the theme generates correct DOI links; supplied URL buttons and PDF links where a source was identified.
- Completed citation journal, volume, issue, pages and year where assigned; corrected author order, names, unique citation keys, duplicate/empty fields, escaped ampersands and BibTeX page ranges.
- Restored supported italic text, mathematical notation and monospace labels in abstracts; kept markup out of downloadable BibTeX.
- Protected title capitalization in BibTeX so acronyms and proper names retain their published spelling when citation styles change case.
- Updated modification dates to 13 October 2026 and synchronized all 65 citations into `publications.bib`. Removed a duplicate master citation and repaired a missing comma in the retained master-only record for Minimal Kullback–Leibler Divergence for Constrained Lévy–Itô Processes. That master-only paper was outside the requested folder audit.
- Kept publication folder URLs stable. The newly added PDFs were verified without editing their bytes.

## Author profile linking

Publication Markdown uses the canonical `authors` value from each existing profile so author links open that profile. BibTeX preserves the published author spelling and order. The profile publication list recognizes both canonical `authors` and the `names` aliases.

Corrected 62 publication files and 101 author-name occurrences. All 124 occurrences of authors with existing profiles were verified to link to the full profile and appear in its publication list in the rebuilt site. Coauthors without an existing profile retain their published names and link to the generated author archive.

| Published spelling | Publication Markdown profile key | Profile folder |
| --- | --- | --- |
| Andrei L. Badescu | Andrei Badescu | Andrei-Badescu |
| Christopher Blier-Wong | Christopher Blier Wong | Christopher-Blier-Wong |
| Ian Weng Chan | Sophia Chan | Sophia-Chan |
| Kathleen E. Miao | Kathleen Miao | Kathleen-Miao |
| Marlon R. Moresco | Marlon Moresco | Marlon-Moresco |
| Sebastián Calcetero Vanegas | Sebastian Calcetero | Sebastian-Calcetero |
| Shuai Yang | Alex Yang | Alex-Yang |
| Silvana M. Pesenti | Silvana Pesenti | Silvana-Pesenti |
| Spark C. Tseung | Spark Tseung | Spark-Tseung |
| Tsz Chai Fung | Samson Fung | Samson-Fung |
| X. Sheldon Lin | Sheldon Lin | Sheldon-Lin |

## Changes by publication

### 1 Marked Cox models for IBNR claims count — continuous and discretized approaches with Dirichlet-driven reporting delays

**Folder:** `abdelrahman-badescu-craiu-lin-2024` · [metadata](../content/publication/abdelrahman-badescu-craiu-lin-2024/index.md) · [citation](../content/publication/abdelrahman-badescu-craiu-lin-2024/cite.bib)

**Current record:** *ASTIN Bulletin*, 2026-01-01. [Publication source](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/marked-cox-models-for-ibnr-claims-count-continuous-and-discretized-approaches-with-dirichletdriven-reporting-delays/7F8EBD9A3AE3A72A44BFC4C352295EBA).

- title: Marked Cox Models for IBNR Claims Count: Continuous and Discretized Approaches with Dirichlet-Driven Reporting Delays → Marked Cox models for IBNR claims count: continuous and discretized approaches with Dirichlet-driven reporting delays
- date: 2024-01-01 → 2026-01-01
- doi: None → 10.1017/asb.2025.10056
- Citation title: Marked Cox Models for IBNR Claims Count: Continuous and Discretized Approaches with Dirichlet-Driven Reporting Delays → {Marked Cox models for IBNR claims count: continuous and discretized approaches with Dirichlet-driven reporting delays}
- Citation author: Abdelrahman, Hassan and Badescu, Andrei and Craiu, Radu and Lin, Sheldon → Abdelrahman, Hassan and Badescu, Andrei L. and Craiu, Radu V. and Lin, X. Sheldon
- Citation volume: 0 → 56
- Citation number: 56 → 1
- Citation pages: 60-88 → 60--88
- Citation year: 2024 → 2026
- Citation eprint: https://doi.org/10.1017/asb.2025.10056 → None
- Citation publisher: Cambridge University Press → Cambridge University Press (CUP)
- Citation note: None → First published online 2025-07-11
- Note: Issue date supplied to month precision; day 01 is a sorting convention, not a claimed publication day.

- authors: ['Hassan Abdelrahman', 'Andrei Badescu', 'Radu Craiu', 'Sheldon Lin'] → ['Hassan Abdelrahman', 'Andrei Badescu', 'Radu V. Craiu', 'Sheldon Lin']
- Author profile links: Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF is a publisher-formatted article and has been preserved.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/marked-cox-models-for-ibnr-claims-count-continuous-and-discretized-approaches-with-dirichletdriven-reporting-delays/7F8EBD9A3AE3A72A44BFC4C352295EBA), [source 2](https://api.crossref.org/works/10.1017/asb.2025.10056).

### 2 An Effective Bayesian GLM Approach for IBNR Claim Count Estimation

**Folder:** `abdelrahman-badescu-lin-2025` · [metadata](../content/publication/abdelrahman-badescu-lin-2025/index.md) · [citation](../content/publication/abdelrahman-badescu-lin-2025/cite.bib)

**Current record:** *North American Actuarial Journal*, 2026-07-03. [Publication source](https://www.tandfonline.com/doi/full/10.1080/10920277.2025.2587884).

- date: 2025-12-01 → 2026-07-03
- doi: None → 10.1080/10920277.2025.2587884
- Citation citation_key: None → abdelrahman_badescu_lin_2025
- Citation entry_type: None → article
- Citation title: None → {An Effective Bayesian GLM Approach for IBNR Claim Count Estimation}
- Citation author: None → Abdelrahman, Hassan and Badescu, Andrei and Lin, X. Sheldon
- Citation journal: None → North American Actuarial Journal
- Citation volume: None → 30
- Citation number: None → 3
- Citation pages: None → 575--598
- Citation year: None → 2026
- Citation doi: None → 10.1080/10920277.2025.2587884
- Citation url: None → https://www.tandfonline.com/doi/full/10.1080/10920277.2025.2587884
- Citation publisher: None → Informa UK Limited
- Citation note: None → First published online 2025-12-01

- Author profile links: X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF is the published online-first article; optionally replace with final issue pagination.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.tandfonline.com/doi/full/10.1080/10920277.2025.2587884), [source 2](https://api.crossref.org/works/10.1080/10920277.2025.2587884).

### 3 A Unified Bayesian Collective Reserving Framework with Hierarchical Temporal Smoothing

**Folder:** `abdelrahman-badescu-lin-2026` · [metadata](../content/publication/abdelrahman-badescu-lin-2026/index.md) · [citation](../content/publication/abdelrahman-badescu-lin-2026/cite.bib)

**Current record:** *SSRN Preprint*, 2026-03-13. [Publication source](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6410160).

- publication_types: ['2'] → ['3']
- doi: None → 10.2139/ssrn.6410160
- Citation citation_key: None → abdelrahman_badescu_lin_2026
- Citation entry_type: None → misc
- Citation title: None → {A Unified Bayesian Collective Reserving Framework with Hierarchical Temporal Smoothing}
- Citation author: None → Abdelrahman, Hassan and Badescu, Andrei and Lin, X. Sheldon
- Citation year: None → 2026
- Citation doi: None → 10.2139/ssrn.6410160
- Citation url: None → https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6410160
- Citation publisher: None → SSRN
- Citation note: None → SSRN preprint 6410160
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: Abstract: corrected typography/spacing while preserving source wording.
- Note: URL button: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6410160

- Author profile links: X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved; its button is checked in the rebuilt site.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6410160), [source 2](https://api.crossref.org/works/10.2139/ssrn.6410160).

### 4 A marked Cox model for the number of IBNR claims — estimation and application

**Folder:** `badescu-chen-lin-tang-2019` · [metadata](../content/publication/badescu-chen-lin-tang-2019/index.md) · [citation](../content/publication/badescu-chen-lin-tang-2019/cite.bib)

**Current record:** *ASTIN Bulletin*, 2019-09-01. [Publication source](https://www.cambridge.org/core/product/identifier/S0515036119000151/type/journal_article).

- date: 2019-01-01 → 2019-09-01
- Links: added or corrected URL/manuscript buttons.
- Citation title: A marked Cox model for the number of IBNR claims: estimation and application → {A marked Cox model for the number of IBNR claims: estimation and application}
- Citation pages: 709–739 → 709--739
- Citation url: None → https://www.cambridge.org/core/product/identifier/S0515036119000151/type/journal_article

- authors: ['Andrei L. Badescu', 'Tianle Chen', 'X. Sheldon Lin', 'Dameng Tang'] → ['Andrei Badescu', 'Tianle Chen', 'Sheldon Lin', 'Dameng Tang']
- Author profile links: Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved: badescu-chen-lin-tang-2019.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/product/identifier/S0515036119000151/type/journal_article), [source 2](https://api.crossref.org/works/10.1017/asb.2019.15).

### 5 A marked Cox model for the number of IBNR claims — Theory

**Folder:** `badescu-lin-tang-2016` · [metadata](../content/publication/badescu-lin-tang-2016/index.md) · [citation](../content/publication/badescu-lin-tang-2016/cite.bib)

**Current record:** *Insurance: Mathematics and Economics*, 2016-07-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S0167668715303401).

- date: 2016-01-01 → 2016-07-01
- doi: https://doi.org/10.1016/j.insmatheco.2016.03.016 → 10.1016/j.insmatheco.2016.03.016
- Links: added or corrected URL/manuscript buttons.
- Citation title: A marked Cox model for the number of IBNR claims: Theory → {A marked Cox model for the number of IBNR claims: Theory}
- Citation pages: 29-37 → 29--37
- Citation doi: https://doi.org/10.1016/j.insmatheco.2016.03.016 → 10.1016/j.insmatheco.2016.03.016
- Citation url: None → https://www.sciencedirect.com/science/article/pii/S0167668715303401

- authors: ['Andrei L. Badescu', 'X. Sheldon Lin', 'Dameng Tang'] → ['Andrei Badescu', 'Sheldon Lin', 'Dameng Tang']
- Author profile links: Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved: badescu-lin-tang-2016.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0167668715303401), [source 2](https://api.crossref.org/works/10.1016/j.insmatheco.2016.03.016).

### 6 Robust distortion risk measures

**Folder:** `bernard-pesenti-vanduffel-2020` · [metadata](../content/publication/bernard-pesenti-vanduffel-2020/index.md) · [citation](../content/publication/bernard-pesenti-vanduffel-2020/cite.bib)

**Current record:** *Mathematical Finance*, 2024-07-01. [Publication source](https://onlinelibrary.wiley.com/doi/10.1111/mafi.12414).

- date: 2024-01-01 → 2024-07-01
- doi: https://doi.org/10.1111/mafi.12414 → 10.1111/mafi.12414
- PDF URL: https://arxiv.org/pdf/2205.08850
- Links: added or corrected URL/manuscript buttons.
- Citation title: Robust distortion risk measures → {Robust distortion risk measures}
- Citation pages: 774-818 → 774--818
- Citation doi: https://doi.org/10.1111/mafi.12414 → 10.1111/mafi.12414
- Citation url: https://onlinelibrary.wiley.com/doi/abs/10.1111/mafi.12414 → https://doi.org/10.1111/mafi.12414
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: Abstract formatting/text: abstract: Abstract The robustness → abstract: The robustness

- authors: ['Carole Bernard', 'Silvana M. Pesenti', 'Steven Vanduffel'] → ['Carole Bernard', 'Silvana Pesenti', 'Steven Vanduffel']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** PDF button links to arXiv manuscript; published PDF can be obtained from the Wiley page.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://onlinelibrary.wiley.com/doi/10.1111/mafi.12414), [source 2](https://arxiv.org/abs/2205.08850).

### 7 Machine Learning in P&C Insurance — A Review for Pricing and Reserving

**Folder:** `blierwong-cossette-lamontagne-marceau-2021` · [metadata](../content/publication/blierwong-cossette-lamontagne-marceau-2021/index.md) · [citation](../content/publication/blierwong-cossette-lamontagne-marceau-2021/cite.bib)

**Current record:** *Risks*, 2021-01-01. [Publication source](https://www.mdpi.com/2227-9091/9/1/4).

- PDF URL: https://res.mdpi.com/d_attachment/risks/risks-09-00004/article_deploy/risks-09-00004-v2.pdf
- Citation title: Machine Learning in P&C Insurance: A Review for Pricing and Reserving → {Machine Learning in P\&C Insurance: A Review for Pricing and Reserving}
- Citation pages: None → 4

- authors: ['Christopher Blier-Wong', 'Hélène Cossette', 'Luc Lamontagne', 'Etienne Marceau'] → ['Christopher Blier Wong', 'Hélène Cossette', 'Luc Lamontagne', 'Etienne Marceau']
- Author profile links: Christopher Blier-Wong → Christopher Blier Wong. Published names remain in the citation.

**PDF:** Added publisher open-access version-of-record PDF link; no PDF downloaded.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.mdpi.com/2227-9091/9/1/4), [source 2](https://doi.org/10.3390/risks9010004), [source 3](https://res.mdpi.com/d_attachment/risks/risks-09-00004/article_deploy/risks-09-00004-v2.pdf).

### 8 Geographic Ratemaking With Spatial Embeddings

**Folder:** `blierwong-cossette-lamontagne-marceau-2022` · [metadata](../content/publication/blierwong-cossette-lamontagne-marceau-2022/index.md) · [citation](../content/publication/blierwong-cossette-lamontagne-marceau-2022/cite.bib)

**Current record:** *ASTIN Bulletin: The Journal of the IAA*, 2022-01-01. [Publication source](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/abs/geographic-ratemaking-with-spatial-embeddings/FE5AF1B2DD96B0D6B2684A775A847013).

- publication: *ASTIN Bulletin* → *ASTIN Bulletin: The Journal of the IAA*
- PDF URL: https://arxiv.org/pdf/2104.12852
- Links: added or corrected URL/manuscript buttons.
- Citation title: Geographic Ratemaking With Spatial Embeddings → {Geographic Ratemaking With Spatial Embeddings}
- Citation journal: ASTIN Bulletin → ASTIN Bulletin: The Journal of the IAA
- Citation pages: 1–31 → 1--31
- Citation url: None → https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/abs/geographic-ratemaking-with-spatial-embeddings/FE5AF1B2DD96B0D6B2684A775A847013

- authors: ['Christopher Blier-Wong', 'Hélène Cossette', 'Luc Lamontagne', 'Etienne Marceau'] → ['Christopher Blier Wong', 'Hélène Cossette', 'Luc Lamontagne', 'Etienne Marceau']
- Author profile links: Christopher Blier-Wong → Christopher Blier Wong. Published names remain in the citation.

**PDF:** Added arXiv preprint PDF link, not the published PDF. Publisher version has a revised abstract; current abstract correctly matches the journal.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/abs/geographic-ratemaking-with-spatial-embeddings/FE5AF1B2DD96B0D6B2684A775A847013), [source 2](https://doi.org/10.1017/asb.2021.25), [source 3](https://arxiv.org/abs/2104.12852), [source 4](https://arxiv.org/pdf/2104.12852).

### 9 A new method to construct high-dimensional copulas with Bernoulli and Coxian-2 distributions

**Folder:** `blierwong-cossette-legros-marceau-2024` · [metadata](../content/publication/blierwong-cossette-legros-marceau-2024/index.md) · [citation](../content/publication/blierwong-cossette-legros-marceau-2024/cite.bib)

**Current record:** *Journal of Multivariate Analysis*, 2024-05-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S0047259X23001070).

- date: 2024-01-01 → 2024-05-01
- doi: https://doi.org/10.1016/j.jmva.2023.105261 → 10.1016/j.jmva.2023.105261
- PDF URL: https://arxiv.org/pdf/2209.13675
- Citation title: A new method to construct high-dimensional copulas with Bernoulli and Coxian-2 distributions → {A new method to construct high-dimensional copulas with Bernoulli and Coxian-2 distributions}
- Citation doi: https://doi.org/10.1016/j.jmva.2023.105261 → 10.1016/j.jmva.2023.105261

- authors: ['Christopher Blier-Wong', 'Hélène Cossette', 'Sebastien Legros', 'Etienne Marceau'] → ['Christopher Blier Wong', 'Hélène Cossette', 'Sebastien Legros', 'Etienne Marceau']
- Author profile links: Christopher Blier-Wong → Christopher Blier Wong. Published names remain in the citation.

**PDF:** Added arXiv preprint PDF link, not the published PDF.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0047259X23001070), [source 2](https://doi.org/10.1016/j.jmva.2023.105261), [source 3](https://arxiv.org/abs/2209.13675), [source 4](https://arxiv.org/pdf/2209.13675), [source 5](https://www.sciencedirect.com/science/article/abs/pii/S0047259X23001070).

### 10 Stochastic representation of FGM copulas using multivariate Bernoulli random variables

**Folder:** `blierwong-cossette-marceau-2022` · [metadata](../content/publication/blierwong-cossette-marceau-2022/index.md) · [citation](../content/publication/blierwong-cossette-marceau-2022/cite.bib)

**Current record:** *Computational Statistics & Data Analysis*, 2022-09-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S016794732200086X).

- date: 2022-01-01 → 2022-09-01
- doi: https://doi.org/10.1016/j.csda.2022.107506 → 10.1016/j.csda.2022.107506
- PDF URL: https://chrisbw.ca/wp-content/uploads/2022/07/fgm-preprint.pdf
- Citation title: Stochastic representation of FGM copulas using multivariate Bernoulli random variables → {Stochastic representation of FGM copulas using multivariate Bernoulli random variables}
- Citation journal: Computational Statistics & Data Analysis → Computational Statistics \& Data Analysis
- Citation doi: https://doi.org/10.1016/j.csda.2022.107506 → 10.1016/j.csda.2022.107506
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: index.md url_pdf: (missing) -> https://chrisbw.ca/wp-content/uploads/2022/07/fgm-preprint.pdf
- Note: abstract: plain d in d-variate -> italic d in website and $d$ in BibTeX

- authors: ['Christopher Blier-Wong', 'Hélène Cossette', 'Etienne Marceau'] → ['Christopher Blier Wong', 'Hélène Cossette', 'Etienne Marceau']
- Author profile links: Christopher Blier-Wong → Christopher Blier Wong. Published names remain in the citation.

**PDF:** Added verified author-hosted preprint PDF dated 20 October 2021, not the published PDF. No arXiv version was located.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S016794732200086X), [source 2](https://doi.org/10.1016/j.csda.2022.107506), [source 3](https://chrisbw.ca/wp-content/uploads/2022/07/fgm-preprint.pdf).

### 11 Risk aggregation with FGM copulas

**Folder:** `blierwong-cossette-marceau-2023` · [metadata](../content/publication/blierwong-cossette-marceau-2023/index.md) · [citation](../content/publication/blierwong-cossette-marceau-2023/cite.bib)

**Current record:** *Insurance: Mathematics and Economics*, 2023-07-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S0167668723000331).

- date: 2023-01-01 → 2023-07-01
- doi: https://doi.org/10.1016/j.insmatheco.2023.03.002 → 10.1016/j.insmatheco.2023.03.002
- PDF URL: https://arxiv.org/pdf/2207.14692
- Citation title: Risk aggregation with FGM copulas → {Risk aggregation with FGM copulas}
- Citation pages: 102-120 → 102--120
- Citation doi: https://doi.org/10.1016/j.insmatheco.2023.03.002 → 10.1016/j.insmatheco.2023.03.002

- authors: ['Christopher Blier-Wong', 'Hélène Cossette', 'Etienne Marceau'] → ['Christopher Blier Wong', 'Hélène Cossette', 'Etienne Marceau']
- Author profile links: Christopher Blier-Wong → Christopher Blier Wong. Published names remain in the citation.

**PDF:** Added arXiv preprint PDF link, not the published PDF.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0167668723000331), [source 2](https://doi.org/10.1016/j.insmatheco.2023.03.002), [source 3](https://arxiv.org/abs/2207.14692), [source 4](https://arxiv.org/pdf/2207.14692).

### 12 Exchangeable FGM copulas

**Folder:** `blierwong-cossette-marceau-2024` · [metadata](../content/publication/blierwong-cossette-marceau-2024/index.md) · [citation](../content/publication/blierwong-cossette-marceau-2024/cite.bib)

**Current record:** *Advances in Applied Probability*, 2024-03-01. [Publication source](https://www.cambridge.org/core/journals/advances-in-applied-probability/article/exchangeable-fgm-copulas/670BBBF0018C8B864AAA7B7A47134304).

- date: 2024-01-01 → 2024-03-01
- PDF URL: https://www.cambridge.org/core/services/aop-cambridge-core/content/view/670BBBF0018C8B864AAA7B7A47134304/S0001867823000198a.pdf/exchangeable-fgm-copulas.pdf
- Links: added or corrected URL/manuscript buttons.
- Citation title: Exchangeable FGM copulas → {Exchangeable FGM copulas}
- Citation pages: 205–234 → 205--234
- Citation url: None → https://www.cambridge.org/core/journals/advances-in-applied-probability/article/exchangeable-fgm-copulas/670BBBF0018C8B864AAA7B7A47134304

- authors: ['Christopher Blier-Wong', 'Hélène Cossette', 'Etienne Marceau'] → ['Christopher Blier Wong', 'Hélène Cossette', 'Etienne Marceau']
- Author profile links: Christopher Blier-Wong → Christopher Blier Wong. Published names remain in the citation.

**PDF:** Added publisher open-access version-of-record PDF link; no PDF downloaded.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/journals/advances-in-applied-probability/article/exchangeable-fgm-copulas/670BBBF0018C8B864AAA7B7A47134304), [source 2](https://doi.org/10.1017/apr.2023.19), [source 3](https://arxiv.org/abs/2205.11302), [source 4](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/670BBBF0018C8B864AAA7B7A47134304/S0001867823000198a.pdf/exchangeable-fgm-copulas.pdf).

### 13 Collective risk models with FGM dependence

**Folder:** `blierwong-cossette-marceau-2024-b` · [metadata](../content/publication/blierwong-cossette-marceau-2024-b/index.md) · [citation](../content/publication/blierwong-cossette-marceau-2024-b/cite.bib)

**Current record:** *Scandinavian Actuarial Journal*, 2025-02-01. [Publication source](https://www.tandfonline.com/doi/abs/10.1080/03461238.2024.2401390).

- date: 2024-01-01 → 2025-02-01
- PDF URL: https://arxiv.org/pdf/2209.13543
- Links: added or corrected URL/manuscript buttons.
- Citation title: Collective risk models with FGM dependence → {Collective risk models with FGM dependence}
- Citation volume: 0 → 2025
- Citation number: 0 → 2
- Citation pages: 1--29 → 139--167
- Citation year: 2024 → 2025
- Citation url: https://doi.org/10.1080/03461238.2024.2401390 → https://www.tandfonline.com/doi/abs/10.1080/03461238.2024.2401390
- Citation eprint: https://doi.org/10.1080/03461238.2024.2401390 → None
- Citation publisher: Taylor & Francis → Taylor \& Francis

- authors: ['Christopher Blier-Wong', 'Hélène Cossette', 'Etienne Marceau'] → ['Christopher Blier Wong', 'Hélène Cossette', 'Etienne Marceau']
- Author profile links: Christopher Blier-Wong → Christopher Blier Wong. Published names remain in the citation.

**PDF:** Added arXiv preprint PDF link, not the published PDF. Download final journal PDF if desired.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.tandfonline.com/doi/abs/10.1080/03461238.2024.2401390), [source 2](https://doi.org/10.1080/03461238.2024.2401390), [source 3](https://arxiv.org/abs/2209.13543), [source 4](https://arxiv.org/pdf/2209.13543), [source 5](https://www.tandfonline.com/toc/sact20/2025/2), [source 6](https://ideas.repec.org/a/taf/sactxx/v2025y2025i2p139-167.html).

### 14 A representation-learning approach for insurance pricing with images

**Folder:** `blierwong-lamontagne-marceau-2024` · [metadata](../content/publication/blierwong-lamontagne-marceau-2024/index.md) · [citation](../content/publication/blierwong-lamontagne-marceau-2024/cite.bib)

**Current record:** *ASTIN Bulletin: The Journal of the IAA*, 2024-05-01. [Publication source](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/representationlearning-approach-for-insurance-pricing-with-images/E442676A2F597A9DBBDFC9FB986C3070).

- date: 2024-01-01 → 2024-05-01
- publication: *ASTIN Bulletin* → *ASTIN Bulletin: The Journal of the IAA*
- PDF URL: https://arxiv.org/pdf/2309.11404
- Links: added or corrected URL/manuscript buttons.
- Citation title: A representation-learning approach for insurance pricing with images → {A representation-learning approach for insurance pricing with images}
- Citation journal: ASTIN Bulletin → ASTIN Bulletin: The Journal of the IAA
- Citation pages: 280–309 → 280--309
- Citation url: None → https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/representationlearning-approach-for-insurance-pricing-with-images/E442676A2F597A9DBBDFC9FB986C3070

- authors: ['Christopher Blier-Wong', 'Luc Lamontagne', 'Etienne Marceau'] → ['Christopher Blier Wong', 'Luc Lamontagne', 'Etienne Marceau']
- Author profile links: Christopher Blier-Wong → Christopher Blier Wong. Published names remain in the citation.

**PDF:** Added arXiv preprint PDF link, not the published PDF. Publisher offers open-access published PDF from the article page.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/representationlearning-approach-for-insurance-pricing-with-images/E442676A2F597A9DBBDFC9FB986C3070), [source 2](https://doi.org/10.1017/asb.2024.9), [source 3](https://arxiv.org/abs/2309.11404), [source 4](https://arxiv.org/pdf/2309.11404).

### 15 Effective experience rating for large insurance portfolios via surrogate modeling

**Folder:** `calcetero-badescu-lin-2024` · [metadata](../content/publication/calcetero-badescu-lin-2024/index.md) · [citation](../content/publication/calcetero-badescu-lin-2024/cite.bib)

**Current record:** *Insurance: Mathematics and Economics*, 2024-09-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S016766872400060X).

- date: 2024-01-01 → 2024-09-01
- doi: https://doi.org/10.1016/j.insmatheco.2024.05.004 → 10.1016/j.insmatheco.2024.05.004
- PDF URL: https://arxiv.org/pdf/2211.06568
- Citation title: Effective experience rating for large insurance portfolios via surrogate modeling → {Effective experience rating for large insurance portfolios via surrogate modeling}
- Citation author: Calcetero Vanegas, Sebastian and Badescu, Andrei and Lin, X. Sheldon → Calcetero Vanegas, Sebastián and Badescu, Andrei L. and Lin, X. Sheldon
- Citation pages: 25-43 → 25--43
- Citation doi: https://doi.org/10.1016/j.insmatheco.2024.05.004 → 10.1016/j.insmatheco.2024.05.004
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: abstract: likelihood-based summary statistic -> italic emphasis (supported by arXiv abstract)

- authors: ['Sebastian Calcetero Vanegas', 'Andrei Badescu', 'X. Sheldon Lin'] → ['Sebastian Calcetero', 'Andrei Badescu', 'Sheldon Lin']
- Author profile links: Sebastián Calcetero Vanegas → Sebastian Calcetero; Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Added arXiv preprint PDF link, not the published PDF. The journal article is open access.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S016766872400060X), [source 2](https://doi.org/10.1016/j.insmatheco.2024.05.004), [source 3](https://arxiv.org/abs/2211.06568), [source 4](https://arxiv.org/pdf/2211.06568), [source 5](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/efficient-dynamic-hedging-for-large-variable-annuity-portfolios-with-multiple-underlying-assets/65AEE4E4D8D06B1060D3414751575F9F).

### 16 Claim reserving via inverse probability weighting — a micro-level Chain-Ladder method

**Folder:** `calcetero-badescu-lin-2024-b` · [metadata](../content/publication/calcetero-badescu-lin-2024-b/index.md) · [citation](../content/publication/calcetero-badescu-lin-2024-b/cite.bib)

**Current record:** *European Actuarial Journal*, 2025-04-01. [Publication source](https://link.springer.com/article/10.1007/s13385-024-00395-3).

- date: 2024-01-01 → 2025-04-01
- doi: None → 10.1007/s13385-024-00395-3
- PDF URL: https://arxiv.org/pdf/2307.10808
- Links: added or corrected URL/manuscript buttons.
- Citation title: Claim reserving via inverse probability weighting: a micro-level Chain-Ladder method → {Claim reserving via inverse probability weighting: a micro-level Chain-Ladder method}
- Citation author: Calcetero Vanegas, Sebastian and Badescu, Andrei and Lin, X. Sheldon → Calcetero Vanegas, Sebastián and Badescu, Andrei L. and Lin, X. Sheldon
- Citation volume: None → 15
- Citation number: None → 1
- Citation pages: 1--47 → 89--135
- Citation year: 2024 → 2025
- Citation doi: None → 10.1007/s13385-024-00395-3
- Citation url: None → https://link.springer.com/article/10.1007/s13385-024-00395-3

- authors: ['Sebastian Calcetero Vanegas', 'Andrei Badescu', 'X. Sheldon Lin'] → ['Sebastian Calcetero', 'Andrei Badescu', 'Sheldon Lin']
- Author profile links: Sebastián Calcetero Vanegas → Sebastian Calcetero; Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Added arXiv preprint PDF link, not the published PDF. Download final journal PDF if desired.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://link.springer.com/article/10.1007/s13385-024-00395-3), [source 2](https://doi.org/10.1007/s13385-024-00395-3), [source 3](https://arxiv.org/abs/2307.10808), [source 4](https://arxiv.org/pdf/2307.10808), [source 5](https://link.springer.com/journal/13385/volumes-and-issues/15-1).

### 17 A Population Sampling Framework for Claim Reserving in General Insurance

**Folder:** `calcetero-badescu-lin-2025` · [metadata](../content/publication/calcetero-badescu-lin-2025/index.md) · [citation](../content/publication/calcetero-badescu-lin-2025/cite.bib)

**Current record:** *arXiv preprint arXiv:2502.15598*, 2025-02-21. [Publication source](https://arxiv.org/abs/2502.15598).

- date: 2025-01-01 → 2025-02-21
- publication_types: ['2'] → ['3']
- doi: None → 10.48550/arXiv.2502.15598
- Links: added or corrected URL/manuscript buttons.
- Citation entry_type: article → misc
- Citation title: A Population Sampling Framework for Claim Reserving in General Insurance → {A Population Sampling Framework for Claim Reserving in General Insurance}
- Citation author: Vanegas, Sebastian Calcetero and Badescu, Andrei L and Lin, X Sheldon → Calcetero Vanegas, Sebastián and Badescu, Andrei L. and Lin, X. Sheldon
- Citation journal: arXiv preprint arXiv:2502.15598 → None
- Citation doi: None → 10.48550/arXiv.2502.15598
- Citation url: None → https://arxiv.org/abs/2502.15598
- Citation eprint: None → 2502.15598
- Citation archivePrefix: None → arXiv
- Note: index.md publication_types: 2 -> 3 (preprint)
- Note: cite.bib journal: arXiv preprint arXiv:2502.15598 -> removed

- authors: ['Sebastian Calcetero Vanegas', 'Andrei L Badescu', 'X Sheldon Lin'] → ['Sebastian Calcetero', 'Andrei Badescu', 'Sheldon Lin']
- Author profile links: Sebastián Calcetero Vanegas → Sebastian Calcetero; Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF retained. It is the preprint dated 24 February 2025. No journal publication identified by exact-title search or current arXiv record.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://arxiv.org/abs/2502.15598), [source 2](https://doi.org/10.48550/arXiv.2502.15598), [source 3](https://actsci.utstat.utoronto.ca/publication/calcetero-badescu-lin-2025/calcetero-badescu-lin-2025.pdf).

### 18 Applications of Population Sampling to Insurance Ratemaking and Reserving

**Folder:** `calcetero-lin-2024` · [metadata](../content/publication/calcetero-lin-2024/index.md) · [citation](../content/publication/calcetero-lin-2024/cite.bib)

**Current record:** *Japanese Journal of Statistics and Data Science*, 2024-11-01. [Publication source](https://link.springer.com/article/10.1007/s42081-024-00260-3).

- date: 2024-01-01 → 2024-11-01
- doi: None → 10.1007/s42081-024-00260-3
- Links: added or corrected URL/manuscript buttons.
- Citation title: Applications of Population Sampling to Insurance Ratemaking and Reserving → {Applications of Population Sampling to Insurance Ratemaking and Reserving}
- Citation author: Calcetero Vanegas, Sebastian and Lin, X. Sheldon → Calcetero Vanegas, Sebastián and Lin, X. Sheldon
- Citation volume: None → 7
- Citation number: None → 2
- Citation pages: 1--16 → 1155--1170
- Citation doi: None → 10.1007/s42081-024-00260-3
- Citation url: None → https://link.springer.com/article/10.1007/s42081-024-00260-3

- authors: ['Sebastian Calcetero Vanegas', 'X. Sheldon Lin'] → ['Sebastian Calcetero', 'Sheldon Lin']
- Author profile links: Sebastián Calcetero Vanegas → Sebastian Calcetero; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF retained; confirmed it is the final published PDF with DOI and pages 1155–1170. Publisher correction only changes open-access licensing, not bibliographic/abstract content.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://link.springer.com/article/10.1007/s42081-024-00260-3), [source 2](https://doi.org/10.1007/s42081-024-00260-3), [source 3](https://actsci.utstat.utoronto.ca/publication/calcetero-lin-2024/calcetero-lin-2024.pdf), [source 4](https://link.springer.com/article/10.1007/s42081-024-00286-7).

### 19 Assessing driving risk through unsupervised detection of anomalies in telematics time series data

**Folder:** `chan-badescu-lin-2025` · [metadata](../content/publication/chan-badescu-lin-2025/index.md) · [citation](../content/publication/chan-badescu-lin-2025/cite.bib)

**Current record:** *ASTIN Bulletin*, 2025-05-01. [Publication source](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/assessing-driving-risk-through-unsupervised-detection-of-anomalies-in-telematics-time-series-data/3E84AF8926F86916929FA9BEA807DC93).

- date: 2025-01-01 → 2025-05-01
- Links: added or corrected URL/manuscript buttons.
- Citation title: Assessing driving risk through unsupervised detection of anomalies in telematics time series data → {Assessing driving risk through unsupervised detection of anomalies in telematics time series data}
- Citation pages: 205–241 → 205--241
- Citation url: None → https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/assessing-driving-risk-through-unsupervised-detection-of-anomalies-in-telematics-time-series-data/3E84AF8926F86916929FA9BEA807DC93
- Citation publisher: None → Cambridge University Press (CUP)
- Citation note: None → First published online 2025-05-22
- Note: Issue date supplied to month precision; day 01 is a sorting convention, not a claimed publication day.

- authors: ['Ian Weng Chan', 'Andrei L. Badescu', 'X. Sheldon Lin'] → ['Sophia Chan', 'Andrei Badescu', 'Sheldon Lin']
- Author profile links: Ian Weng Chan → Sophia Chan; Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF is a publisher-formatted article and has been preserved.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/assessing-driving-risk-through-unsupervised-detection-of-anomalies-in-telematics-time-series-data/3E84AF8926F86916929FA9BEA807DC93), [source 2](https://api.crossref.org/works/10.1017/asb.2025.14).

### 20 Data Mining of Telematics Data — Unveiling the Hidden Patterns in Driving Behavior

**Folder:** `chan-tseung-badescu-lin-2024` · [metadata](../content/publication/chan-tseung-badescu-lin-2024/index.md) · [citation](../content/publication/chan-tseung-badescu-lin-2024/cite.bib)

**Current record:** *North American Actuarial Journal*, 2025-04-03. [Publication source](https://www.tandfonline.com/doi/full/10.1080/10920277.2024.2376816).

- date: 2024-01-01 → 2025-04-03
- PDF URL: https://arxiv.org/pdf/2304.10591
- Links: added or corrected URL/manuscript buttons.
- Citation title: Data Mining of Telematics Data: Unveiling the Hidden Patterns in Driving Behavior → {Data Mining of Telematics Data: Unveiling the Hidden Patterns in Driving Behavior}
- Citation volume: 0 → 29
- Citation number: 0 → 2
- Citation pages: 1--35 → 275--309
- Citation year: 2024 → 2025
- Citation url: https://doi.org/10.1080/10920277.2024.2376816 → https://www.tandfonline.com/doi/full/10.1080/10920277.2024.2376816
- Citation eprint: https://doi.org/10.1080/10920277.2024.2376816 → None
- Citation publisher: Routledge → Informa UK Limited
- Citation note: None → First published online 2024-09-16

- authors: ['Ian Weng Chan', 'Spark C. Tseung', 'Andrei L. Badescu', 'X. Sheldon Lin'] → ['Sophia Chan', 'Spark Tseung', 'Andrei Badescu', 'Sheldon Lin']
- Author profile links: Ian Weng Chan → Sophia Chan; Spark C. Tseung → Spark Tseung; Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Added arXiv PDF link; download final journal PDF if desired.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.tandfonline.com/doi/full/10.1080/10920277.2024.2376816), [source 2](https://arxiv.org/abs/2304.10591), [source 3](https://api.crossref.org/works/10.1080/10920277.2024.2376816).

### 21 Static marginal expected shortfall — Systemic risk measurement under dependence uncertainty

**Folder:** `chen-furman-lin-2025` · [metadata](../content/publication/chen-furman-lin-2025/index.md) · [citation](../content/publication/chen-furman-lin-2025/cite.bib)

**Current record:** *Insurance: Mathematics and Economics*, 2026-09-01. [Publication source](https://www.sciencedirect.com/science/article/abs/pii/S0167668726000752).

- title: Marginal expected shortfall: Systemic risk measurement under dependence uncertainty → Static marginal expected shortfall: Systemic risk measurement under dependence uncertainty
- date: 2025-04-29 → 2026-09-01
- publication: *arXiv* → *Insurance: Mathematics and Economics*
- doi: None → 10.1016/j.insmatheco.2026.103285
- Links: added or corrected URL/manuscript buttons.
- Citation title: Marginal expected shortfall: Systemic risk measurement under dependence uncertainty → {Static marginal expected shortfall: Systemic risk measurement under dependence uncertainty}
- Citation author: Chen, Jinghui and Furman, Edward and Lin, Sheldon → Chen, Jinghui and Furman, Edward and Lin, X. Sheldon
- Citation journal: None → Insurance: Mathematics and Economics
- Citation volume: None → 130
- Citation pages: None → 103285
- Citation year: 2025 → 2026
- Citation doi: None → 10.1016/j.insmatheco.2026.103285
- Citation url: https://arxiv.org/abs/2504.19953 → https://www.sciencedirect.com/science/article/abs/pii/S0167668726000752
- Citation publisher: arXiv → Elsevier BV
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: Abstract: updated to published wording.
- Note: Issue date supplied to month precision; day 01 is a sorting convention, not a claimed publication day.

- Author profile links: X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

- PDF URL: /publication/chen-furman-lin-2025/chen-furman-lin-2026.pdf

**PDF:** User added a published journal PDF, chen-furman-lin-2026.pdf. Verified the paper identity, matching DOI, and successful PDF parsing. PDF buttons on the publication page and publications list link to the local file; the built copy is byte-for-byte identical. Added explicit url_pdf for the 2026 filename inside the unchanged 2025 folder.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/abs/pii/S0167668726000752), [source 2](https://arxiv.org/abs/2504.19953), [source 3](https://api.crossref.org/works/10.1016/j.insmatheco.2026.103285).

### 22 An insurance risk model with stochastic volatility

**Folder:** `chi-jaimungal-lin-2010` · [metadata](../content/publication/chi-jaimungal-lin-2010/index.md) · [citation](../content/publication/chi-jaimungal-lin-2010/cite.bib)

**Current record:** *Insurance: Mathematics and Economics*, 2010-02-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S0167668709000365).

- date: 2010-01-01 → 2010-02-01
- doi: https://doi.org/10.1016/j.insmatheco.2009.03.006 → 10.1016/j.insmatheco.2009.03.006
- PDF URL: https://papers.ssrn.com/sol3/Delivery.cfm/SSRN_ID1370482_code879537.pdf?abstractid=1316223&mirid=1
- Links: added or corrected URL/manuscript buttons.
- Citation title: An insurance risk model with stochastic volatility → {An insurance risk model with stochastic volatility}
- Citation pages: 52-66 → 52--66
- Citation doi: https://doi.org/10.1016/j.insmatheco.2009.03.006 → 10.1016/j.insmatheco.2009.03.006
- Citation url: None → https://www.sciencedirect.com/science/article/pii/S0167668709000365

- authors: ['Yichun Chi', 'Sebastian Jaimungal', 'X. Sheldon Lin'] → ['Yichun Chi', 'Sebastian Jaimungal', 'Sheldon Lin']
- Author profile links: X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** User added a published journal PDF, chi-jaimungal-lin-2010.pdf. Verified the paper identity, matching DOI, and successful PDF parsing. PDF buttons on the publication page and publications list link to the local file; the built copy is byte-for-byte identical.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0167668709000365), [source 2](https://api.crossref.org/works/10.1016/j.insmatheco.2009.03.006), [source 3](https://papers.ssrn.com/sol3/Delivery.cfm/SSRN_ID1370482_code879537.pdf?abstractid=1316223&mirid=1).

### 23 On the threshold dividend strategy for a generalized jump–diffusion risk model

**Folder:** `chi-lin-2011` · [metadata](../content/publication/chi-lin-2011/index.md) · [citation](../content/publication/chi-lin-2011/cite.bib)

**Current record:** *Insurance: Mathematics and Economics*, 2011-05-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S0167668710001332).

- date: 2011-01-01 → 2011-05-01
- doi: https://doi.org/10.1016/j.insmatheco.2010.11.006 → 10.1016/j.insmatheco.2010.11.006
- Links: added or corrected URL/manuscript buttons.
- Citation title: On the threshold dividend strategy for a generalized jump–diffusion risk model → {On the threshold dividend strategy for a generalized jump–diffusion risk model}
- Citation pages: 326-337 → 326--337
- Citation doi: https://doi.org/10.1016/j.insmatheco.2010.11.006 → 10.1016/j.insmatheco.2010.11.006
- Citation url: None → https://www.sciencedirect.com/science/article/pii/S0167668710001332

- authors: ['Yichun Chi', 'X. Sheldon Lin'] → ['Yichun Chi', 'Sheldon Lin']
- Author profile links: X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** User added a published journal PDF, chi-lin-2011.pdf. Verified the paper identity, matching DOI, and successful PDF parsing. PDF buttons on the publication page and publications list link to the local file; the built copy is byte-for-byte identical.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0167668710001332), [source 2](https://api.crossref.org/works/10.1016/j.insmatheco.2010.11.006).

### 24 Are Flexible Premium Variable Annuities Under-Priced?

**Folder:** `chi-lin-2012` · [metadata](../content/publication/chi-lin-2012/index.md) · [citation](../content/publication/chi-lin-2012/cite.bib)

**Current record:** *ASTIN Bulletin*, 2012-11-01. [Publication source](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/are-flexible-premium-variable-annuities-underpriced/AB6E9E20847119B25A680DA8CD57A8EE).

- date: 2012-01-01 → 2012-11-01
- PDF URL: https://www.cambridge.org/core/services/aop-cambridge-core/content/view/AB6E9E20847119B25A680DA8CD57A8EE/S0515036100001197a.pdf/div-class-title-are-flexible-premium-variable-annuities-under-priced-div.pdf
- Links: added or corrected URL/manuscript buttons.
- Citation title: Are Flexible Premium Variable Annuities Under-Priced? → {Are Flexible Premium Variable Annuities Under-Priced?}
- Citation pages: 559–574 → 559--574
- Citation url: None → https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/are-flexible-premium-variable-annuities-underpriced/AB6E9E20847119B25A680DA8CD57A8EE

- authors: ['Yichun Chi', 'X. Sheldon Lin'] → ['Yichun Chi', 'Sheldon Lin']
- Author profile links: X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** User added a published journal PDF, chi-lin-2012.pdf. Verified the paper identity, matching DOI, and successful PDF parsing. PDF buttons on the publication page and publications list link to the local file; the built copy is byte-for-byte identical.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/are-flexible-premium-variable-annuities-underpriced/AB6E9E20847119B25A680DA8CD57A8EE), [source 2](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/AB6E9E20847119B25A680DA8CD57A8EE/S0515036100001197a.pdf/div-class-title-are-flexible-premium-variable-annuities-under-priced-div.pdf).

### 25 Optimal reinsurance with limited ceded risk — A stochastic dominance approach

**Folder:** `chi-lin-2014` · [metadata](../content/publication/chi-lin-2014/index.md) · [citation](../content/publication/chi-lin-2014/cite.bib)

**Current record:** *ASTIN Bulletin*, 2014-01-01. [Publication source](https://www.cambridge.org/core/product/identifier/S0515036113000287/type/journal_article).

- PDF URL: https://www.cambridge.org/core/services/aop-cambridge-core/content/view/S0515036113000287
- Links: added or corrected URL/manuscript buttons.
- Citation title: Optimal reinsurance with limited ceded risk: A stochastic dominance approach → {Optimal reinsurance with limited ceded risk: A stochastic dominance approach}
- Citation pages: 103–126 → 103--126
- Citation url: None → https://www.cambridge.org/core/product/identifier/S0515036113000287/type/journal_article

- authors: ['Yichun Chi', 'X. Sheldon Lin'] → ['Yichun Chi', 'Sheldon Lin']
- Author profile links: X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Added external PDF endpoint; no file downloaded. Verified HTTP 200 and Content-Type application/pdf.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/product/identifier/S0515036113000287/type/journal_article), [source 2](https://api.crossref.org/works/10.1017/asb.2013.28), [source 3](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/S0515036113000287).

### 26 Optimal Reinsurance Under the Risk-Adjusted Value of an Insurer’s Liability and an Economic Reinsurance Premium Principle

**Folder:** `chi-lin-tan-2017` · [metadata](../content/publication/chi-lin-tan-2017/index.md) · [citation](../content/publication/chi-lin-tan-2017/cite.bib)

**Current record:** *North American Actuarial Journal*, 2017-07-03. [Publication source](https://www.tandfonline.com/doi/full/10.1080/10920277.2017.1302346).

- date: 2017-01-01 → 2017-07-03
- PDF URL: https://www.tandfonline.com/doi/pdf/10.1080/10920277.2017.1302346
- Links: added or corrected URL/manuscript buttons.
- Citation title: Optimal Reinsurance Under the Risk-Adjusted Value of an Insurer’s Liability and an Economic Reinsurance Premium Principle → {Optimal Reinsurance Under the Risk-Adjusted Value of an Insurer’s Liability and an Economic Reinsurance Premium Principle}
- Citation pages: 417-432 → 417--432
- Citation url: None → https://www.tandfonline.com/doi/full/10.1080/10920277.2017.1302346
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.

- authors: ['Yichun Chi', 'X. Sheldon Lin', 'Ken Seng Tan'] → ['Yichun Chi', 'Sheldon Lin', 'Ken Seng Tan']
- Author profile links: X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** User added a published journal PDF, chi-lin-tan-2017.pdf. Verified the paper identity, matching DOI, and successful PDF parsing. PDF buttons on the publication page and publications list link to the local file; the built copy is byte-for-byte identical.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.tandfonline.com/doi/full/10.1080/10920277.2017.1302346), [source 2](https://api.crossref.org/works/10.1080/10920277.2017.1302346), [source 3](https://www.tandfonline.com/doi/pdf/10.1080/10920277.2017.1302346).

### 27 Risk budgeting portfolios from simulations

**Folder:** `dacosta-pesenti-targino-2021` · [metadata](../content/publication/dacosta-pesenti-targino-2021/index.md) · [citation](../content/publication/dacosta-pesenti-targino-2021/cite.bib)

**Current record:** *European Journal of Operational Research*, 2023-12-16. [Publication source](https://www.sciencedirect.com/science/article/pii/S0377221723004277).

- title: Risk Budgeting Portfolios from Simulations → Risk budgeting portfolios from simulations
- date: 2023-01-01 → 2023-12-16
- doi: https://doi.org/10.1016/j.ejor.2023.06.003 → 10.1016/j.ejor.2023.06.003
- PDF URL: https://arxiv.org/pdf/2302.01196
- Links: added or corrected URL/manuscript buttons.
- Citation title: Risk Budgeting Portfolios from Simulations → {Risk budgeting portfolios from simulations}
- Citation author: B. Freitas Paulo da Costa and Silvana M. Pesenti and Rodrigo S. Targino → da Costa, Bernardo Freitas Paulo and Pesenti, Silvana M. and Targino, Rodrigo S.
- Citation pages: 1040-1056 → 1040--1056
- Citation doi: https://doi.org/10.1016/j.ejor.2023.06.003 → 10.1016/j.ejor.2023.06.003
- Citation url: https://www.sciencedirect.com/science/article/pii/S0377221723004277 → https://doi.org/10.1016/j.ejor.2023.06.003
- Note: BibTeX author: B. Freitas Paulo da Costa → da Costa, Bernardo Freitas Paulo (full author name verified on arXiv; surname explicitly delimited).

- authors: ['B. Freitas Paulo da Costa', 'Silvana M. Pesenti', 'Rodrigo S. Targino'] → ['B. Freitas Paulo da Costa', 'Silvana Pesenti', 'Rodrigo S. Targino']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** PDF button links to arXiv manuscript; published PDF requires publisher access.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0377221723004277), [source 2](https://arxiv.org/abs/2302.01196).

### 28 Sensitivity measures based on scoring functions

**Folder:** `fissler-pesenti-2022` · [metadata](../content/publication/fissler-pesenti-2022/index.md) · [citation](../content/publication/fissler-pesenti-2022/cite.bib)

**Current record:** *European Journal of Operational Research*, 2023-06-16. [Publication source](https://www.sciencedirect.com/science/article/pii/S0377221722007718).

- date: 2023-01-01 → 2023-06-16
- doi: https://doi.org/10.1016/j.ejor.2022.10.002 → 10.1016/j.ejor.2022.10.002
- PDF URL: https://arxiv.org/pdf/2203.00460
- Links: added or corrected URL/manuscript buttons.
- Citation title: Sensitivity measures based on scoring functions → {Sensitivity measures based on scoring functions}
- Citation pages: 1408-1423 → 1408--1423
- Citation doi: https://doi.org/10.1016/j.ejor.2022.10.002 → 10.1016/j.ejor.2022.10.002
- Citation url: https://www.sciencedirect.com/science/article/pii/S0377221722007718 → https://doi.org/10.1016/j.ejor.2022.10.002
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: Abstract formatting/text: functional T of → functional $T$ of
- Note: Abstract formatting/text: consistent for T. → consistent for $T$.

- authors: ['Tobias Fissler', 'Silvana M. Pesenti'] → ['Tobias Fissler', 'Silvana Pesenti']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** PDF button links to arXiv manuscript; published PDF is available through ScienceDirect.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0377221722007718), [source 2](https://arxiv.org/abs/2203.00460).

### 29 A class of mixture of experts models for general insurance — application to correlated claim frequencies

**Folder:** `fung-badescu-lin-2019` · [metadata](../content/publication/fung-badescu-lin-2019/index.md) · [citation](../content/publication/fung-badescu-lin-2019/cite.bib)

**Current record:** *ASTIN Bulletin*, 2019-09-01. [Publication source](https://www.cambridge.org/core/product/identifier/S0515036119000254/type/journal_article).

- date: 2019-01-01 → 2019-09-01
- Links: added or corrected URL/manuscript buttons.
- Citation title: A class of mixture of experts models for general insurance: application to correlated claim frequencies → {A class of mixture of experts models for general insurance: application to correlated claim frequencies}
- Citation author: Chai Fung, Tsz and Badescu, Andrei L. and Sheldon Lin, X. → Fung, Tsz Chai and Badescu, Andrei L. and Lin, X. Sheldon
- Citation pages: 647–688 → 647--688
- Citation url: None → https://www.cambridge.org/core/product/identifier/S0515036119000254/type/journal_article

- authors: ['Tsz Chai Fung', 'Andrei L. Badescu', 'X. Sheldon Lin'] → ['Samson Fung', 'Andrei Badescu', 'Sheldon Lin']
- Author profile links: Tsz Chai Fung → Samson Fung; Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved: fung-badescu-lin-2019.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/product/identifier/S0515036119000254/type/journal_article), [source 2](https://api.crossref.org/works/10.1017/asb.2019.25).

### 30 A class of mixture of experts models for general insurance — Theoretical developments

**Folder:** `fung-badescu-lin-2019-b` · [metadata](../content/publication/fung-badescu-lin-2019-b/index.md) · [citation](../content/publication/fung-badescu-lin-2019-b/cite.bib)

**Current record:** *Insurance: Mathematics and Economics*, 2019-11-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S0167668719303956).

- date: 2019-01-01 → 2019-11-01
- doi: https://doi.org/10.1016/j.insmatheco.2019.09.007 → 10.1016/j.insmatheco.2019.09.007
- Links: added or corrected URL/manuscript buttons.
- Citation title: A class of mixture of experts models for general insurance: Theoretical developments → {A class of mixture of experts models for general insurance: Theoretical developments}
- Citation pages: 111-127 → 111--127
- Citation doi: https://doi.org/10.1016/j.insmatheco.2019.09.007 → 10.1016/j.insmatheco.2019.09.007
- Citation url: None → https://www.sciencedirect.com/science/article/pii/S0167668719303956

- authors: ['Tsz Chai Fung', 'Andrei L. Badescu', 'X. Sheldon Lin'] → ['Samson Fung', 'Andrei Badescu', 'Sheldon Lin']
- Author profile links: Tsz Chai Fung → Samson Fung; Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved: fung-badescu-lin-2019-b.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0167668719303956), [source 2](https://api.crossref.org/works/10.1016/j.insmatheco.2019.09.007).

### 31 Multivariate Cox Hidden Markov models with an application to operational risk

**Folder:** `fung-badescu-lin-2019-c` · [metadata](../content/publication/fung-badescu-lin-2019-c/index.md) · [citation](../content/publication/fung-badescu-lin-2019-c/cite.bib)

**Current record:** *Scandinavian Actuarial Journal*, 2019-09-14. [Publication source](https://www.tandfonline.com/doi/full/10.1080/03461238.2019.1598482).

- date: 2019-01-01 → 2019-09-14
- Links: added or corrected URL/manuscript buttons.
- Citation title: Multivariate Cox Hidden Markov models with an application to operational risk → {Multivariate Cox Hidden Markov models with an application to operational risk}
- Citation pages: 686-710 → 686--710
- Citation url: None → https://www.tandfonline.com/doi/full/10.1080/03461238.2019.1598482
- Citation publisher: Taylor & Francis → Taylor \& Francis
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.

- authors: ['Tsz Chai Fung', 'Andrei L. Badescu', 'X. Sheldon Lin'] → ['Samson Fung', 'Andrei Badescu', 'Sheldon Lin']
- Author profile links: Tsz Chai Fung → Samson Fung; Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved: fung-badescu-lin-2019-c.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.tandfonline.com/doi/full/10.1080/03461238.2019.1598482), [source 2](https://api.crossref.org/works/10.1080/03461238.2019.1598482).

### 32 A New Class of Severity Regression Models with an Application to IBNR Prediction

**Folder:** `fung-badescu-lin-2021` · [metadata](../content/publication/fung-badescu-lin-2021/index.md) · [citation](../content/publication/fung-badescu-lin-2021/cite.bib)

**Current record:** *North American Actuarial Journal*, 2021-04-03. [Publication source](https://www.tandfonline.com/doi/full/10.1080/10920277.2020.1729813).

- date: 2021-01-01 → 2021-04-03
- Links: added or corrected URL/manuscript buttons.
- Citation title: A New Class of Severity Regression Models with an Application to IBNR Prediction → {A New Class of Severity Regression Models with an Application to IBNR Prediction}
- Citation pages: 206-231 → 206--231
- Citation url: None → https://www.tandfonline.com/doi/full/10.1080/10920277.2020.1729813
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.

- authors: ['Tsz Chai Fung', 'Andrei L. Badescu', 'X. Sheldon Lin'] → ['Samson Fung', 'Andrei Badescu', 'Sheldon Lin']
- Author profile links: Tsz Chai Fung → Samson Fung; Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved: fung-badescu-lin-2021.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.tandfonline.com/doi/full/10.1080/10920277.2020.1729813), [source 2](https://api.crossref.org/works/10.1080/10920277.2020.1729813).

### 33 Fitting Censored and Truncated Regression Data Using the Mixture of Experts Models

**Folder:** `fung-badescu-lin-2022` · [metadata](../content/publication/fung-badescu-lin-2022/index.md) · [citation](../content/publication/fung-badescu-lin-2022/cite.bib)

**Current record:** *North American Actuarial Journal*, 2022-10-02. [Publication source](https://www.tandfonline.com/doi/full/10.1080/10920277.2021.2013896).

- date: 2022-01-01 → 2022-10-02
- Links: added or corrected URL/manuscript buttons.
- Citation title: Fitting Censored and Truncated Regression Data Using the Mixture of Experts Models → {Fitting Censored and Truncated Regression Data Using the Mixture of Experts Models}
- Citation volume: 0 → 26
- Citation number: 0 → 4
- Citation pages: 1-25 → 496--520
- Citation url: None → https://www.tandfonline.com/doi/full/10.1080/10920277.2021.2013896
- Citation eprint: https://doi.org/10.1080/10920277.2021.2013896 → None
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.

- authors: ['Tsz Chai Fung', 'Andrei L. Badescu', 'X. Sheldon Lin'] → ['Samson Fung', 'Andrei Badescu', 'Sheldon Lin']
- Author profile links: Tsz Chai Fung → Samson Fung; Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved: fung-badescu-lin-2022.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.tandfonline.com/doi/full/10.1080/10920277.2021.2013896), [source 2](https://api.crossref.org/works/10.1080/10920277.2021.2013896).

### 34 Mixture of experts models for multilevel data — Modeling framework and approximation theory

**Folder:** `fung-tseung-2025` · [metadata](../content/publication/fung-tseung-2025/index.md) · [citation](../content/publication/fung-tseung-2025/cite.bib)

**Current record:** *Neurocomputing*, 2025-04-14. [Publication source](https://www.sciencedirect.com/science/article/pii/S0925231225000293).

- date: 2025-01-01 → 2025-04-14
- doi: https://doi.org/10.1016/j.neucom.2025.129357 → 10.1016/j.neucom.2025.129357
- Citation title: Mixture of experts models for multilevel data: Modeling framework and approximation theory → {Mixture of experts models for multilevel data: Modeling framework and approximation theory}
- Citation doi: https://doi.org/10.1016/j.neucom.2025.129357 → 10.1016/j.neucom.2025.129357

- authors: ['Tsz Chai Fung', 'Spark C. Tseung'] → ['Samson Fung', 'Spark Tseung']
- Author profile links: Tsz Chai Fung → Samson Fung; Spark C. Tseung → Spark Tseung. Published names remain in the citation.

**PDF:** Existing local PDF preserved: fung-tseung-2025.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0925231225000293), [source 2](https://api.crossref.org/works/10.1016/j.neucom.2025.129357).

### 35 Fitting the Erlang mixture model to data via a GEM-CMM algorithm

**Folder:** `gui-huang-lin-2018` · [metadata](../content/publication/gui-huang-lin-2018/index.md) · [citation](../content/publication/gui-huang-lin-2018/cite.bib)

**Current record:** *Journal of Computational and Applied Mathematics*, 2018-12-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S0377042718302140).

- date: 2018-01-01 → 2018-12-01
- doi: https://doi.org/10.1016/j.cam.2018.04.032 → 10.1016/j.cam.2018.04.032
- Links: added or corrected URL/manuscript buttons.
- Citation title: Fitting the Erlang mixture model to data via a GEM-CMM algorithm → {Fitting the Erlang mixture model to data via a GEM-CMM algorithm}
- Citation pages: 189-205 → 189--205
- Citation doi: https://doi.org/10.1016/j.cam.2018.04.032 → 10.1016/j.cam.2018.04.032
- Citation url: None → https://www.sciencedirect.com/science/article/pii/S0377042718302140

- authors: ['Wenyong Gui', 'Rongtan Huang', 'X. Sheldon Lin'] → ['Wenyong Gui', 'Rongtan Huang', 'Sheldon Lin']
- Author profile links: X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved: gui-huang-lin-2018.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0377042718302140), [source 2](https://api.crossref.org/works/10.1016/j.cam.2018.04.032).

### 36 Fitting multivariate Erlang mixtures to data — A roughness penalty approach

**Folder:** `gui-huang-lin-2021` · [metadata](../content/publication/gui-huang-lin-2021/index.md) · [citation](../content/publication/gui-huang-lin-2021/cite.bib)

**Current record:** *Journal of Computational and Applied Mathematics*, 2021-04-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S0377042720305070).

- date: 2021-01-01 → 2021-04-01
- doi: https://doi.org/10.1016/j.cam.2020.113216 → 10.1016/j.cam.2020.113216
- Links: added or corrected URL/manuscript buttons.
- Citation title: Fitting multivariate Erlang mixtures to data: A roughness penalty approach → {Fitting multivariate Erlang mixtures to data: A roughness penalty approach}
- Citation doi: https://doi.org/10.1016/j.cam.2020.113216 → 10.1016/j.cam.2020.113216
- Citation url: None → https://www.sciencedirect.com/science/article/pii/S0377042720305070

- authors: ['Wenyong Gui', 'Rongtan Huang', 'X. Sheldon Lin'] → ['Wenyong Gui', 'Rongtan Huang', 'Sheldon Lin']
- Author profile links: X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved: gui-huang-lin-2021.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0377042720305070), [source 2](https://api.crossref.org/works/10.1016/j.cam.2020.113216).

### 37 Risk contributions of lambda quantiles

**Folder:** `ince-peri-pesenti-2021` · [metadata](../content/publication/ince-peri-pesenti-2021/index.md) · [citation](../content/publication/ince-peri-pesenti-2021/cite.bib)

**Current record:** *Quantitative Finance*, 2022-10-01. [Publication source](https://www.tandfonline.com/doi/10.1080/14697688.2022.2092543).

- title: Risk contributions of lambda quantiles* → Risk contributions of lambda quantiles
- date: 2022-01-01 → 2022-10-01
- PDF URL: https://arxiv.org/pdf/2106.14824
- Citation title: Risk contributions of lambda quantiles* → {Risk contributions of lambda quantiles}

**PDF:** PDF button links to arXiv manuscript. Removed title footnote asterisk; this is not part of the title.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.tandfonline.com/doi/10.1080/14697688.2022.2092543), [source 2](https://www.tandfonline.com/toc/rquf20/22/10), [source 3](https://arxiv.org/abs/2106.14824).

### 38 Risk Budgeting Allocation for Dynamic Risk Measures

**Folder:** `jaimungal-pesenti-saporito-targino-2023` · [metadata](../content/publication/jaimungal-pesenti-saporito-targino-2023/index.md) · [citation](../content/publication/jaimungal-pesenti-saporito-targino-2023/cite.bib)

**Current record:** *Operations Research*, 2025-05-01. [Publication source](https://pubsonline.informs.org/doi/10.1287/opre.2023.0299).

- date: 2023-01-01 → 2025-05-01
- publication: *Available at SSRN 4452742* → *Operations Research*
- doi: None → 10.1287/opre.2023.0299
- PDF URL: https://arxiv.org/pdf/2305.11319
- Links: added or corrected URL/manuscript buttons.
- Citation title: Risk Budgeting Allocation for Dynamic Risk Measures → {Risk Budgeting Allocation for Dynamic Risk Measures}
- Citation author: Jaimungal, Sebastian and Pesenti, Silvana M and Saporito, Yuri F and Targino, Rodrigo S → Pesenti, Silvana M. and Jaimungal, Sebastian and Saporito, Yuri F. and Targino, Rodrigo S.
- Citation journal: Available at SSRN 4452742 → Operations Research
- Citation volume: None → 73
- Citation number: None → 3
- Citation pages: None → 1208--1229
- Citation year: 2023 → 2025
- Citation doi: None → 10.1287/opre.2023.0299
- Citation url: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4452742 → https://doi.org/10.1287/opre.2023.0299
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: links: - name: URL   url: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4452742 → links:  - name: URL   url: https://doi.org/10.1287/opre.2023.0299
- Note: Abstract: replaced outdated preprint wording with the published abstract.
- Note: BibTeX url = {https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4452742}, → url = {https://doi.org/10.1287/opre.2023.0299},

- authors: ['Sebastian Jaimungal', 'Silvana M Pesenti', 'Yuri F Saporito', 'Rodrigo S Targino'] → ['Silvana Pesenti', 'Sebastian Jaimungal', 'Yuri F. Saporito', 'Rodrigo S. Targino']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** User added a published journal PDF, jaimungal-pesenti-saporito-targino-2023.pdf. Verified the paper identity, matching DOI, and successful PDF parsing. PDF buttons on the publication page and publications list link to the local file; the built copy is byte-for-byte identical.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://pubsonline.informs.org/doi/10.1287/opre.2023.0299), [source 2](https://arxiv.org/abs/2305.11319).

### 39 Robust Risk-Aware Reinforcement Learning

**Folder:** `jaimungal-pesenti-wang-tatsat-2022` · [metadata](../content/publication/jaimungal-pesenti-wang-tatsat-2022/index.md) · [citation](../content/publication/jaimungal-pesenti-wang-tatsat-2022/cite.bib)

**Current record:** *SIAM Journal on Financial Mathematics*, 2022-03-01. [Publication source](https://epubs.siam.org/doi/10.1137/21M144640X).

- date: 2022-01-01 → 2022-03-01
- PDF URL: https://arxiv.org/pdf/2108.10403
- Links: added or corrected URL/manuscript buttons.
- Citation title: Robust Risk-Aware Reinforcement Learning → {Robust Risk-Aware Reinforcement Learning}
- Citation pages: 213-226 → 213--226
- Citation url: None → https://doi.org/10.1137/21M144640X

- authors: ['Sebastian Jaimungal', 'Silvana M. Pesenti', 'Ye Sheng Wang', 'Hariom Tatsat'] → ['Sebastian Jaimungal', 'Silvana Pesenti', 'Ye Sheng Wang', 'Hariom Tatsat']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** PDF button links to arXiv manuscript; published PDF requires SIAM access.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://epubs.siam.org/doi/10.1137/21M144640X), [source 2](https://arxiv.org/abs/2108.10403).

### 40 Optimal robust reinsurance with multiple insurers

**Folder:** `kroell-jaimungal-pesenti-2023` · [metadata](../content/publication/kroell-jaimungal-pesenti-2023/index.md) · [citation](../content/publication/kroell-jaimungal-pesenti-2023/cite.bib)

**Current record:** *Scandinavian Actuarial Journal*, 2025-05-01. [Publication source](https://www.tandfonline.com/doi/10.1080/03461238.2024.2431539).

- title: Optimal Robust Reinsurance with Multiple Insurers → Optimal robust reinsurance with multiple insurers
- date: 2023-01-01 → 2025-05-01
- publication: *Available at SSRN 4548858* → *Scandinavian Actuarial Journal*
- doi: None → 10.1080/03461238.2024.2431539
- PDF URL: https://arxiv.org/pdf/2308.11828
- Links: added or corrected URL/manuscript buttons.
- Citation title: Optimal Robust Reinsurance with Multiple Insurers → {Optimal robust reinsurance with multiple insurers}
- Citation author: Kroell, Emma and Jaimungal, Sebastian and Pesenti, Silvana M → Kroell, Emma and Jaimungal, Sebastian and Pesenti, Silvana M.
- Citation journal: Available at SSRN 4548858 → Scandinavian Actuarial Journal
- Citation volume: None → 2025
- Citation number: None → 5
- Citation pages: None → 479--509
- Citation year: 2023 → 2025
- Citation doi: None → 10.1080/03461238.2024.2431539
- Citation url: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4548858 → https://doi.org/10.1080/03461238.2024.2431539
- Note: links: - name: URL   url: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4548858 → links:  - name: URL   url: https://doi.org/10.1080/03461238.2024.2431539
- Note: BibTeX url = {https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4548858}, → url = {https://doi.org/10.1080/03461238.2024.2431539},

- authors: ['Emma Kroell', 'Sebastian Jaimungal', 'Silvana M Pesenti'] → ['Emma Kroell', 'Sebastian Jaimungal', 'Silvana Pesenti']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** User added a published journal PDF, kroell-jaimungal-pesenti-2023.pdf. Verified the paper identity, matching DOI, and successful PDF parsing. PDF buttons on the publication page and publications list link to the local file; the built copy is byte-for-byte identical.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.tandfonline.com/doi/10.1080/03461238.2024.2431539), [source 2](https://www.tandfonline.com/toc/sact20/2025/5), [source 3](https://arxiv.org/abs/2308.11828).

### 41 Stressing dynamic loss models

**Folder:** `kroell-pesenti-jaimungal-2023` · [metadata](../content/publication/kroell-pesenti-jaimungal-2023/index.md) · [citation](../content/publication/kroell-pesenti-jaimungal-2023/cite.bib)

**Current record:** *Insurance: Mathematics and Economics*, 2024-01-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S0167668723000975).

- doi: https://doi.org/10.1016/j.insmatheco.2023.11.002 → 10.1016/j.insmatheco.2023.11.002
- PDF URL: https://arxiv.org/pdf/2211.03221
- Links: added or corrected URL/manuscript buttons.
- Citation title: Stressing dynamic loss models → {Stressing dynamic loss models}
- Citation pages: 56-78 → 56--78
- Citation doi: https://doi.org/10.1016/j.insmatheco.2023.11.002 → 10.1016/j.insmatheco.2023.11.002
- Citation url: https://www.sciencedirect.com/science/article/pii/S0167668723000975 → https://doi.org/10.1016/j.insmatheco.2023.11.002

- authors: ['Emma Kroell', 'Silvana M. Pesenti', 'Sebastian Jaimungal'] → ['Emma Kroell', 'Silvana Pesenti', 'Sebastian Jaimungal']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** PDF button links to arXiv manuscript; published PDF is available through ScienceDirect.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0167668723000975), [source 2](https://arxiv.org/abs/2211.03221).

### 42 A portfolio-anchored frequency–severity behavioral risk index for trip and driver assessment using telematics signals

**Folder:** `lee-badescu-lin-2026` · [metadata](../content/publication/lee-badescu-lin-2026/index.md) · [citation](../content/publication/lee-badescu-lin-2026/cite.bib)

**Current record:** *ASTIN Bulletin*, 2026-09-01. [Publication source](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/portfolioanchored-frequencyseverity-behavioral-risk-index-for-trip-and-driver-assessment-using-telematics-signals/B126D1D692B1F4162C7F8D18FDAB9A63).

- date: 2026-07-30 → 2026-09-01
- publication: ASTIN Bulletin → *ASTIN Bulletin*
- Links: added or corrected URL/manuscript buttons.
- Citation title: A Portfolio-Anchored Frequency–Severity Risk Index for Trip and Driver Assessment Using Telematics Signals → {A portfolio-anchored frequency–severity behavioral risk index for trip and driver assessment using telematics signals}
- Citation journal:  → ASTIN Bulletin
- Citation volume: 0 → 56
- Citation number:  → 3
- Citation pages:  → 613--638
- Citation doi: 10.48550/arXiv.2603.15839 → 10.1017/asb.2026.10112
- Citation url: None → https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/portfolioanchored-frequencyseverity-behavioral-risk-index-for-trip-and-driver-assessment-using-telematics-signals/B126D1D692B1F4162C7F8D18FDAB9A63
- Citation eprint: https://arxiv.org/abs/2603.15839 → None
- Citation publisher:  → Cambridge University Press (CUP)
- Citation note: None → First published online 2026-07-30
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: Issue date supplied to month precision; day 01 is a sorting convention, not a claimed publication day.
- Note: cite.bib replaced preprint DOI/title/abstract and empty fields with journal version 56(3):613–638; local PDF already matches the published version.
- Note: Abstract font: restored publisher monospace labels normal, aggressive, drowsy and risky; citation uses \texttt{} instead of HTML.

- authors: ['Jongtaek Lee', 'Andrei L. Badescu', 'X. Sheldon Lin'] → ['Jongtaek Lee', 'Andrei Badescu', 'Sheldon Lin']
- Author profile links: Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF is a publisher-formatted article and has been preserved.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/portfolioanchored-frequencyseverity-behavioral-risk-index-for-trip-and-driver-assessment-using-telematics-signals/B126D1D692B1F4162C7F8D18FDAB9A63), [source 2](https://api.crossref.org/works/10.1017/asb.2026.10112).

### 43 Delta Boosting Machine with Application to General Insurance

**Folder:** `lee-lin-2018` · [metadata](../content/publication/lee-lin-2018/index.md) · [citation](../content/publication/lee-lin-2018/cite.bib)

**Current record:** *North American Actuarial Journal*, 2018-07-03. [Publication source](https://www.tandfonline.com/doi/full/10.1080/10920277.2018.1431131).

- date: 2018-01-01 → 2018-07-03
- Links: added or corrected URL/manuscript buttons.
- Citation title: Delta Boosting Machine with Application to General Insurance → {Delta Boosting Machine with Application to General Insurance}
- Citation pages: 405-425 → 405--425
- Citation url: None → https://www.tandfonline.com/doi/full/10.1080/10920277.2018.1431131
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.

**PDF:** Existing local PDF preserved: lee-lin-2018.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.tandfonline.com/doi/full/10.1080/10920277.2018.1431131), [source 2](https://api.crossref.org/works/10.1080/10920277.2018.1431131).

### 44 Efficient dynamic hedging for large variable annuity portfolios with multiple underlying assets

**Folder:** `lin-yang-2020` · [metadata](../content/publication/lin-yang-2020/index.md) · [citation](../content/publication/lin-yang-2020/cite.bib)

**Current record:** *ASTIN Bulletin*, 2020-09-01. [Publication source](https://www.cambridge.org/core/product/identifier/S0515036120000264/type/journal_article).

- date: 2020-01-01 → 2020-09-01
- Links: added or corrected URL/manuscript buttons.
- Citation title: Efficient dynamic hedging for large variable annuity portfolios with multiple underlying assets → {Efficient dynamic hedging for large variable annuity portfolios with multiple underlying assets}
- Citation pages: 913–957 → 913--957
- Citation url: None → https://www.cambridge.org/core/product/identifier/S0515036120000264/type/journal_article
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: Replace older, truncated abstract with final publisher abstract, including missing final sentence and italic journal / bold volume in embedded citation.
- Note: Synchronize final publisher abstract and use LaTeX formatting in BibTeX.

- authors: ['X. Sheldon Lin', 'Shuai Yang'] → ['Sheldon Lin', 'Alex Yang']
- Author profile links: X. Sheldon Lin → Sheldon Lin; Shuai Yang → Alex Yang. Published names remain in the citation.

**PDF:** Existing local PDF preserved: lin-yang-2020.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/product/identifier/S0515036120000264/type/journal_article), [source 2](https://api.crossref.org/works/10.1017/asb.2020.26).

### 45 Fast and efficient nested simulation for large variable annuity portfolios — A surrogate modeling approach

**Folder:** `lin-yang-2020-b` · [metadata](../content/publication/lin-yang-2020-b/index.md) · [citation](../content/publication/lin-yang-2020-b/cite.bib)

**Current record:** *Insurance: Mathematics and Economics*, 2020-03-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S0167668720300020).

- date: 2020-01-01 → 2020-03-01
- doi: https://doi.org/10.1016/j.insmatheco.2020.01.002 → 10.1016/j.insmatheco.2020.01.002
- Links: added or corrected URL/manuscript buttons.
- Citation title: Fast and efficient nested simulation for large variable annuity portfolios: A surrogate modeling approach → {Fast and efficient nested simulation for large variable annuity portfolios: A surrogate modeling approach}
- Citation pages: 85-103 → 85--103
- Citation doi: https://doi.org/10.1016/j.insmatheco.2020.01.002 → 10.1016/j.insmatheco.2020.01.002
- Citation url: None → https://www.sciencedirect.com/science/article/pii/S0167668720300020

- authors: ['X. Sheldon Lin', 'Shuai Yang'] → ['Sheldon Lin', 'Alex Yang']
- Author profile links: X. Sheldon Lin → Sheldon Lin; Shuai Yang → Alex Yang. Published names remain in the citation.

**PDF:** Existing local PDF preserved: lin-yang-2020-b.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0167668720300020), [source 2](https://api.crossref.org/works/10.1016/j.insmatheco.2020.01.002).

### 46 Robust elicitable functionals

**Folder:** `miao-pesenti-2025` · [metadata](../content/publication/miao-pesenti-2025/index.md) · [citation](../content/publication/miao-pesenti-2025/cite.bib)

**Current record:** *European Journal of Operational Research*, 2025-10-16. [Publication source](https://www.sciencedirect.com/science/article/pii/S037722172500267X).

- date: 2025-09-14 → 2025-10-16
- doi: None → 10.1016/j.ejor.2025.04.017
- Links: added or corrected URL/manuscript buttons.
- Citation title: Robust elicitable functionals → {Robust elicitable functionals}
- Citation author: Miao, Kathleen E and Pesenti, Silvana M → Miao, Kathleen E. and Pesenti, Silvana M.
- Citation journal: None → European Journal of Operational Research
- Citation volume: None → 326
- Citation number: None → 2
- Citation pages: None → 311--325
- Citation doi: None → 10.1016/j.ejor.2025.04.017
- Citation url: https://www.sciencedirect.com/science/article/pii/S037722172500267X?via=ihub → https://www.sciencedirect.com/science/article/pii/S037722172500267X
- Citation publisher: European Journal of Operational Research → Elsevier BV
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: Abstract: corrected typography/spacing while preserving source wording.

- Author profile links: Kathleen E. Miao → Kathleen Miao; Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** Existing local PDF is a publisher-formatted article and has been preserved.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S037722172500267X), [source 2](https://api.crossref.org/works/10.1016/j.ejor.2025.04.017).

### 47 Discrimination-insensitive pricing

**Folder:** `miao-pesenti-2026` · [metadata](../content/publication/miao-pesenti-2026/index.md) · [citation](../content/publication/miao-pesenti-2026/cite.bib)

**Current record:** *arXiv preprint arXiv:2603.16720*, 2026-03-17. [Publication source](https://arxiv.org/abs/2603.16720).

- date: 2026-03-27 → 2026-03-17
- publication_types: ['2'] → ['3']
- publication: *arXiv* → *arXiv preprint arXiv:2603.16720*
- Links: added or corrected URL/manuscript buttons.
- Citation citation_key: lee_badescu_lin_2026 → miao_pesenti_2026
- Citation entry_type: article → misc
- Citation title: Discrimination-insensitive pricing → {Discrimination-insensitive pricing}
- Citation journal:  → None
- Citation volume: 0 → None
- Citation number:  → None
- Citation pages:  → None
- Citation url: None → https://arxiv.org/abs/2603.16720
- Citation eprint: https://arxiv.org/abs/2603.16720 → 2603.16720
- Citation archivePrefix: None → arXiv
- Citation publisher:  → None
- Citation note: None → Preprint
- Note: publication: "*arXiv*" → "*arXiv preprint arXiv:2603.16720*"
- Note: No journal publication confirmed; preprint date/year uses first arXiv submission, not a later revision.

- Author profile links: Kathleen E. Miao → Kathleen Miao; Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** Existing local PDF preserved; its button is checked in the rebuilt site.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://arxiv.org/abs/2603.16720).

### 48 Uncertainty Propagation and Dynamic Robust Risk Measures

**Folder:** `moresco-mailhot-pesenti-2023` · [metadata](../content/publication/moresco-mailhot-pesenti-2023/index.md) · [citation](../content/publication/moresco-mailhot-pesenti-2023/cite.bib)

**Current record:** *Mathematics of Operations Research*, 2025-08-01. [Publication source](https://pubsonline.informs.org/doi/10.1287/moor.2023.0267).

- date: 2023-01-01 → 2025-08-01
- publication: *Available at SSRN 4551069* → *Mathematics of Operations Research*
- doi: None → 10.1287/moor.2023.0267
- PDF URL: https://arxiv.org/pdf/2308.12856
- Links: added or corrected URL/manuscript buttons.
- Citation title: Uncertainty Propagation and Dynamic Robust Risk Measures → {Uncertainty Propagation and Dynamic Robust Risk Measures}
- Citation author: Moresco, Marlon and Mailhot, Mélina and Pesenti, Silvana → Moresco, Marlon R. and Mailhot, Mélina and Pesenti, Silvana M.
- Citation journal: Available at SSRN 4551069 → Mathematics of Operations Research
- Citation volume: None → 50
- Citation number: None → 3
- Citation pages: None → 1939--1964
- Citation year: 2023 → 2025
- Citation doi: None → 10.1287/moor.2023.0267
- Citation url: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4551069 → https://doi.org/10.1287/moor.2023.0267
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: links: - name: URL   url: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4551069 → links:  - name: URL   url: https://doi.org/10.1287/moor.2023.0267
- Note: Abstract formatting/text: f-divergences → *f*-divergences
- Note: Abstract formatting/text: time-consistency while the Wasserstein → time-consistency whereas the Wasserstein
- Note: BibTeX url = {https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4551069}, → url = {https://doi.org/10.1287/moor.2023.0267},
- Note: BibTeX abstract: use $f$ for mathematical f in f-divergences.

- Author profile links: Marlon R. Moresco → Marlon Moresco; Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** User added a published journal PDF, moresco-mailhot-pesenti-2023.pdf. Verified the paper identity, matching DOI, and successful PDF parsing. PDF buttons on the publication page and publications list link to the local file; the built copy is byte-for-byte identical.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://pubsonline.informs.org/doi/10.1287/moor.2023.0267), [source 2](https://arxiv.org/abs/2308.12856).

### 49 Reverse Sensitivity Analysis for Risk Modelling

**Folder:** `pesenti-2021` · [metadata](../content/publication/pesenti-2021/index.md) · [citation](../content/publication/pesenti-2021/cite.bib)

**Current record:** *Risks*, 2022-07-18. [Publication source](https://www.mdpi.com/2227-9091/10/7/141).

- date: 2022-01-01 → 2022-07-18
- PDF URL: https://www.mdpi.com/2227-9091/10/7/141/pdf
- Links: added or corrected URL/manuscript buttons.
- Citation title: Reverse Sensitivity Analysis for Risk Modelling → {Reverse Sensitivity Analysis for Risk Modelling}
- Citation url: https://www.mdpi.com/2227-9091/10/7/141 → https://doi.org/10.3390/risks10070141
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: Abstract formatting/text: in the R package SWIM on CRAN → in the `R` package `SWIM` on `CRAN`
- Note: BibTeX abstract: retain plain R, SWIM, and CRAN; monospace is page-only.

- authors: ['Silvana M. Pesenti'] → ['Silvana Pesenti']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** PDF button links to the published open-access PDF.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.mdpi.com/2227-9091/10/7/141), [source 2](https://www.mdpi.com/2227-9091/10/7/141/notes).

### 50 Scenario Weights for Importance Measurement (SWIM) – an R package for sensitivity analysis

**Folder:** `pesenti-bettini-millossovich-tsanakas-2021` · [metadata](../content/publication/pesenti-bettini-millossovich-tsanakas-2021/index.md) · [citation](../content/publication/pesenti-bettini-millossovich-tsanakas-2021/cite.bib)

**Current record:** *Annals of Actuarial Science*, 2021-07-01. [Publication source](https://www.cambridge.org/core/journals/annals-of-actuarial-science/article/abs/scenario-weights-for-importance-measurement-swim-an-r-package-for-sensitivity-analysis/85DA03DC399CEB78F8C0EADF41F796D4).

- date: 2021-01-01 → 2021-07-01
- PDF URL: https://openaccess.city.ac.uk/id/eprint/25845/1/SWIM_AAS_Accepted.pdf
- Links: added or corrected URL/manuscript buttons.
- Citation title: Scenario Weights for Importance Measurement (SWIM) – an R package for sensitivity analysis → {Scenario Weights for Importance Measurement ({SWIM}) – an {R} package for sensitivity analysis}
- Citation pages: 458–483 → 458--483
- Citation url: None → https://doi.org/10.1017/S1748499521000130

- authors: ['Silvana M. Pesenti', 'Alberto Bettini', 'Pietro Millossovich', 'Andreas Tsanakas'] → ['Silvana Pesenti', 'Alberto Bettini', 'Pietro Millossovich', 'Andreas Tsanakas']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** PDF button links to institutional accepted manuscript; published PDF requires Cambridge access.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/journals/annals-of-actuarial-science/article/abs/scenario-weights-for-importance-measurement-swim-an-r-package-for-sensitivity-analysis/85DA03DC399CEB78F8C0EADF41F796D4), [source 2](https://openaccess.city.ac.uk/id/eprint/25845/1/SWIM_AAS_Accepted.pdf).

### 51 Portfolio Optimization within a Wasserstein Ball

**Folder:** `pesenti-jaimungal-2021` · [metadata](../content/publication/pesenti-jaimungal-2021/index.md) · [citation](../content/publication/pesenti-jaimungal-2021/cite.bib)

**Current record:** *SIAM Journal on Financial Mathematics*, 2023-12-01. [Publication source](https://epubs.siam.org/doi/10.1137/22M1496803).

- date: 2023-01-01 → 2023-12-01
- PDF URL: https://arxiv.org/pdf/2012.04500
- Citation title: Portfolio Optimization within a Wasserstein Ball → {Portfolio Optimization within a Wasserstein Ball}
- Citation pages: 1175-1214 → 1175--1214

- authors: ['Silvana M. Pesenti', 'Sebastian Jaimungal'] → ['Silvana Pesenti', 'Sebastian Jaimungal']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** PDF button links to arXiv manuscript; published PDF requires SIAM access.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://epubs.siam.org/doi/10.1137/22M1496803), [source 2](https://arxiv.org/abs/2012.04500).

### 52 Robustness regions for measures of risk aggregation

**Folder:** `pesenti-millossovich-tsanakas-2016` · [metadata](../content/publication/pesenti-millossovich-tsanakas-2016/index.md) · [citation](../content/publication/pesenti-millossovich-tsanakas-2016/cite.bib)

**Current record:** *Dependence Modeling*, 2016-01-01. [Publication source](https://arts.units.it/handle/11368/2897183).

- doi: doi:10.1515/demo-2016-0020 → 10.1515/demo-2016-0020
- PDF URL: https://arts.units.it/bitstream/11368/2897183/2/Robustness%20Regions%20for%20Measures%20of%20Risk%20Aggregation.pdf
- Links: added or corrected URL/manuscript buttons.
- Citation title: Robustness regions for measures of risk aggregation → {Robustness regions for measures of risk aggregation}
- Citation pages: 000010151520160020 → 348--367
- Citation doi: doi:10.1515/demo-2016-0020 → 10.1515/demo-2016-0020
- Citation url: None → https://doi.org/10.1515/demo-2016-0020

- authors: ['Silvana M. Pesenti', 'Pietro Millossovich', 'Andreas Tsanakas'] → ['Silvana Pesenti', 'Pietro Millossovich', 'Andreas Tsanakas']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** PDF button links to the published open-access PDF held by University of Trieste.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://arts.units.it/handle/11368/2897183), [source 2](https://arts.units.it/bitstream/11368/2897183/2/Robustness%20Regions%20for%20Measures%20of%20Risk%20Aggregation.pdf).

### 53 Reverse sensitivity testing — What does it take to break the model?

**Folder:** `pesenti-millossovich-tsanakas-2019` · [metadata](../content/publication/pesenti-millossovich-tsanakas-2019/index.md) · [citation](../content/publication/pesenti-millossovich-tsanakas-2019/cite.bib)

**Current record:** *European Journal of Operational Research*, 2019-04-16. [Publication source](https://www.sciencedirect.com/science/article/pii/S037722171830852X).

- date: 2019-01-01 → 2019-04-16
- doi: https://doi.org/10.1016/j.ejor.2018.10.003 → 10.1016/j.ejor.2018.10.003
- PDF URL: https://arts.units.it/retrieve/e2913fdc-cabf-f688-e053-3705fe0a67e0/Millossovich_Reverse%20sensitivity%20testing_postprint.pdf
- Links: added or corrected URL/manuscript buttons.
- Citation title: Reverse sensitivity testing: What does it take to break the model? → {Reverse sensitivity testing: What does it take to break the model?}
- Citation pages: 654-670 → 654--670
- Citation doi: https://doi.org/10.1016/j.ejor.2018.10.003 → 10.1016/j.ejor.2018.10.003
- Citation url: None → https://doi.org/10.1016/j.ejor.2018.10.003

- authors: ['Silvana M. Pesenti', 'Pietro Millossovich', 'Andreas Tsanakas'] → ['Silvana Pesenti', 'Pietro Millossovich', 'Andreas Tsanakas']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** PDF button links to institutional postprint; published PDF requires ScienceDirect access.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S037722171830852X), [source 2](https://arts.units.it/retrieve/e2913fdc-cabf-f688-e053-3705fe0a67e0/Millossovich_Reverse%20sensitivity%20testing_postprint.pdf).

### 54 Cascade Sensitivity Measures

**Folder:** `pesenti-millossovich-tsanakas-2021` · [metadata](../content/publication/pesenti-millossovich-tsanakas-2021/index.md) · [citation](../content/publication/pesenti-millossovich-tsanakas-2021/cite.bib)

**Current record:** *Risk Analysis*, 2021-12-01. [Publication source](https://onlinelibrary.wiley.com/doi/10.1111/risa.13758).

- date: 2021-01-01 → 2021-12-01
- doi: https://doi.org/10.1111/risa.13758 → 10.1111/risa.13758
- PDF URL: https://openaccess.city.ac.uk/25904/8/Cascade_Sensitivity_11-2020.pdf
- Links: added or corrected URL/manuscript buttons.
- Citation title: Cascade Sensitivity Measures → {Cascade Sensitivity Measures}
- Citation pages: 2392-2414 → 2392--2414
- Citation doi: https://doi.org/10.1111/risa.13758 → 10.1111/risa.13758
- Citation url: None → https://doi.org/10.1111/risa.13758

- authors: ['Silvana M. Pesenti', 'Pietro Millossovich', 'Andreas Tsanakas'] → ['Silvana Pesenti', 'Pietro Millossovich', 'Andreas Tsanakas']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** PDF button links to institutional submitted manuscript; published PDF requires Wiley access.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://onlinelibrary.wiley.com/doi/10.1111/risa.13758), [source 2](https://openaccess.city.ac.uk/id/eprint/25904/), [source 3](https://openaccess.city.ac.uk/25904/8/Cascade_Sensitivity_11-2020.pdf).

### 55 Differential quantile-based sensitivity in discontinuous models

**Folder:** `pesenti-millossovich-tsanakas-2023` · [metadata](../content/publication/pesenti-millossovich-tsanakas-2023/index.md) · [citation](../content/publication/pesenti-millossovich-tsanakas-2023/cite.bib)

**Current record:** *European Journal of Operational Research*, 2025-04-16. [Publication source](https://www.sciencedirect.com/science/article/pii/S0377221724009500).

- title: Differential Sensitivity in Discontinuous Models → Differential quantile-based sensitivity in discontinuous models
- date: 2023-01-01 → 2025-04-16
- publication: *Available at SSRN 4597400* → *European Journal of Operational Research*
- doi: None → 10.1016/j.ejor.2024.12.008
- PDF URL: https://openaccess.city.ac.uk/id/eprint/34368/1/1-s2.0-S0377221724009500-main.pdf
- Links: added or corrected URL/manuscript buttons.
- Citation title: Differential Sensitivity in Discontinuous Models → {Differential quantile-based sensitivity in discontinuous models}
- Citation author: Pesenti, Silvana M and Millossovich, Pietro and Tsanakas, Andreas → Pesenti, Silvana M. and Millossovich, Pietro and Tsanakas, Andreas
- Citation journal: Available at SSRN 4597400 → European Journal of Operational Research
- Citation volume: None → 322
- Citation number: None → 2
- Citation pages: None → 554--572
- Citation year: 2023 → 2025
- Citation doi: None → 10.1016/j.ejor.2024.12.008
- Citation url: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4597400 → https://doi.org/10.1016/j.ejor.2024.12.008
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: links: - name: URL   url: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4597400 → links:  - name: URL   url: https://doi.org/10.1016/j.ejor.2024.12.008
- Note: Abstract formatting/text: complex computational models used in applications → complex computational models, as used in applications
- Note: BibTeX url = {https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4597400}, → url = {https://doi.org/10.1016/j.ejor.2024.12.008},
- Note: Published abstract: input-output → input–output; and derive → and we derive.

- authors: ['Silvana M Pesenti', 'Pietro Millossovich', 'Andreas Tsanakas'] → ['Silvana Pesenti', 'Pietro Millossovich', 'Andreas Tsanakas']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** User added a published journal PDF, pesenti-millossovich-tsanakas-2023.pdf. Verified the paper identity, matching DOI, and successful PDF parsing. PDF buttons on the publication page and publications list link to the local file; the built copy is byte-for-byte identical.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0377221724009500), [source 2](https://openaccess.city.ac.uk/id/eprint/34368/).

### 56 Euler allocations in the presence of non-linear reinsurance — Comment on Major (2018)

**Folder:** `pesenti-tsanakas-millossovich-2018` · [metadata](../content/publication/pesenti-tsanakas-millossovich-2018/index.md) · [citation](../content/publication/pesenti-tsanakas-millossovich-2018/cite.bib)

**Current record:** *Insurance: Mathematics and Economics*, 2018-11-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S0167668718301124).

- date: 2018-01-01 → 2018-11-01
- doi: https://doi.org/10.1016/j.insmatheco.2018.09.001 → 10.1016/j.insmatheco.2018.09.001
- PDF URL: https://openaccess.city.ac.uk/id/eprint/20437/1/MajorCommentAccepted.pdf
- Links: added or corrected URL/manuscript buttons.
- Citation title: Euler allocations in the presence of non-linear reinsurance: Comment on Major (2018) → {Euler allocations in the presence of non-linear reinsurance: Comment on Major (2018)}
- Citation pages: 29-31 → 29--31
- Citation doi: https://doi.org/10.1016/j.insmatheco.2018.09.001 → 10.1016/j.insmatheco.2018.09.001
- Citation url: None → https://doi.org/10.1016/j.insmatheco.2018.09.001

- authors: ['Silvana M. Pesenti', 'Andreas Tsanakas', 'Pietro Millossovich'] → ['Silvana Pesenti', 'Andreas Tsanakas', 'Pietro Millossovich']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** PDF button links to institutional accepted manuscript; published PDF requires ScienceDirect access.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0167668718301124), [source 2](https://www.sciencedirect.com/author/12242529200/andreas-tsanakas), [source 3](https://openaccess.city.ac.uk/id/eprint/20437/1/MajorCommentAccepted.pdf).

### 57 Optimal transport divergences induced by scoring functions

**Folder:** `pesenti-vanduffel-2023` · [metadata](../content/publication/pesenti-vanduffel-2023/index.md) · [citation](../content/publication/pesenti-vanduffel-2023/cite.bib)

**Current record:** *Operations Research Letters*, 2024-11-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S0167637724000828).

- title: Optimal Transport Divergences induced by Scoring Functions → Optimal transport divergences induced by scoring functions
- date: 2023-01-01 → 2024-11-01
- publication: *Available at SSRN 4638937* → *Operations Research Letters*
- doi: None → 10.1016/j.orl.2024.107146
- PDF URL: https://arxiv.org/pdf/2311.12183
- Links: added or corrected URL/manuscript buttons.
- Citation title: Optimal Transport Divergences induced by Scoring Functions → {Optimal transport divergences induced by scoring functions}
- Citation author: Pesenti, Silvana M and Vanduffel, Steven → Pesenti, Silvana M. and Vanduffel, Steven
- Citation journal: Available at SSRN 4638937 → Operations Research Letters
- Citation volume: None → 57
- Citation pages: None → 107146
- Citation year: 2023 → 2024
- Citation doi: None → 10.1016/j.orl.2024.107146
- Citation url: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4638937 → https://doi.org/10.1016/j.orl.2024.107146
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: links: - name: URL   url: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4638937 → links:  - name: URL   url: https://doi.org/10.1016/j.orl.2024.107146
- Note: Abstract: replaced outdated preprint wording with the published abstract.
- Note: BibTeX url = {https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4638937}, → url = {https://doi.org/10.1016/j.orl.2024.107146},

- authors: ['Silvana M Pesenti', 'Steven Vanduffel'] → ['Silvana Pesenti', 'Steven Vanduffel']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** User added a published journal PDF, pesenti-vanduffel-2023.pdf. Verified the paper identity, matching DOI, and successful PDF parsing. PDF buttons on the publication page and publications list link to the local file; the built copy is byte-for-byte identical.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0167637724000828), [source 2](https://arxiv.org/abs/2311.12183).

### 58 Optimizing distortion riskmetrics with distributional uncertainty

**Folder:** `pesenti-wang-wang-2021` · [metadata](../content/publication/pesenti-wang-wang-2021/index.md) · [citation](../content/publication/pesenti-wang-wang-2021/cite.bib)

**Current record:** *Mathematical Programming*, 2025-09-01. [Publication source](https://link.springer.com/article/10.1007/s10107-024-02128-6).

- title: Optimizing Distortion Riskmetrics With Distributional Uncertainty → Optimizing distortion riskmetrics with distributional uncertainty
- date: 2021-01-01 → 2025-09-01
- publication: *Available at SSRN 3728638* → *Mathematical Programming*
- doi: None → 10.1007/s10107-024-02128-6
- PDF URL: https://www.math.uwaterloo.ca/~wang/papers/2024Pesenti-Wang-Wang-MP.pdf
- Links: added or corrected URL/manuscript buttons.
- Citation title: Optimizing Distortion Riskmetrics With Distributional Uncertainty → {Optimizing distortion riskmetrics with distributional uncertainty}
- Citation journal: Available at SSRN 3728638 → Mathematical Programming
- Citation volume: None → 213
- Citation pages: None → 51--106
- Citation year: 2021 → 2025
- Citation doi: None → 10.1007/s10107-024-02128-6
- Citation url: https://ssrn.com/abstract=3728638 → https://doi.org/10.1007/s10107-024-02128-6
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: links: - name: URL   url: https://ssrn.com/abstract=3728638 → links:  - name: URL   url: https://doi.org/10.1007/s10107-024-02128-6
- Note: Abstract formatting/text: that allows   us to convert an optimization → that allows to convert an optimization
- Note: Abstract formatting/text: to a convex one, leading to great tractability. → to a convex one induced from the concave envelope of the distortion function, leading to practical tractability.
- Note: BibTeX url = {https://ssrn.com/abstract=3728638}, → url = {https://doi.org/10.1007/s10107-024-02128-6},

- authors: ['Silvana M. Pesenti', 'Qiuqi Wang', 'Ruodu Wang'] → ['Silvana Pesenti', 'Qiuqi Wang', 'Ruodu Wang']
- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** User added a published journal PDF, pesenti-wang-wang-2021.pdf. Verified the paper identity, matching DOI, and successful PDF parsing. PDF buttons on the publication page and publications list link to the local file; the built copy is byte-for-byte identical.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://link.springer.com/article/10.1007/s10107-024-02128-6), [source 2](https://www.math.uwaterloo.ca/~wang/papers/2024Pesenti-Wang-Wang-MP.pdf), [source 3](https://arxiv.org/abs/2011.04889).

### 59 Dynamic Pareto Optima in Multi-Period Pure-Exchange Economies

**Folder:** `tam-ghossoub-pesenti-2026` · [metadata](../content/publication/tam-ghossoub-pesenti-2026/index.md) · [citation](../content/publication/tam-ghossoub-pesenti-2026/cite.bib)

**Current record:** *arXiv preprint arXiv:2603.19414*, 2026-03-19. [Publication source](https://arxiv.org/abs/2603.19414).

- publication_types: ['2'] → ['3']
- publication: *arXiv* → *arXiv preprint arXiv:2603.19414*
- PDF URL: /publication/tam-ghossoub-pesenti-2026/tam-pesenti-2026.pdf
- Links: added or corrected URL/manuscript buttons.
- Citation entry_type: article → misc
- Citation title: Dynamic Pareto Optima in Multi-Period Pure-Exchange Economies → {Dynamic Pareto Optima in Multi-Period Pure-Exchange Economies}
- Citation journal:  → None
- Citation volume: 0 → None
- Citation number:  → None
- Citation pages:  → None
- Citation url: None → https://arxiv.org/abs/2603.19414
- Citation eprint: https://arxiv.org/abs/2603.19414 → 2603.19414
- Citation archivePrefix: None → arXiv
- Citation publisher:  → None
- Citation note: None → Preprint
- Note: publication: "*arXiv*" → "*arXiv preprint arXiv:2603.19414*"
- Note: No journal publication confirmed; preprint date/year uses first arXiv submission, not a later revision.

- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** Existing local PDF preserved. The nonmatching filename tam-pesenti-2026.pdf contains the correct Dynamic Pareto Optima paper; an explicit local url_pdf now enables its previously missing PDF button.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://arxiv.org/abs/2603.19414).

### 60 Bounds for Distributionally Robust Optimization Problems

**Folder:** `tam-pesenti-2026` · [metadata](../content/publication/tam-pesenti-2026/index.md) · [citation](../content/publication/tam-pesenti-2026/cite.bib)

**Current record:** *arXiv preprint arXiv:2504.06381*, 2025-04-08. [Publication source](https://arxiv.org/abs/2504.06381).

- date: 2026-01-28 → 2025-04-08
- publication_types: ['2'] → ['3']
- publication: *arXiv* → *arXiv preprint arXiv:2504.06381*
- Links: added or corrected URL/manuscript buttons.
- Citation citation_key: tam_ghossoub_pesenti_2026 → tam_pesenti_2026
- Citation entry_type: article → misc
- Citation title: Bounds for Distributionally Robust Optimization Problems → {Bounds for Distributionally Robust Optimization Problems}
- Citation journal:  → None
- Citation volume: 0 → None
- Citation number:  → None
- Citation pages:  → None
- Citation year: 2026 → 2025
- Citation url: None → https://arxiv.org/abs/2504.06381
- Citation eprint: https://arxiv.org/abs/2504.06381 → 2504.06381
- Citation archivePrefix: None → arXiv
- Citation publisher:  → None
- Citation note: None → Preprint
- Note: publication: "*arXiv*" → "*arXiv preprint arXiv:2504.06381*"
- Note: No journal publication confirmed; preprint date/year uses first arXiv submission, not a later revision.
- Note: Local PDF is a January 2026 revision; arXiv now has v4 dated 14 August 2026.

- Author profile links: Silvana M. Pesenti → Silvana Pesenti. Published names remain in the citation.

**PDF:** Existing local PDF preserved; its button is checked in the rebuilt site.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://arxiv.org/abs/2504.06381).

### 61 LRMoE.jl — a software package for insurance loss modelling using mixture of experts regression model

**Folder:** `tseung-badescu-fung-lin-2021` · [metadata](../content/publication/tseung-badescu-fung-lin-2021/index.md) · [citation](../content/publication/tseung-badescu-fung-lin-2021/cite.bib)

**Current record:** *Annals of Actuarial Science*, 2021-07-01. [Publication source](https://www.cambridge.org/core/product/identifier/S1748499521000087/type/journal_article).

- date: 2021-01-01 → 2021-07-01
- Links: added or corrected URL/manuscript buttons.
- Citation title: LRMoE.jl: a software package for insurance loss modelling using mixture of experts regression model → {LRMoE.jl: a software package for insurance loss modelling using mixture of experts regression model}
- Citation pages: 419–440 → 419--440
- Citation url: None → https://www.cambridge.org/core/product/identifier/S1748499521000087/type/journal_article
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: Restore publisher monospace styling for julia.
- Note: Restore publisher monospace styling with BibTeX LaTeX.

- authors: ['Spark C. Tseung', 'Andrei L. Badescu', 'Tsz Chai Fung', 'X. Sheldon Lin'] → ['Spark Tseung', 'Andrei Badescu', 'Samson Fung', 'Sheldon Lin']
- Author profile links: Spark C. Tseung → Spark Tseung; Andrei L. Badescu → Andrei Badescu; Tsz Chai Fung → Samson Fung; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved: tseung-badescu-fung-lin-2021.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/product/identifier/S1748499521000087/type/journal_article), [source 2](https://api.crossref.org/works/10.1017/S1748499521000087).

### 62 Improving risk classification and ratemaking using mixture-of-experts models with random effects

**Folder:** `tseung-chan-fung-badescu-lin-2023` · [metadata](../content/publication/tseung-chan-fung-badescu-lin-2023/index.md) · [citation](../content/publication/tseung-chan-fung-badescu-lin-2023/cite.bib)

**Current record:** *Journal of Risk and Insurance*, 2023-09-01. [Publication source](https://onlinelibrary.wiley.com/doi/10.1111/jori.12436).

- date: 2023-01-01 → 2023-09-01
- doi: https://doi.org/10.1111/jori.12436 → 10.1111/jori.12436
- Citation title: Improving risk classification and ratemaking using mixture-of-experts models with random effects → {Improving risk classification and ratemaking using mixture-of-experts models with random effects}
- Citation pages: 789-820 → 789--820
- Citation doi: https://doi.org/10.1111/jori.12436 → 10.1111/jori.12436
- Citation url: https://onlinelibrary.wiley.com/doi/abs/10.1111/jori.12436 → https://onlinelibrary.wiley.com/doi/10.1111/jori.12436
- Citation eprint: https://onlinelibrary.wiley.com/doi/pdf/10.1111/jori.12436 → None
- Abstract: wording or typography corrected. Review the `index.md` diff for the exact text.
- Note: Remove imported Abstract heading and restore publisher italic styling for model name.
- Note: Remove imported Abstract heading; restore model name italics with BibTeX LaTeX.

- authors: ['Spark C. Tseung', 'Ian Weng Chan', 'Tsz Chai Fung', 'Andrei L. Badescu', 'X. Sheldon Lin'] → ['Spark Tseung', 'Sophia Chan', 'Samson Fung', 'Andrei Badescu', 'Sheldon Lin']
- Author profile links: Spark C. Tseung → Spark Tseung; Ian Weng Chan → Sophia Chan; Tsz Chai Fung → Samson Fung; Andrei L. Badescu → Andrei Badescu; X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved: tseung-chan-fung-badescu-lin-2023.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://onlinelibrary.wiley.com/doi/10.1111/jori.12436), [source 2](https://api.crossref.org/works/10.1111/jori.12436).

### 63 Fitting mixtures of Erlangs to censored and truncated data using the EM algorithm

**Folder:** `verbelen-gong-antonio-badescu-lin-2015` · [metadata](../content/publication/verbelen-gong-antonio-badescu-lin-2015/index.md) · [citation](../content/publication/verbelen-gong-antonio-badescu-lin-2015/cite.bib)

**Current record:** *ASTIN Bulletin*, 2015-09-01. [Publication source](https://www.cambridge.org/core/product/identifier/S051503611500015X/type/journal_article).

- date: 2015-01-01 → 2015-09-01
- Links: added or corrected URL/manuscript buttons.
- Citation title: Fitting mixtures of Erlangs to censored and truncated data using the EM algorithm → {Fitting mixtures of Erlangs to censored and truncated data using the EM algorithm}
- Citation pages: 729–758 → 729--758
- Citation url: None → https://www.cambridge.org/core/product/identifier/S051503611500015X/type/journal_article

**PDF:** Existing local PDF preserved: verbelen-gong-antonio-badescu-lin-2015.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/product/identifier/S051503611500015X/type/journal_article), [source 2](https://api.crossref.org/works/10.1017/asb.2015.15).

### 64 Efficient estimation of Erlang mixtures using iSCAD penalty with insurance application

**Folder:** `yin-lin-2016` · [metadata](../content/publication/yin-lin-2016/index.md) · [citation](../content/publication/yin-lin-2016/cite.bib)

**Current record:** *ASTIN Bulletin*, 2016-09-01. [Publication source](https://www.cambridge.org/core/product/identifier/S0515036116000143/type/journal_article).

- date: 2016-01-01 → 2016-09-01
- Links: added or corrected URL/manuscript buttons.
- Citation title: Efficient estimation of Erlang mixtures using iSCAD penalty with insurance application → {Efficient estimation of Erlang mixtures using iSCAD penalty with insurance application}
- Citation pages: 779–799 → 779--799
- Citation url: None → https://www.cambridge.org/core/product/identifier/S0515036116000143/type/journal_article

- authors: ['Cuihong Yin', 'X. Sheldon Lin'] → ['Cuihong Yin', 'Sheldon Lin']
- Author profile links: X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved: yin-lin-2016.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.cambridge.org/core/product/identifier/S0515036116000143/type/journal_article), [source 2](https://api.crossref.org/works/10.1017/asb.2016.14).

### 65 On the consistency of penalized MLEs for Erlang mixtures

**Folder:** `yin-lin-huang-yuan-2019` · [metadata](../content/publication/yin-lin-huang-yuan-2019/index.md) · [citation](../content/publication/yin-lin-huang-yuan-2019/cite.bib)

**Current record:** *Statistics & Probability Letters*, 2019-02-01. [Publication source](https://www.sciencedirect.com/science/article/pii/S0167715218302797).

- date: 2019-01-01 → 2019-02-01
- doi: https://doi.org/10.1016/j.spl.2018.08.004 → 10.1016/j.spl.2018.08.004
- Links: added or corrected URL/manuscript buttons.
- Citation title: On the consistency of penalized MLEs for Erlang mixtures → {On the consistency of penalized MLEs for Erlang mixtures}
- Citation journal: Statistics & Probability Letters → Statistics \& Probability Letters
- Citation pages: 12-20 → 12--20
- Citation doi: https://doi.org/10.1016/j.spl.2018.08.004 → 10.1016/j.spl.2018.08.004
- Citation url: None → https://www.sciencedirect.com/science/article/pii/S0167715218302797

- authors: ['Cuihong Yin', 'X. Sheldon Lin', 'Rongtan Huang', 'Haili Yuan'] → ['Cuihong Yin', 'Sheldon Lin', 'Rongtan Huang', 'Haili Yuan']
- Author profile links: X. Sheldon Lin → Sheldon Lin. Published names remain in the citation.

**PDF:** Existing local PDF preserved: yin-lin-huang-yuan-2019.pdf. No journal PDF downloaded or replaced.

**Built buttons:** PDF ready, Cite ready, DOI ready, URL ready.

**Verification sources:** [source 1](https://www.sciencedirect.com/science/article/pii/S0167715218302797), [source 2](https://api.crossref.org/works/10.1016/j.spl.2018.08.004).

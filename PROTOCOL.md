# DOC-2-092 F0: paired image-transcriptome source audit

State: draft, not locked, not released. Zero success credit. No image pixels, feature tables, expression matrices or outcome scoring have been opened. This audit is preparation, not evidence that images predict molecular state.

## Original question

DOC-2-092, original source position 192: "Drought Before Wilting - From Public Images to Molecular State". Can visible plant stress patterns predict hidden molecular stress programs? The requested validation is cross-species or cross-study. The source must join image trajectories to measured molecular states, not assign RNA labels to unrelated image plants simply because both received drought.

## Prior exposure and duplicate check

Current GitHub most-recent-100 repository listing and Drive filename search (092, drought, phenotyp) showed no matching new artifact. This bounded screen is not proof of absence across every repository/file. Existing 200-row matrix and cross-program owner reports have no exact binding for this topic. Parent has reaffirmed 091/092/093 ownership.

Discovery viewed published summaries and article text, including reported biological outcomes, for Brassica napus GSE261928 and sunflower Dryad v6wwpzh20. These are exposed prior knowledge, not untouched tests. The Brassica paper reports RGB/NIR images and leaf RNA-seq from an experiment; the associated GitHub README currently says raw image location "XXX". Sunflower Dryad exposes phenotype and molecular file names, but no image archive in the viewed listing. Bean Zenodo 11179671 exposes phenotype CSV file names and CC-BY 4.0; no transcriptome pairing was established. These observations inform the bounded set below; they are not registered audit results. No numerical tables or actual dataset images were downloaded.

## Fixed candidate sources and admitted metadata routes

1. Brassica napus: GSE261928; paper PMC11849911; danforthcenter/ktgreenham-brassica-drought-paper.
2. Sunflower: Dryad doi:10.5061/dryad.v6wwpzh20; article doi:10.3390/ijms24119351.
3. Phaseolinae beans: Zenodo record 11179671.

After lock/release, inspect only record descriptions, README/data dictionaries, file manifests, source-use terms and article methods/data-availability text. For GitHub use repository metadata/tree and README only; do not open analysis scripts/results, images or numerical tables. For Dryad/Zenodo use record metadata/file listings and explicitly named README only. For GEO use brief series metadata only, never sample pages, matrices or family archives. If a listed primary metadata page links an external image repository, record its link but do not expand this fixed set or download; a new source requires amendment. No numerical supplements or expression data.

Save each admitted page/metadata response with exact final URL, UTC time, byte length and SHA256. HTTP 200 is not admission: require correct accession/DOI/repository title plus expected metadata fields. Record interstitial/errors verbatim, allow one bounded retry per failed route, then mark unavailable. No accession swapping or source expansion. Browser fallback may render the same record/README only. Audit each candidate once.

## Required gates

P1 Images: an actual public image archive/manifest link, described acquisition times and plant/plot identifiers. Merely publishing image-derived traits is not sufficient for an image model.
P2 Molecular labels: measured RNA-seq or comparable transcriptomics with actual public file links, biological units and collection times. Treatment labels alone are not molecular state.
P3 Joinability: explicit mapping from an individual image trajectory to its RNA biological sample, or a documented designed cohort mapping. Cohort-level mapping must be named as ecological/cohort prediction, not individual prediction. A same-genotype/treatment guess does not establish a paired sample. Missing join keys -> UNRESOLVED; documented separate unmatched populations -> STOP for individual prediction.
P4 Temporal direction: image observations before or at molecular collection, with enough dated observations to distinguish trajectory from a single image. "Before wilting" needs documented onset/phenotype criteria, not a title. An endpoint transcriptome cannot establish earlier molecular detection without timestamped labels.
P5 External validation: at least two independently collected paired studies or species with compatible pathway labels and documented ortholog mapping plan. One study with held-out genotypes is not the requested cross-study/cross-species validation.
P6 Access/terms: free public metadata and data access; dataset license/reuse constraints recorded. Unknown reuse license stays UNKNOWN, prevents raw redistribution and cannot be treated as public domain. Code license does not automatically license images/RNA data.

GO only if a documented pair of candidates meets all required gates for the original question. STOP if a documented hard floor fails across the fixed set. UNRESOLVED for insufficient documentation. Do not convert metadata GO into predictive success or source novelty.

## Next boundary

No fitting, transformations, feature extraction, molecular pathway construction, train/test split or scoring during F0. A later outcome protocol must define sample units, temporal cutoff, exposure ledger, image/label transforms, pathway targets, cross-study/species folds, baselines, missingness, dependence and fail policy before any dataset values. Publication/gate review stays separate from a builder's own assessment.

## Observed source URLs

- https://seqout.org/p/GSE261928 (discovery lead, secondary)
- https://pmc.ncbi.nlm.nih.gov/articles/PMC11849911/
- https://github.com/danforthcenter/ktgreenham-brassica-drought-paper
- https://datadryad.org/dataset/doi:10.5061/dryad.v6wwpzh20
- https://www.mdpi.com/1422-0067/24/11/9351
- https://zenodo.org/records/11179671

The GEO primary accession link must be observed from source metadata before inclusion in a collector; it is not guessed here.

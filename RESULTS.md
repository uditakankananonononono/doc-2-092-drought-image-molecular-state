# DOC-2-092 F0: METADATA-UNRESOLVED

Builder assessment, pending independent review. Zero project-success credit. No image pixels, feature tables, expression matrices, molecular labels, model fitting or scoring accessed.

Lock-1: 2a8e5f48d11333046b1b430c192cf93c8d98d307. Reviewed protocol was published and tag readback verified before the audit. Primary page collection began 2026-10-09T19:29:10Z. The candidate set was not expanded.

## Gates

| Gate | Brassica napus | Sunflower | Phaseolinae beans |
|---|---|---|---|
| P1 images | Actual CyVerse image link in paper; archive/manifest not inspected under fixed-set rule, IDs unresolved | No image archive in the admitted Dryad listing; microscope images described but no downloadable trajectory archive established | Record lists image-derived trait CSVs, not an image archive |
| P2 measured molecular labels | RNA collection and GEO link described; actual GEO metadata blocked by challenge, table links unverified | Dryad name_merge.matrix and molecular files listed, paper names PRJNA976033; contents not opened | No molecular files or RNA pairing in record |
| P3 joinability | Individual/cohort joins UNRESOLVED, no explicit image-to-GSM mapping in admitted documentation | UNRESOLVED; README route blocked, image joins absent | UNRESOLVED, no molecular units to join |
| P4 temporal direction | Daily images and endpoint tissue collection described, but exact day contradictory and pre-wilting criterion unverified | Phenotype timing described, not a paired image/molecular onset timeline | No paired molecular timing established |
| P5 independent external validation | No documented pair of admitted studies satisfies P1-P3; cross-species/study evaluation cannot be registered honestly from this evidence | Same | Same |
| P6 source terms | Article CC-BY 4.0, code MPL-2.0; dataset-specific image/RNA terms UNKNOWN, not inherited from article/code | Article CC-BY 4.0; dataset-specific license not recovered in admitted record/blocked README | Dataset CC-BY 4.0 explicitly stated |

METADATA-UNRESOLVED, not GO and not a biological negative. Missing links/joins do not prove no dataset exists. No original-question success is claimed. The fixed-set audit cannot justify treating unrelated drought datasets as paired molecular labels. A candidate expansion, CyVerse metadata inspection or alternate GEO route needs a reviewed amendment; an outcome protocol is not started.

## Exact evidence and discrepancies

Brassica paper data-availability: "Images from the phenotyping experiments are available on Cyverse" followed by the link below. This resolves the discovery lead's README "XXX" at the link level only. Registered rule was to record external repository links without expanding the fixed set, so CyVerse was not opened.

Methods: "On each day of the experiment, all plants moved from the controlled environment growth house to the imaging loop via a conveyor belt" and "Two side view images from 0° and 90° angles were captured each day by the RGB and NIR cameras."

Tissue methods: "After 2 days (21 treatment days) on the Bellwether Phenotyping Facility, leaf tissue was collected from the apex of the youngest leaf on each plant." This exact published wording is internally inconsistent with its parenthetical and broader four-week description; it is not silently repaired to 28 days. It also says "For each accession, tissue was collected from three replicates of each treatment at each time point." This is collection design, not an explicit image-ID-to-RNA mapping.

Brassica GitHub README: "Raw image data associated with this paper can be found: XXX". Code license MPL-2.0 is not an image-data license.

Sunflower paper data availability: "Data for this study are available at Dryad Digital Repository, https://doi.org/10.5061/dryad.v6wwpzh20, and with BioProject accession number PRJNA976033 in the NCBI BioProject database". Dryad lists 18HP02_shape_height.csv, phenotype/stomatal tables, name_merge.matrix, modules and README.md, but no raw image archive in the admitted listing. No tables were opened. It describes microscope stomatal images, not a publicly paired whole-plant trajectory archive.

Bean record: "Using a high-throughput phenotypic imaging system, we evaluated the drought tolerance of 151 bean accessions" and "The base data for calculating the drought response indicators and the accessions used in the study are listed in these datasets". Five CSV names concern biomass, NDVI, root/shoot, water content and water-use efficiency. Record license is Creative Commons Attribution 4.0 International. Image acquisition alone does not make the raw images public or RNA labels paired.

## Transport/admission

Primary collection admitted Brassica PMC paper, GitHub README page, sunflower Dryad record and bean Zenodo record. MDPI HTTP route returned 403 Access Denied twice; same-article browser fallback admitted full article text. GEO primary returned HTTP-200 reCAPTCHA HTML, not a series record; browser same-series fallback remained challenge after 30 seconds and was stopped. Dryad README HTTP route returned 403; bounded web-render fallback returned "Validating...", not README and was rejected. Failures retained, not counted as empty data.

Published article results encountered in discovery/audit remain prior exposure, not blind outcome tests. Any later numerical protocol needs a program-wide exposure check.

## Observed sources

- https://pmc.ncbi.nlm.nih.gov/articles/PMC11849911/
- https://github.com/danforthcenter/ktgreenham-brassica-drought-paper
- https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE261928 (blocked)
- https://datacommons.cyverse.org/browse/iplant/home/shared/danforth_center/Ricono_et_al_Brassica (link observed, not opened)
- https://datadryad.org/dataset/doi:10.5061/dryad.v6wwpzh20
- https://datadryad.org/downloads/file_stream/2351750 (README route blocked)
- https://www.mdpi.com/1422-0067/24/11/9351
- https://zenodo.org/records/11179671

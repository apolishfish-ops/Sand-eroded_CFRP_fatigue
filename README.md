# Sand-eroded_CFRP_fatigue
# Raw Data for Fatigue Damage Evolution and Residual-Life Prediction of Sand-Eroded CFRP Laminates

This repository contains the original data and supporting code for the study:

**Fatigue damage evolution and residual-life prediction of sand-eroded CFRP laminates based on energy dissipation characteristics**

The dataset is organized to support data traceability, result reproduction, and future reuse. The files are provided as research data associated with fatigue damage evolution, residual-life prediction, sand erosion treatment, CFRP laminate testing, S-N data analysis, image records, and related calculation scripts.

## Repository Structure

```text
.
├── README.md
├── wsr523/
├── code/
├── S_N Original/
└── PlainImages/
```

## Directory Description

### `wsr523/`

This folder contains the original experimental data files used in the study. These files are retained as raw records and should not be directly modified. If data cleaning, format conversion, or further processing is required, the processed results should be saved separately.

Possible contents include raw measurement data, test output files, intermediate experimental records, and related source files generated during fatigue or residual-life analysis.

### `code/`

This folder contains code used for data processing, calculation, analysis, plotting, and model-related work.

Typical usage may include:

- Reading and organizing raw experimental data
- Calculating energy dissipation-related parameters
- Processing fatigue damage evolution data
- Performing residual-life prediction
- Generating figures or tables for analysis

Before running the code, please check file paths, input data locations, software dependencies, and version requirements.

### `S_N Original/`

This folder contains the original S-N data used for fatigue analysis.

The data in this folder are intended to preserve the original stress-life or fatigue-life records before further fitting, normalization, filtering, or statistical treatment. These files may be used to reproduce S-N curves, fatigue life comparisons, and related analysis results.

### `PlainImages/`

This folder contains original image data related to the experiments.

The images may include specimen images, surface morphology records, damage evolution images, erosion-related images, or other plain image records used for observation, comparison, or documentation. These files are treated as raw image data.

## Data Usage Notes

- Raw data should be preserved in its original form whenever possible.
- Do not overwrite original files directly.
- If processed data are generated, save them in a separate folder such as `processed/` or `results/`.
- Keep file names stable when they are referenced by scripts, figures, or tables.
- Large files may require Git LFS when uploaded to GitHub.
- Sensitive or unpublished information should be checked before making the repository public.

## Suggested Workflow

1. Place all original experimental files in their corresponding raw-data folders.
2. Use scripts in `code/` to read and process the raw data.
3. Save derived results, processed data, and generated figures in a separate output folder.
4. Record any manual data corrections or preprocessing steps clearly.
5. Cite this repository when reusing the dataset or code.

## Large File Storage

Some image files or raw experimental files may exceed the normal GitHub file size limit. If GitHub reports that a file is too large, use Git Large File Storage:

```bash
git lfs install
git lfs track "*.jpg"
git lfs track "*.jpeg"
git lfs track "*.png"
git lfs track "*.tif"
git lfs track "*.tiff"
git lfs track "*.xlsx"
git add .gitattributes
git add .
git commit -m "Add raw research data"
git push
```

## Citation

If you use this dataset or code, please cite the related paper:

> Fatigue damage evolution and residual-life prediction of sand-eroded CFRP laminates based on energy dissipation characteristics.

The complete citation information should be updated after publication.

## License

Please specify the data license before public release.

- **CC0 1.0**: Allows unrestricted public reuse.

## Contact

For questions about the dataset, experimental conditions, or code usage, please contact the corresponding author or repository maintainer.

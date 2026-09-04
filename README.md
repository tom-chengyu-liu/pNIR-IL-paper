# Python code and data for portable near-infrared analysis of ignitable liquids using the Powder Puck instrument

## Background

This repository accompanies a manuscript on 'Rapid intact ignitable liquid detection and characterization with portable NIR spectroscopy using a novel 3D-printed glass cell.'

## Summary

The repository contains the data, Python notebooks, interactive PCA outputs, QGIS files, and Excel workbooks used to generate the results presented in the manuscript and its Supplementary Information.

The Python notebooks cover spectral visualization, PCA, PCA-LDA classification, SIMCA modelling, gasoline type classification, brand classification, and the evaporation study. Selected figures were generated directly in Microsoft Excel rather than with Python. The geographical sampling-site map was prepared in QGIS.

## Data

Two Excel data files are provided in the `data` folder:

* `data.xlsx` contains the spectral data used for the main pNIR analyses.
* `evaporation data.xlsx` contains the spectral data used for the evaporation experiment described in Section 3.6.

## Notebooks

The `notebooks` folder contains the Python notebooks used for the analyses and generation of manuscript figures and tables:

* `IL_class_mean_spectra.ipynb` generates Figure 5, showing the mean spectra of the ignitable-liquid classes.
* `3D_PCA_plot.ipynb` generates the interactive 3D PCA analyses corresponding to Figure 6 and Figure S4.
* `#95_and_#98_gasoline_mean_spectra.ipynb` generates Figure 7, showing the mean spectra of #95 and #98 gasoline samples.
* `LDA_posterior_probability_plot_for_type_classification.ipynb` generates the gasoline type-classification result presented in Figure 8.
* `IL_class_PCA_LDA.ipynb` contains the PCA-LDA analysis used for Table 2 and Figure S6.
* `IL_class_SIMCA.ipynb` contains the SIMCA analysis used for Table 1 and Table S2.
* `LDA_discrimination_plots_for_brand_classification.ipynb` generates the LDA discrimination plots for brand classification presented in Figure S7.
* `evaporation_PCA_LDA.ipynb` contains the PCA-LDA analysis for the evaporation study described in Section 3.6.
* `evaporation_SIMCA_.ipynb` contains the SIMCA analysis for the evaporation study described in Section 3.6.

## Interactive outputs

The `outputs` folder contains interactive HTML versions of the 3D PCA plots corresponding to Figure 6 and Figure S4:

* `pca_3d_plot_snv.html`
* `pca_3d_plot_sg1_p2_w3.html`
* `pca_3d_plot_sg2_p2_w3.html`

These files can be opened in a web browser to rotate, zoom, and inspect the PCA score plots interactively.

## QGIS files

The `qgis` folder contains the files used to generate Figure 1, which shows the geographical distribution of gasoline and diesel sampling locations across the Netherlands.

The folder includes:

* Natural Earth administrative boundary data (`ne_10m_admin_0_countries`)
* Natural Earth lake data (`ne_10m_lakes`)
* `NLD map.gpkg`
* sampling-site data
* the Figure 1 output

## Excel-generated figures

The following Excel workbooks are provided in the repository because these figures were generated directly in Microsoft Excel rather than with Python:

* `Figure 4-mean spectra for different thickness.xlsx` was used to generate Figure 4.
* `Figure 9-evaporation mean spectra.xlsx` was used to generate Figure 9.
* `Figure S5.xlsx` was used to generate Figure S5.

## Contributing

The data analysis was performed by Chengyu Liu.

GPT-5.6 Sol (OpenAI) was used to assist in the generation and modification of the Python code. All AI-assisted code was reviewed, tested, and executed by the author.

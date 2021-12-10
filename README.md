# Electrical and electromagnetic responses over steel-cased wells
Lindsey J. Heagy and Douglas W. Oldenburg

Notebooks to accompany the Leading Edge Article: _Electrical and electromagnetic responses over steel-cased wells_. Accepted for publication. 

## Abstract

Electrical and electromagnetic (EM) methods can be diagnostic geophysical imaging tools for monitoring applications, such as carbon capture and storage or hydraulic fracturing. In these settings, it is common that steel-cased wells and other steel infrastructure are present. Grounded source methods, which use electrodes to inject current into the earth are of interest for casing integrity and monitoring applications. Electrostatic, or direct current (DC) resistivity, experiments form the basis of our understanding of the physics of grounded source experiments in terms of charges, currents, and electric fields. Steel-cased wells are highly conductive and although their presence makes numerical modelling more challenging, they can help targets of interest be detected because they channel charges and currents to depth. Time-domain EM experiments use a time-varying transmitter current. Understanding the EM response requires that we consider both galvanic, or DC currents, as well as image currents that are induced in the subsurface. As compared to DC experiments, the physics of EM is more complex because of the multiple current systems, as well as the need to consider magnetic permeability of steel cased wells. However, EM experiments have the advantage that they can provide a large data set that is sensitive to a target of interest. Ultimately this will increase the potential for being able to extract information about the target.

## Usage

To run the notebooks locally, you will need to have python installed,
preferably through [anaconda](https://www.anaconda.com/download/) .

You can then clone this repository. From a command line, run

```
git clone https://github.com/simpeg-research/heagy-2021-tle-casing.git
```

Then `cd` into the `heagy-2021-tle-casing` directory:

```
cd heagy-2021-tle-casing
```

To setup your software environment, we recommend you use the provided conda environment

```
conda env create -f environment.yml
conda activate heagy-2021-tle-casing
```

You can then launch Jupyter

```
jupyter notebook
```

Jupyter will then launch in your web-browser.

## Running the notebooks

Each cell of code can be run with `shift + enter` or you can run the entire notebook by selecting `cell`, `Run All` in the toolbar.

<img src="https://em.geosci.xyz/_images/run_all_cells.png" width=80% align="middle">

For more information on running Jupyter notebooks, see the [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/)

## Issues

Please [make an issue](https://github.com/simpeg-research/heagy-2021-tle-casing/issues) if you encounter any problems while trying to run the notebooks.

## Citation

If you build upon or use these examples in your work, please cite:

Heagy, L. J., & Oldenburg, D. W. (2021, submitted). Electrical and electromagnetic responses over steel-cased wells. The Leading Edge.

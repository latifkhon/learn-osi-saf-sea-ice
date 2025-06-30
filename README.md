# Learn OSI SAF Sea Ice 🌊❄️

![GitHub release](https://img.shields.io/github/release/latifkhon/learn-osi-saf-sea-ice.svg)

Welcome to the **Learn OSI SAF Sea Ice** repository! This project hosts a collection of Python-based Jupyter Notebooks designed to help you explore and understand the EUMETSAT Ocean and Sea Ice Satellite Application Facility (OSI SAF) sea-ice products. These resources are tailored for marine applications, offering valuable insights into ocean and sea ice dynamics.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Jupyter Notebooks](#jupyter-notebooks)
- [Key Topics](#key-topics)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Releases](#releases)

## Introduction

The Earth's oceans and ice cover play a crucial role in the global climate system. Understanding these components is vital for marine research, climate studies, and environmental monitoring. The EUMETSAT OSI SAF provides satellite data that help in monitoring sea ice conditions. This repository offers tools to analyze and visualize this data effectively.

## Getting Started

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/latifkhon/learn-osi-saf-sea-ice.git
```

Then navigate to the project directory:

```bash
cd learn-osi-saf-sea-ice
```

You can find the latest releases [here](https://github.com/latifkhon/learn-osi-saf-sea-ice/releases). Download the necessary files and execute them to explore the capabilities of the OSI SAF sea-ice products.

## Repository Structure

The repository is organized as follows:

```
learn-osi-saf-sea-ice/
│
├── notebooks/               # Contains Jupyter Notebooks
│   ├── amsr2_analysis.ipynb
│   ├── amsr_e_analysis.ipynb
│   ├── aqua_terra_analysis.ipynb
│   ├── ascat_analysis.ipynb
│   ├── dmsp_analysis.ipynb
│   ├── metop_analysis.ipynb
│   └── smmr_analysis.ipynb
│
├── data/                    # Sample data files
│   ├── amsr2_data.csv
│   ├── amsr_e_data.csv
│   └── ascat_data.csv
│
├── requirements.txt         # Python package dependencies
└── README.md                # Project documentation
```

## Jupyter Notebooks

Each Jupyter Notebook in this repository focuses on a specific satellite product. Below is a brief overview of the notebooks available:

- **amsr2_analysis.ipynb**: Analyze data from the AMSR-2 satellite. Learn how to visualize sea ice concentration and extent.
- **amsr_e_analysis.ipynb**: Explore AMSR-E data. This notebook provides insights into historical sea ice trends.
- **aqua_terra_analysis.ipynb**: Investigate data from Aqua and Terra satellites. Understand their role in monitoring ocean and ice conditions.
- **ascat_analysis.ipynb**: Examine scatterometer data. Learn how wind patterns affect sea ice dynamics.
- **dmsp_analysis.ipynb**: Delve into DMSP satellite data. Understand its contributions to sea ice monitoring.
- **metop_analysis.ipynb**: Analyze data from the Metop satellites. Discover their impact on weather forecasting and climate studies.
- **smmr_analysis.ipynb**: Study SMMR data. Understand historical changes in sea ice cover.

## Key Topics

This repository covers a range of topics related to ocean and sea ice studies, including:

- **AMSR-2**: Advanced Microwave Scanning Radiometer 2, used for sea ice concentration and temperature.
- **AMSR-E**: Advanced Microwave Scanning Radiometer - Earth Observing System, providing critical data for climate research.
- **Aqua and Terra**: NASA satellites that monitor Earth's water and ice resources.
- **ASCAT**: Advanced Scatterometer, measuring wind speed and direction over oceans.
- **DMSP**: Defense Meteorological Satellite Program, providing data for weather and climate studies.
- **Metop**: Meteorological Operational satellite, crucial for weather forecasting.
- **Nimbus**: A series of satellites providing data for various Earth observation missions.
- **Remote Sensing**: The use of satellite or aircraft-based sensor technologies to detect and monitor physical characteristics of an area.

## Installation

To run the Jupyter Notebooks, ensure you have Python and Jupyter installed. You can install the required packages using pip:

```bash
pip install -r requirements.txt
```

Make sure to have the following libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `xarray`
- `netCDF4`

These libraries are essential for data manipulation and visualization.

## Usage

To use the Jupyter Notebooks, launch Jupyter in your terminal:

```bash
jupyter notebook
```

This command will open a new tab in your web browser. From there, navigate to the `notebooks` directory and select the notebook you wish to explore.

## Contributing

We welcome contributions! If you have suggestions or improvements, feel free to open an issue or submit a pull request. Please ensure that your code adheres to the existing style and includes appropriate documentation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, you can reach out via GitHub issues or contact the repository maintainer directly.

## Releases

You can find the latest releases of this project [here](https://github.com/latifkhon/learn-osi-saf-sea-ice/releases). Download the necessary files and execute them to explore the capabilities of the OSI SAF sea-ice products.

Thank you for your interest in the **Learn OSI SAF Sea Ice** project! We hope these resources help you in your journey to understand ocean and sea ice dynamics.
# SIH-SEN2-SR: Trust-Aware Super Resolution for Earth Observation

## Overview

SIH-SEN2-SR explores deep-learning-based super-resolution for Sentinel-2 satellite imagery, aiming to enhance imagery from 10 m to approximately 2.5 m spatial resolution.

The project investigates super-resolution models, image quality, spectral consistency, and uncertainty-aware Earth observation.

## Objectives

- Enhance the spatial detail of Sentinel-2 imagery.
- Evaluate a pretrained SEN2SRLite model against a bicubic interpolation baseline.
- Examine spectral consistency and image quality.
- Explore uncertainty analysis to communicate the reliability of enhanced imagery.
- Support potential applications in Earth observation and environmental monitoring.

## Technology Stack

- Python
- Google Colab
- Sentinel-2 imagery
- SEN2SRLite
- NumPy and raster/image-processing libraries
- GeoTIFF and QGIS for geospatial inspection

## Workflow

1. Select and prepare Sentinel-2 imagery.
2. Apply preprocessing and normalization.
3. Generate super-resolved imagery using the pretrained model.
4. Compare results against a bicubic baseline.
5. Evaluate image quality and spectral consistency.
6. Inspect and visualize the outputs.

## Results

The project includes experiments with super-resolved imagery and quantitative evaluation. Detailed results, validation conditions, and limitations should be documented alongside the corresponding outputs.

## How to Run

1. Open `notebooks/SIH_SRM_Sentinel2_v1.ipynb` in Google Colab.
2. Follow the notebook instructions to install dependencies and obtain the required input data.
3. Run the notebook cells in sequence.
4. Review the generated outputs and evaluation metrics.

## Limitations

Super-resolution generates enhanced image detail; it does not guarantee that every fine feature corresponds to a real-world object. Results depend on model assumptions, input imagery, preprocessing, and validation conditions.

## Project Status

Prototype / research project developed for the Smart India Hackathon (SIH).

## License

To be decided in accordance with applicable SIH rules and the permissions of the underlying model, code, and datasets.

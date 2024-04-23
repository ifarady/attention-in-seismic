# Seismic Layer Segmentation with Channel Attention U-Net & BiSeNet

## Description

This repository provides the implementation code for our work presented at the EnvSys Conference. We propose a novel, lightweight channel attention mechanism that seamlessly integrates with state-of-the-art (SOTA) models like U-Net and BiSeNet for enhanced seismic layer segmentation.

## Key Features

- **Light and Efficient Channel Attention**: Inspired by SENet, our attention module offers similar performance benefits but with reduced computational cost through the removal of pooling layers.
- **Minimal Performance Impact**: Integrating this module into existing models leads to insignificant changes in computational overhead, making it a practical choice for real-world scenarios.

## Datasets and Results

We demonstrate the effectiveness of our approach on the publicly available Salt dataset (https://www.kaggle.com/code/vaibhavthakur/salt-segmentation) and the SEG2020 dataset ([insert dataset details here]).

- Our model achieves consistently higher Intersection over Union (IoU) values compared to baseline models and those without the proposed channel attention module.

## Current Status and Future Work

This channel attention module is actively under development for further improvement. We will continue to enhance its capabilities and incorporate updates into this repository.

We welcome contributions and suggestions from the community to push the boundaries of seismic layer segmentation!

## Running the Code

1. **Download the Code**: Clone or download the full code base from this repository.
2. **Data Preparation**:
   - Prepare your 2D seismic datasets. If working with 3D data, convert it to 2D using `segyio` or a suitable library.
3. **Experiment Setup**:
   - Choose the script corresponding to your desired dataset (Salt or SEG2020).
   - Adjust parameters within the script to match your specific data requirements.
4. **Run the Experiment**: Execute the selected script to initiate the segmentation process.
5. **Results Collection**: After completion, the script will generate segmentation results for further analysis.

## Additional Notes

- Consider including detailed installation instructions (e.g., dependencies, environment setup) if necessary.
- Provide clear instructions on how to customize parameters for different datasets.
- Offer guidance on how to interpret the generated segmentation results.

## Collaboration

We encourage contributions and suggestions to improve this project. Feel free to create pull

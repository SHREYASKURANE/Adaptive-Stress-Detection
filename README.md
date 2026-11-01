# Adaptive Multimodal Sensor Fusion with Explainable AI for Human Stress Detection

Research and prototype work exploring whether physiological signals from multiple wearable-sensor modalities can support stress-state recognition, and how adaptive sensor fusion and explainability can improve the transparency of model outputs.

## Research direction

The project explores multimodal physiological signals, including:

- Electrocardiography (ECG)
- Electrodermal activity (EDA)
- Blood volume pulse (BVP)
- Skin temperature (TEMP)
- Accelerometer (ACC)

The WESAD dataset was considered as a research data source.

## Proposed experimental approach

1. Inspect and preprocess the selected physiological time-series data.
2. Build modality-specific feature representations.
3. Compare basic, adaptive, and advanced fusion strategies.
4. Evaluate machine-learning approaches such as Random Forest and LightGBM.
5. Use SHAP to investigate feature contributions and model behaviour.
6. Present exploratory results through a Streamlit interface, if included in the final implementation.

## Technology areas

Python · Pandas · NumPy · Scikit-learn · LightGBM · SHAP · Streamlit · Multimodal Learning

## Current publication status

This repository currently contains the project overview, not a complete reproducible implementation. Dataset processing, model architecture, train/test protocol, measured performance, and dashboard functionality must be added and validated before results or deployment claims can be made.

This is an academic/research prototype, not a medical or psychological diagnostic tool.

## Suggested reproducibility checklist

- [ ] Add dataset access instructions and licensing notes (do not commit restricted raw data)
- [ ] Add preprocessing and feature-extraction notebooks/scripts
- [ ] Document participant-independent validation and leakage prevention
- [ ] Add fusion-model implementations and baseline comparisons
- [ ] Publish verified metrics, confusion matrices, and limitations
- [ ] Add SHAP analysis and dashboard source code

## Author

Shreyas Kurane · [GitHub](https://github.com/SHREYASKURANE) · [Portfolio](https://shreyaskurane.github.io/portfolio.github.io/)

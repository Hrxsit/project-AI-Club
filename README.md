# Vision Diagnostics AI Club Project

This project evaluates the robustness of a pre-trained ResNet18 model against simulated environmental degradations.

## Degradation Visualizations

| Baseline (Clean) | Turbidity (Murky) | Color Shift (Depth Loss) | Sensor Noise (Low Light) |
| :---: | :---: | :---: | :---: |
| ![Clean](./my_test_images/jellyfish.jpg) | ![Turbidity](./output_images/jellyfish_turbidity.jpg) | ![Color Shift](./output_images/test_colorshift_jellyfish.jpg) | ![Sensor Noise](./output_images/jellyfish_sensor_noise.jpg) |

## Model Diagnostic Results
* **Baseline:** Predicted *jellyfish* (99.49% confidence)
* **Turbidity:** Predicted *jellyfish* (84.93% confidence)
* **Sensor Noise:** Predicted *wool* (48.26% confidence) ❌

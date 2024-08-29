# Cancer-Detection
This dataset is designed for developing a machine learning model that classifies tumors as malignant (M) or benign (B) based on features derived from cell nucleus images. The key objective is to utilize these features to predict the diagnosis of a tumor, thereby aiding in early and accurate cancer detection.


Target Variable (y):

Diagnosis: Indicates whether a tumor is malignant (M) or benign (B).
Features (X):

Radius: Average distance from the center to the perimeter of the nucleus.

Texture: Variation in gray-scale intensity values.

Perimeter: Boundary length of the nucleus.

Area: Size of the nucleus.

Smoothness: Local variations in the radius, indicating boundary smoothness.

Compactness: Shape compactness, calculated as (perimeter² / area) - 1.0.

Concavity: Depth of concave areas in the nucleus contour.

Concave Points: Number of concave areas in the contour.

Symmetry: Symmetry of the nucleus shape.

Fractal Dimension: Measure of boundary complexity.

For each feature, three metrics are provided:


Mean: Average value.

Standard Error: Measurement variability.

Largest/Worst: Extreme observed value

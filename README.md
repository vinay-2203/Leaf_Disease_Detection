Objective of this Project
To develop a Deep Learning Model Capable to indentifying and classifying leaf disease using image data. 
The Project aim to assist Farmers and agronomists in early Diagnosis and timely treatment recommendations.

CNN - Based Leaf Disease Detection
  1. Input Image
    1. Leaf image (infected or healthy) is taken as input.
    2. Image is resized to a fixed size (e.g., 64×64 ) for uniformity.

  2. Preprocessing
     1.Image is converted to array format.
     2.Pixel values are normalized (divided by 255) to bring them into the [0,1] range.

  3. Feature Extraction via Convolution Layers
      1.Convolution layers apply filters (kernels) to detect edges, textures, spots, color patterns.
      2.These filters learn to identify disease-related features like:
          1.Spots
          2.Discoloration
          3.Mold patterns
          4.Holes or wrinkles
  4. Activation and Pooling
     1. ReLU activation makes the model non-linear.
     2. Pooling layers (like MaxPooling) reduce spatial dimensions while keeping important features.
  5.Pooling
     1.2D feature maps are flattened into a 1D vector to feed into dense layers.
  6.Dense Layer
       Dense layers process the flattened data and classify the image into one of the known disease categories:
       1.Healthy
       2.Leaf Blight
       3.Leaf Spot
       4.Rust, etc.
  7.Output Layer
     1.Final layer gives probability scores for each disease class.
     2.The class with highest probability is selected as the prediction.
  8.Prediction
    The model outputs:
    "This leaf is affected by Leaf Spot with 94.57% confidence."


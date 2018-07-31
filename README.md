# deep-echo
Deep learning for echocardiography

The ssl-gan directory lists the code for implementing semi-supervised generative adversarial networks for image classification that we used for view and LVH (left ventricular hypertrophy) classification.

The pipeline directory contains the code for models used in solely supervised techniques (segmentation then classification) for the same classification tasks as above.

Before running, PyTorch (for ssl-gan) and Keras/Tensorflow (for pipeline) should be installed. We suggest updating the architecture to reflect the image dimensions for the particular user's task. The comments describe more in-depth usage (including command-line arguments) and implementation details. For further assistance in adapting the code to your purposes, feel free to contact authors.

# Blood-Cell-Detection-TFOD-2.0

This project demonstrates the use of TensorFlow Object Detection API to automatically detect Red Blood Cells (RBCs), White Blood Cells (WBCs), and Platelets in each image taken via microscopic image readings.

The dataset used in this project was collected from [here](https://github.com/Shenggan/BCCD_Dataset).

The directory structure looks like so:

```
.
├── BCCD-Dataset
│   ├── test
│   └── train
├── LICENSE
├── README.md
├── annotations
│   └── label_map.pbtxt
├── assets
│   └── example.jpeg
├── export_tflite_graph_tf2.py
├── exporter_main_v2.py
├── generate_tfrecord.py
├── model_main_tf2.py
├── models
│   └── pipeline.config
├── output_images
│   ├── four.png
│   ├── one.png
│   ├── three.png
│   └── two.png
└── results_graph
    ├── classification_loss.png
    └── total_loss.png
```

## Sample Image

# Alpaca_detection_YOLOV8 🦙

<div align="center">
  <img src="https://github.com/EmanAbdelWhab/Alpaca_detection_YOLOV8/assets/103004153/0298ccd1-be1d-452f-a84e-4b7ca4628d8d.jpg" alt="Alpaca Detection Example" width="300">
</div>

## Introduction 📜

Welcome to the Alpaca Detection project, powered by YOLO (You Only Look Once) deep learning algorithm. This repository aims to showcase accurate and efficient real-time alpaca detection in images.

## Methodology 🧪

Our approach to achieving accurate alpaca detection involves the following key steps:

1. **Dataset Collection and Annotation 📊:**
   We curated a custom dataset of diverse alpaca images. Each image was meticulously annotated with bounding boxes around alpacas to create ground truth data.

2. **YOLO Model Configuration ⚙️:**
   We employed the YOLOv8 architecture as our base model due to its robustness and real-time capabilities. The `yolov8.cfg` configuration file was customized to adapt the model for alpaca detection.

3. **Training Strategy 🏋️‍♂️:**
   The dataset was split into training and validation sets. We trained the YOLO model using these datasets for a specific number of iterations, fine-tuning its parameters for optimal performance.

4. **Model Evaluation 📈:**
   We evaluated the trained model's performance on a separate test set. Metrics such as precision, recall, and mean average precision (mAP) were calculated to quantify the model's accuracy.

5. **Inference and Detection 🔍:**
   The trained YOLO model was utilized to perform real-time alpaca detection on new images. The detection script `detect.py` allows users to input their own images for detection.

## Getting Started 🚀

### Installation 💻

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-username/alpaca-detection-yolo.git
   cd alpaca-detection-yolo
   ```

2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

### Usage 📝

1. **Download Pre-trained Weights:**
   Download the pre-trained YOLO weights from [YOLO website](https://pjreddie.com/darknet/yolo/) and place them in the `weights/` directory.

2. **Detect Alpacas:**
   Run the detection script on an image:
   ```sh
   python detect.py --image path/to/image.jpg
   ```

## Results 📊

Our trained YOLO model achieves an impressive 0.7 mPA on the alpaca detection task. Example results are showcased in the `results/` directory.

![results](https://github.com/EmanAbdelWhab/Alpaca_detection_YOLOV8/assets/103004153/9c40aec0-f9e7-4210-8d4d-69545c4f7538)

</div>

<div class="section">
  
## Output




https://github.com/EmanAbdelWhab/Alpaca_detection_YOLOV8/assets/103004153/da6bb745-c628-4bb6-a44d-c7bc75d8acf3







## Contributing 🤝

We embrace contributions to enhance this project! Please feel free to report issues or submit pull requests to make this project even better.

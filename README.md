# Roaddamgedetection
UNMANNED AERIAL ROAD DAMAGE DETECTION USING CONVOLUTIONAL NEURAL NETWORKS

Unmanned Aerial Road Damage Detection using Convolutional Neural Networks is a smart system designed to identify road surface defects using aerial imagery. The project leverages drone-captured images for efficient and wide-area road monitoring. A Convolutional Neural Network (CNN) is trained to detect and classify various types of road damages such as cracks and potholes. This automation reduces manual inspection efforts and improves road maintenance planning. The system enhances accuracy, speed, and safety in infrastructure monitoring using modern AI techniques.

TECH STACKS
- **Language**: Python
- **Deep Learning Framework**: PyTorch, TorchVision
- **Model**: CNN + YOLOv8
- **Libraries**: OpenCV, NumPy, Pandas, Matplotlib
- **Tools**:  Google Colab, Jupiter Notebook

 DATASET
- Custom-labeled dataset containing **UAV-captured road images**.
- Classes: `pothole`, `longitudinal crack`, `transverse crack` and `repair`.

MODEL ARCHITECTURE
- **CNN-based classification model**
- **YOLOv8** object detection for real-time bounding box predictions.
- Data augmentation applied to improve generalization.

INSTALAATION
Clone the repository and install dependencies.
git clone https://github.com/bharat1721/Roaddamgedetection.git
cd Roaddamgedetection
pip install -r requirements.txt


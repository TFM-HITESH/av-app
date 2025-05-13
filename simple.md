| Task Description               | AI/ML Models                       | Sensor Used       | Application              | Domain                        |
| ------------------------------ | ---------------------------------- | ----------------- | ------------------------ | ----------------------------- |
| **DEFENSE & SECURITY**         |
| Radar signature classification | SVM, ResNet-1D                     | Continental Radar | Perimeter Security       | Defense & Security            |
| LiDAR intrusion detection      | DBSCAN, PointNet                   | 32-Ch LiDAR       | Base Protection          | Defense & Security            |
| **SMART CITIES**               |
| Traffic light state detection  | HSV Thresholding, YOLOv4-Tiny      | Perception Camera | Traffic Management       | Smart Cities & Urban Mobility |
| Ultrasonic parking detection   | Thresholding, TinyML CNN           | Ultrasonic        | Smart Parking            | Smart Cities & Urban Mobility |
| **INDIA-SPECIFIC**             |
| Pothole depth measurement      | RANSAC, 3D Line Fitting            | 32-Ch LiDAR       | Road Maintenance         | India-Specific Applications   |
| Traffic horn detection         | MFCC+CNN, Audio Transformer        | Perception Camera | Noise Monitoring         | India-Specific Applications   |
| **TRANSPORTATION**             |
| IMU trajectory estimation      | Kalman Filter, Madgwick AHRS       | IMU               | Fleet Tracking           | Transportation & Logistics    |
| Radar vehicle counting         | CFAR Detection, RadarOD            | Continental Radar | Traffic Analysis         | Transportation & Logistics    |
| **AGRICULTURE**                |
| Crop health monitoring         | Color Thresholding, MobileNetV2    | Perception Camera | Precision Farming        | Agriculture                   |
| Tree trunk detection           | Circle Fitting, RangeNet++         | 32-Ch LiDAR       | Orchard Navigation       | Agriculture                   |
| **CONSTRUCTION**               |
| Material level monitoring      | Time-of-Flight Regression          | Ultrasonic        | Inventory Management     | Construction                  |
| Construction volume estimation | Voxel Grid, Poisson Reconstruction | 32-Ch LiDAR       | Site Tracking            | Construction                  |
| **EMERGING TECH**              |
| Precipitation detection        | Texture Analysis, WeatherNet       | Perception Camera | Weather-Adaptive Driving | Emerging Technologies         |
| Slippery road detection        | RF Classifier, IceNet              | Continental Radar | Winter Safety            | Emerging Technologies         |
| **EDUCATION**                  |
| Classroom occupancy monitoring | Background Subtraction, YOLO-Nano  | Perception Camera | Space Utilization        | Teaching + Education          |
| **HEALTHCARE**                 |
| Wheelchair obstacle detection  | Threshold Detection, TinyML        | Ultrasonic        | Assisted Mobility        | Healthcare                    |
| Mask compliance checking       | HSV Masking, EfficientDet-Lite     | Perception Camera | Hospital Safety          | Healthcare                    |
| **RESEARCH**                   |
| Vehicle vibration analysis     | FFT Analysis, LSTM                 | IMU               | Road Quality Assessment  | Research                      |

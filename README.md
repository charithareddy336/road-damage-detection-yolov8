# Road Damage Detection using YOLOv8

This project is a road damage detection application developed using the YOLOv8 object detection framework. The system is designed to identify and classify different types of road damage from images, videos, and real-time camera feeds.

The objective of the project is to explore the application of deep learning and computer vision techniques for automated road inspection and infrastructure monitoring.

## Performing Detection Using Image
![Detection using image](resource/RDD_Image_Example.gif)

## Performing Detection Using Video
![Detection using video](resource/RDD_Video_Example.gif)

Damage Categories

The model can detect the following types of road damage:

Longitudinal Crack
Transverse Crack
Alligator Crack
Potholes
Technologies Used
Python
YOLOv8
Streamlit
OpenCV
NumPy
Pandas
Features
Real-time road damage detection
Image-based damage detection
Video-based damage detection
Interactive Streamlit web application
Deep learning-based object detection
Running on Local Server
# Create environment
conda create -n rdd python=3.8
conda activate rdd

# Install dependencies
pip install -r requirements.txt

# Run application
streamlit run Home.py
Dataset

The project utilizes the RDD2022 (Road Damage Detection) dataset, which contains annotated road images collected from multiple countries for road damage detection research.

Applications
Automated road inspection
Smart city infrastructure monitoring
Road maintenance planning
Transportation safety analysis
Future Improvements
Severity classification of road damages
Analytics dashboard
GPS-based damage reporting
Mobile application integration
Project Structure
RoadDamageDetection/
├── Home.py
├── pages/
├── models/
├── resource/
├── sample_utils/
├── training/
└── README.md
Acknowledgements
RDD2022 Road Damage Detection Dataset
Ultralytics YOLOv8 Framework
Streamlit

## License and Acknowledgements

This project utilizes the RDD2022 Road Damage Detection Dataset and the YOLOv8 object detection framework.

Special thanks to:

* RDD2022 Road Damage Detection Dataset
* Ultralytics YOLOv8 Framework
* Streamlit

## Future Improvements

* Severity classification of road damages
* Analytics dashboard for damage statistics
* GPS-based damage reporting
* Mobile application support
* Improved model performance and optimization

## Conclusion

This project demonstrates the application of deep learning and computer vision techniques for automated road damage detection. By leveraging YOLOv8 and Streamlit, the system provides an intuitive interface for detecting road defects from images, videos, and real-time camera feeds, making it a useful tool for infrastructure monitoring and road maintenance analysis.

## Author

Charitha Reddy

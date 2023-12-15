## Automatic Number Plate Recognition System

### Overview

This repository contains the implementation of an Automatic Number Plate Recognition (ANPR) System. The primary objective is to detect the region of a vehicle's number plate, extract individual characters, and eventually recognize those characters using machine learning techniques.

### Key Components

1. **Number Plate Region Detection:**
   - Utilizes image processing techniques to identify the region containing the vehicle's number plate.
   - Achieved through a combination of image segmentation, edge detection, and contour analysis.

2. **Character Detection:**
   - Once the number plate region is identified, the system extracts individual character boxes.
   - This involves further image processing techniques, such as contour analysis and bounding box detection.

3. **Character Recognition (In Progress):**
   - The repository currently focuses on preprocessing and character-level detection.
   - Future development includes training a machine learning model for character recognition.

4. **Object Detection for Plate Bounding Box (Planned):**
   - There are plans to enhance the system by incorporating object detection techniques.
   - YOLO (You Only Look Once) will be explored for detecting the entire number plate bounding box.

### How to Use

1. **Clone the Repository:**
   ```
   git clone https://github.com/prabinbohara10/Automatic-Number-Plate-Recognition-System.git
   cd Automatic-Number-Plate-Recognition-System
   ```

2. **Install Dependencies:**
   - Ensure you have the necessary dependencies installed. Detailed instructions can be found in the `requirements.txt` file.

3. **Run the Code:**
   - Execute the main script or Jupyter notebook to see the system in action.

### Future Development

1. **Character Recognition Model:**
   - Train a machine learning model to recognize individual characters.

2. **Object Detection for Plate Bounding Box:**
   - Implement YOLO or similar techniques for detecting the entire number plate bounding box.

3. **Integration with External Systems:**
   - Explore options for integrating the ANPR system with external databases or security systems.

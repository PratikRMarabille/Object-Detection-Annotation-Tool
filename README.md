# Object-Detection-Annotation-Tool
Object Detection and Annotation Tool is designed to identify objects within an image. It not only detects existing objects but also provides a user-friendly interface to annotate any undetected objects. The tool allows users to save annotated images in both YOLO and PASCAL VOC formats.

 ## Demo
 https://github.com/PratikRMarabille/Object-Detection-Annotation-Tool/assets/155374707/0ad8e503-359c-47ff-a892-b5bac27a4fe5

 ## Installation

 Clone the repository: git clone "https://github.com/PratikRMarabille/Object-Detection-Annotation-Tool.git" <br/>
 Change to the repository directory: ```cd Object-Detection-Annotation-Tool ``` <br/>
 Create a virtual environment: ```python -m venv env_name```

 ## Requirements
```bash
    pip install ultralytics
    pip install -r requirements
```
## Usage

* Execute the application using the command: ```streamlit run app.py``` 
* A new browser window will open, displaying the app.
* The main page showcases an initial image alongside its corresponding object-detected version. 
* Upload an image by clicking the "Browse files" button.
* If some objects are not detected then use the Object annotation tool.
* Select the image, start to add bounding box by clicking on the Add bounding box then name the object using the drop down menu.
* Then click on the save button.
* The annotated image will get saved in the YOLOv8 as well as PASCAL VOC format.
* The YOLOv8 formate will get saved in the labels directory and PASCAL VOC format will get saved in the img_dir.

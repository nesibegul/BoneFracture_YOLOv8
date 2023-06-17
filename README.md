This project is about the bone fracure detection with YOLOv8 model. The model is trained with 1036 images from elbow and hand areas splitted in % 75, 15, and 10 % for train, validation, and test parts. The yolov8l model is used with sgd and adam optimization models. The best result is got with sgd and 0.01 learning rate.
# BoneFracture_YOLOv8
### to create environment
```
conda create --prefix ./venv python -y 
```
### to activate environment
```
conda activate ./venv
```
### to install requirements
```
pip install -r requirements.txt
```
### to activate streamlit
```
streamlit run app.py
```


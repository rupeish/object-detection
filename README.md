<strong>Object Detection</strong><br>

create virtual environment<br> 
`python3 -m venv name`<br>

Start virtual environment<br>
`source name/bin/activate`<br>

Install requirements<br>
`pip install -r requirements.txt`<br>

Download yolov3 weights trained on coco dataset<br>
`wget https://pjreddie.com/media/files/yolov3.weights`<br>

Move downloaded weights to weights folder <br>

Change yolov3 weights to tensorflow2 <br>
`python load_weights.py`<br>

Run flask app<br>
 `python app.py` <br>

Go to <br>
`http://0.0.0.0:5000/`

Demo
![Home](https://github.com/rupeish/object-detection/blob/master/data/images/Screenshot%20from%202020-06-05%2013-32-58.png)
<br>
![Home](https://github.com/rupeish/object-detection/blob/master/data/images/Screenshot%20from%202020-06-05%2013-33-09.png)
<br>

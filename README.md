# Alexander_Shin_CPE-490-590-ST_hw05.
To run the webapp, make sure to make a directory to store the following data tree:
~/(any_folder_name)
  -app.py
  -MNIST_classifier.onnx
  -static
    -css
      -styles.css
    -js
      -script.js
  -templates
    -index.html

Next, open any powershell able to run python.
Personally, I used Anaconda Prompt.
Apparently, Git Bash could also work.

Move to the directory into the (any_folder_name) using "cd any_folder_name"
Run " python3 -m venv venv " and "uv venv" to create and then open a virtual python environment
Install dependencies using:
"pip install flask numpy onnxruntime pandas scikit-learn gunicorn flask_wtf werkzeug wtforms pillow python-magic-bin."
Finally, the webpage can be open through "python app.py."

URL of python notebook used for the first part of the homework: 
https://colab.research.google.com/drive/1DL00d7P_xrhUflye_ABn7Nw4z2ntwR0U?usp=sharing

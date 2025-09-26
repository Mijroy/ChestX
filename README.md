Keras == 2.3.1
tensorflow-gpu == 1.15.0
python == 3.6.13

pip install numpy==1.19.5 pandas matplotlib seaborn h5py opencv-python scikit-learn

(the "Chest_X-Ray_Diagnosis.yaml" show my env using anaconda)

Caution:
There maybe error: AttributeError: 'str' object has no attribute 'decode'
need to go to "lib\site-packages\keras\engine\saving.py", remove .decode('utf8') in the code.



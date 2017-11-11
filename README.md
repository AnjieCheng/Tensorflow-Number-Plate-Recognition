# Tensorflow-Number-Plate-Recognition

## Dependencies
```
TensorFlow 1.0
OpenCV
NumPy
```

## Usage
1. Download pretrained model `weights.npz` from [here](https://drive.google.com/file/d/0B-MtVXQMUxQiZElfSy1ON09QQ0U/view?usp=sharing).
2. Place `weights.npz` in the same directory of `source.py`.
3. `./detect.py in.jpg weights.npz out.jpg`

## Other
1. Codes are credited to [Matthew Earl](https://github.com/matthewearl)'s [Deep Anpr](https://github.com/matthewearl/deep-anpr).
2. To genereate your own training dataset, please refer to the original repository and retrain you model.

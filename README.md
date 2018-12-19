# tensorflow-ocr
🖺 OCR using tensorflow with attention

# Installation
```
git clone --recursive http://github.com/pannous/tensorflow-ocr
pip install -r requirements.txt

```
You can detect the text under your mouse pointer with `mouse_prediction.py`

To combine our approach with real world images we forked the [EAST](https://github.com/quasiris/EAST) boundary boxing.


To get started with a minimal example similar to the famous MNIST try
`./train_letters.py` ;
It automatically generates letters for all different font types from your computer in all different shapes and trains on it.

For the full model used in the demo start `./train.py`
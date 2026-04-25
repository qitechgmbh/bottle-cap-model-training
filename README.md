# bottle-cap-model-training
Simple Training notebooks we use for our bottlecap detection model
Image files and other large binary files are added into git lfs.
If you havent already then install git lfs before cloning.

Prerequisites:
You need to install support for jupyter notebook to train this ai model.

After cloning inside the repo directory execute: 
```
git-lfs pull
```
to replace the textual references with the actual files.

Afterwards just run all of the steps in the training.ipynb , and you can rebuild the yolo model.
After that you can export to ONNX format as well by running all of the steps in onnx_export.ipynb

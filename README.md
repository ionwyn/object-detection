# Object Detection

A small project utilizing RetinaNet object detection module developed by **Tsung-Yi Lin at Facebook AI Research (FAIR)**, implemented with **Keras**, (the original project by FAIR is called [**Detectron**](https://github.com/facebookresearch/Detectron)).  For the paper and libraries used, see References below.  For installation, see instructions

# Steps taken inside the code

  1. Declare object detection module as implemented by [**AI Commons**](https://commons.specpal.science/projects/)
  2. Set *RetinaNet* as the model type.
  3. Use a pre-trained model.  You can find the latest version [here](https://github.com/fizyr/keras-retinanet/releases) or on [**Kaggle**](https://www.kaggle.com/) (search yourself.)
  4. Magic

That's it.

# Installing
```
pip install tensorflow numpy scipy pillow matplotlib h5py keras opencv-python
```

# Running
Default parameters:
- An image for the input, you can put it on the same directory.  Default name for image is *ilia.jpg*
- Default model: *resnet50_coco_best_v2.1.0.h5*.

![ilia.jpg](https://github.com/ionwyn/object-detection/blob/master/ilia.jpg "logo")
```
python objD.py
```
If everything runs smooth as criminal, you should see *iliaRevealed.jpg*

![iliaRevealed.jpg](https://github.com/ionwyn/object-detection/blob/master/iliaRevealed.jpg "logo2")

# Did you make the whole thing?

No.  As said, I am only using algorithms and pre-trained models that were developed by **FAIR** and **ImageAI**.  The reason why this is on GitHub is because later on I'm planning to do use it for future projects.  The reason why it's public is because of **Contributor Agreements**, so this project, despite having *30 lines of code*, has to be open-sourced.

# Trouble? Questions?

Submit an issue.

# Training your own model

[Good luck with that](https://github.com/fizyr/keras-retinanet)

# References

- [The paper](https://arxiv.org/pdf/1708.02002.pdf)
- [AI Commons](https://commons.specpal.science/)
- [Detectron](https://github.com/facebookresearch/Detectron)
- [Keras RetinaNet](https://github.com/fizyr/keras-retinanet)
- [ImageAI](https://github.com/OlafenwaMoses/ImageAI)
- [TensorFlow](https://github.com/tensorflow/tensorflow)
- [Keras](https://github.com/keras-team/keras)

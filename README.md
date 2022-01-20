# character-recognition-diagnosis
Randomly revealing portions of characters to understand the use of visual information in neural nets and human perception

```createBubbledStim.ipynb``` generates stimuli by randomly revealing certain portions of images of characters, which are later used as inputs to the model as well as experimental stimuli for participants.

```english diagnostic planes human data.ipynb``` analyzes some pilot data to characterize which regions are more informative when people perform character classification

```notMNIST_classification_proportionPlane.ipynb``` trains a LeNet on notMNIST and then evaluates it on bubbled stimuli to characterize which portions of images are more informative for classification by the model

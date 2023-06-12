## Pen & Paper Task

### (a)

One probable approach for the colour probing task can be to fine tune CLIP on an object (image) to colour (text) pair dataset. The underlying research question then can be whether CLIP is more suitable for more generalised multimodal perception (object text similarity, zero shot object detection) or can it tend to specific probes as well?

Without fine-tuning, attention maps from text and vision encoders of CLIP can be inspected (seaprately and combined). It may be possible that CLIP captures color information but it gets lost in the higher levle layers of the encoders.

### (b)

Both encoders in CLIP are transformer based (except if Resnet is used as the vision model). So the attention maps can be compared with colour probing as a target.

Even for Resnet, the feature maps can be inspected.

### (c)

Since BERT based models are trained with the masked modelling objective, the fusion models which use BERT or BERT variants for the text model can also probed for colour probing using masked methods, as was done in the previous assignment on RoBERTa.

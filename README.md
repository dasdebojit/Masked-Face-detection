# Masked-Face-Recognition
## About the Project:
<p> This project uses CNN with Transfer Learning to classify whether a face is masked or not. It uses RESNET-18 Backend with pretrained weights, and customized final layers for Binary Classification (Masked/ Not-Masked).
</p>

## Languages/ Tools used:
<ul>
  <li> Python </li>
  <li> Jupyter Notebook </li>
  <li> Pytorch </li>
</ul>

## Dependencies:
<ul>
  <li> OpenCV </li>
  <li> PILLOW </li>
  <li> Resnet-18 (Architecture + Weights) </li>
  <li> Face_detection Library </li>
</ul>

## Dataset
RWMFD (Real World Masked Face Dataset)
## Inferences from dataset:
Since the dataset didn't contain accurately cropped image consisting of just the face, face_recognition library was applied on the images, to get closeup cropped imgages.
### Some examples of closely cropped masked images
<img src = "/Images/masked.png"/>
### Some examples of closely cropped unmasked images
<img src = "/Images/unmasked.png"/>

## Training Results
After training for 10 epochs the training loss graphs is as shown below:
<img src = "/Images/training.png" />
The validation accuracy is almost 94 % after 10 epochs.
<img src = "/Images/validation.png" />

## Testing Result
After testing a total of around 150 images, the testing accuracy stands at 97% which can be inferred from the results shown below:

<img src = "/Images/result.png" />

## Scopes of Improvement
1. Since the dataset was small, using a large number of images might result in better accuracy.
2. Since the model is dependent on face detection, greater occlusions in face due to mask might be the reason for incorrect prediction sometimes.
3. Face detection module doesn't help identify skewed faces so accurately especially when the size of face is so small. 




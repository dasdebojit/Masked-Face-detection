# Masked-Face-Detection
## About the Project:
<p> This project uses CNN with Trasnfer Learning to classify whether a face is masked or not. It uses RESNET-18 Backend with pretrained weights, and customized final layers for Binary Classification (Masked/ Not-Masked).
</p>

## Languages/ Framework used:
<ul>
  <li> Python </li>
  <li> Pytorch </li>
</ul>

## Dependencies:
<ul>
  <li> OpenCV </li>
  <li> PILLOW </li>
  <li> Resnet-18 (Architecture + Weights) </li>
</ul>

## Dataset
RWMFD (Real World Masked Face Dataset) contains 5,000 masked faces of 525 people and 90,000 normal faces. For more information click <a href = "https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset" > <strong> here </strong></a>

## Results:
After training the model for 10 epochs, the best model provided a loss of 0.027 and a very good validation accuracy. On evaluating it on the test sets, an overall accuracy of 0.99 is achieved.

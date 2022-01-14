# Machine Learning Projects

This project focuses on Computer Vision which process image input to detect and classify object from annotated label

## ASL Classification

<ul>
  <li>Predict and Classify 29 alphabet from American Sign Language, a natural language that serves as the predominant sign language of Deaf communities in the United States and most of Anglophone Canada, expressed by facial expression as well as movements and motions with the hands</li>
  <li>87000 image datasets from https://www.kaggle.com/grassknoted/asl-alphabet</li>
  <li>Using Resnet50 Pre Trained model from Keras tuned with Bacth Normalization & Dropout layer, So the total paramaters from the model is 25.673.933 params</li>
  <li>Early stopping & Reduce LR On Pletau as regularization techniques</li>
  <li>Only with 2 epoch and reach 99.75% accuracy & 1.51% loss</li>
</ul>

## Rebar Count Detection

<ul>
  <li>Detect and counting rebar (steel bar) in image. Works in steel manufacturers and construction sites that usually managed manually, which inefficient in terms of cost and time-consuming</li>
  <li>200 image dataset provided by Huawei for the benefit of the competition</li>
  <li>Using Mask-RCNN Object Detection, and reach 68.1% mAP train and 64.7% mAP test</li>
</ul>

## Road Damage Real Time Object Detection

<ul>
  <li>Detect and classify 3 types of road damage (Pothole, Longitudinal Crack, Alligator Crack) in real time conditions. Helps to streamlined the road damage survey process by reducing costs, time and effort</li>
  <li>Approximately 18000 road damage image dataset, annotated manually with labelimg. The label distribution is 44% longitudinal crack, 37% alligator crack, 15% photole, and 4% shadow</li>
  <li>Using SSD MobileNet V2 pre-trained model in Tensorflow Object Detection API, and reach 8.7% mAP in 50.000 steps</li>
</ul>

# Multimodal Failure Prediction for Vision-based Manipulation Tasks with Camera Faults
Yuliang Ma*, Jingyi Liu, Ilshat Mamaev, and Andrey Morozov

{yuliang.ma@ias.uni-stuttgart.de}

<img src="/figures/sample_trajectory.png" height="280" /><img src="/figures/sample_lidar.png" height="278" />
## Abstract
Due to the increasing behavioral and structural complexity of robots, it is challenging to predict the execution outcome after error detection. Anomaly detection methods can help detect errors and prevent potential failures. However, not every fault leads to a failure due to the system's fault tolerance or unintended error masking. In practical applications, a robotic system should have a potential failure evaluation module to estimate the probability of failures when receiving an error alert. Subsequently, a decision-making mechanism should help to take the next action, e.g., terminate, degrade performance, or continue the execution of the task. This paper proposes a multimodal method for failure prediction for vision-based manipulation systems that suffer from potential camera faults. We inject faults into images (e.g., noise and blur) and observe manipulation failure scenarios (e.g., pick failure, place failure, and collision) that can occur during the task. Through extensive fault injection experiments, we created a FAULT-to-FAILURE dataset containing 4000 real-world manipulation samples. The dataset is subsequently used to train the failure predictor. Our approach processes the combination of RGB images, masked images, and planned paths to effectively evaluate whether a certain faulty image could potentially lead to a manipulation failure. Results demonstrate that the proposed method outperforms state-of-the-art models in terms of overall performance, requires fewer sensors, and achieves faster inference speeds. 
## Description of the code

## Dataset
[\[dataset\]](https://www.kaggle.com/datasets/yuliangma/proactive-failure-prediction)

## Citation


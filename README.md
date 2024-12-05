<div align="center">
  <p>
    <a >
       <img width="100%" src="https://github.com/user-attachments/assets/bfb95dfe-466e-4cd6-b7f3-3c5c755f999b"> </a>
            
  </p>
<br>
</div>


## <div align="center">Efficient YoloPose</div> 
<div align="justify">

Efficient YoloPose is a deep learning-based architecture designed to balance computational efficiency and accuracy for real-time multi-person pose estimation. This repository contains the implementation of Efficient YoloPose, which improves upon YOLOv8-Pose by incorporating advanced lightweight techniques, reducing computational demands while maintaining high performance, particularly for resource-constrained devices.
</div>  

## <div align="left"> Overview</div> 
<div align="justify">
Human pose estimation (HPE) is crucial for various real-time applications, but achieving high accuracy with low computational overhead is a challenge, especially on resource-constrained devices. Efficient YoloPose addresses this challenge by optimizing YOLOv8-Pose with lightweight components to achieve both efficiency and accuracy.
Efficient design: Utilizes Depthwise Convolution, Ghost Convolution, and C3Ghost to reduce model size and complexity.
Advanced attention mechanism: Integrates Squeeze Excitation (SE) attention for improved feature extraction.
Superior performance: Reduces inference time, computational complexity, and parameter count compared to traditional models like YOLOv8-Pose.
</div>  

## <div align="left"> Key Features</div> 
  <div align="justify">
- Improved Inference Time: The proposed model reduces the inference time from 1.1 ms to 0.9 ms.
 </div>  
 <div align="justify">
- Reduced Computational Complexity: The computational complexity decreases from 9.2 GFlops to 4.8 GFlops.
 </div>   
  <div align="justify">
- Lower Parameter Count: The parameter count is reduced from 3.3 million to 1.3 million.
</div>   
  <div align="justify">
- Accuracy: The model achieves an average precision (AP) score of 78.8 on the COCO dataset, outperforming other models in both efficiency and accuracy.
  </div>    
  <div align="justify">
- Lightweight Design: Optimized for resource-constrained devices while maintaining high performance.
</div>  

<img width="100%" src="https://github.co![Weixin Image_20241205175712](https://github.com/user-attachments/assets/f908b7e0-768d-4a4f-a219-9e8d7257ce1b"></a>
![Weixin Image_20241205175638](https://github.com/user-attachments/assets/cfde1263-597a-4ddd-b228-332fa89f2d54)

![Weixin Image_20241205175712](https://github.com/user-attachments/assets/ed3357a5-5cc6-4e96-8b1a-81e26fb1bc58)

## <div align="left"> Performance Comparison</div> 
  <div align="justify">
When compared to YOLOv8-Pose, Efficient YoloPose:
. </div>  
 <div align="justify">
- Reduces inference time
 </div>   
  <div align="justify">
- Lowers computational complexity
</div>   
  <div align="justify">
- Reduces parameter count
  </div>    
  <div align="justify">
-  Maintains competitive accuracy
</div>  

## <div align="left"> Datasets Used</div> 
  <div align="justify">
The model was evaluated on the following datasets:
. </div>  
 <div align="justify">
- COCO: Common Objects in Context, a large-scale object detection dataset.
 </div>   
  <div align="justify">
- OCHuman: A dataset specifically designed for human pose estimation.
</div>   


## Installation

To use Efficient YoloPose, clone this repository to your local machine:

```bash
git clone https://github.com/malareeqi/Efficient-YoloPose.git
cd Efficient-YoloPose
```
Install the required dependencies:
```bash
pip install -r requirements.txt
```
Usage
```bash
yolo pose predict model=Efficient YoloPose.pt
```
## <div align="center">Note</div>

This repository is actively being improved, with continuous updates and optimizations underway. Check back for the latest improvements and updates to the model's performance and capabilities.



## <div align="center">Citation</div>
If you use this model in your research or projects, please cite the following:
```python
@article{EfficientYoloPose,
    title={Resource-Aware Strategies for Real-Time Multi-Person Pose Estimation},
    author={Mohammed A. Esmail, Jinlei Wang,*,Yihao Wang, Li Sun, Guoliang Zhu, and Guohe Zhang*}
    journal={XXXX.XXXX},
    year={2024}
}
```
## <div align="center">License</div>
 This project is licensed under the MIT License - see the LICENSE file for details.





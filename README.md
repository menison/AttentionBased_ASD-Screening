# Attention-based ASD Screening
This code implements the attention-based ASD screening software.
It is used to predict results on handcrafted data sampled from Tobii 4C/EyeX consumer-level eye-tracking devices.
The underlying model was trained and validated on Saliency4ASD(https://saliency4asd.ls2n.fr/datasets/) dataset.[1]


### Requirements
1. Pytorch: We use Pytorch 1.2.0 in our experiments.
2. Tensorflow: We only use the tensorboard for visualization.
3. Python 3.6+
4. CUDA-Enabled GPU
5. MATLAB
6. Tobii Consumer Eye-Tracker Device (Tested against 4C/EyeX)
7. Latest Tobii Eye-Tracker Driver installed: Tobii.EyeX.Interaction.exe and Tobii.EyeX.Configuration should be present in the '\Tobii\Tobii EyeX Config' path in your PC.

### Data Processing
The code displays images from [Saliency4ASD](https://saliency4asd.ls2n.fr/datasets/) dataset. Please download the dataset accordingly and unzip it to folder `generated/Images`.

### Installation
Extract the folder 'PyProjects' to drive F:/ to create the path 'F:/PyProjects'. The rest is straight-forward, just run the main file and follow the instructions on the screen.
Additional instructions can be find within the 'User Guide: Operating Instructions' section of our book.

python main.py 

## Acknowledgments
We would like to thank Shi Chen and Qi Zhao for their valuable contribution to the field of autism research [1].

### References
[1] Chen, S., & Zhao, Q. (2019). Attention-Based Autism Spectrum Disorder Screening With Privileged Modality. In The IEEE International Conference on Computer Vision (ICCV).


# ImageColorizer
Transform black and white images into beautifully colored images using Deep Learning.

![result.jpg](images/result.png)

- Used pretrained model from [Zhang's Github](https://github.com/richzhang/colorization)  
- Original paper: [Colorful Image Colorization](https://arxiv.org/pdf/1603.08511.pdf)


  

# Requirement
- Python
- OpenCV 3.4.2+
- Numpy
  



- **[Important]** Download the model from the following [link](https://drive.google.com/drive/folders/1hNvYYq9i7XYMhv9AtH9bFXRpxP8YcGo_?usp=sharing) and place it in the `model` folder

- Now excute the following command -
```
python imagecolorizer.py --image <path_to_image>
```
This script requires one arguments be passed to the script directly from the terminal, i.e. **--image** or **-i** which is the path to our input black/white image. All the colorized image will be saved in `output` folder#   I m a g e C o l o r i z e r _ S I T 
 
 

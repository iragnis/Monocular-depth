<h1> Monocular Depth Vision </h1>

Monocular Depth Estimation is the task of estimating the depth value (distance relative to the camera) of each pixel given a single (monocular) RGB image.

This documentation will cover the overview of two models namely: MiDaS and Transformer built on DPT,GLPN model architectures


<h2> 1. MiDaS </h2>

## Dependency

```
pip install timm
```

## Usage

```
python test.py
```

## Inference
![image](https://user-images.githubusercontent.com/97392797/230759964-83537627-8fc2-4d6a-9214-5265153b5236.png)

<h2> 2. Transformers</h2>

## Dependency
```
pip install transformers
```
## Usage
```
python monocular_depth_est.py
```
## Inference
![image](https://user-images.githubusercontent.com/97392797/230759980-8dd0856d-ce41-439b-896a-b63d68bb104e.png)


## Comparative view of the outputs of both models
![image](https://user-images.githubusercontent.com/97392797/230760000-d4998441-fadc-4745-8c39-dd6eb195bf8c.png)


left image - input image <br/>
center image - output of Transformers <br/>
right image - output of MiDaS <br/>


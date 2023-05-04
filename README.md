# OctoPD(Octo=8 Pose Detection)
It's not relate with Meaning Eight, my Team No. is 8, so I select name about the Octo.

# 1. 목적
 ## *미래의 인간을 대신해서 우리를 도와줄 서포트 로봇 휴먼 포징으로 앞의 사람같은게 있다는 것을 모바일 로봇에게 인식시켜보자!*<br><br>


# 1.1 일반 노트북으로 무조건 도전!<br>
## Computer Spec
CPU : Intel CORE i7 <br>
GPU : NVIDIA GTX 2070 <br>
RAM : 16 GB <br>
OS : Linux 22.04 LTS <br>

## Using Library 
Python = 3.10.6<br>
PyTorch = 2.0.0<br>
CUDA = 11.7<br>
cuDNN = 8.2.1<br>

## Pre-Trained Models
- Tiny-YOLO oneclass - [.pth](https://drive.google.com/file/d/1obEbWBSm9bXeg10FriJ7R2cGLRsg-AfP/view?usp=sharing),
[.cfg](https://drive.google.com/file/d/19sPzBZjAjuJQ3emRteHybm2SG25w9Wn5/view?usp=sharing)
- SPPE FastPose (AlphaPose) - [resnet101](https://drive.google.com/file/d/1N2MgE1Esq6CKYA6FyZVKpPwHRyOCrzA0/view?usp=sharing),
[resnet50](https://drive.google.com/file/d/1IPfCDRwCmQDnQy94nT1V-_NVtTEi4VmU/view?usp=sharing)
- ST-GCN action recognition - [tsstg](https://drive.google.com/file/d/1mQQ4JHe58ylKbBqTjuKzpwN2nwKOWJ9u/view?usp=sharing)

<b align="right">
<img src="./Image/IMG_0.gif" width=250 height= 500> 
<b align="left">
<img src="./Image/change.gif" width=400 height= 500>

## 1.2 Micro Controller Unit(MCU)로 도전

## Computer Spec
Model : Jetson NANO 4GB <br>
CPU : Quad-core ARM A57 @ 1.43 GHz
GPU : 128-core Maxwell <br>
RAM : 16 GB <br>
OS : Linux 18.02 LTS <br>
※JetPack = 4.6.3

## Using Library 
PyTorch = .0.0<br>
Python = 3.10.6<br>
CUDA = 10.2<br>
cuDNN = 7.6.5<br>

<a align="center">
<img src="./Image/test.gif"> <br><br><br><br>


<a align="center">
<img src="./Image/000000.jpg">

### 1.3모델융합

#### - 코드 형식 간결화 및 python parser -h 기능  추가 완료
#### - YOLO 모델 TINY v3 를 적용
#### - Pretrained된 MMSKeleton 적용으로 간단한 Sit down, Stand Up, Walking, Fall Down 등을 적용

-------------------------------------------
- 여러 요구상황에 대한 라벨링을 실시 <br>
병원 

add UML

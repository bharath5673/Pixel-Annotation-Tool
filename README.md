# Pixel Annotation Tool
출처 : https://github.com/abreheret/PixelAnnotationTool

이 툴을 간단히 소개하자면, semantic segmentation에 이미지를 학습시키려면 object별로 pixel을 구분하면 구분은 color 및 label등으로 한다.
이 툴을 통하면 간단히? object 구분하는 label mask 이미지를 만들수 있고,
my github에 Semantic-Segmentation에서 자신이 구현하고자 하는 Segmentation을 모델링 할 수 있다

## Using pixel annotation tool for generating mask


## 1. Open tool and select Image folder

## 2. Mask image
- 1)select the config(json) you want to used
- 2)colour the object with the selected colour; you could zoom in/out by changing value of Resize factor and change size of brush by changing Circle size
- 3)if ther are multiple object then select different colour for each object and colour the object a bit
- 4)colour background with different colour
- 5)check watershed mask and click on watershed
- 6)you could change value of alpha mask to make mask more visible
- 7)fine tune mask a bit if required
- 8)see final mask clearly by setting alpha mask 1.0
- 9)save image
- 10)do it for all images in image

## 3. Cut take <image name>_color_mask.png for all images and move it to Annotation folder

참고 유튜브 (https://www.youtube.com/watch?v=tX-xcg5wY4U)

사전에 하기와 같이 label과 rgb를 정의해놓으면 편할 것 같다.
name,r,g,b
Animal,64,128,64
Archway,192,0,128
Bicyclist,0,128, 192
Bridge,0, 128, 64
Building,128, 0, 0
Car,64, 0, 128
CartLuggagePram,64, 0, 192
Child,192, 128, 64
Column_Pole,192, 192, 128
Fence,64, 64, 128
LaneMkgsDriv,128, 0, 192
LaneMkgsNonDriv,192, 0, 64
Misc_Text,128, 128, 64
MotorcycleScooter,192, 0, 192
OtherMoving,128, 64, 64
ParkingBlock,64, 192, 128
Pedestrian,64, 64, 0
Road,128, 64, 128
RoadShoulder,128, 128, 192
Sidewalk,0, 0, 192
SignSymbol,192, 128, 128
Sky,128, 128, 128
SUVPickupTruck,64, 128,192
TrafficCone,0, 0, 64
TrafficLight,0, 64, 64
Train,192, 64, 128
Tree,128, 128, 0
Truck_Bus,192, 128, 192
Tunnel,64, 0, 64
VegetationMisc,192, 192, 0
Void,0, 0, 0
Wall,64, 192, 0
```

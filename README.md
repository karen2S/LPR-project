# LPR-project
Comparing YOLOv5, YOLOv7 and YOLOv8 for Autonomous License Plate Recognition System

Dataset: <br>
&ensp;License Plate Detection<br>
&emsp;		- Plat Nomor Indo (https://universe.roboflow.com/easy-apk-trhqj/plat-nomor-indo)<br>
&emsp;    - OCRv2 (https://universe.roboflow.com/institut-teknologi-sumatera/ocrv2-j2eo6)<br>
&ensp;License Plate Character Recognition<br>
&emsp;    - kombinasi v1 (https://universe.roboflow.com/tes-coba-v1/kombinasi-v1)<br>
&emsp;    - carplatedetection-ocr (https://universe.roboflow.com/institut-teknologi-sumatera/ocrv2-j2eo6)<br><br>

![image](https://github.com/karen2S/LPR-project/assets/107234140/d786ab3b-9975-430d-9a30-23515e15ef70)<br>
The proposed license plate recognition system comprises two key components: <br>
- **License Plate Detection** will be done only with YOLOv8 + NMS (Accuracy = 96.85% from LP user testing -> detect_LP.pt)<br>
- **License Plate Character Recognition** will be done with YOLOv5, YOLOv7 and YOLOv8 (Accuracy = 36.2% from Vehicle user testing -> 10epoch_car.pt)<br>

We have run in total of 22 models

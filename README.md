# LPR-project
Comparing YOLOv5, YOLOv7 and YOLOv8 for Autonomous License Plate Recognition System

Dataset:
	License Plate Detection
		- Plat Nomor Indo (https://universe.roboflow.com/easy-apk-trhqj/plat-nomor-indo)
    - OCRv2 (https://universe.roboflow.com/institut-teknologi-sumatera/ocrv2-j2eo6)
  License Plate Character Recognition
    - kombinasi v1 (https://universe.roboflow.com/tes-coba-v1/kombinasi-v1)
    - carplatedetection-ocr (https://universe.roboflow.com/institut-teknologi-sumatera/ocrv2-j2eo6)

![image](https://github.com/karen2S/LPR-project/assets/107234140/d786ab3b-9975-430d-9a30-23515e15ef70)
The proposed license plate recognition system comprises two key components: License Plate Detection and License Plate Character Recognition
License Plate Detection will be done only with YOLOv8 + NMS (Accuracy = 96.85% from LP user testing -> detect_LP.pt)
License Plate Character Recognition will be done with YOLOv5, YOLOv7 and YOLOv8 (Accuracy = 36.2% from Vehicle user testing -> 10epoch_car.pt)

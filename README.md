# AITHENUTRIGENE, AI Researcher, 04. 2023 - 
• Responsibility : Classification models, location detection, OCR, and more with AI image teams


* Project 1: Azure OCR ( 23.04 ~ 23.07 )
![Azure OCR1](./image/azure_ocr/IMG_8657.JPG)  
![Azure OCR2](./image/azure_ocr/IMG_8657_0.JPG)
    <details>
    <summary> Azure OCR details </summary>
        <div markdown="1">

        - Background : Extracting information from in-store price tags with photography

        – Achievement: 
        • Taking in-store photos. 
        • Locate price tags in the photo. ( Azure computer vision : Object Detection)
        • Identify text within a price tag. ( Azure OCR )
    </div>
    </details>

* Project 2: Shelf object detection ( 23.07 ~ 23.11 )
![shelf_object_detection](./image/shelf_object_detection/output.png)  
    <details>
    <summary> Shelf object detection </summary>
        <div markdown="1">

        - Background : Object detection and image classification on snack shelf

        – Achievement: 
        • Taking in-store snack shelf photos. 
        • Object detect snack in the photo. ( DINO model in deterx library (https://github.com/IDEA-Research/detrex/))
        • Image classification and find snack name ( VIT in timm library)
    </div>
    </details>


* Project 3: Commercial vehicle classification ( 23.11 ~ 24.08 )
![Commercial vehicle](./image/Commercial_vehicle_classification/Commercial_vehicle_classification.png)
    <details>
    <summary> Commercial vehicle classification </summary>
        <div markdown="1">

        - Background : A project to check with AI whether the contents of the photo and the entered vehicle information match in commercial vehicles

        – Achievement: 
        • Input 6 images and vehicle information through the app.
            • Vehicle photos 4(front, back, right, left)
            • Vehicle information 3 (car type , car license plate, vehicle identification number(VIN) )
        • Image classification by combining four images. ( Swin-Transformer V2 (https://github.com/microsoft/Swin-Transformer) )
            • Anomaly detection through slightly unsupervised methods
        • Commercial vehicle license plate details and VIN OCR ( Use PaddleOCR Directly (https://github.com/PaddlePaddle/PaddleOCR/tree/release/2.7.1) )
    </div>
    </details>



# SPILAB, AI Researcher 07. 2020 - 11. 2021
• Responsibility : collaborated with the CEO on the start-up and external aspects of the project, while leading the development and execution of the work tasks

* Project 1: Car Plat OCR
    <details>
    <summary> Car Plat OCR details</summary>
        <div markdown="1">
        
        
        - Background : Check the type and license plate number of the vehicle entering the electric vehicle charging station

        – Achievement: 
        • Raspberry pi 4 Image Collection. 
        • Electronic car plate generate (image aug-mentation). 
        • Car Plate Detection (Yolo v4, v5). 
        • Optical Character Recognition (BidirectionalLSTM).

        - link : https://github.com/forallx94/Electronic-Car-Generate

    </div>
    </details>

* Project 2: Grass disease detection
![grass_disease_detection](./image/grass_disease_detection/place_mountain1_date_May6_Time_1720_speed_3_Height_5M_6.jpg)
    <details>
    <summary> Grass disease detection details</summary>
        <div markdown="1">

        - Background : Check the condition of the grass and the presence of diseases through drone images taken in the morning at the golf course

        – Achievement: 
        • Switch uploaded videos to images. 
        • Grass disease detect (EfficientNet B5).
        • Upload result at MongoDB.
    </div>
    </details>

* Project 3: Cancer Clinical Trials Eligibility
![CCTE](./image/CCTE/001.png)
    <details>
    <summary> Cancer Clinical Trials Eligibility details </summary>
        <div markdown="1">
        - Background : Using cancer clinical trial data to provide additional information on new patients

        – Achievement: 
        • Data preprocessing. 
        • Word Embedding (TF-IDF, Word2Vec, BERT).
        • Network Anlysis, Clustering (HDBSCAN, Hierarchical Clustering). 
        • keyword extraction.

    </div>
    </details>

* Project 4: Smart Factory IoT Unsupervised Anomaly Detection
![samrt_facory](./image/smart_factory/001.png)
    <details>
    <summary> Smart Factory IoT Unsupervised Anomaly Detection details</summary>
        <div markdown="1">

        - Background : A model that predicts abnormal parts using IoT data provided from factories

        – Achievement: 
        • Call factory compressor,rectifier data from MySQL. 
        • Data Preprocessing. Un-supervised anomaly detection(Machine Learning, prophet, Autoencoder). 

        - link : https://github.com/forallx94/Sequential_Anomaly_detecion

    </div>
    </details>

* Project 5: BAMS, HAMS Energy consumption forecast
    <details>
    <summary>  BAMS, HAMS Energy consumption forecast details</summary>
        <div markdown="1">

        - Background : Predict temperature, humidity, electricity usage, hot water usage, etc. of house and buildings

        – Achievement: 
        • House, Building Energy consumption data preprocessing. 
        • Energy consumption forecast (Prophet, Residual LSTM). 
        • Upload result at MongoDB.
    </div>
    </details>

# HERSS, AI Researcher 03. 2020 - 06. 2020
• Responsibility: Brain MRI data preprocessing for brain tumor detection(U-Net)  
* Project : MRI Brain Tumor Segmentation
    <details>
    <summary> MRI Brain Tumor Segmentation details </summary>
    <div markdown="1">

        – Achievement: Applied 6 data preprocessing methods(Z-score normalization, whit strip, Ravel etc) to the brain MRI data, but none resulted in a significant improvement in performance.  

        – Insight: When compared to the underlying The Brain Tumor Segmentation (BraTS) data Identified that the delivered data was not the original data, leading to the discovery of a problem with the data preprocessing. This helped to identify a major issue with the data and led to improvements in data handling processes at the company.  
    </div>
    </details>

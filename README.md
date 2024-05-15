# UAV and Deep Learning: Detection of selected riparian species along the Ganga River

## Abstract
 Environmental protection and sustainable natural resource management are being recognised worldwide as essential goals to safe guard human health and wellbeing. Riparian zones, that face the highest decline in freshwater biodiversity, are of prime conservation priority because they are essential for regulating climate, preserving aquatic-terrestrial biodiversity, maintaining ground water recharge and restoring rivers. In today's fast-paced data-driven environment, artificial intelligence (AI) is the precise answer to a wide range of problems including biodiversity conservation and wildlife management. Leveraging advancements like Uncrewed/Unmanned Aerial Vehicles (UAVs) and AI has resulted innovative strides in wildlife conservation. This study utilised UAV imagery to record high-resolution data of aquatic habitat and species along the Ganga River and employed deep learning algorithms to analyse the data. Through extensive field surveys in the Hastinapur Wildlife Sanctuary, 7,025 photos representing a variety of environments, including 20,000 annotated samples of aquatic animals such as turtles and gharials were generated. Vision based computing capabilities such as pattern recognition model were developed to identify these species. To enrich and enhance the dataset and model, we used different image pre-processing techniques. Slight rotation (±5 degrees), minor cropping (up to 10%), and adjustments in brightness, saturation, and shear (±15%) were applied. Controlled blur (up to 0.5%) and exposure modifications (±5%) were also implemented on the image dataset to improve accuracy. Three Convolutional Neural Network (CNN) architectures, single-stage detectors named YOLO v7, YOLO v8, and Roboflow 3.0, were used for detecting the select species. Results show YOLO v8 excels, achieving mean average precision (mAP) of 98.8% for gharial and 92.2% for turtle detection, with a rapid average detection time of 0.308 seconds per frame at 3200 x 3200 resolution. Additionally, our model demonstrates real-time species detection capability through innovative frame sampling techniques with UAVs. This methodology provides promising technique to collect scientific data on IUCN red listed turtles and critically endangered gharials, allowing detection, monitoring, and real time counting with minimal intrusion. In conclusion, the fusion of UAVs and deep learning promises to revolutionize habitat monitoring, aiding conservation decision-making.

 ![Ghariyal Model Comaprision](/images/Ghariyalmodelcomparision.png)
 ![Turtle Model Comparision](/images/TurtleModelComparision.png)

 ## Authors

- Ravindra Nath Tripathi
- Aishwarya Ramachandran
- Karan Agarwal
- Vikas Tripathi
- Ruchi Badola
- Ainul Syed Hussain


Read full paper [here](https://isprs-archives.copernicus.org/articles/XLVIII-1-2024/637/2024/)
# Fashion_Recognition_and_Recommendation_System_Project

This is a Object detection and Recommendation System project. With 'SpotDbuy', we can be a fresh pair eyes to serch out the sport swears eith the best price in just a click, and also bring you the perfect recommendations. 'SpotDbuy' is the place you can enjoy your shopping journey with remarkable experiences. Let's show what I done.

# Aims:
With the use of techologies
  - saving time on searching
  - Bringing a better online shopping experiences 

# Business Values:
People are more expecting a healthy life now a days, doing exercise is becoming a part of out daily life as it is a way to keep us healthy.
  -  Foreseeing the sports wear industry will grow more rapidly in coming years.
  -  Bridging the sports wear industal with AI through online shopping platforms.
  - Enable the use of computer-vision to bring conveniences to consumers.
  - To be an independent, credible source the consumers can always rely on when they compare sports wear products online.

# Data Collection:
### Web-Scraping
  -  From 4 different websites (adidas offical, asos, amazon, Taobao.com)
  - over 8000 images

### Attribute selection
Category(9) 
  - Adidas 
  - Shorts
  - Short-T  
  - Pants
  - Long-T   
  - SportBra
  - Polo-T   
  - Jacket
  - Hoodie

### Data Cleaing
  - filling the missing image links
  - remove the missing data row
  - remove row with outliers
  - remove corrupted data of showing errors etc

### Image labelling
  - label all image files with 'LabelImg' for yolov4 model

# Yolov4 model evaluation<img src="https://github.com/cpuikin/Fashion_Recognition_and_Recommendation_System_Project/blob/main/image/yolo.png" width="20" height="20" />

<img src="https://github.com/cpuikin/Fashion_Recognition_and_Recommendation_System_Project/blob/main/image/yolov4-darknet53.png" width="300" height="300" />

- Yolov4-Darknet53
- running time: ~13h
- mAP: ~ 89%

<img src="https://github.com/cpuikin/Fashion_Recognition_and_Recommendation_System_Project/blob/main/image/yolo-tiny.png" width="300" height="300" />

- Yolov4-Tiny
- running time: ~5h
- mAP: ~67%

# Keras VGG16 model
<img src="https://github.com/cpuikin/Fashion_Recognition_and_Recommendation_System_Project/blob/main/image/kerasVGG16.png" width="300" height="300" />

- Accruracy : ~71%

# Deployment
### Web-app Architechtrue
<img src="https://github.com/cpuikin/Fashion_Recognition_and_Recommendation_System_Project/blob/main/image/Web-app%20architechtrue.png" width="250" height="250" />

### Streamlit web-app display  
<img src="https://github.com/cpuikin/Fashion_Recognition_and_Recommendation_System_Project/blob/main/image/web-app%20show.png" width="250" height="250" /> <img src="https://github.com/cpuikin/Fashion_Recognition_and_Recommendation_System_Project/blob/main/image/web-app%20show2.png" width="250" height="250" /> <img src="https://github.com/cpuikin/Fashion_Recognition_and_Recommendation_System_Project/blob/main/image/web-app%20show3.png" width="250" height="250" />


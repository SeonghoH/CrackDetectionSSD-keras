# CrackDetectionSSD-keras



## The Objective of Chamomile
* Crack detection : Chamomile detects the cracks on the surface of the concrete structure.</br>
* Crack width estimation & classification based on seriousness: Chamomile estimate the width of the detected cracks, and reports the more serious crack first which has wider width than others. Basically, the crack of which width is more than 0.3mm is to be classified as "high risk crack", 0.3mm ~ 0.2mm as "low risk crack", and ~ 0.2mm as "minor crack.</br>
* Crack location reporting : Chamomile reports the actual location of the crack based on the flight log saved in the drone. With combining pixel information and the flight log, the location of crack can be calculated. It is useful for safety inspectors to know where the serious cracks locates which needs further precision diagnosis, before they physically approach to the target structure.


## User Benefit

* Automation of Safety Inspection

The examination on structual health can be partially automated. Chamomile selects which crack must be inspected based on width, which makes the further safety inspection done by human more efficient. Chamomile "filters".

* Reducing the time spent on Safety Inspection

* One-stop System 

* Assuring the higher level of safety in the long term

</br></br>

## Performance

Data set | Detection rate
:---: | :---:
METU data set | 85.7% (1714/2000)
Real concrete surface video | 81.1% (43/53)
Random crack images | 76% (19/25)


</br>

## Framework
* Crack detection : Keras 2.2, Tensorflow 1.9.0, Python 3.6.6</br>
* Crack width estimation : Scikit-image 0.14.0, Python 3.6.6</br>

</br>

## Reference
1. Liu, Wei, et al. "SSD: Single shot multibox detector." European conference on computer vision. Springer, Cham, 2016. (Link : https://arxiv.org/abs/1512.02325) </br>
2. Kim, Hyunjun, et al. "Concrete crack identification using a UAV incorporating hybrid image processing." Sensors 17.9 (2017): 2052. (Link : http://www.mdpi.com/1424-8220/17/9/2052/htm)

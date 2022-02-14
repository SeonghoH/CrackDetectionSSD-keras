# CrackDetectionSSD-keras

This is https://github.com/Garamda/Concrete_Crack_Detection_and_Analysis_SW. and https://github.com/pierluigiferrari/ssd_keras It's based on that.

I recommend you install and use https://github.com/pierluigiferrari/ssd_keras on the same file.



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

##Dataset

METU Dataset: https://doi.org/10.15142/T3TD19

</br>

## Framework
* Crack detection : Keras 2.2, Tensorflow 1.9.0, Python 3.6.6</br>
* Crack width estimation : Scikit-image 0.14.0, Python 3.6.6</br>

</br>

## Reference
1. Liu, Wei, et al. "SSD: Single shot multibox detector." European conference on computer vision. Springer, Cham, 2016. (Link : https://arxiv.org/abs/1512.02325) </br>
2. Kim, Hyunjun, et al. "Concrete crack identification using a UAV incorporating hybrid image processing." Sensors 17.9 (2017): 2052. (Link : http://www.mdpi.com/1424-8220/17/9/2052/htm)

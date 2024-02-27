# Machine learning-based soft-sensor development for road quality classification

Vibrations in road vehicles cause several harmful effects, health problems can occur for the passengers, and
mechanical damage can occur to the vehicle components. Given the health, safety, and financial issues that arise,
keeping the road network in good condition and detecting road defects as early as possible requires an extensive
monitoring system. Related to this, our study presents the development of hardware and software for a low-cost,
multi-sensor road quality monitoring system for passenger vehicles. The developed monitoring system can classify
road sections according to their quality parameters into four classes. In order to detect vibrations in the vehicle,
accelerometers and gyroscope sensors are installed at several points. Then, a machine learning-based soft-sensor
development is introduced. Besides noise filtering, each data point is resampled by spatial frequency to reduce the
velocity dependence. Subsequently, a decision tree-based classification model is trained using features from the power
spectrum and principal component analysis. The classification algorithm is validated and tested with measurement data
in a real-world environment. In addition to reviewing the accuracy of the model, we examine the correlation of the data
measured in the cabin and on the suspension to see how much additional information is provided by the sensor on the
axle.

![image](https://github.com/DataCentricSE/road-quality-classification/assets/160244794/9fdf38b2-9a83-464b-8664-caab2bad03a0)
<p>
    <em>The applied methodology for the development of the road quality classification model</em>
</p>

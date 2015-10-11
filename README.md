# SEAMS
### Smart Emergency Alert and Monitoring System
https://docs.google.com/presentation/d/1NitohiGjYeXeJdz5qjj-PC42TEjij9u2CllShMYydcg/edit#slide=id.p

###Description

SEAMS is a machine-learning driven wearable application for primarily senior citizens who live alone. It runs on Intel Edison with Sparkfun Muscle Sensors, accelerometers, and other sensors with the aim of alerting senior citizens' remote family and other loved ones as soon as an incident (defined below) is recorded on the wearable. The wearable also has support for tripping an audible alarm in the vicinity when an incident is tripped.

Currently, SEAMS has support for the following:
- identifying when a person falls/trips
- identifying a tonic clonic seizure (total body seizure)
- identifying epilepsy.
- monitoring sleep patterns
- support for false positives via reset button

Future directions include:
- Utilizing a smartphone’s built-in accelerometer to capitalize on existing hardware market, thus saving costs and cutting development time
- Integrating other sensors, such as heart rate monitor and muscle sensor for greater precision
- Emphasizing design of product so as to incentivize more users to see it not solely as a medical/diagnosis product, but also as a stylistic one
- Bluetooth connectivity to fire alarm at home to amplify emergency signal

###Motivation

More and more senior citizens are moving into homes alone, with the proportion of senior citizens doing in a certain age cohort increasing with age. There are currently many proposed ways to increase the safety of senior citizens living alone, including having a family member or loved one checking in periodically, improving general health and awareness, and safe-proofing the home. 

Nonetheless, these solutions do not take into account the worry that constantly burdens these seniors' loved ones. Senior citizens have a right to choose to live independently if they so desire; simultaneously, their loved ones have a right to keep non-invasive tabs on their well-being.

We are working hard to ensure that SEAMS will cater to this necessary need, while also taking ordinarily auxillary matters, such as comfort and style, into serious consideration.

###API Reference
- Intel Edison
- Sparknotes 9DOF module
- Sparknotes Muscle Sensor v3
- Parse back-end
- Docker container
- scikit-learn (logistic regression)

###Contributors
@archang, @naokiyokoyama, @jennycheung1217, @vkaran101

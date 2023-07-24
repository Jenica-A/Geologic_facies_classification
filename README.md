## Geologic Lithofacies Classification

This project aims to use x-ray fluorescence (XRF) data from rock cores to predict lithofacies lables in a rock core from the Permian Basin in Texas. 

The data are shared with me by AIM GeoAnalytics, a geologic services company in Missoula, MT. 

The XRF data report the elemental composition of a rock. 

The lithofacies (facies) label is short hand for a longer description of the rock type. For example, a rock may be described in many way, such as "very fine sandstone with calcitic cement", or "shale", or "interbedded limestone and shale" and so on. In a rock core description, these descriptions are coded, to be tabularized, and described in a lengthier legend section. The core is then analyzed by a geologist and a label is given for every half a deci-foot (a mind-boggling unit, to be sure, but a resolution with its reasons). In a final report, the XRF data are provided along side of the facies description, and a suite of other analyses. 

The lengthiest (read "expensive") and perhaps most subjective portion of the description is the facies label. It is an important step, where a geologist puts her hand lense, grain-size card and her bottle of hydrochloric acid to the rock to really understand what has happened, in what sequence in the past. Without this step, the description of a rock, and a resource, can be massively misunderstood or misrepresented, skewing any working model of resource or region and potentially leading to many millions of dollars being misappropriated or lost by an operating company. The unfortunate truth is that it can be difficult to remain objective day to day and in the face of slight evolution in rock over geologic time. Although the aforementioned scenario is more likely, mis-judgements on the part of a geologist have the potential to do as much harm to a working model as skipping this step of having a skilled and educated geologist neglect to observe a rock. 

In this project, I attempt to produce a logistic regression classification model that can predict a rock's lithofacies type, based on the XRF data alone. My specific research question is: *Based on XRF data alone, how well can a logistic regression model predict a facies label?*

As with other AI tools, augmenting the work of a human is the powerful outcome desired. I argue, if done reliably, responsibly, successfully, the automation of facies description could produce more objective rock description data on a quicker timeline than having a geologist start from scratch, describing the rock by hand. Ground-truthing and human oversight is necessary, but would be a simpler, more streamlined, perhaps more reliable way to produce more consistent results and build more reliable models.  

As it stands, this project awaits facies labels to accompany the XRF data, for model training and testing. Model-building commencing in jupyter notebook 

Update to this project: In the absence of facie data, I am now thinking about applying a clustering model and an anomoly detection model. 

# Determining  Event Outcomes: The case of #fail
This repository includes the annotated datasets used in the paper.


## Datasets
This folder contains the annotated datasets used in the project and it has the following files:
 - FinalOutputBaking.csv that contains 1000 baking related tweets that did not possess a related image,their annotated  labels and respective tweet ids.
 - FinalOutputBakingImg.csv that contains 1000 baking related tweets with a related image,image url,image name, their annotated  labels and respective tweet ids.
 - FinalOutputCooking.csv that contains 1000 cooking related tweets that did not possess a related image,their annotated  labels and respective tweet ids.
 - FinalOutputCooking Img.csv that contains 1000 cooking related tweets with a related image,image url,image name,their annotated  labels and respective tweet ids.
##### Attributes and their explaination
- Tweet: Tweets in plain English obtained from scratch using Twitter api.
- Image_Url: If the tweet possess image, the url to the related image.
- Image name: Name assigned to each image. This name is obtained from the url.
- Cooking/Baking Event:This field determines if the mentioned tweet is a related to a cooking/baking  event. Assigned labels are either 'yes' or 'no'.
- Edible or not: This field determines if the event resulted in an edible outcome or not. We defined edible as ' something that is worth trying and not trashed'. Labels assigned are 'yes' or 'no'.
- Output Quality: This field determines the quality of the outcome produced.Labels assigned are:
    - Perfect : If event resulted in perfect outcome as expected.
    - Partial: If event was a partial success(eg: partially burnt)
    - Alternative Outcome: An edible and unexpected outcome is achieved.
    - Cannot determine: Outcome quality cannot be determined, but its an edible one.
- Tweet_id

## BakingImages
This folder contains the images present in tweets related to baking event.

## CookingImages
This folder contains the images present in tweets related to cooking event.









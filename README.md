# Event_outcome
Determining event outcomes from social media
Listed are the annotated csv's containing the data and labels used in the paper 'Determining Event Outcomes: The Case of #fail, published in EMNLP Findings 2020'.
FinalOutputBaking.csv contains 1000 baking related tweets that did not possess a related image,their annotated  labels and respective tweet ids.
FinalOutputBakingImg.csv contains 1000 baking related tweets that did possess a related image,image url,image name, their annotated  labels and respective tweet ids.
FinalOutputCooking.csv contains 1000 cooking related tweets that did not possess a related image,their annotated  labels and respective tweet ids.
FinalOutputCooking Img.csv contains 1000 cooking related tweets that did possess a related image,image url,image name,their annotated  labels and respective tweet ids.
The general fields in the csv are explained below.
  1.Tweet:Tweets in plain English obtained from scratch using Twitter api.
  2.Image_Url: If the tweet possess image, the url to the related image.
  3.Image name: Name assigned to each image. This name is obtained from the url for easier identification.
  4. Cooking/Baking Event:This field determines if the mentioned tweet is a related to a cooking/baking  event. Assigned labels are either 'yes' or 'no'.
  5.Edible or not: This field determines if the event resulted in an edible outcome or not. We defined edible as ' something that is worth trying and not trashed'. Labels assigned are 'yes' or 'no'.
  6.Output Quality: This field determines the quality of the outcome produced.Labels assigned are:
          1.Perfect : If event resulted in perfect outcome as expected.
          2.Partial: If event was a partial success(eg: partially burnt)
          3.Alternative Outcome: An edible and unexpected outcome is achieved.
          4.Cannot determine: Outcome quality cannot be determined, but its an edible one.
  7.Tweet_Id
Related images are included as multiple zip files.

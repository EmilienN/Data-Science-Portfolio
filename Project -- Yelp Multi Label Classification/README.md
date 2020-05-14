# Deep Learning Advanced

## Projet - Yelp Multi-Label Classification


At Yelp, there are lots of photos and lots of users uploading photos. These photos provide rich local business information across categories. Teaching a computer to understand the context of these photos is not an easy task. Yelp engineers work on deep learning image classification projects in-house, and you can read about them here.

In this competition, you are given photos that belong to a business and asked to predict the business attributes. There are 9 different attributes in this problem:

 - 0: good_for_lunch
 - 1: good_for_dinner
 - 2: takes_reservations
 - 3: outdoor_seating
 - 4: restaurant_is_expensive
 - 5: has_alcohol
 - 6: has_table_service
 - 7: ambience_is_classy
 - 8: good_for_kids

These labels are annotated by the Yelp community. *Build a model that will predict 9 labels purely (good_for_lunch, good_for_dinner, takes_reservations, outdoor_seating...) from the business photos uploaded by users.*

The evaluation metric for this competition is Mean F1-Score also known as example-based F-measure in the multi-label learning literature. The F1 score, commonly used in information retrieval, measures accuracy using the statistics precision p and recall r. Precision is the ratio of true positives (tp) to all predicted positives (tp + fp).  

*Result : F1 score = 0,76 with ResNet50 model*

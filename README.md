# Predict-Call-Drop-Category

This project is intended to predict the call drop category from a real time voice call quality data, India

Real time voice quality data India

Content:

The data is captured for various service providers, at multiple locations, network types
3G, 4G, 2G, ratings, coorditanes etc. The data attached is for two different months.
Note: If Latitude and Longititude is -1 or 0 or any out of india geography there state should
be null .It usually happens when an android user or apple user blocked the App to accesses
their location or Android Apis which google provide are unable to capture lat or Long.
Format:

 Operator- Company name

 Indoor_Outdoor_Travelling

 Network Type

 Rating

 Call Drop Category

 Latitude

 Longitude

 State Name

Task:


1. Can you predict the call drop category?



Solution: 

I used Multi-Label Classification to predict Call Drop Category with 0.735 accuracy.

I was able to predict ANY single category from Call Drop Category with a 0.934 accuracy using Grid-Search CV.

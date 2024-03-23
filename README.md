
# Reverse Geocoding: Acquiring Address from Location Coordinates

**Geocoding** is the process of converting addresses into geographic coordinates (latitude and longitude). You see their familiar form whenever you search for your local restaurant or place to visit. There is also something called **Reverse Geocoding** where you want to convert latitude and longitude into readable addresses. Both are equally important, especially for industries related to moving goods or people, e.g. food delivery service or taxi service. Reverse geocoding is essential if you want to understand the underlying pattern of customer behavior. For example, as a food delivery service or a food merchant offers or partners with a delivery service, you want to know where most of your customers are located based on their delivery addresses.

There are several alternatives to do reverse geocoding. In this repo we will explore 2 options on doing reverse geocoding and see their pros and cons:

- Using API 
- Using shapefile map data

We will use data from [Food Delivery Dataset](https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset) acquired from Kaggle. A quick sampling of the address coordinates inform me that the delivery service is located in India. The map shapefile data is acquired from [GADM](https://gadm.org/download_country.html).
# Space-Grown-Empowering-Farmers-to-Grow-Exotic-Fruits-with-Geographic-Insights
Space-Grown helps farmers grow exotic fruits by using satellite data to provide personalized insights on soil, weather, and location. We empower farmers to cultivate unique crops, boost their income, and bring new flavors to their communities.

This project mainly focuses on the development of an interface which allows you to use the coordinates of a place and compare the conditions of the place with that of the places where a certain exotic variety thrives well

This is done by comparing the weather conditions like the rainfall, hourly rain data with that of the ideal conditons of a particular place the NDVI data of the satellite imagery of the particular region. The code also offers a segemented image apart from the NDVI image which tells us which are the regions of vegetation and barren land in the particular satellite image.

![image](https://github.com/user-attachments/assets/a5d2f160-9317-4d86-8777-c9a053088ab2)


The NDVI image generated is as below:

![image](https://github.com/user-attachments/assets/eeb39fa5-0752-4069-8f22-7915f1d20d3e)

The data visualization for comparison of the NDVI is visualized as below:

![image](https://github.com/user-attachments/assets/59860649-4eec-4766-a071-8887039d9b08)



This data is retrieved from a dataset of satellite images and use of a weather API to retrieve data. The data is put through a formula to calculate and give a scoring for that particular place out of 100 based on how much we attain for that particular region.

After doing the scoring we briefly compare which parameter is lagging and how it fixing that particular issue will help improve the score by how much. After all of this done the data is stored in a csv file.


This data is then loaded to a lightweight LLM model like chatGPT-Neo being used which is then analyzed by the llm and gives further advice as to how to improve the conditions and what can be done to make it more favourable for the growth of the particular variety.


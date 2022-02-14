# Crop-Soil-prediction
 RECOMMENDATION USING WEATHER AND SOIL CONTENT

Despriction
predictive model helps the farmers to make decision about the farming strategy.
The model recommend the most suitable crops to grow in a particular farm based on various parameters.

This dataset was build by augmenting datasets of rainfall, climate and fertilizer data available for India.

Data fields
N - ratio of Nitrogen content in soil
P - ratio of Phosphorous content in soil
K - ratio of Potassium content in soil
temperature - temperature in degree Celsius
humidity - relative humidity in %
ph - ph value of the soil
rainfall - rainfall in mm

![Soil-Conditions](https://user-images.githubusercontent.com/99526815/153738000-a0806724-d5c4-466e-8270-2780bca91cc4.jpg)

Today soil conditions, including moisture level, temperature, and chemical makeup, all of which have an impact upon crop growth.
This can allow crops to be grown at much higher precision, enabling farmers to treat plants and animals almost individually, which in turn significantly increases the effectiveness of farmers' decisions.

Using this can develop means to predict harvest yields and evaluate crop quality.

Overall description

![6](https://user-images.githubusercontent.com/99526815/153738801-687e0d05-9458-4851-a333-bb32289d6298.PNG)

Distribution of temperature and ph.

![1](https://user-images.githubusercontent.com/99526815/153738276-36c54aed-b4de-487c-a6e5-064414d0ae19.PNG)

To visualize the diagonal distribution between two features for all the combinations! It is great to visualize how classes differ from each other in a particular space.

![2](https://user-images.githubusercontent.com/99526815/153738461-6a44e26a-cf79-497d-9ef8-e3c961351714.PNG)

During rainy season, average rainfall is high (average 120 mm) and temperature is mildly chill (less than 30'C).

Rain affects soil moisture which affects ph of the soil. 

Here are the crops which are likely to be planted during this season.

Rice needs heavy rainfall (>200 mm) and a humidity above 80%. No wonder major rice production in India comes from East Coasts which has average of 220 mm rainfall every year!

Coconut is a tropical crop and needs high humidity therefore explaining massive exports from coastal areas around the country.

![3](https://user-images.githubusercontent.com/99526815/153738517-a3bfa0a6-6241-4ca9-bbd5-f56dd73d6f7b.PNG)

This graph correlates with average potassium (K) and average nitrogen (N) value (both>50).

These soil ingredients direcly affects nutrition value of the food. Fruits which have high nutrients typically has consistent potassium values.

![4](https://user-images.githubusercontent.com/99526815/153738621-6ec40dd1-5a44-433d-8d45-f26d230d5efc.PNG)

Let's try to plot a specfic case of pairplot between `humidity` and `K` (potassium levels in the soil.)

sns.jointplot() can be used for bivariate analysis to plot between humidity and K levels based on Label type. It further generates frequency distribution of classes with respect to features

![5](https://user-images.githubusercontent.com/99526815/153738690-e45870dd-a09d-4b16-93bd-7868f3be58dd.PNG)


We can see PH values are critical when it comes to soil. Normally PH is 6 to 7

![7](https://user-images.githubusercontent.com/99526815/153738856-133db513-0d96-4b60-9090-9a9014958511.PNG)

Another interesting analysis where Phosphorous levels are quite differentiable when it rains heavily (above 150 mm).

![8](https://user-images.githubusercontent.com/99526815/153738884-07565c8d-b0a1-48da-8fc1-ebb9b7974183.PNG)

When humidity is less than 65, almost same phosphor levels(approx 14 to 25) are required for 6 crops which could be grown just based on the amount of rain expected over the next few weeks.

![9](https://user-images.githubusercontent.com/99526815/153738930-bc622b2f-4628-4c3f-9170-2d7b3e49d06d.PNG)

![10](https://user-images.githubusercontent.com/99526815/153807415-05699ea5-9a00-403c-a4a0-bd07a75ec2c8.PNG)

![11](https://user-images.githubusercontent.com/99526815/153807427-7a124771-f201-41af-b309-5ac5bc4cf60e.PNG)

![12](https://user-images.githubusercontent.com/99526815/153807439-c08c62d4-f17b-4fd9-9f10-3079d33ce047.PNG)

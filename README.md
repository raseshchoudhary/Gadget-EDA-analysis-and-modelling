# Gadget-EDA-analysis-and-modelling

![alt text](https://static.timesofisrael.com/blogs/uploads/2012/01/powermat.jpg)

Welcome techies, in this project I will make you traverse a journey all the way from the era of blackberry gadgets to the status quo. If you wish to look at the gadgets trends, the occurance of
5G, the evolution of gadget batteries and camera quality, then this is the place who were looking for. I have already mentioned in this in all my other project and I'll mention this here as well, do look at the ipynb file if you wish to get the most out of this project. Lets begin the journey.

# What all is covered in this project.

In this file I have done the EDA (Exploratory data analysis) on the used device dataset. Apart from this I have performed decision tree regressor and linear regression, then I have compared the accuracy of the both the models to decide which one works better.

# About the dataset.

![alt text](https://www.inzata.com/wp-content/uploads/2019/06/shutterstock_433582672.jpg)

This dataset expounds information about different gadgets manufactured by different brands. Also information is give about the ios type, the screen size, whether the gadget has a 5g feature in it, the camera specifications, features such as internal memory, ram, batter, weight, release year, days used ,normalized used price,normalized new price. Funny enough in this brief I have mentioned all the variables in the dataset. And as you might have guessed by now that there are myraid insights that can be generated from the dataset.

# Who is the user?

![alt text](https://th.bing.com/th/id/OIP.hbBXIwO5Blhp7L6mMoHORwAAAA?pid=ImgDet&rs=1)

1.Any gadget manufacturing company aiming to launch a new product in the market.

2.Any gadget enthusiast who want to look at the status of gadget industry for fun.

# Key insights

>Because I have done verbose insights, I think its better if I only present 5-6 key insights and leave it up to you to look at the rest of the visualizations. With that being said here are the insights.

1.Gadgets sporting higher MAH battery are genrally heavier. This may be becuase the power of the battery might impact its weight which inturn might impact the overall weight of the gadget. So if you are looking for a gadget with good battery life, you should genrallly go for a heavy gadget. Although there are some abberations where gadgets are lighter as well as giving more power batteries. Probably they are made in China.

2.It can be deduced that the gargets have eclectic weight ranging from a miniscule 100gm to a whopping 800 gms. Another interesting observation is that as the weight increases, the screen size also increases.

3.Normalized used price is nothing but the second hand price available in the market. It seems as if 2020 was the worst year to purchase second hand gadgets as the prices were exorbitantly costly this year.

4.Be it any year 4g gadgets have a better selfie camera than non 4g gadgets.Also 2019 can be considered a year in which the selfie trend which at its peak as both 4g and non 4g gadgets released their respective best quality front camera gadgets.

# Some more observations!!!

5.In the initial year 2014-2017, all the companies were manufacturing non 5g gadgets (as there are huge datapoints in the no column with lighter shades). But as the time went forward, the number of non 5g gadgets being manufactured became significantly less, this might be becuase companies were starting to focus on the 5g era, so they had to stall the manufacturing of non 5g gadgets for some time.

6.Even blackberry is in this dataset.Black berry used to manufacture feature phones long time back.Although not the leading brand,it is still being sold in the market. This might be because customers have a propensity to attribute gadget companies to nostalgic sentiments. So to relive their childhood they might be still purchasing gadgets of such obsolete comapnies.

# All about modelling 

Comming to the point, I made two prediction models namely **Decision tree regressor** and **Multiple linear regression**. Then I have compared the testing accuracy of these with based on their MSE, RMSE and R quared score. 

# Conclusion

![alt text](https://th.bing.com/th/id/OIP.GPVlOu_M2CRGW-A3Nhk7iQAAAA?pid=ImgDet&rs=1)

After all this I came to the conclusion that **Decision tree regressor** was a better predictor than the multiple linear regression. Althout the tables can turn depending on the type of data being feeded to the models and other factors.

With this I would thank you for devoting you time to view this project, hope you learnt something from it.

# Mathematics-Project by Peder Brekke, Espen Urheim and Simen Nesland

As british matematician and data scientist Clive Humby once said, "Data is the new oil. It's valuable, but if unrefined, it cannot really be used." (https://www.gwprime.geospatialworld.net/business-and-industry-trends/data-was-analytics-is-the-new-oil/). The amount of data collected and stored by big tech alone is almost incomprehensible, and it requires an incredible amount of storage space. Therefore, the abilty to effectively compress data is pivotal. In lossy data compression methods, it is often necessary to optimize for both data size after compression and having a sufficient approximation of the data. In this project we will take a closer look at how we can use one specific method, namely non-negative matrix factorization (NMF), and how we can apply it to image datasets, with and without random color and brightness variations, also called noise. The dataset we will use contains face images called CryptoPunks. The motivation for using NMF specifically, is that the resulting reduced matrices will give us information about any trends in our dataset. Before applying NMF to our images, we start by exploring the method and look at some of its properties.


# Project: Wrangling and Analyzing Data

<a id='intro'></a>
## Introduction

Learning Data Analysis on Udacity is a worthwhile venture. Among the things that makes it fun is a collection of real life projects. One of such projects is this. This is a project that wrangled and analyzed data from WeRateDogs. The report of this project is given under the following headings:

<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#eda">Exploratory Data Analysis</a></li>
<li><a href="#conclusions">Conclusions</a></li>
</ul>

<a id='wrangling'></a>
## Data Wrangling
> I gathered data from three sources: downloaded twitter archive, tweet-json data (from twitter API) and image prediction data (from the web)

> I noted 14 data issues during assessment, both quality and tidiness issues.

### Data Cleaning
- I proceeded in cleaning the datasets as per the data issues noted.

<a id='eda'></a>
## Exploratory Data Analysis

#### Research Question 1 (Which breed got the highest rating on average?)

![image](https://user-images.githubusercontent.com/103776681/188330107-6cca6399-98cb-4533-9254-fc07c37b0396.png)

#### Research Question 2  (What stage of dog is popular posted?)
![image](https://user-images.githubusercontent.com/103776681/188330142-bb8ae6e3-61c6-4770-b343-c4bf84a95c34.png)

#### Research Question 3 (Are high or low rates associated with particular breeds?)
![image](https://user-images.githubusercontent.com/103776681/188330248-9fb3abdf-3429-43a7-b7ce-627f2cfc6e82.png)

#### Research Question 4 (Which breed has the highest number of occurrence in the twitter archive?)

![image](https://user-images.githubusercontent.com/103776681/188330265-576fb901-9c49-44ba-8de8-bf042b671313.png)

#### Research Question 5 (Which breed got the highest number of retweets and favorites on average?)
![image](https://user-images.githubusercontent.com/103776681/188330291-2a330308-772a-45d4-b351-46a3fb3fe24a.png)

![image](https://user-images.githubusercontent.com/103776681/188330305-52a3ee5b-52b5-4ed0-9c7c-ae3469454d62.png)

<a id='conclusions'></a>
## Conclusions
> Questions for Analysis again
> + Which breed got the highest rating on average?

Saluki breed (rating=12.5) got the highest rating on average, followed by Briard and Tibetan_mastiff with 12.3 and 12.25, respectively.

> + What stage of dog is popular posted?

The pupper dog stage is most popularly posted in the twitter archive.

> + Are high or low rates associated with particular breeds?

Low or high rating is not associated with any particular breed. The ratings less than 8 or greater than 12 spread across so many breeds. And almost all dogs posted have ratings above 8.

> + Which breed has the highest number of occurrence in the twitter archive?

The golden_retriever breed is the most common breed in this twitter archive.

> + Which breed got the highest number of retweets and favorites on average?

The Afghan_hound has the highest number of retweets and favorites.



## Limitations

> Inability to access wider range of dataset due to absence of image predictions for tweets beyong august 1, 2017

> A lot of missing data in the dog stage column may not allow us have true representation of commonly posted dog stage

## Reference
> Not applicable

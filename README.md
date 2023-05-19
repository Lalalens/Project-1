# Project-1

## Project Track: Public Safety/Policy

## Project Name:  Media mass shooting narrative: Fact or Agenda?

## Project Team Members:  
##                                           • Shelonta Gilbert
##                                           • Janice Powers
##                                           • Delon Lawrence



## Project Description/Outline

#### Is the way the media portrays mass shootings the reality of what occurs. The media portrays mass shootings in a way that promotes a stereotype of the individuals, their background, and the weapons they use. Is this the reality or is it a false narrative? We want to look at the data for the last 25 years of mass shootings to describe the actuality of these events. 

## Research Questions to Answer

#### Based on Mass shooter articles from popular News outlets Does the media give the full image of mass shooters?
#### Does the media give honest information when reporting on mass shootings?
#### Is a ban on assault weapons an effective way to stop mass shootings?


## What Type of Weapons are typically used in mass shootings - Shelonta Gilbert 

In the article *More mass shooters are using semi-automatic rifles – often bought legally* by Ashley Williams for USA Today, the claim is made that semi-automatic rifles are utilized more often than any other weapon in mass shootings. This made me question if what is often reported by the media is the truth. Before we dive into the data, we should first look at what a mass shooting is defined as. The United States Congress defines a mass shooting as four or more people killed in a single incident, excluding the shooter. Knowing this information, I thought thoroughly about what I wanted to know and went in search of data that could help me answer: What types of guns are typically used in mass shootings and compare the results to the medias claims.

The Associated Press and Northwestern University created a Mass Killings database that tracks all US homicides since 2006, where four or more people are killed.  The database included four data sets that included details about the incidents, offenders, victims, and weapons type. Keeping my question in mind I decided to utilize the two datasets that involved the gun type and the number of deaths. I then merged the two data sets by looking at information about the type of weapons that were used, I cleaned this data frame by dropping all the empty and duplicate rows. My goal with this first data frame was to simply answer the question which weapon is utilized most often? I was surprised when I found out that the most used weapon was not a semiautomatic weapon, but a handgun. There were 135 mass shootings where a handgun was utilized, with semi-automatic weapons coming in very closely behind at 120 semiautomatic handguns and 62 semiautomatic rifles used in mass shootings since 2006. 

![Screenshot 2023-05-18 at 5 01 43 PM](https://github.com/Lalalens/Project-1/assets/127805883/ee4c082e-c70a-4a2a-ad57-7a9daf72fd87)

Keeping this data in mind I wanted get a better understanding of what message the media was trying to portray. I decided to dig a little deeper and look at the mass shooting with the highest killings and look at what types of weapons were utilized in them. I created another data frame still using the same original csv’s. This time however I looked at the location, gun type and how many victims were killed. After cleaning the data by dropping duplicates, renaming my columns, and arranging the data so that the highest killing count would be first. I was ready to visualize my data and gain an understanding of the story behind the data. I mapped the data frame using the hv plots method and created a dictionary that contained the latitude, longitude, city, state, death, and injury population. This map showed that the incidents that had the largest number of killings. I was beginning to understand the story behind the data, although handguns are utilized more in mass shootings.  When there is a large death toll the weapons that are most often used are semi-automatic weapons. It should be noted that some of these incidents appear multipule times in the data because the shooter would use more than one type of weapon and there is not an easy way to tell what bullet caused the death when there are many people who are hurt.

![Screenshot 2023-05-18 at 5 04 24 PM](https://github.com/Lalalens/Project-1/assets/127805883/51ba6cb2-ccf5-4176-9db4-b3f23705e9be)
![Screenshot 2023-05-18 at 6 59 06 PM](https://github.com/Lalalens/Project-1/assets/127805883/7299fd07-8c25-48b9-af23-6553b444d8c7)

In conclusion the media is misrepresenting the truth by only reporting the mass shootings that have a high death rate, because the narrative is that semi-automatic weapons are most often used when the data shows that they are not.

## Resources - Shelonta Gilbert
DataFrame: https://data.world/associatedpress/mass-killings-public

Article: https://www.usatoday.com/story/news/nation/2022/07/12/mass-shootings-weapons-legal-what-to-know/7814081001/

***
## Federal Ban Review – Janice Powers
The United States federal government passed a ban on assault type weapons ban known as the “Public Safety and Recreational Firearms Use Protection Act” as a subsection of the “Violent Crime Control and Law Enforcement Act of 1994”. The act prohibited the manufacturing for civilian use of certain semi-automatic firearms, defined as assault weapons and large capacity magazines for ammunition. The ban was in effect from September 1994 – September 2004, when it expired. 
Many pundits call for laws to restrict access to weapons and specifically focus on assault weapons. By looking at the data and comparing frequencies of mass shootings, types of weapons used, and the number of victims of mass shootings, grouped by dates when the ban was in place and when it was not, we should be able to see if the ban made a difference in these incidents. 
The data that I used is from the National Archive of Criminal Justice Data. The specific dataset is “Turanovic, Jillian J. A Comprehensive Assessment of Deadly Mass Shootings, 1980-2018, United States. [distributor], 2022-09-29. https://doi.org/10.3886/ICPSR38482.v2”.  
### Data Description and cleaning methods
The dataset consists of 89 variables and 719 records. The dataset is not complete with missing variables for several of the variables. The data is coded 0 = no, 1 = yes, and 99 = missing. 
The original data is in a tab delimited file. It was downloaded to a Jupyter Notebook and the tabs were replaced with commas. The data was then saved into a csv file to use for the project. The columns were reduced from 89 to 17 and the “99” variable was replaced as a NAN to run the analysis. 

### Findings
Descriptive data for “Yearly Counts” of mass shootings:       
|count |39.00|
|mean	|18.43|
|std |4.07|
|min |10.00|
|25% |15.00|
|50% |18.00|
|75% |21.50|
|max |26.00|

![scatterbyyear](https://github.com/Lalalens/Project-1/assets/128756664/0394378a-f2ca-4a14-8ed5-ea760fd4c20e)

![number_group](https://github.com/Lalalens/Project-1/assets/128756664/34ea067a-e41d-4c5c-a6c5-f731d3829d82)

![number_byfive](https://github.com/Lalalens/Project-1/assets/128756664/eba660e8-08a4-40b8-a8fb-9f141547d305)

![assualt_group](https://github.com/Lalalens/Project-1/assets/128756664/25a7412c-c621-4344-a139-eed4f7c2b5ba)

![weapon_type](https://github.com/Lalalens/Project-1/assets/128756664/14f474e9-96d5-46c5-a199-52d449d80543)

![victims](https://github.com/Lalalens/Project-1/assets/128756664/204c7de1-20bb-42f7-894b-321ab5447c70)


### Conclusion
Although there is an upward trend of the number of mass shootings, analysis of this data set does not show that there was a real difference in the number of mass shootings during the period of the federal ban on assault weapons. The number of assault weapons used during a mass shooting did go up. However, the data shows that handguns are used more often than any other weapon. The number of victims did not increase significantly either. 


### Datasets


#### A Comprehensive Assessment of Deadly Mass Shootings, 1980-2018, United States (ICPSR 38482)
#### Turanovic, Jillian J. A Comprehensive Assessment of Deadly Mass Shootings, 1980-2018, United States. [distributor], 2022-09-29.
#### https://doi.org/10.3886/ICPSR38482.v2




#Resources Delon Lawrence

https://theconversation.com/race-of-mass-shooters-influences-how-the-media-cover-their-crimes-new-study-shows-100152

https://news.sky.com/story/why-are-white-men-more-likely-to-carry-out-mass-shootings-11252808

https://abcnews.go.com/amp/US/living-us-mass-school-shooters-incarcerated/story?id=36986507

https://www.nydailynews.com/news/nydn-news-remembering-columbine-high-school-shooting-1-3080137-photogallery.html

Based on Mass shooter articles from popular News outlets Does the media give the full image of mass shooters? No. I found that shooters vary and have complex backgrounds shaped by many factors.

While they might not be intentionally doing this the narrative portrayed in the media is not the full truth. This may be due to factors like time constraints, level of interest of stories covered etc. Regardless of what the reason is much information about what constitutes mass shooters is not told to us in the news. And what is revealed to us plays a part in shaping our perception of reality.

To find out what the media says about mass shooters I pulled 3 articles about mass shootings from the internet. This was mainly due to the time constraint of the project. However I did manage to find a study that examines how news media portrays the causes of mass shootings for shooters of different races.

The general portrayal I observed in the articles is white with mental illness while the study used 433 online and print news articles covering 219 mass shootings from 2013 to 2015.

The goal of the mass shooter profile part of the data was to show that there is much more to mass shooters than what the media portrays.




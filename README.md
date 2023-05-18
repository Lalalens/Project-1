# Project-1

## Project Track: Public Safety/Policy

## Project Name:  Media mass shooting narrative: Fact or Agenda?

## Project Team Members:  
##                                           • Shelonta Gilbert
##                                           • Janice Powers
##                                           • Delon Lawrence

# Datasets




#### A Comprehensive Assessment of Deadly Mass Shootings, 1980-2018, United States (ICPSR 38482)
#### Turanovic, Jillian J. A Comprehensive Assessment of Deadly Mass Shootings, 1980-2018, United States. [distributor], 2022-09-29.
#### https://doi.org/10.3886/ICPSR38482.v2

## Project Description/Outline

#### Is the way the media portrays mass shootings the reality of what occurs. The media portrays mass shootings in a way that promotes a stereotype of the individuals, their background, and the weapons they use. Is this the reality or is it a false narrative? We want to look at the data for the last 25 years of mass shootings to describe the actuality of these events. 

## Research Questions to Answer

#### Is the typical profile given for the people who commit mass shootings a true representation?
#### Does the media give honest information when reporting on mass shootings?
#### Is a ban on assault weapons an effective way to stop mass shootings?


## What Type of Weapons are typically used in mass shootings - Shelonta Gilbert 

In the article *More mass shooters are using semi-automatic rifles – often bought legally* by Ashley Williams for USA Today, the claim is made that semi-automatic rifles are utilized more often than any other weapon in mass shootings. This made me question if what is often reported by the media is the truth. Before we dive into the data, we should first look at what a mass shooting is defined as. The United States Congress defines a mass shooting as four or more people killed in a single incident, excluding the shooter. Knowing this information, I thought thoroughly about what I wanted to know and went in search of data that could help me answer: What types of guns are typically used in mass shootings and compare the results to the medias claims.

The Associated Press and Northwestern University created a Mass Killings database that tracks all US homicides since 2006, where four or more people are killed.  The database included four data sets that included details about the incidents, offenders, victims, and weapons type. Keeping my question in mind I decided to utilize the two datasets that involved the gun type and the number of deaths. I then merged the two data sets by looking at information about the type of weapons that were used, I cleaned this data frame by dropping all the empty and duplicate rows. My goal with this first data frame was to simply answer the question which weapon is utilized most often? I was surprised when I found out that the most used weapon was not a semiautomatic weapon, but a handgun. There were 135 mass shootings where a handgun was utilized, with semi-automatic weapons coming in very closely behind at 120 semiautomatic handguns and 62 semiautomatic rifles used in mass shootings since 2006. 

![Screenshot 2023-05-18 at 5 01 43 PM](https://github.com/Lalalens/Project-1/assets/127805883/ee4c082e-c70a-4a2a-ad57-7a9daf72fd87)

Keeping this data in mind I wanted get a better understanding of what message the media was trying to portray. I decided to dig a little deeper and look at the mass shooting with the highest killings and look at what types of weapons were utilized in them. I created another data frame still using the same original csv’s. This time however I looked at the location, gun type and how many victims were killed. After cleaning the data by dropping duplicates, renaming my columns, and arranging the data so that the highest killing count would be first. I was ready to visualize my data and gain an understanding of the story behind the data. I mapped the data frame using the hv plots method and created a dictionary that contained the latitude, longitude, city, state, death, and injury population. This map showed that the incidents that had the largest number of killings. I was beginning to understand the story behind the data, although handguns are utilized more in mass shootings.  When there is a large death toll the weapons that are most often used are semi-automatic weapons. It should be noted that some of these incidents appear multipule times in the data because the shooter would use more than one type of weapon and there is not an easy way to tell what bullet caused the death when there are many people who are hurt.

![Screenshot 2023-05-18 at 5 04 24 PM](https://github.com/Lalalens/Project-1/assets/127805883/51ba6cb2-ccf5-4176-9db4-b3f23705e9be)
![Screenshot 2023-05-18 at 5 05 39 PM](https://github.com/Lalalens/Project-1/assets/127805883/4b20b140-8fc6-41f0-9c97-131777244426)

In conclusion the media is misrepresenting the truth by only reporting the mass shootings that have a high death rate, because the narrative is that semi-automatic weapons are most often used when the data shows that they are not.


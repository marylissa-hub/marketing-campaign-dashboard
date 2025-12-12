\# Data Dictionary



\## **ad\_events field dataset**



**Field                                   Description** 

event\_id                             Unique identifier for each event

ad\_id                                Links to ads table

user\_id                              Links to users table 

timestamp                            Exact time of event  

day\_of\_week                          Derived field: day of the week

time\_of\_day                          Derived field: segment of day 

event\_type                           Type of event: Impression, Click, Share, Comment, Purchase





\## **ads field datase**t



**Field                                 Description** 

ad\_id                                Unique ad identifier 

campaign\_id                          Campaign association 

ad\_platform                          Platform where ad runs (Facebook, Instagram) 

ad\_type                              Creative format (Image, Video, Carousel, Story) 

target\_gender                        Gender targeted 

target\_age\_group                     Age group targeted 

target\_interests                     Topics/interests targeted



\## **campaign field dataset**



**Field                                Description**                        

campaign\_id                         Unique campaign ID 

name                                Campaign name

start\_date                          Campaign lauch date 

end\_date                            Campaign end date  

duration\_days                       campaign length 

total\_budget                        Budget allocated for campaign



\## **user field dataset**



**Field                                Description**

user\_id                            Unique user identifier 

user\_gender                        Gender of user Male Gender-based performance

user\_age                           Age of user 27 Basis for custom segmentation

age\_group                          Grouped age bucket (18–24, 25–34, etc.) 

country                            User’s country 

location                           More specific location

interests                          User’s interests






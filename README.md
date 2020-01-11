# Sport-Sharing
# Template for open source projects to learn Holochain

# Project name
Sport-Sharing

# Project discription
This application is interesting because it enables us to share sports equipement locally ang globally. On the basis of certain criteria like time, cost, C0² impact and distance you can search within your area sport equipments that you would like to rent or use. On the other hand you will be able to rent or freely offer your sport equipments for others.

Possible enhancements:
- Keep track of your events with HOLOREA and make it visible on a distributed accounting system
- Earn reputation within the sacred capital ecosystem. 
- Proof your identity by synchronizing with the HoloVault happ. 

# Project category
Sharing application

# Difficulty
![difficulty](https://raw.githubusercontent.com/holochain-community-resources/Open-Source-Learning-Projects/master/difficulty.png)

Middle

# Design documents

##  Simple UI sketch (or more)
1) Starting Page - Little description about the application --> automatically loads only the first 3 products which are in 100km distance -> if there are no objects tell the user that he/she should open the whole category 
2) Offer Equipment --> Filling out the form: 1-Take a picture 2-Write a description 3-Decide a price 4-Define pic-up address 5-Define taggs 
3) Category Page --> It will automatically retrieve every bike within 100 km distance and list only the description and the pic. In the category page you have an search function and a filter function which is located in the front-end. The filter function encompasses distance, cost, time and environmental impact. 
4) Product Page --> Every typed in information which is available from the prodile and product data will be listed on the page. 

## Zome layout
1) object
2) transacting - TBD
3) admin - TBD --> for example needed for register object_categories

## Functions needed
1) register object_with_details
2) register hashtag
3) link hashtag to object_header
4) get objects_by_distance_max3
5) get objects_by_distance_unlimited
6) get hashtags

## Entries structures
1) object 
2) hashtag

## Additional design conciderations
1) defined codelists for object_categories for proof of concept

## Phasing
3 Phases 
1) Proof of concept --> make the hApp happen without TBD
2) Enhance it with the transaction and admin zome
3) Integrate other DNAs 

# Phase-divided tasks
tasks now. (also use github issues for tasks)

# Events planned for community to work with it
(is there anyone activly doing work with this that want to pair up?)

# People that have been involved that are open to be contacted
Karl: karl.maier@edu.campus02.at, 
Toby & James



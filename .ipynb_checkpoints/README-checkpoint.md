# Quick Summary of Fleet Mertrics:

## Background: ##
* Airlines have a fleet of airplanes with the number of units on hand and different metrics associated with the fleet. Being able to visualize fleet data and present to stakeholders is an extremely important aspect of being a data analyst.

## Goal: ##
* Tasked with building a dashboard or visualization that presents the airplane data in a meaningful way. The purpose is to identify any trends or insights in the data and present that in a way for someone non-technical to understand. Think about the story that you want to tell.


### Dataset: ##
* All data is open sourced, and more information can be found here:
[AirlineFleet Data](https://www.kaggle.com/traceyvanp/airlinefleet)

| Features |  Data Type  |  Description |
| ---   |  ---   |  ---        |
| **Parent_Airline** | **Object** | i.e. International Airlines Group (IAG) |
| **Airline** | **Object** | i.e. Iberia, Aer Lingus, British Airways...etc. which are owned by IAG |
| **Aircraft_Type** | **Object** | Manufacturer & Model |
| **Current** | **Float** | Quantity of airplanes in Operation |
| **Future** | **Float** | Quantity of airplanes on order, from planespotter.net |
| **Order** | **Float** | Quantity airplanes on order, from Wikipedia |
| **Unit_Cost** | **Float** | Average unit cost (M) of Aircraft Type, as found by Wikipedia and various google searches |
| **Total_Cost** | **Float** | Current quantity * Unit Cost (M) |
| **Average_Age** | **Float** | Average age of "Current" airplanes by "Aircraft Type" |



## Observations:
Parent Airline:
* American Airline
* Delta Airline
* Lufthansa
* United Airline

These Parent Airlines have the most total airplanes in their arsenal. This includes current airplanes in operation as well as historic airplanes in the past. 


Lion Air, IndiGo, AirAsia, American Airlines, and Southwest Airlines ordered the most amount of planes. However, **Lion Air, IndiGo, and AirAsia are the airlines with rapid rate of growth (low planes in operation currently; high order for new planes)**


Most Common (currently) & the most ordered aircraft types:
* Boeing 737
* Airbus A320  
* Airbus A321

However, **Airbus A350 XWB, Mitsubishi MRJ90, and Boeing 787 are the fastest growing "newer" aircraft types.**

But many of the newer aircrafts (within the last 5 years): Boeing 787 Dreamliner, Airbus A350 XWB, Airbus A380, and Bombardier BD-500-CSeries tend to be much more expensive than their counterparts. To no surprise, many of the older aircrafts are much cheaper. 
* Popular and common aircraft types: Boeing 747, Airbus A340, Airbus A330, and Boeing 777 are average age aircraft types and are among the most expensive.

In terms of the most dominant brand, it seems that Airbus and Boeing aircraft types take up most of the market and are the most expensive. 
Even majority of the new orders for airplanes are of Airbus or Boeing brands, in some cases becoming the fastest growing new aircraft types in the market currently. 

However, there are many other Parent Airlines that do not use Airbus or Boeing aircrafts. I suppose it really depends on their cost operation/efficiency strategy. Airlines that prefer to go a cheaper route, may choose aircraft types such as Antonov or Cessna. Something I'd like to point out is that Boeing 727 is among the cheapest aircraft types out in the market. Indicating that a major brand like Boeing is trying to become more appealing to the lower masses. 
Other major airlines may exclusively shop for Boeing or Airbus aircrafts. It really boils down to the economic reasons at the end of the day.





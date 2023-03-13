# Capstone Module 3
### By: Dhimas Aditya Z (JCDS 1904)

## **Business Context**
Daegu, as the third largest official metropolitan area in South Korea, also becomes one of destinations for locals and international tourists in South Korea. As a metropolitan city, housing is one common problem. As land price rises every year and limited choices, apartments becomes the alternatives for housing. Apartments may also becomes one option for tourists while visiting as an alternative to hotels, especially for longer terms.

As a Data Scientist recruited by a Property Rental Agent in Daegu, South Korea, we we're asked to predict the price of Apartments rents based on several conditions of the Apartment for the newly developed web-application service of the Rental Agent. Beforehand, the Rental Agent was manually estimating the rent price of properties based on locations and facilities only by their domain expertise, but not having a standard price estimation for estimating a property price, especially apartments. As a data scientist, we we're asked to find the rent price estimation standard for Apartments rents in Daegu, South Korea.

## **Problem Statement**

The difficulties of rent price estimation of properties as usually caused by the misuderstandings of property owners to set property rent price. The tendency to obtain high profit caused several properties are being offered in relatively high price, but it would took longer time to rent. This might be a bad news for both rental agent and property owners, as property owners might need quick cash while property agents depends on the commissions which the commision's amount would depends on the property rent price. This means that **a competitive property price while still relatively affordable is important to make sure the property to be sold as soon as possible**.

## **Metric Evaluation**

To evaluate the model, we're using RMSE, MAE and MAPE. RMSE is the root of mean squared error value, MAE is the absolute value of error mean, while MAPE is the mean percentage of error value. The lower the value of RMSE, MAE or MAPE, the better the model we made as the result would be more accurate to predict the price of rented apartment.

**Data Understanding**

- The dataset contains the apartment property data of Daegu, South Korea.
- Each row of data represent any information regarding the apartment and its facilities including inside and outside the apartment.

**Attributes Information**

| **Attribute** | **Data Type** | **Description** |
| --- | --- | --- |
| HallwayType | Object | Apartment Type |
| TimeToSubway | Object | Estimated time needed to nearest subway station |
| SubwayStation | Object | The name of nearest subway station |
| N_FacilitiesNearBy(ETC) | Float | Number of undescribed facilities |
| N_FacilitiesNearBy(PublicOffice) | Float | Number of nearest Public Office facilities |
| N_SchoolNearBy(University) | Float | Number of nearest universities |
| N_Parkinglot(Basement) | Float | Number of parking spaces available in the building's basement |
| N_FacilitiesInApt | Integer | Number of facilities available in apartment |
| YearBuilt | Integer | Year where the building was built |
| Size(sqf) | Integer | Size of apartment's room |
| SalePrice | Integer | Price of the apartment's room |

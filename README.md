# Pump_it_Up #

Using data from Taarifa and the Tanzanian Ministry of Water, we try to predict which pumps are functional, which need some repairs, and which do not work at all. Predict of one of these three classes is based on a number of variables about what kind of pump is operating, when it was installed, and how it is managed. Ultimately, a smart understanding of which waterpoints will fail can improve maintenance operations and ensure that clean, potable water is available to communities across Tanzania.

----

## Assignment Details ##

Your goal is to predict the operating condition of a waterpoint for each record in the dataset. 

Label | Description
------------ | -------------
**functional** | the waterpoint is operational and there are no repairs needed
**non functional** | the waterpoint is operational, but needs repairs
**functional needs repair** | the waterpoint is not operational

The data comes from the Taarifa waterpoints dashboard, which aggregates data from the Tanzania Ministry of Water.

In their own words:

> Taarifa is an open source platform for the crowd sourced reporting and triaging of infrastructure related issues. Think of it as a bug tracker for the real world which helps to engage citizens with their local government. We are currently working on an Innovation Project in Tanzania, with various partners.

You can learn more here:
[Taarifa Homepage](http://taarifa.org)
[Taarifa Blog](https://taarifa.wordpress.com)
[Taarifa Github](https://github.com/taarifa)

You are provided the following set of information about the waterpoints:
* *amount_tsh* - Total static head (amount water available to waterpoint) 
* *date_recorded* - The date the row was entered 
* *funder* - Who funded the well 
* *gps_height* - Altitude of the well 
* *installer* - Organization that installed the well 
* *longitude* - GPS coordinate 
* *latitude* - GPS coordinate 
* *wpt_name* - Name of the waterpoint if there is one 
* *num_private* - *no description*
* *basin* - Geographic water basin 
* *subvillage* - Geographic location 
* *region* - Geographic location 
* *region_code* - Geographic location (coded) 
* *district_code* - Geographic location (coded) 
* *lga* - Geographic location 
* *ward* - Geographic location 
* *population* - Population around the well 
* *public_meeting* - True/False 
* *recorded_by* - Group entering this row of data 
* *scheme_management* - Who operates the waterpoint 
* *scheme_name* - Who operates the waterpoint 
* *permit* - If the waterpoint is permitted 
* *construction_year* - Year the waterpoint was constructed 
* *extraction_type* - The kind of extraction the waterpoint uses 
* *extraction_type_group* - The kind of extraction the waterpoint uses 
* *extraction_type_class* - The kind of extraction the waterpoint uses 
* *management* - How the waterpoint is managed 
* *management_group* - How the waterpoint is managed 
* *payment* - What the water costs 
* *payment_type* - What the water costs 
* *water_quality* - The quality of the water 
* *quality_group* - The quality of the water 
* *quantity* - The quantity of water 
* *quantity_group* - The quantity of water source - The source of the water 
* *source_type* - The source of the water 
* *source_class* - The source of the water 
* *waterpoint_type* - The kind of waterpoint 
* *waterpoint_type_group* - The kind of waterpoint

The direct link to the competition is:

https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/23/

## Jupyter Notebook ## 
(Please allow the following large images to load)

<img src="https://github.com/Fe1ix789/MBD/blob/master/Pump_it_Up_Project/Slide1.png?raw=true" width=fill>
<img src="https://github.com/Fe1ix789/MBD/blob/master/Pump_it_Up_Project/Slide2.png?raw=true" width=fill>
<img src="https://github.com/Fe1ix789/MBD/blob/master/Pump_it_Up_Project/Slide3.png?raw=true" width=fill>



## License ##

The License is a general MIT license. Please see the LICENSE.rtf file in the Python_Project Folder as an additional reference.

This work is a joint project by Clelia Cervetto, Felix Krueger, Léon Junique and Anggie Pratama,  during the IE Master in Big Data and Business Analytics.

# UFOs

## Overview of Project

The purpose of this project is to create a web page with dynamic filters for data displaying related to UFO sightings.
We are using 5 criterias to filter the data: Date, City, State, Country and Shape of the UFO.  
During the construction of this web page, different files were created to configure the visualization environment. The result is a combination of css, js and html files. 

## Results

User instruction for the UFO's website:

1. Open the webpage: This version of the website is deployed by opening the index.html using  any browser. (i.e.: Chrome)

<p align="center"><img src="https://user-images.githubusercontent.com/88695570/139874874-6e8fb6be-8f5e-4e4f-ae5f-10490a26a970.png">


2. Default view: When the page is opened the first the time, all the data available will be displayed by default.
  
<p align="center"><img src="https://user-images.githubusercontent.com/88695570/139875029-c1131099-32fc-4126-9632-6eebf9a7b0f1.png">

3. Filters - Date selection: The filters are located on the lower left corner. The first filter available is the "Enter Date". The format for this filter is D/M/YYYY.
  
<p align="center"><img src="https://user-images.githubusercontent.com/88695570/139875107-7141189d-d6e1-4add-afab-8b001be8a0a1.png">

4. Filters - Multiple selection: Additional filters for City, State, Country and Shape are available on the lower left corner (below the first filter). 
You can write the filter criteria and press enter or click other field, the searching logic will refresh the table view automatically.
  
<p align="center"><img src="https://user-images.githubusercontent.com/88695570/139875522-16abc755-cb4d-4c4c-84a9-04c9c5a4bc6b.png">

## Summary

- One of the drawback for the new website version is the automatic refresh after insert a filter. Personally, I prefer have a button to execute the "refresh" manually because if there is an typo error in one of the filter, the entire result of the table could be affected. 

- Export results: Sharing information is one of the main goals of this kind of websites. As additional tool to create a user friendly environment, I would recommend add an export logic/tool to download the filtered selection in a csv or excel file. 

- Special filter under the "Comment" column: Besides the main filters on the lower left corner, it would be beneficial if we add a global search for the "Comments" columns. It will bring more flexibility for the visitors to look for key words.

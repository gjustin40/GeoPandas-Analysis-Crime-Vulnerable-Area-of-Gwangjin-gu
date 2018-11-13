# GeoPandas-Analysis-Crime-Rate-of-Gwangjin-gu
This project was done when I was second-year student.
The reason why I upload this project now is that I started GitHub recently.

## The Goal
The goal is to know the crime vulnerable area in the Gwangjin-gu. Furthermore, We want to learn how to handle spatial data such as shapefile and geometry.

## Method
- We can know the crime valnerable area using CCTV installation rate.
- So in this project, we get all of the CCTV installation poi data and location of police office in Gwangjin-gu and buffer about 1km of those police office to size the security.
- Union those area and difference from Gwangjin-gu area.
- We can see the vulnerable area, and that will be the area we should be concerned.

## Analysis Process

1. Plot crime&arrest rate of each police office around the Gwangjin-gu with graph.
2. Display the CCTV location using Folium.
3. Display the police-office-1km-buffered-area using Folium.
4. Union upper area using 'Union', GeoPandas function, and analysis difference area with Gwangjin-gu area using 'Difference', GeoPandas Function.
5. This area also display with Folium.
<hr>
Sorry for the English

## Result

### 1. CCTV Distribution<Br>
![result_cctv](https://user-images.githubusercontent.com/25999141/48416449-96bd5780-e793-11e8-88e7-6e29b069c9c1.PNG)

### 2. Police Office Distribution<Br>
![result_policeoffice](https://user-images.githubusercontent.com/25999141/48416490-b2286280-e793-11e8-887a-886a8c0f7044.PNG)

### 3. Police Office Icon Customize<Br>
![result_policeoffice_customize_icon](https://user-images.githubusercontent.com/25999141/48416528-ce2c0400-e793-11e8-96f5-af531dbc28f5.PNG)

### 4. Police Office Jurisdiction<Br>
![result_policeoffice_jurisdiction](https://user-images.githubusercontent.com/25999141/48416572-eef45980-e793-11e8-88d2-8ba2f78bf266.PNG)

### 5. A Danger Zone<Br>
![result_non-jurisdiction](https://user-images.githubusercontent.com/25999141/48416603-03d0ed00-e794-11e8-8e1c-aa8a9a671a65.PNG)

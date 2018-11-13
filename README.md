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
![result_cctv](https://user-images.githubusercontent.com/25999141/48417069-329b9300-e795-11e8-93e9-1bb71ae1832c.PNG)

### 2. Police Office Distribution<Br>
![result_policeoffice](https://user-images.githubusercontent.com/25999141/48417074-34fded00-e795-11e8-916a-600bfa56a451.PNG)

### 3. Police Office Jurisdiction<Br>
![result_policeoffice_jurisdiction](https://user-images.githubusercontent.com/25999141/48417083-39c2a100-e795-11e8-9e16-fa5183f31a71.PNG)
 
### 4. Police Office Icon Customize<Br>
![result_policeoffice_customize_icon](https://user-images.githubusercontent.com/25999141/48417085-3af3ce00-e795-11e8-9e60-81cb25e5a5f7.PNG)

### 5. A Danger Zone<Br>
![result_non-jurisdiction](https://user-images.githubusercontent.com/25999141/48417093-3e875500-e795-11e8-8372-53e5797af397.PNG)

<Br>
 
According to result, You can see the lack of safety zone. But those are unnecessary places such as mountain, river, etc.

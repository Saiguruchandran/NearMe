# Ex04 Places Around Me
## Date: 20.11.2023

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
 map.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Tiruchirapalli</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>SAIGURU CHANDRAN G(23014037)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="500" width="1350">
            <map name="MyCity">
                <area shape="rect" coords="950,300,900,800" href="home.html" title="MY HOME TOWN">
                <area shape="circle" coords="850,0,1200,700" href="park.html" title="Tropical butterfly park">
                <area shape="circle" coords="850,300,1000,850" href="temple1.html" title="Uchi pillayar temple">
                <area shape="circle" coords="900,150,900,820" href="temple2.html" title="Thirumeni Alageeshwarar sivan temple">
                <area shape="rect" coords="950,250,1100,750" href="temple3.html" title="Arulmigu erumbeeshwarar temple">
            </map>
        </center>
    </body>
</html>
home.html
<html>
    <head>
        <title>home</title>
    </head>
    <body bgcolor="coral">
        <h1 align="center">
            <font color="red"><b>Tiruchirapalli</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Tiruchirapalli - My Home Town</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color ="yellow">
                Tiruchchirappalli was an important regional capital of the Pallava, Chola, and Vijayanagar dynasties from the 7th to the 17th century. 
                Its rock fortress temple, dominating the city, was the scene of bitter fighting between Muslim, Maratha, British, and French troops from the 17th to the 19th century.
            </font>
        </p>
        </body>
        </html>
park.html
 </head>
    <body bgcolor="yellow">
        <h1 align="center">
            <font color="red"><b>Tiruchirapalli</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Tiruchirapalli - Tropical butterfly park</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                The Tropical Butterfly Conservatory, is located in the Upper Anaicut reserve forest in Srirangam.
                 It covers 25 acres. 
                 The conservatory lies in the river Cauvery and Kollidam drainage basin. 
                 The Conservatory consists of Butterfly Park and Nakshatravanam (star forest).
                 The conservatory falls under Tiruchirappalli Forest Division.
                 This park is the largest butterfly park in Asia.
            </font>
            </p>
            </body>
            </html>
    temple1.html
    <html>
    <head>
        <title>temple1</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
            <font color="red"><b>Tiruchirapalli</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Tiruchirapalli - Ucchi Pillayar Temple</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                Ucchi Pillayar Temple is a 7th-century Hindu temple, one dedicated to Lord Ganesha located a top of Rockfort, Trichy, Tamil Nadu, India.
                According to legend, this rock is the place where Lord Ganesha ran from King Vibishana, after establishing the Ranganathaswamy deity in Srirangam. 
                Tiruchirapalli Rock Fort is also fondly called as Malaikottai in Tamil.
            </font>
        </p>
        </body>
        </html>
temple2.html
<html>
 <head>
        <title>temple2</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="red"><b>Tiruchirapalli</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Tiruchirapalli - thirumeni alageswarar sivan temple</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                Thirumeninathar temple (also called Boominathar temple or Tiruchuli temple) is a Hindu temple dedicated to the deity Shiva, located in Tiruchuli in Virudhunagar district, in the South Indian state of Tamil Nadu.
                Shiva is worshipped as Thirumeninathar, and is represented by the lingam. 
                His consort Parvati is depicted as Thunaimalaiyammai Amman. 
                The temple is located on the Virudhunagar Manamadurai road. 
                The presiding deity is revered in the 7th century Tamil Saiva canonical work, the Tevaram, written by Tamil saint poets known as the nayanmars and classified as Paadal Petra Sthalam. 
            </font>
        </p>
        </body>
        </html>  
temple3.html
<html>
    <head>
        <title>temple3</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>Tiruchirapalli</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Tiruchirapalli - arulmigu erumbeeswarar temple</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                Erumbeeswarar Temple in Thiruverumbur, Tamil Nadu, India, is a Hindu temple dedicated to the deity Shiva. 
                Built on a 60-foot (18 m) tall hill, it is accessible via a flight of steps. 
                The temple's main shrines and its two prakarams (outer courtyards) are on top of the hill, while a hall and the temple tank are located at the foothills. 
                Shiva is believed to have transformed himself into an ant hill and tilted his head at this place to enable ants to climb up and worship him. 
                Erumbeeswarar is revered in the canonical 7th-century Tamil Saiva work the Tevaram, written by Tamil saint poets known as nayanmars and classified as Paadal Petra Sthalam.
            </font>
        </p>
        </body>
        </html>
    
## OUTPUT

![image](https://github.com/selvasachein/NearMe/assets/144870946/08ef2780-acfd-4126-a4c6-5bbeb6cdf4de)
![image](https://github.com/selvasachein/NearMe/assets/144870946/a5f45f85-3117-4b9b-88eb-ed02bfaa4460)
![image](https://github.com/selvasachein/NearMe/assets/144870946/a748f2f1-87c1-419d-b63f-ae72d8978db7)
![image](https://github.com/selvasachein/NearMe/assets/144870946/734f9139-4aff-4d0f-873f-d86ce44df721)
![image](https://github.com/selvasachein/NearMe/assets/144870946/a1b51cfa-7bc8-4d69-8df8-1e618f1339f4)
![image](https://github.com/selvasachein/NearMe/assets/144870946/bab64072-2223-4db3-9c25-8478ad90883c)














## RESULT
The program for implementing image maps using HTML is executed successfully.

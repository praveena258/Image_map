# Ex04 Places Around Me
# Date:09.04.2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
web.html

<html>
<head>
    <title>My city</title>
</head>
<body>
    <h1 align="center">
    <font color="black"><b>Nolambur</b></font>
    </h1>
    <h3 align="center">
    <font color="blue"><b>PRAVEENA D</b></font>
    </h3>
    <center>
        <img src="map.png" usemap="#My city" height="610" width="1450">
        <map name="My city">
        <area shape="rect" coords="538,433,639,507" href="home.html" title="My Home">
        <area shape="rect" coords="446,113,508,75" href="decathlon.html" title="DECATHLON">
        <area shape="circle" coords="1256,280,91"   href="theatre.html" title="theatre">
        <area shape="rect" coords="533,178,652,239"   href="restaurant.html" title="restaurant">
        <area shap="rect"  coords="350,687,70,453"  href="wedding.html" title="wedding convention">
        </map>
    </center>
</body>
</html>

theatre.html

<html>
    <head>
        <title>My city</title>
    </head>
    <body bgcolor="yellow">
    <h1 align="center">
        <font color="red"><b>Nolambur</b></font>
    </h1>
      <h3 align="center">
        <font color="blue"><b>theatre<sub>-</sub>rohini theatre</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="avenue" size="5">
            Rohini Silver Screens is a prominent multiplex cinema located at 141/2, Poonamallee High Road, Koyambedu, Chennai, Tamil Nadu 600107, near St. Thomas College of Arts and Science. Established in 1991 as a single-screen theater, it transformed into India's first six-screen multiplex in 1999 and was rebranded as Rohini Silver Screens in 2016. ​
            Known for its vibrant fan celebrations, especially during first-day first shows of major film releases, the theater has become a cultural landmark where fans from around the world gather to celebrate iconic movie premieres. ​
        </font>
    </p>
    </body>
</html>
restaurant.html

<html>
    <head>
        <title>My city</title>
    </head>
    <body bgcolor="pink">
    <h1 align="center">
        <font color="black"><b>Nolambur</b></font>
    </h1>
      <h3 align="center">
        <font color="blue"><b>restuarants<sub>-</sub>SAMCO</b></font>
    </h3>
    <hr size="3" color="ceon">
    <p align="justify">
        <font face="restaurant" size="5">
            Nolambur, a growing neighborhood in the western part of Chennai, is home to a vibrant and diverse culinary scene. The area caters to a wide range of tastes and preferences, offering everything from traditional South Indian dishes to international fast food. One of the local favorites is Momo Nation Cafe, known for its cozy setting and wide variety of momos and Indo-Chinese dishes. It's a go-to spot for quick bites and casual hangouts.
For those craving rich and hearty meals, Kadhar Bhai Biryani in nearby Mogappair West Depot is a hit among biryani lovers. Their aromatic rice dishes paired with spicy gravies make it a popular choice during lunch and dinner hours. Another must-visit is The Madras Diner, a multi-cuisine restaurant that offers an eclectic mix of Indian, Continental, and Asian flavors. The stylish decor and diverse menu make it ideal for family dinners or weekend outings.
Pizza lovers in Nolambur frequent La Pino'z Pizza, a fast-growing chain offering a range of cheesy delights and quick service, perfect for both dine-in and takeout. Spicy Eats is another notable spot, well-liked for its North Indian curries and tandoori items served in a welcoming atmosphere. Lastly, Chariyaas Kitchen stands out for its homestyle cooking and friendly service, offering traditional meals that bring a sense of comfort and familiarity.
        </font>
    </p>
    </body>
</html>

wedding.html


<html>
    <head>
        <title>My city</title>
    </head>
    <body bgcolor="green">
    <h1 align="center">
        <font color="black"><b>Nolambur</b></font>
    </h1>
      <h3 align="center">
        <font color="black"><b>wedding venue<sub>-</sub> m wedding &convention</b></font>
    </h3>
    <hr size="3" color="yellow">
    <p align="justify">
        <font face="wedding venue" size="5">
            M Weddings & Conventions is a luxurious and spacious event venue located in Vanagaram, Chennai.
             Known for its elegance and modern amenities, it is a popular choice for hosting grand weddings, receptions,
              and high-profile corporate events. The venue offers multiple event halls, including The Grand Ballroom, which can accommodate up to 1,800 guests,
               making it perfect for large gatherings. For more intimate functions, spaces like The V Elite and The A Lounge provide stylish and comfortable settings for mid-sized and small events.
        </font>
    </p>
    </body>
</html>


decathlon.html

<html>
    <head>
        <title>My city</title>
    </head>
    <body bgcolor="pink">
    <h1 align="center">
        <font color="green"><b>Nolambur</b></font>
    </h1>
      <h3 align="center">
        <font color="blue"><b>DECATHLON<sub>-</sub>sports</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="DECATHLON" size="5">
            Decathlon Nolambur, located at Plot No -115/1, Service Road, Maduravoyal - Ambattur Estate, NH West, Nolambur, Mogappair, Chennai, Tamil Nadu 600058,
             is a prominent sporting goods store offering an extensive range of equipment and apparel for various sports and outdoor activities. ​
            
            Store Details:
            
            Address: Plot No -115/1, Service Road, Maduravoyal - Ambattur Estate, NH West, Nolambur, Mogappair, Chennai, Tamil Nadu 600058​
            
            Phone: +91 95139 55601
        </font>
    </p>
    </body>
</html>

home.html

<html>
    <head>
        <title>My city</title>
    </head>
    <body bgcolor="ceon">
    <h1 align="center">
        <font color="blue"><b>Nolambur</b></font>
    </h1>
      <h3 align="center">
        <font color="black"><b>my home<sub>-</sub>mogappair west</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Home" size="5">
            Nolambur is the neighbourhood in the western part of Chennai. 
            It is near to the Poonamallee High Road near Maduravoyal, Mogappair West, Ambattur, Ayanambakkam, and Athipet.
          Road access from the north is from Mogappair and Ambattur Industrial Estate. 
         Nolambur is located adjacent to Maduravoyal and Nerkundram, which are situated at its south boundaries. 
       Bharathi Salai and its continuation Nolambur Phase II road are 70 ft wide. They form the primary route of travelling for the residents nearby.
      The Inner ring road runs in the western fringes of Nolambur making it a place for rapid connectivity from all part of Chennai City.
    A few buses also ply through this area.
        </font>
    </p>
    </body>
</html>
```

# OUTPUT
![alt text](<praveena/mapapp/static/Screenshot 2025-04-09 184612.png>)
![alt text](<praveena/mapapp/static/Screenshot 2025-04-09 184628.png>)
![alt text](<praveena/mapapp/static/Screenshot 2025-04-09 184642.png>)
![alt text](<praveena/mapapp/static/Screenshot 2025-04-09 184705.png>)
![alt text](<praveena/mapapp/static/Screenshot 2025-04-09 184716.png>)
![alt text](<praveena/mapapp/static/Screenshot 2025-04-09 184840.png>)
# RESULT
The program for implementing image maps using HTML is executed successfully.

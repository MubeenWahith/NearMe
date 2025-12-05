# Ex03 Places Around Me
## Date: 03.12.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
~~~

<html>
    <head>
        <title>mapapp</title>
    </head>
    <body align = "center"></body>
        <h1>Ramanathapuram-Ramnad</h1>
        <br>
        <h4>25004201-MOHAMED MUBEEN.A </h4>
        <img src="Screenshot 2025-11-28 112709.png" usemap="#image-map">

            <map name="image-map">
                <area target="" alt="Saba Henna Artistry" title="Saba Henna Artistry" href="artistry.html" coords="1542,307,1595,374" shape="rect">
                <area target="" alt="Railway Station" title="Railway Station" href="station.html" coords="543,803,631,850,735,819,678,740,587,752" shape="poly">
                <area target="" alt="Government Hospital" title="Government Hospital" href="hospital.html" coords="414,555,71" shape="circle">
                <area target="" alt="Hotel Rifaya" title="Hotel Rifaya" href="rifaya.html" coords="512,293,379,221" shape="rect">
                <area target="" alt="Ponni Mess" title="Ponni Mess" href="mess.html" coords="693,291,634,262,657,202,794,227,819,265,918,327" shape="poly">
        </map>


    </body>
</html>


<html>   
    <head>
        <title>Ponni Mess</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="pink"><b>Ramanathapuram</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Ponni Mess</b></font>
        </h3>
        <hr size="3" color="white">
        <p align="justify">
            <font face="Georgia" size="5">
                 Ponni Mess in Ramanathapuram is a popular local eatery situated on Kenikarai, Devipattinam Road.
                 It is well known for serving authentic South Indian meals and biryani in a homely mess-style atmosphere.
                 The place has earned a strong reputation among locals for its flavorful dishes and good service, making it a go-to spot for those seeking traditional tastes in the region.
        
        </p>
                
   </body>
</html>


<html>   
    <head>
        <title>Rifaya</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">
            <font color="red"><b>Ramanathapuram</b></font>
        </h1>
        <h3 align="center">
        <font color="green"><b>Hotel Rifaya</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
            <font face="Georgia" size="5">
                Hotel Rifaya is a local budget hotel in Ramanathapuram town. 
                It is primarily used by pilgrims visiting the Ramanathaswamy Temple.
                Online information and booking options are very limited. 
                It is best to contact the hotel directly by phone for availability and rates. 
                Consider other established hotels in the area like Hotel Saravana for easier online booking. 
        </p>
                
   </body>
</html>


<html>   
    <head>
        <title>GH</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="green"><b>Ramanathapuram</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Government Hospital</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
            <font face="Georgia" size="5">
                Government District Headquarters Hospital, Ramanathapuram is the main public hospital in the district.
            It is located in the heart of Ramanathapuram town and offers a wide range of medical services across various departments, including General Medicine, 
            Surgery, Pediatrics, Gynecology, and Orthopedics.
            As a government facility, it provides affordable and often free healthcare to 
            the local population and is a crucial referral center for primary health centers in the area. 
            The hospital includes emergency services, inpatient wards, outpatient departments, and basic diagnostic facilities.</p>
   </body>
</html>

<html>   
    <head>
        <title>Railway</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">
            <font color="red"><b>Ramanathapuram</b></font>
        </h1>
        <h3 align="center">
        <font color="green"><b>Railway Station</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
            <font face="Georgia" size="5">
                Ramanathapuram Railway Station (station code: RMD) is a major railhead in Tamil Nadu's Ramanathapuram district. 
                It is well-connected to key cities like Chennai, Coimbatore, Madurai, and Trichy via several express and passenger trains. 
                The station serves as the main rail gateway for pilgrims visiting the famous Ramanathaswamy Temple in town and for travellers heading to the pilgrimage island of Rameswaram (connected via a separate branch line from Mandapam). 
                Facilities include basic waiting areas, reservation counters, and food stalls, with auto-rickshaws and taxis available outside for local transport.
        </p>       
   </body>
</html>


 <html>   
    <head>
        <title>seba</title>
    </head>
    <body bgcolor="aqua">
        <h1 align="center">
            <font color="red"><b>Ramanathapuram</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Seba Henna Artistry</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                Seba Henna Artistry is a professional bridal and special events henna service.
                They create intricate, detailed designs using natural henna paste for a rich, long-lasting stain.
                You can view their portfolio and contact them via their Instagram profile.</p>
   </body>
</html>


~~~

## OUTPUT

![alt text](<Screenshot (29).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (26).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.

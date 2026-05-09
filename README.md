# Ex04 Places Around Me
# Date:2/05/2026
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
map.html

<html>
<head>
<title>Image map</title>
</head>
<body>
<h1 align="center"><font color="red"><b>Tiruchirappalli</b></font></h1>
<h3 align="center"><font color="blue"><b>Avinash A(25018434)</b></font></h3>

<img src="tirchy.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="tiruchirappalli" title="tiruchirappalli" href="tiruchirappalli.html" coords="1768,1022,1345,882" shape="rect">
    <area target="" alt="panjappur" title="panjappur" href="panjappur.html" coords="1175,1270,99" shape="circle">
    <area target="" alt="samayapuram" title="samayapuram" href="samayapuram.html" coords="1682,10,1921,127" shape="rect">
    <area target="" alt="nochiyam" title="nochiyam" href="nochiyam.html" coords="1481,339,105" shape="circle">
    <area target="" alt="manachanallur" title="manachanallur" href="manachanallur.html" coords="1672,191,1376,79" shape="rect">
</map>
</body>
</html>

tiruchirappalli.html

<html>
<head>
<title>Tiruchirappalli</title>
</head>
</html>
<body bgcolor="Ivory">
<h1 align="center"><font color="red"><b>Tiruchirappalli</b></font>
</h1>
<h3 align="center"><font color="blue"><b>Tiruchirappalli, often called Trichy, is a historic city in Tamil Nadu known for its ancient temples, rich culture, and educational excellence.</b>
</font>
</h3>
<hr size="3" color="green">
<p align="center">
<font face="Georgia" size="5">Tiruchirappalli, commonly known as Trichy, is one of the oldest and most prominent cities in Tamil Nadu, situated along the banks of the River Cauvery.
The city is famous for the Rockfort Temple, a magnificent structure built on a massive rock over 3.8 billion years old.
Trichy has a deep historical legacy, having been ruled by the Cholas, Nayaks, Pallavas, and British.
It serves as a major cultural and educational hub, home to institutions like NIT Trichy and Bharathidasan University.
The Srirangam Ranganathaswamy Temple, one of the largest functioning Hindu temples in the world, is located here.
Trichy's economy thrives on education, engineering, manufacturing, and energy sectors.
The city is also known for its fine cigars, artificial diamonds, and traditional jewelry craftsmanship.
Festivals such as Vaikunta Ekadasi and Panguni Uthiram attract thousands of devotees and tourists every year.
It is well-connected by road, rail, and air, serving as a gateway to central Tamil Nadu.
Blending history, spirituality, and modern progress, Tiruchirappalli stands as a living symbol of Tamil culture and resilience.</font>
</p>
</body>

samayapuram.html

<html>
<head>
<title>Samayapuram</title>
</head>
</html>
<body bgcolor="Ivory">
<h1 align="center"><font color="red"><b>Samayapuram</b></font>
</h1>
<h3 align="center"><font color="blue"><b>Samayapuram, near Trichy, is best known for its Arulmigu Mariamman Temple — a major pilgrim destination in Tamil Nadu famed for its healing lore and crowded festivals.</b>
</font>
</h3>
<hr size="3" color="green">
<p align="center">
<font face="Georgia" size="5">Samayapuram is a small town located about 12 kilometers north of Tiruchirappalli (Trichy) in Tamil Nadu, India.
It is world-famous for the Arulmigu Mariamman Temple, dedicated to the goddess Mariamman, revered as a powerful deity of health and protection.
The temple is one of the most significant shrines in South India, attracting lakhs of devotees throughout the year.
Mariamman is believed to cure diseases and bring prosperity, and many devotees perform rituals like paal kudam (milk offering) and mottai adikkal (head shaving) as acts of devotion.
The temple's architecture follows traditional Dravidian style, featuring ornate gopurams (towers) and sacred sanctums.
The most important festival celebrated here is the Chithirai Festival, held in April, which lasts nearly 13 days with grand processions and rituals.
Devotees from Tamil Nadu and neighboring states like Kerala, Karnataka, and Andhra Pradesh visit during the festival season.
The temple is managed by the Hindu Religious and Charitable Endowments Department of Tamil Nadu.
Samayapuram is well-connected by road, located along the Trichy Chennai National Highway, making it easily accessible.
Beyond religion, Samayapuram is a cultural landmark representing Tamil Nadu's enduring faith, tradition, and temple heritage.</font>
</p>
</body>

panjappur.html

<html>
<head>
<title>Panjappur</title>
</head>
</html>
<body bgcolor="Ivory">
<h1 align="center"><font color="red"><b>Panjappur</b></font>
</h1>
<h3 align="center"><font color="blue"><b>Panjappur is a suburban locality of Tiruchirappalli, now known especially for the large, modern Integrated Bus Terminus and developing transport infrastructure.</b>
</font>
</h3>
<hr size="3" color="green">
<p align="center">
<font face="Georgia" size="5">Panjappur (also spelled Panjapur) is a suburb in the Edamalaipatti Pudur area, part of the Tiruchirappalli city limits.
It lies along the Tiruchi-Madurai National Highway, giving it strategic importance for transport and connectivity. 
A major development there is the Muthamizh Arignar Kalaignar M. Karunanidhi Integrated Bus Terminus (IBT), inaugurated in May 2025, at a cost of roughly ₹492-500 crore. 
This bus terminus handles both intra-city (city buses) and mofussil (long-distance/inter-district) bus services. 
It has many passenger amenities: numerous bus bays (for city and long distance), waiting lounges, restrooms & bathrooms, kiosk/shops, auto rickshaw bays, etc. 
The terminus is multi-level: the ground floor mostly for mofussil buses, the first floor for city buses. 
Panjappur is also host to educational institutions, for example Saranathan College of Engineering in the Venkateswara Nagar area. 
The area falls under a ward of the Trichy Corporation (Ward No. 39 and others), indicating it's officially part of the city governance area. 
Infrastructure improvements include new checkposts (for traffic control), better road access, etc., due to its growing importance as a transport node. 
Because of all these developments, Panjappur is fast evolving, playing a key role in decongesting older bus stands (like the Central Bus Stand) and improving transit flow in Trichy.</font>
</p>
</body>

manachanallur.html

<html>
<head>
<title>Manachanallur</title>
</head>
</html>
<body bgcolor="Ivory">
<h1 align="center"><font color="red"><b>Manachanallur</b></font>
</h1>
<h3 align="center"><font color="blue"><b>Manachanallur is a suburban town/taluk of Tiruchirappalli, Tamil Nadu, known for its rice mills, growing residential expansion, and improving connectivity.</b>
</font>
</h3>
<hr size="3" color="green">
<p align="center">
<font face="Georgia" size="5">Manachanallur is a town and taluk in Tiruchirappalli district in Tamil Nadu.
Its population as per the 2011 Census was 25,931, with literacy higher than many rural averages. 
The town is famous for its numerous rice mills, which form a key part of its economy (“RiceFort / Mannai Maanagaram” is a nickname). 
Tamil is the official and dominant language here.Geographically, Manachanallur is about 16 km from central Trichy, on the route towards Thuraiyur. 
To reduce traffic congestion in the town, a bypass road was constructed (around 2.6 km stretch), helping long-distance and tourist travel. 
The town was recently merged into the Tiruchirappalli City Municipal Corporation (in 2023), making it more integrated with the urban governance of Trichy. 
Manachanallur has moderate climate, average elevation ~67 meters above sea level, and gets about 860 mm annual rainfall. 
There are landmarks like Sri Boominathar Temple (dedicated to Lord Shiva) that add cultural / religious significance. 
Property values vary: guideline values for land in Manachanallur range from ~ ₹134/sq ft to ~ ₹469/sq ft depending on locality.</font>
</p>
</body>

notchiyam.html

<html>
<head>
<title>Nochiyam</title>
</head>
</html>
<body bgcolor="Ivory">
<h1 align="center"><font color="red"><b>Nochiyam</b></font>
</h1>
<h3 align="center"><font color="blue"><b>Nochiyam is a village situated in the Manachanallur block of Tiruchirappalli district, approximately 3 to 4 km from No. 1 Tollgate, known for its agricultural activities and developing infrastructure..</b>
</font>
</h3>
<hr size="3" color="green">
<p align="center">
<font face="Georgia" size="5">Nochiyam is part of the Manachanallur block in Tiruchirappalli district, Tamil Nadu. It is approximately 3 to 4 km from No. 1 Tollgate, a prominent area in the region.
As per the 2011 Census, Nochiyam had a population of 3,611, with a near-equal gender distribution.The literacy rate stands at 68.9%, with a notable difference between male (76.9%) and female (60.6%) literacy rates.
The primary occupation of the residents is agriculture, with many engaged as cultivators and agricultural laborers.
The village is well-connected by road, with proximity to major highways facilitating access to nearby towns and cities.
There are several schools in and around Nochiyam, including Raja Middle School and Raja High School, providing educational opportunities to the local population.
Basic healthcare services are available locally, with hospitals like Manachannallur Vasantham Medica and Dr. Shankar Ayurvedic Hospital in the vicinity.
The village is home to the Bragadeeswara Temple, a significant religious site attracting devotees and visitors.
There has been a gradual increase in residential developments, with plots and properties available for sale, indicating a growing interest in the area.
Nochiyam holds cultural importance, with local festivals and traditions playing a vital role in community life.</font>
</p>
</body>

```
# OUTPUT
<img width="1470" height="835" alt="trichymap" src="https://github.com/user-attachments/assets/225d4262-7280-4361-9228-aef5c9e0f95d" />
<img width="1470" height="833" alt="trichy" src="https://github.com/user-attachments/assets/a396cdd8-7312-4a4f-9474-7fe73f360f13" />
<img width="1470" height="832" alt="nochiyam" src="https://github.com/user-attachments/assets/e77f0573-df59-41b7-a6bc-8176144263b5" />
<img width="1470" height="835" alt="Manachanallur" src="https://github.com/user-attachments/assets/1daa64e0-73a3-4392-a7aa-f12babeda640" />
<img width="1470" height="833" alt="panjappur" src="https://github.com/user-attachments/assets/ec275a71-0bbf-4910-97b9-dc6205e63570" />
<img width="1470" height="836" alt="samayapuram" src="https://github.com/user-attachments/assets/76f479ef-3e23-47b0-bc90-9bbfad6d59a8" />

# RESULT
The program for implementing image maps using HTML is executed successfully.

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
index.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>Places Around College</title>
    </head>
    <body>
        <h1>Places Around</h1>
        <img src="images/map.png" usemap="#image-map">
        <map name="image-map">
            <area target="" alt="Saveetha Engineering College"
            title="Saveetha Engineering College"
            href="saveetha.html"
            coords="470,280,650,340"
            shape="rect">

            <area target="" alt="Queens Land"
            title="Queens Land"
            href="queensland.html"
            coords="815,170,40"
            shape="circle">

            <area target="" alt="Rajalakshmi Engineering College"
            title="Rajalakshmi Engineering College"
            href="rajalakshmi.html"
            coords="320,520,520,640"
            shape="rect">
        </map>
    </body>
</html>
```

Saveetha.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Saveetha Engineering College</title>
</head>

<body>

<h1>Saveetha Engineering College</h1>

<p>This college is located near Chennai.</p>

<p>It offers engineering and technology courses.</p>

<p style="text-align: justify; font-size: 20px;">Saveetha Engineering College is a co-educational Institution. The college is affiliated with Anna University, Chennai, the largest technical university in India.[1] Saveetha Engineering College is granted Autonomous status by University Grants Commission (UGC)., Affiliated to Anna University located in Chennai, India. It was founded in 2001 by the Saveetha Medical and Educational Trust, a registered charitable society. Approved by the All India Council for Technical Education (AICTE), a statutory body of the Government of India, and also by the Government of Tamil Nadu. The campus is facing Chembarambakkam lake on the Chennai-Bangalore National Highway (NH4), Thandalam, Kancheepuram District, Chennai, Pin: 602105. Located about 8 km (5.0 mi) from Poonamalee township.

Academics
Saveetha Engineering College offers undergraduate, postgraduate, and doctoral programmes in engineering and management. As of 2025, the college provides 12 full-time undergraduate engineering courses, including Agricultural Engineering, Artificial Intelligence and Data Science, Biomedical Engineering, Civil Engineering, Computer Science and Engineering, Electronics and Communication Engineering, Electrical and Electronics Engineering, Information Technology, Mechanical Engineering, Medical Electronics, and Bioinformatics.[2] The institution also offers postgraduate programmes such as Master of Business Administration (MBA) and Master of Engineering (M.E.), along with opportunities for doctoral research (Ph.D.).[3]

Rankings
University rankings
Engineering – India
NIRF (2024)[4]	201-300
The National Institutional Ranking Framework (NIRF) ranked the college in 201-300 band in the engineering rankings in 2024.[5]

References
 "Affiliated Colleges – Kancheepuram District". Centre for Affiliation of Institutions – Anna University, Chennai. Retrieved 28 May 2018.
 "Saveetha Engineering College Chennai: Programmes Offered". Collegedunia. Retrieved 10 September 2025.
 "Saveetha Engineering College Strategic Plan 2025" (PDF). Saveetha Engineering College. Retrieved 10 September 2025.
 "National Institutional Ranking Framework 2024 (Engineering)". National Institutional Ranking Framework. Ministry of Education. 12 August 2024.
 "NIRF Ranking 2024"</p>

<a href="index.html">Go Back</a>

</body>
</html>
```


QuensLand.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Queens Land</title>
</head>

<body>

<h1>Queens Land Amusement Park</h1>

<p>A famous amusement park near Chennai.</p>

<p>It contains water rides and entertainment games.</p>

<p style="text-align: justify; font-size: 20px;">Queens Land Theme Park in Chennai is a fun destination that promises an exhilarating experience for visitors of all ages. Nestled amidst lush greenery, this amusement park offers if you’re looking for a 1-day trip in Chennai.

The Queensland Amusement Park in Chennai is a thrilling escape from the hustle and bustle of city life. As one of the premier amusement parks in the region, Queens Land boasts an array of exciting rides, attractions, and entertainment options that cater to the diverse interests of its guests.

From adrenaline-pumping roller coasters to family-friendly rides, there’s something for everyone to enjoy at the Queensland Amusement Park in Chennai, Tamil Nadu. The park’s beautiful landscaped grounds provide a picturesque backdrop for an unforgettable day of fun and adventure. Whether you’re seeking heart-stopping thrills or leisurely activities, Queensland has it all!

Moreover, the theme park is also renowned for its commitment to safety, cleanliness, and customer satisfaction, ensuring every visitor has a memorable and enjoyable experience. With its affordable ticket prices and convenient location, Queensland is the perfect destination for families, friends, and thrill-seekers alike.

If you plan to visit Queensland Amusement Park in Chennai soon, this article provides you with all the essential information you’ll need.</p>

<a href="index.html">Go Back</a>

</body>
</html>
```

Rajalakshmi.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Rajalakshmi Engineering College</title>
</head>

<body>

<h1>Rajalakshmi Engineering College</h1>

<p>A popular engineering college in Chennai.</p>

<p style="text-align: justify; font-size: 20px;">Rajalakshmi Engineering College is a private engineering college[3] located at Thandalam, Sriperumbudur near Chennai, Tamil Nadu, India. The college was established in 1997 by the Rajalakshmi Educational Trust and is part of the Rajalakshmi Institutions.[4] At its 24th graduation ceremony on August 24, 2025, Rajalakshmi Engineering College awarded degrees to approximately 1,720 students.[5]

Accreditations
It is approved and accredited by the National Board of Accreditation (NBA)[6]

The college is also accredited by companies like Tata Consultancy Services, Cognizant Technology Solutions, WIPRO Trusted Academic Partner and Infosys Campus Connect. Ashok Leyland recognized the college as a centre of excellence in automotives. IBM named it a "Centre of Excellence for Certified Software Center".[6]

Cooperation with other organisations
It has memoranda of understanding with the following industry representatives:

Robert Bosch GmbH to set up a joint certification training centre.[7]
Aban Group focusing on biofuel from algae.[8]
Rajalakshmi Education Private Limited has entered into an agreement with University of Worcester to jointly offer courses in computing and management.[9]

REC sponsored the Aircel Chennai Open from 2012.[10]

Facilities
The REC library has a collection of 48,100 volumes and periodicals.[11]

Transport
Since the campus is located 35 kilometres (22 mi) away from Chennai city, transportation is provided between Chennai and the college. The college now runs over 119 air-conditioned buses.[12]

Conferences and symposia
In 2013, REC organised an international conference on surface engineering for research and industrial applications, Interfinish SERIA 2013 Asia Pacific.[13]

Rankings
University and college rankings
General – India
NIRF (Overall) (2024)[14]	151-200
Engineering – India
NIRF (2024)[15]	101-150
The National Institutional Ranking Framework (NIRF) ranked it between 101-150 among engineering colleges and 151-200 overall in 2024.[16][17]

Societies and extracurricular activities
NSS (a community service initiative)[18]
KRIYA
KRIYA is an "entrepreneurship development cell" with the stated aim of conducting research, inspiring students, assist with project development and provide interaction with entrepreneurs and industrialists. The facility is designed by students.[19]

Alumni association
Some alumni have achieved a degree of international recognition.[20][21]</p>

<a href="index.html">Go Back</a>

</body>
</html>



```
# OUTPUT
<img width="1124" height="1026" alt="Screenshot 2026-05-12 220833" src="https://github.com/user-attachments/assets/bcad279b-f8a5-4fc8-baad-211cad76da9d" />
<img width="1919" height="450" alt="Screenshot 2026-05-12 220840" src="https://github.com/user-attachments/assets/f5351278-6f7e-488c-8f42-1891d0fd1ffc" />
<img width="1919" height="601" alt="Screenshot 2026-05-12 220821" src="https://github.com/user-attachments/assets/a12734f1-b577-4e7b-b83c-6c9cc45d053e" />
<img width="1918" height="659" alt="Screenshot 2026-05-12 220901" src="https://github.com/user-attachments/assets/c8023ccb-c04a-4d8d-b56c-694346943063" />



# RESULT
The program for implementing image maps using HTML is executed successfully.

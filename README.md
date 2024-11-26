# Ex04 Places Around Me
## Date: 26/11/24

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
```
map.html

<html>
<head>
<title>My City</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Vishal (24900214)</b></font>
</h3>
<center>
<img src="1.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="home.html" title="My Home Town">
<area shape="circle" coords="570,230,45" href="temple.html" title="Balamurugan Temple">
<area shape="circle" coords="640,200,30" href="lake.html" title="Anathur Lake">
<area shape="circle" coords="1120,360,25" href="garden.html" title="RR Garden">
<area shape="rect" coords="950,120,1100,140" href="stone.html" title="Virpattu Big Stone">
</map>
</center>
</body>
</html>

Home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Chennai - My Home Town</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Chennai, the capital of Tamil Nadu, is a major cultural, economic, and educational hub on India's southeastern coast. Known for its rich heritage, the city is famous for classical music, dance, and historic temples. It is also a key player in the automotive and IT industries, earning the nickname "Detroit of India."

    Key highlights:
    - Culture:Tamil is the primary language; known for classical music festivals like Margazhi and cultural landmarks such as the Kapaleeshwarar Temple.
    - Economy:A major center for automobile manufacturing, IT services, and trade (Chennai Port).
    - Attractions: Marina Beach, Fort St. George, and the Government Museum.
    - Climate:Hot and humid with a northeast monsoon season.
    - Cuisine: Famous for South Indian food like idli, dosa, and filter coffee.
    - Transport: Chennai International Airport, Metro, buses, and suburban trains.
    
    Chennai combines modern development with deep cultural traditions, making it a dynamic and diverse city.</font>
</p>
</body>
</html>

garden.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>THEAR PARK-Theosophical Park</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Theosophical Society Garden (Thear Park) is a serene and peaceful green space located in Adyar, Chennai. It is part of the Theosophical Society, an international organization dedicated to promoting universal brotherhood and the exploration of spiritual and philosophical ideas. 

     Key Features:
    - Historic Trees:The park is home to a famous 450-year-old banyan tree, one of the largest in India.
    - Nature & Tranquility: The garden has a calm, tranquil atmosphere, with lush greenery, walking trails, and a variety of plant species.
    - Spiritual Significance: The park is associated with the Theosophical Society's teachings and serves as a place for meditation and reflection.
    - Wildlife: The garden is also home to birds and small wildlife, adding to its peaceful and natural charm.
    
    It’s a popular destination for nature lovers, meditation practitioners, and those seeking a quiet retreat in the heart of Chennai.</font>
</p>
</body>
</html>

lake.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="purple">
<h1 align="center">
<font color="cyan"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="lime"><b>Pulicat Lake</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5" color="white">
    Pulicat Lake is a large brackish water lake located about 60 km north of Chennai, straddling the Tamil Nadu-Andhra Pradesh border. It is the second-largest coastal lagoon in India and is famous for its Pulicat Lake Bird Sanctuary, which attracts migratory birds like flamingos and pelicans, especially during the winter. The lake is also home to diverse marine life, mangrove forests, and fishing communities.

Key highlights:
- Popular for birdwatching and boating.
- Ecologically significant with rich flora and fauna.
- Faces environmental challenges like pollution and encroachment.
- Easily accessible by road from Chennai, it is a peaceful retreat for nature lovers.
</font>
</p>
</body>
</html>

stone.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Virpattu Big Stone - The Tourists Attraction</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Krishna's Butter Ball is a large, round granite boulder located in Mahabalipuram, Tamil Nadu. It is famous for its unusual positioning, as it appears to be precariously balanced on a small slope, seemingly defying gravity. The rock has been a subject of fascination for centuries and has become one of the most iconic landmarks in Mahabalipuram.

     Key Features:
    - Size and Shape: The massive boulder weighs several tons and measures about 6 meters in diameter.
    - Natural Wonder: The rock is a natural formation and has not been moved or altered; it simply sits at an angle on the ground, which makes it look as though it could roll down at any moment.
    - Historical Significance: The rock is believed to have been named after Lord Krishna, and some local legends say it resembles a ball of butter, referring to the deity's childhood habit of stealing butter.
    - Tourist Attraction: Krishna's Butter Ball has become a popular tourist spot, and visitors often take photos of the unique formation, marveling at its stability.
    
    It is one of the many fascinating stone formations in Mahabalipuram, showcasing nature's wonder and the mystery surrounding ancient monuments.</font>
</p>
</body>
</html>

temple.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b> Kapaleeshwarar Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Kapaleeshwarar Temple is a historic Hindu temple dedicated to Lord Shiva, located in the Mylapore area of Chennai. It is one of the most prominent and oldest temples in the city, with a rich cultural and spiritual significance.

    Key Features:
    - Deity: The temple is dedicated to Lord Kapaleeshwarar (a form of Shiva) and his consort Karpagambal (a form of Parvati).
    - Architecture: The temple showcases classic **Dravidian architecture**, featuring a beautifully ornate gopuram (gateway tower) with intricate carvings of deities, mythological scenes, and animals.
    - Historical Significance: Believed to have been originally built by the Pallavas in the 7th century and later expanded by the Vijayanagara kings, the temple has been an important center of worship for centuries.
    - Festivals: The temple hosts many annual festivals, with the Arupathimoovar Festival (celebrating Lord Murugan) and Mahashivaratri being major events, drawing large numbers of devotees.
    - Location: The temple is located in the heart of Mylapore, a culturally rich area in Chennai, and is a popular pilgrimage site for locals and tourists alike.
    
    Kapaleeshwarar Temple is not only a spiritual landmark but also a hub of cultural activities, making it an important part of Chennai’s heritage.</font>
</p>
</body>
</html>

```


## OUTPUT

![alt text](<Screenshot 2024-11-25 202057.png>)
![alt text](<MAPPROJECT/MAPAPP/static/Screenshot 2024-11-26 091456.png>)
![alt text](<MAPPROJECT/MAPAPP/static/Screenshot 2024-11-26 091651.png>)
![alt text](<MAPPROJECT/MAPAPP/static/Screenshot 2024-11-26 091816.png>)
![alt text](<MAPPROJECT/MAPAPP/static/Screenshot 2024-11-26 093044.png>)
![alt text](<MAPPROJECT/MAPAPP/static/Screenshot 2024-11-26 091901.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.

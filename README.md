# Ex04 Places Around Me
## Date: 12/05/2025

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
~~~
map.html
<html>
  <head>
    <title>My City</title>
  </head>
  <body>
    <h1 align="center">
      <font color="red"><b>TIRUTTANI</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>YAMUNA SHRI VARDHINI (212224040368)</b></font>
    </h3>
    <center>
      <img src="tiruttani map.png" usemap="#MyCity" height="610" width="1450">
      <map name="MyCity">
        <area shape="rect" coords="210,130,350,225" href="home.html" title="My Home Town">
        <area shape="rect" coords="905,255,1095,335" href="temple.html" title="ARULMIGU SUBRAMANYA SWAMY TEMPLE">
        <area shape="rect" coords="935,255,1075,425" href="waterfalls.html" title="KAILASAKONA WATERFALLS">
        <area shape="rect" coords="935,255,1075,425" href="resorts.html" title="REVA RESORTS HOLIDAY HOMES">
      </map>
    </center>
  </body>
</html>

home.html
<html>
<head>
<title>HOMETOWN</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>TIRUTTANI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>HOME TOWN</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Tiruttani is a historic temple town in Tamil Nadu, India, located in the Tiruvallur district and part of the Chennai Metropolitan Area. It is best known for the Tiruttani Murugan Temple, an ancient Hindu temple dedicated to Kartikeya (Murugan), the god of war. This temple is one of the Arupadaiveedu, the six sacred abodes of Murugan.
Historically, Tiruttani was part of Andhra Pradesh until 1960, when it was transferred to Tamil Nadu based on linguistic considerations. The town is surrounded by small hills and has a hot and humid climate. It is well-connected to major cities like Chennai (80 km away), Tirupati (66 km), and Vellore (80 km)
</font>
</p>
</body>
</html>

temple.html
<html>
<head>
<title>TEMPLE</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>TIRUTTANI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>ARULMIGU SUBRAMANYA SWAMY TEMPLE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The Tiruttani Murugan Temple, also known as Arulmigu Subramaniya Swamy Temple, is one of the six sacred abodes (Arupadaiveedu) of Lord Murugan, located in Tiruttani, Tamil Nadu. Perched atop a hill with 365 steps, symbolizing the days of the year, this temple is believed to be the place where Lord Murugan calmed his anger after defeating the demon Tarakasura, which is why the Surasamharam festival is not celebrated here. The temple’s Dravidian-style architecture features intricate carvings and a grand gopuram, and its main deity, Murugan, is worshipped alongside his consorts Valli and Devasena. The temple has strong connections to Indra, the king of gods, who is said to have gifted his daughter Devasena to Murugan along with his divine elephant Airavata. It is open daily from 5:45 AM to 9:00 PM, with significant rituals such as Viswaroopa Pooja (5:45 AM), Kalasandhi Pooja (8:00 AM), Uchikkala Pooja (12:00 PM), Sayaraksha Pooja (5:00 PM), and Palliyarai Pooja (8:45 PM). Special sevas, including the Golden Chariot procession, Panchamritha Abhishekam, and Thirukalyana Urchavam, attract devotees throughout the year.
</font>
</p>
</body>
</html>

waterfalls.html
<html>
<head>
<title>WATERFALLS</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>TIRUTTANI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>KAILASAKONA WATERFALLS</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Kailasakona Waterfalls is a serene and picturesque perennial waterfall located in the Nagari Valley, Chittoor district, Andhra Pradesh, near Tiruttani. Cascading from a height of approximately 30 meters, the waterfall forms a clear pond below, and its waters are believed to have medicinal properties. Surrounded by lush greenery, it offers a tranquil retreat for nature lovers. Close to the falls, there is a small temple dedicated to Lord Shiva and Parvati, adding a spiritual touch to the location. According to legend, Lord Kailasanatheswara Swamy visited this site during the wedding of Lord Venkateswara Swamy and Goddess Padmavathi at Narayanavanam, which is about 9 km away. The best time to visit is between October and February, when the water flow is at its peak. The falls are easily accessible by road, and visitors can reach the foot of the falls with their vehicles. APSRTC buses connect Tirupati and Puttur to the site, and nearby guest houses, such as Haritha Hotel, provide accommodation options
</font>
</p>
</body>
</html>

resorts.html
<html>
<head>
<title>RESORTS</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>TIRUTTANI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>REVA RESORTS HOLIDAY HOMES</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Reva Resorts & Holiday Homes is a leisure and adventure resort located near Tiruttani, offering a blend of relaxation, entertainment, and wellness experiences. Spread across 25 acres of lush green mango groves, the resort provides a serene escape from city life. Guests can enjoy a variety of activities, including swimming, rain dance, trekking, cycling, and outdoor games. The resort features 30+ deluxe rooms with attached balconies and restrooms, ensuring a comfortable stay. It also offers a health spa, making it an ideal destination for rejuvenation. The property is known for hosting private parties, team outings, and family gatherings, with facilities like campfires, music, and fun games. Located near K.J. Puram Bus Stand, Ranipet, the resort is easily accessible.

</font>
</p>
</body>
</html>
~~~

## OUTPUT

![alt text](<yamuna/Screenshot 2025-05-12 111950.png>)

![alt text](<yamuna/Screenshot 2025-05-12 113556.png>)

![alt text](<yamuna/Screenshot 2025-05-12 113638.png>)

![alt text](<yamuna/Screenshot 2025-05-12 113713.png>)

![alt text](<yamuna/Screenshot 2025-05-12 113757.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.

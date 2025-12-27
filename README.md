EX-3
# Date:20/11/2025
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

# Code
Map .html


{% load static %}
<title>Thiruvannamalai </title>
<body>
    <center><h1>sathish v (25012470)</h1>
<img src="static.tvm.png" usemap="#image-map">
</center>

<map name="image-map">
    <area alt="arunachaleswarar temple" title="arunachaleswarartemple" href="temple.html" coords="748,498,847,539" shape="rect">
    <area alt="jawadhu hills" title="jawadhu hills" href="jawadhu .html" coords="35,215,121,140" shape="rect">
    <area alt="Parvathamalai" title="Parvathamalai" href="malai.html" coords="1196,639,1298,717" shape="circle">
    <area alt="Gingee For" title="Gingee For" href="fort.html" coords="555,572,572,607" shape="rect">

</map>
</body>
</html>
```
Temple.html
```{load static %}
<html>
    <head>
        <title>arunachaleswarar temple</title>
        <img src="temple.jpeg"  usemap="#image-map">
    
    </head>
    <body bgcolor="lime">
        The Arunachalam Temple, also known as the Arunachaleswarar Temple<br>
         Is a historic Hindu temple dedicated to Lord Shiva, located in Tiruvannamalai, Tamil Nadu, India<br>
         It is one of the five Pancha Bhoota Sthalams, representing the element of fire (\(Agni\))<br>
         The temple complex is massive, featuring four large gopurams (towers), significant sculptures,<br> 
         and a rich history of being built and expanded upon by the Chola, Pallava, and Vijayanagara dynasties.<br>
         <br>
           Legend: The temple is said to be the spot where Lord Shiva appeared as a column of fire to challenge Lord Vishnu and Lord Brahma. 
           Visitor experience<br>
           It is a significant pilgrimage site that draws millions of visitors.<br>
           The circumambulation of the hill is believed to be a sacred act<br>
           Many saints and sages, like Sri Ramana Maharshi, have worshipped there<br> 
           ```
jawadhu.html
<html>
    <head>
        <title>jawadhu </title>
         <img src="jawadhu.jpeg"  usemap="#image-map">
    
    </head>
    <body bgcolor="teal">
        The Javadhu Hills (also Jawadhi, Jawadhu Hills) are an extension of the Eastern Ghats spread across parts of Vellore and Tiruvannamalai districts in the northern part of the state of Tamil Nadu in southeastern India.<br>
        This range separates Vellore and Tiruvannamalai districts. Vellore district lies on the north western side and Tiruvannamalai district lies on the south eastern side of this range. About 50 miles (80 km) wide and 20 miles (32 km) long,<br>
         they are bisected into eastern and western sections by the Cheyyar and Agaram rivers, tributaries of the Palar. They consist of bluish gray granites, with peaks averaging 3,600–3,800 feet (1,100–1,150 m). The hills are sparsely populated; <br>
         the majority of the inhabitants are Malayali tribespeople, though other castes are also present. There are many tourist places near Javadhu Hills, e.g., the Beemanmadavu waterfalls.<br>
         <br>
       

    </body>
</html>```

malai.html
<html>
    <head>
        <title>Parvathamalai </title>
         <img src="malai.jpeg"  usemap="#image-map">
    
    </head>
    <body bgcolor="teal">
        Parvathamalai is a sacred hill in the Tiruvannamalai district of Tamil Nadu, famous for the ancient Mallikarjuna Swamy Temple dedicated to Lord Shiva at its summit<br>
        It is a popular trekking destination, known for its moderately difficult, steep, and rocky trails, including a challenging section called Kadapaarai <br>
        Padhai that requires using iron rods and chains to ascend. The trek is considered both a spiritual and adventurous experience<br>
        <br>
        Difficulty: The trek is considered moderately difficult, with some sections being very steep.
         Distance: The trek is about 5 km uphill.<br>
        Time: It takes around 2.5 to 3.5 hours to complete the trek one way.
        Terrain: The path includes rocky trails, forest routes, and steep, rocky sections with iron ladders, rods, and chains.<br>
        Kadapaarai Padhai: This is the most challenging part of the trek, involving climbing using iron rods and chains drilled into the rocks.
        Best Time to Visit: The best time to visit is between September and February.<br>
        Access points: There are three ways to access the peak: Thenmadhi mangalam, Mambakkam, and Kadaladi.<br>
        <br>

    </body>
</html>

# OUTPUT
<img width="1919" height="1077" alt="Screenshot 2025-12-15 202519" src="https://github.com/user-attachments/assets/6a1ba710-fcb6-419a-884f-65e83546c519" />

<img width="1919" height="1077" alt="Screenshot 2025-12-15 203358" src="https://github.com/user-attachments/assets/92009617-3b14-4080-b676-db8efc66b6de" />

<img width="1919" height="1079" alt="Screenshot 2025-12-15 203423" src="https://github.com/user-attachments/assets/71169638-0cff-444d-ac08-049bc0bdd4c1" />

<img width="1917" height="1079" alt="Screenshot 2025-12-15 204030" src="https://github.com/user-attachments/assets/4d233a99-b983-487e-9b59-b4ce2b474e4b" />

#Result!:
 The program for implementing image maps using HTML is executed successfully.

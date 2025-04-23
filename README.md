# Ex04 Places Around Me
## Date: 23-04-2025

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
## map.html
<html>
    <title>Mycity</title>
    <body bgcolor="white">
        <h1 align="center"><font color="black">ARAKKONAM</font></h1>
        <h3 align="center">
            <font color="red">AJITH KUMAR (212223230009)</font></h3>
        <center>
            <img src="map.png" usemap="#image-map">

            <map name="image-map">
                <area target="" alt="minnal" title="minnal" href="minnal.html" coords="79,578,218,647" shape="rect">
                <area target="" alt="big lake" title="big lake" href="biglake.html" coords="576,103,819,246" shape="rect">
                <area target="" alt="arakkonam" title="arakkonam" href="arakkonam.html" coords="1580,425,1748,515" shape="rect">
                <area target="" alt="sindhu cinema" title="sindhu cinema" href="cinema.html" coords="1439,584,1643,628" shape="rect">
                <area target="" alt="rajali" title="rajali" href="rajali.html" coords="1568,657,1775,712" shape="rect">
            </map>
        </center>

    </body>
</html>

## minnal.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">ARAKKONAM</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">MINNAL</font>
    </h3>
    <body bgcolor="yellow" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Minnal is a well-known multiplex cinema located in Arakkonam, offering a modern and enjoyable movie-watching experience for patrons. Equipped with state-of-the-art facilities and comfortable seating arrangements, Minnal attracts movie enthusiasts from the town and surrounding areas. It showcases a diverse selection of films, ranging from mainstream blockbusters to regional cinema, ensuring there's something for everyone. Its convenient location and quality amenities make it a favored destination for entertainment seekers in Arakkonam.
        </font>
        </p
    </body>
</html>

## arakkonam.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">ARAKKONAM</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">arakkonam</font>
    </h3>
    <body bgcolor="cyan" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Arakkonam is a town located in the Indian state of Tamil Nadu. It is known for its strategic importance due to the presence of the Indian Air Force and Indian Navy bases. The town is also a major railway junction, connecting various parts of Tamil Nadu and neighboring states. Arakkonam is renowned for its historical significance, with landmarks like the Rajiv Gandhi Memorial and the nearby Kanchipuram district, famous for its temples and silk sarees. Additionally, it boasts a diverse cultural heritage, blending traditional Tamil culture with modern influences.
        </font>
        </p
    </body>
</html>

## cinema.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">ARAKKONAM</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="black" size="5.5">Sindhu cinema</font>
    </h3>
    <body bgcolor="red" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Sindhu Cinema in Arakkonam is a popular entertainment destination in the town. It offers a diverse range of movies, catering to various tastes and preferences of the audience. With comfortable seating and modern amenities, it provides a pleasant cinematic experience for moviegoers. The theater often screens the latest releases, keeping the audience engaged and entertained. Its central location makes it easily accessible for residents and visitors alike, contributing to its popularity in the local community.
        </font>
        </p
    </body>
</html>

## rajali.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">ARAKKONAM</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Rajali</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Rajali Cinema in Arakkonam is a prominent movie theater known for its long-standing presence in the town's entertainment scene. With its spacious auditoriums and comfortable seating, Rajali provides a satisfying cinematic experience for movie buffs. It regularly screens a variety of films, including the latest releases and popular classics, catering to the diverse tastes of its audience. Situated conveniently within the town, Rajali is easily accessible to residents and visitors alike, making it a favored destination for moviegoers seeking entertainment in Arakkonam.
        </font>
        </p
    </body>
</html>

## biglake.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">ARAKKONAM</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">BIG LAKE</font>
    </h3>
    <body bgcolor="orange" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The big lake in Arakkonam, also known as the Arakkonam Lake, is a prominent water body situated in the heart of the town. Spanning a considerable area, the lake serves as a crucial water source for local residents and supports a rich ecosystem. It also provides a picturesque backdrop for recreational activities such as boating and fishing. Moreover, the lake contributes to the town's natural beauty and plays a significant role in maintaining the environmental balance of the region.
        </font>
        </p
    </body>
</html>
```
## OUTPUT
![Screenshot 2024-04-15 083316](https://github.com/Ajith1413/NearMe/assets/139842524/88d713e4-849c-4779-9e51-5c08597c25f7)
![Screenshot 2024-04-15 083330](https://github.com/Ajith1413/NearMe/assets/139842524/11a652fa-e5d8-4d31-a7a8-e39fac63d3d3)
![Screenshot 2024-04-15 083344](https://github.com/Ajith1413/NearMe/assets/139842524/194df563-7638-4a24-8025-f79c720eb590)
![Screenshot 2024-04-15 084334](https://github.com/Ajith1413/NearMe/assets/139842524/27e3575f-7db4-4cc4-bad3-d2bbf924d36f)
![Screenshot 2024-04-15 083410](https://github.com/Ajith1413/NearMe/assets/139842524/cac717a9-7115-481e-b2ac-8240b3a3473f)
![Screenshot 2024-04-15 083638](https://github.com/Ajith1413/NearMe/assets/139842524/446fce97-7256-4134-b971-481b0febec31)


## RESULT
The program for implementing image maps using HTML is executed successfully.

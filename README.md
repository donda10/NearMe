# Ex04 Places Around Me
## Date: 
24-12-2024

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
<style>
    img {
        width: 1000px;

        
    }
</style>
</head>
<body>
<h1 align="center">
<font color="black"><b>Vadamadurai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Simon Malachi S</b></font>
</h3>
<center>
    <img src="Screenshot (24).png" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="d mart" title="d mart" href="temp.html" coords="977,278,1109,379" shape="rect">
        <area target="" alt="krishna mandapam" title="krishna mandapam" href="mahal.html" coords="982,632,1072,714,1012,747,959,721" shape="poly">
        <area target="" alt="clinic" title="clinic" href="vcare.html" coords="1532,601,76" shape="circle">
        <area target="" alt="dasarathan school" title="dasarathan school" href="clg.html" coords="778,407,74" shape="circle">
        <area target="" alt="emerald" title="emerald" href="park.html" coords="1087,115,1156,166,1076,188" shape="poly">
    </map>
</center>
</body>
</html>

temp.html

<html>
<head>
    <title>D Mart</title>
    <style>
        body {
            background-color: #e8f5e9;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #424242;
        }
        h1 {
            text-align: center;
            color: #388e3c;
            background-color: #c8e6c9;
            padding: 20px;
            margin: 0;
        }
        p {
            text-align: justify;
            margin: 20px 50px;
            font-size: 16px;
        }
    </style>
</head>
<body>

    <h1>D Mart</h1>

    <p>Avenue Supermarts Limited, d/b/a DMart, is an Indian retail corporation that operates a chain of supermarkets and hypermarkets. The company was founded by Radhakishan Damani and is based in Mumbai. As of September 2024, DMart has 377 stores across 12 states and union territories in India.</p>

</body>
</html>

clg.html


<html>
<head>
    <title>Dr.Dasarathan International School</title>
    <style>
        body {
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
            color: #333;
        }
        h1 {
            text-align: center;
            color: #004080;
            background-color: #e0f7fa;
            padding: 20px;
            margin: 0;
        }
        p {
            text-align: justify;
            margin: 20px 50px;
            font-size: 22px;
        }
    </style>
</head>
<body>

    <h1>Dr.Dasarathan International School</h1>

    <p>Dr.Dasarathan International School is a school that provides a rich and holistic education to its students. The school’s credo is to Inspire, Explore, and Excel, and it aims to nurture well-educated and disciplined citizens. The school emphasizes research-based learning, literacy, critical thinking, leadership, and provides opportunities for its students to grow. It offers a strong foundation for its students and has facilities that support their overall development. The school is committed to providing a supportive environment that allows its students to thrive and reach their full potential.





    </p>

</body>
</html>

mahal.html
<html>
<head>
    <title>Sri Krishna Thirumana Mand</title>
    <style>
        body {
            background-color: #fff0f5; /* Lavender blush background */
            font-family: 'Arial', sans-serif;
            color: #333;
        }
        h1 {
            text-align: center;
            color: #800080; /* Purple color for the header */
            background-color: #f5e6fa; /* Light purple background */
            padding: 20px;
            margin: 0;
        }
        p {
            text-align: justify;
            margin: 20px 50px;
            font-size: 22px;
        }
    </style>
</head>
<body>

    <h1>Sri Krishna Thirumana Mand</h1>

    <p>Sri Krishna Thirumana Mandapam is a spacious and elegant wedding hall designed for special occasions like weddings, receptions, and celebrations. It offers modern amenities, ample seating, and beautiful decor to create a memorable experience. Conveniently located, it provides parking facilities and excellent service to ensure a stress-free event. The venue is perfect for bringing families and friends together to celebrate cherished moments.</p>

</body>
</html>

park.html

<html>
<head>
    <title>Emerald Jewel Industry</title>
    <style>
        body {
            background-color: #fff8e1;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #424242;
        }
        h1 {
            text-align: center;
            color: #2e7d32;
            background-color: #a5d6a7;
            padding: 20px;
            margin: 0;
        }
        p {
            text-align: justify;
            margin: 20px 50px;
            font-size: 16px;
        }
    </style>
</head>
<body>

    <h1>Emerald Jewel Industry</h1>

    <p>Introduction to Emerald Jewel Industry: Emerald Jewel Industry India Limited is a renowned jewellery manufacturer based in Coimbatore, India. Established in 1984 by K. Srinivasan, the company has grown to become one of the world’s largest jewellery manufacturers, known for its quality consciousness, uniqueness in design, and quality workmanship.</p>

</body>
</html>


```


## OUTPUT

![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)
![alt text](<Screenshot (46).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.

# Ex04 Places Around Me
## Date: 

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
``` python

Developed by :SHYAM KUMAR.E
Register Number :212223230207
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            background-color: aqua;
        }
        
    </style>
</head>
<body>
    <img src="d2.png" alt="" height = "530" usemap = "#MapNew" onmousemove = "coordinate(event)">
    <map name="MapNew">
        <area shape="RECT" coords="214,177,240,204" href="https://www.careerindia.com/colleges/c-t-m-college-of-arts-and-science-chennai-tamil-nadu-cp2816/" alt="ctm college">
        <area shape="RECT" coords="339,211,367,246" href="https://www.sreesasthaarts.in/" alt="sree sasthaa">
        <area shape="rect" coords="221,296,230,319" href="https://dmice.ac.in/" alt="dmice">
        <area shape="rect" coords="40,213,64,239" href="https://www.apolloartsandsciencecollegechennai.ac.in/about.aspx" alt="apollo arts and science">
        <area shape="rect" coords="190,453,216,473" href="https://lakeviewlifecentre.org/" alt="lakeview">
    </map><br>
    
    
   
</body>
</html>
```
## OUTPUT:
![map](https://github.com/Romanshyam/NearMe/assets/123962992/7b86f224-9f47-45ca-aad1-55bfa9b9a1d1)
![apollo](https://github.com/Romanshyam/NearMe/assets/123962992/31fe6171-c6a6-48d2-a915-dcb2375b4900)
![dmi](https://github.com/Romanshyam/NearMe/assets/123962992/e6f38230-c920-4c73-9f4a-ec58fd14211e)
![lakeview](https://github.com/Romanshyam/NearMe/assets/123962992/4452d76c-348c-492b-93e3-aa7f954c936f)
![sree sastha](https://github.com/Romanshyam/NearMe/assets/123962992/03520d78-e055-43d6-825c-1072616cb3dd)

## RESULT
The program for implementing image maps using HTML is executed successfully.

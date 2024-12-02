# Ex04 Places Around Me
## Date: 02/12/2024

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
<img src="Screenshot (7).png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="A.Reddihalli" title="A.Reddihalli" href="A.Reddihalli.html" coords="480,484,644,566" shape="rect">
    <area target="" alt="vennampatti" title="vennampatti" href="Vennampatti.html" coords="843,676,112" shape="circle">
    <area target="" alt="Reliance" title="Reliance" href="Reliance.html" coords="1220,765,1141,890,1419,833" shape="poly">
    <area target="" alt="viswabhartahi" title="viswabhartahi" href="viswabharathi.html" coords="1523,749,1729,856" shape="rect">
    <area target="" alt="Don" title="Don" href="Don.html" coords="230,525,116" shape="circle">
</map>
A.Reddihalli.html
<html>
    <body bgcolor="Red">
        <h1>DHARMAPURI</h1>
        <h3>A.REDDIHALLI</h3>
       <p>
        According to Census 2011 information the location code or village code of A Reddihalli village is 643576. A Reddihalli village is located in Dharmapuri taluka of Dharmapuri district in Tamil Nadu, India. It is situated 1km away from Dharmapuri, which is both district & sub-district headquarter of A Reddihalli village. As per 2009 stats, Sogathur is the gram panchayat of A Reddihalli village.
       </p>
    </body>
</html>
Don.html
<html>
    <body bgcolor="pink">
        <h1>DHARMAPURI</h1>
        <h3>DON BOSCO COLLEGE</h3>
         <p>
            History. St John Bosco High School was originally founded in 1978 at the initiative of the parishioners of St John Bosco Parish, Engadine, as a systemic Years 7 - 10 school under the administration of the Salesians of Don Bosco.
         </p>
    </body>
</html>
Reliance.html
<html>
    <body bgcolor="yellow">
        <h1>DHARMAPURI</h1>
        <h3>RELIANCE</h3>
         <p>Reliance Digital is an Indian consumer electronics retailer. It is a subsidiary of Reliance Retail, a wholly owned subsidiary of Reliance Industries. Reliance Digital opened its first store on 24 April 2007 in Delhi. </p>
    </body>
</html>
Vennampatti.html
<html>
    <body bgcolor="cyan">
     <h1>DHARMAPURI</h1>
     <h3>VENNAMPATTI</h3>
     <p>Vennampatti is a small Village/hamlet in Dharmapuri Block in Dharmapuri District of Tamil Nadu State, India. It comes under Lakkiyampatti 2 Panchayath. It is located 1 KM towards East from District head quarters Dharmapuri. 289 KM from State capital Chennai
    </p>
    </body>
</html>
viswabharathi.html
<html>
    <body bgcolor="chocolate">
        <h1>DHARMAPURI</h1>
        <h3>VISWABHARATHI</h3>
        <P>Sri Viswabharathi Matriculation Higher Secondary School is an excellent choice for students seeking highly specialized education. The school provides a top-notch learning environment, dedicated faculty, and a strong focus on academic excellence. With its comprehensive curriculum and state-of-the-art facilities, it`s no wonder why this institution is highly regarded in the field of education.</P>
    </body>
</html>
```
## OUTPUT
![
](<Screenshot (13).png>)
](<Screenshot (12).png>)
](<Screenshot (11).png>)
](<Screenshot (10).png>)
![alt text](<Screenshot (9).png>)
![alt text](<Screenshot (8).png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.

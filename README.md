# Ex04 Places Around Me
## Date: 27.10.2023

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
<!DOCTYPE html>
<html lang="en">

<head>
    <title>My City</title>
</head>

<body>
    <h1 align="center">
        <font color="red"><b>Villupuram</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Surothaaman R (23008504)</b></font>
    </h3>
    <center>
        <img src="map1.png" usemap="#MyCity" height="914" width="1920">
        <map name="MyCity">
            <area shape="rectangle" coords="785,332,946,405" href="rail.html" title="Railaway station">
            <area shape="rectangle" coords="1690,800,1863,895" href="sacredherat.html" title="Sacred Heart Convent">
            <area shape="rectangle" coords="657,499,824,587" href="dell.html" title="dell">
            <area shape="rectangle" coords="243,445,397,520" href="titan.html" title="Titan world">
            <area shape="rectangle" coords="1676,323,1804,419" href="sportsstadium.html"
                title="villupuram district sports stadium">
        </map>
    </center>
</body>

</html>

dell.html

<!DOCTYPE html>
<html lang="en">

<head>
    <title>Dell</title>
</head>

<body bgcolor="lime">
    <h1 align="center">
        <font color="red"><b>Villupuram</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Dell</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            Dell Inc. is an American based technology company. It develops, sells, repairs, and supports computers and
            related products and services. Dell is owned by its parent company, Dell Technologies.

            Dell sells personal computers (PCs), servers, data storage devices, network switches, software, computer
            peripherals, HDTVs, cameras, printers, and electronics built by other manufacturers. The company is known
            for how it manages its supply chain and electronic commerce. This includes Dell selling directly to
            customers and delivering PCs that the customer wants. Dell was a pure hardware vendor until 2009 when it
            acquired Perot Systems. Dell then entered the market for IT services. The company has expanded storage and
            networking systems. It is now expanding from offering computers only to delivering a range of technology for
            enterprise customers.
        </font>
    </p>
</body>

</html>

titan.html

<!DOCTYPE html>
<html lang="en">

<head>
    <title>Titan</title>
</head>

<body bgcolor="lime">
    <h1 align="center">
        <font color="red"><b>Villupuram</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Titan</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            Titan Company Limited is an Indian company that mainly manufactures fashion accessories such as jewellery,
            watches and eyewear. Part of the Tata Group and started as a joint venture with the TIDCO, the company has
            its corporate headquarters in Electronic City, Bangalore, and registered office in Hosur, Tamil Nadu.

            Titan company commenced operations in 1984 under the name Titan Watches Limited. In 1994, Titan diversified
            into jewellery with Tanishq and subsequently into eyewear with Titan Eyeplus. In 2005, it launched its youth
            fashion accessories brand Fastrack.[9] The company is the largest branded jewellery maker in India, with
            more than 80% of its total revenues coming from the jewellery segment. As of 2022, Titan has a 6% market
            share in India's jewellery market. As of 2019, it is also the fifth-largest watch manufacturer in the world.
        </font>
    </p>
</body>

</html>

rail.html

<!DOCTYPE html>
<html lang="en">

<head>
    <title>Railaway station</title>
</head>

<body bgcolor="lime">
    <h1 align="center">
        <font color="red"><b>Villupuram</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Railaway station</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            Villupuram Junction is a railway station in Villupuram, Tamil Nadu. Being a prominent railway station, it
            serves as the distribution point of rail traffic from Chennai, the state capital of Tamil Nadu, towards the
            southern and central parts of the state. It is the third largest junction by number of branch lines in the
            state of Tamil Nadu after Salem junction,Tiruchchirapalli Junction . It is one of the A Grade train stations
            in Tamil Nadu.[1]
        </font>
    </p>
</body>
</html>

sportsstadium.html

<!DOCTYPE html>
<html lang="en">

<head>
    <title>villupuram district sports stadium</title>
</head>

<body bgcolor="lime">
    <h1 align="center">
        <font color="red"><b>Villupuram</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>villupuram district sports stadium</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            in the heart of Villupuram, amidst the lush landscapes and vibrant culture of Tamil Nadu, lies a place where
            dreams are nurtured, champions are born, and the spirit of sportsmanship thrives. The Villupuram District
            Sports Stadium, often called the "Pride of Sports" in this region, is more than just an arena; it's a symbol
            of the community's dedication to athletic excellence.

            Situated on the outskirts of Villupuram town, the stadium is a sprawling complex that caters to a multitude
            of sports and recreational activities. Its prominent feature is a well-maintained cricket field, where local
            and regional cricket matches are held regularly. The deafening cheers and enthusiastic applause of the crowd
            resonate through the stadium, giving life to the very spirit of the game.
        </font>
    </p>
</body>
</html>

```


## OUTPUT
![map1](https://github.com/surothaaman/NearMe/assets/133313653/2c108091-f2b1-4277-affa-e507dface21d)
![Screenshot (74)](https://github.com/surothaaman/NearMe/assets/133313653/4b26ab47-8ce1-48c4-a91c-9b528a4b867c)
![Screenshot (73)](https://github.com/surothaaman/NearMe/assets/133313653/6130632c-ff19-490f-9706-fca3dd24d42c)
![Screenshot (72)](https://github.com/surothaaman/NearMe/assets/133313653/c3bab5f4-6d1e-4dac-beb4-fa934a10e9d5)
![Screenshot (71)](https://github.com/surothaaman/NearMe/assets/133313653/e1dcdb7d-99a4-45f9-bf7f-028f01688b6e)
![Screenshot (70)](https://github.com/surothaaman/NearMe/assets/133313653/3e81b2f8-7690-48eb-b47c-d3907b2ce172)


## RESULT
The program for implementing image maps using HTML is executed successfully.

# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### step 1:
clone the github repository into their theia IDE.

### Step 2:
create a new Django project.
 
### step 3:
write the needed HTML code.

### step 4:
Run the django server and execute the HTML.

## Code:
...

map.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Kanchipuram - Temple City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Thrikeswar p (22000731)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/sct.html" title="Shri Chitragupta Swamy Temple">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/kk.html" title="Kanchi Kudil">
<area shape="circle" coords="400,350,50" href="/static/html/kco.html" title="Kanchipuram District Collector Office">
<area shape="circle" coords="400,200,75" href="/static/html/skkt.html" title="Hi-Sri Kanchi Kamakshi Amman Temple">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/skt.html" title="Shri Karchapaswarar Temple">
</map>
</center>
</body>
</html>

skkt.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Sri Kanchi Kamakshi Amman Temple</title>

</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>kanchipuram - Temple City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Hi-shri kanchi kamatchi Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
The Kamatchi Amman Temple is an ancient Hindu Temple dedicated to the goddess Kamakshi, one of the highest aspects of Adi Shakti in Shaktism. It is located in the historic city of Kanchipuram, near Chennai, India. Its construction is credited to the Pallava kings, whose capital was in the same city. 
</b>
</font>
</p>
</body>
</html>

kk.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Kanchi Kudil</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Kanchipuram - Temple City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Kanchi Kudil</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
Heritage museum in a century-old home, featuring traditional Kanchipuram antiques, photos & art.
</font>
</p>
</body>
</html>

kco.html
<head>
<title>Kanchipuram District Collector Office</title>

</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Kanchipuram - Temple City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Kanchipuram District Collector Office</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
Kancheepuram district is situated on the northern East Coast of Tamil Nadu and is adjacent by  Chennai city and is bounded in the east by Chengalpattu District, west by Vellore District , south by  Thiruvannamalai district, in the north by Thiruvallur district and Chennai district.  It lies between 11° 00′ to 12° 00’ North latitudes and 77° 28′ to 78° 50′ East longitudes. The district has a total geographical area of 1704.79 Sq.Kms . Kancheepuram, the temple town is the district headquarters. For administrative reasons, the district has been divided into 2 revenue divisions comprising of 5 taluks with 520 revenue villages. For development reasons, it is divided into 5 development blocks with 274 Village Panchayats.
</b>
</font>
</p>
</body>
</html>

sct.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Shri Chitragupta Swamy Temple</title>

</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Kanchipuram - Temple City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Shri Chitragupta Swamy Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
Chitragupta temple is a Hindu temple located in Nellukara Street Kanchipuram in the South Indian state of Tamil Nadu. It is one of the rare temples of the Hindu deity Chitragupta, considered to the assistant of Yama, the Hindu god of death.
</b>
</font>
</p>
</body>
</html>


skt.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Shri Karchapaswarar Temple</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Kanchipuram - Temple City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Shri Karchapaswarar Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
In Kaccippalathali more than one temple of Kancheepuram has been referred as the Vaippu Sthalams by Tamil Saivite Nayanar Appar. They are as under:
Kaccapesam, Kailayam and Kayokaranam.
Tirumetrazhi, Onakanthanthazhi, Tirukamakottai and Kacchineri Karikkadu.
According to popular folklore, Vishnu is believed to have worshipped Shiva in the form of kurma (tortoise).[4] The other name given to the temple is Kachipedu in some inscriptions.[4] The temple is adjacent to the Kanthakottam temple. The temples was constructed by the Pallavas and renovated by Vijayanagar kings.
</b>
</font>
</p>
</body>
</html>
...



## Output:
![Output](./screenshots/s1.png)

![Output](./screenshots/s2.png)

![Output](./screenshots/s3.png)

![Output](./screenshots/s4.png)

![Output](./screenshots/s5.png)

![Output](./screenshots/s6.png)

## Result:
The program for implementing image map is executed sucessfully.
# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
## Step 1:
Create a folder 'static' under the project folder 'myproj'

## Step 2:
In 'static',create another folder 'html',under which the file 'index.html' should be created.

## Step 3:
Go to google maps and take a screenshot of your home on it along with some places around it.

## step 4:
Go to image-maps.com and make 5 locations on it using the shapes used in maps.

## step 5:
Copy the html code for the map and add it to 'index.html'

## step 6:
Create the html documents to be displayed when clicked on the location in the image map.

## step 7:
Take screenshots of the output.

## step 8:
Push it to 'README.md' and push it to the repository.

# Code:
# map.html:
<!DOCTYPE html>
<html>
    <body>
        <h2>IMAGE MAP</h2>
        <P>You can click on pachaiyappas school ground, babu cinemas, arignar anna memorial park, 
        sri navaneetha krishna kovil and kanchi skating
        to read more about the topic:</P>
        <img src="https://res.cloudinary.com/dlseemi4e/image/upload/v1700543373/Screenshot_2023-11-21_103158_id5rt0.png" 
        alt="Workplace" usemap="#workmap" width="1000" height="600">
        <map name="workmap">
            <area shape="circle" coords="973,531,94"  alt="ground"
            href="ground.html">
            <area shape="rect" coords="691,474,866,596" alt="cinemas" href="cinema.html">
            <area shape="poly" coords="408,519,356,594,216,577,236,346,411,360" alt="park" href="park.html">
            <area shape="circle" coords="460,203,86" alt="temple" href="temple.html">
            <area shape="circle" coords="431,637,92" alt="sport" href="sport.html">
          </map>
    </body>
</html>


# cinema.html:

<!DOCTYPE html>
<head>
    <body>
        <h1>BABU CINEMAS</h1>
        <ul>
            <li>Babu cinemas is a movie theatre in kancheepuram to watch movies<li>
            <li>Movie theatre with parking and refreshment facilities airing Indian language and Hollywood films.</li>
        </ul>
    </body>
</head>


# ground.html:
<!DOCTYPE html>
<head>
    <body>
        <h1>PACHAIYAPPAS SCHOOL GROUND</h1>
        <P>Pachaiyappa's Play ground
            Madam Street
            631502 Kanchipuram
        type of place:stadium 
    can play cricket 
	Madam St, Pillaiyarpalayam, Kanchipuram, Tamil Nadu 631501, India</P>
    </body>
</head>


# park.html:
<!DOCTYPE html>
<head>
    <body>
        <h1>ARIGNAR ANNA MEMORIAL PARK</h1>
        <Ul>
            <li>Arignar Anna Memorial Park- Kanchipuram,</li>
            <li>Tamilnadu is a memorial park located in Kanchipuram, Tamil Nadu. </li>
            <li>The average rating of this place is 3.80 out of 5 stars based on 722 reviews. </li>
            <li>The street address of this place is RMHW+QQQ, Pillaiyarpalayam,</li>
            <li>Kanchipuram, Tamil Nadu 631501, India. It is about 0.55 kilometers away from the</li> 
            <li>Kanchipuram railway station.</li>
        </Ul>
    </body>
</head>


# sport.html;
<!DOCTYPE html>
<head>
    <body>
        <h1>KANCHI SKATING</h1>
        <p>Kanchipuram District Roller Skating Association has successfully completed the 
            14th Kanchipuram District Roller Skating Championship 2022 in a grand manner. 
            More than 450 Skaters from Kanchipuram District participated in this Championship.
            Congratulations to everyone.</p>
    </body>
</head>


# temple.html
<!DOCTYPE html>
<head>
    <body>
        <h1>SRI NAVANEETHA KRISHNA KOVIL</h1>
        <ul>
            <li>Presiding diety lord navaneethakrishna is 4 feet tall gracing the devotees </li>
            <li>with a smiling face offering boons sought by them. There is child krishna idol 2 feet tall</li>
            <li>made of a mixture of 5  metals. He is a two year old child with ornamnets around the</li> 
            <li>waist, belly slightly big(thondi) holding butter in hand. Sri garuda is 4 feet tall </li>
            <li>idol made of 5 metals so ready to respond to the call of devotees.</li>
        </ul>
    </body>
</head>



# Output:
![Alt text](output.png)

![Alt text](cinema.png)

![Alt text](ground.png)

![](park.png)

![Alt text](sport.png)

![Alt text](temple.png)


# Result:
The output was verified successfully.

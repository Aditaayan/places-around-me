# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Fork the repository to your github and clone it into a folder in github
### Step 2:
Then make sure that django is activated and then start a new django project
### Step 3:
Now create a folder called static and within that folder create a folder called html
### Step 4:
Now create a file called map.html in that folder
### Step 5:
Now open google maps and take a screenshot of your hometown
### Step 6:
Now open "imagemap.org" and upload your image there and generate image maps of that using the rectangular or circle tool
### Step 7:
Now inside the html folder create the necessary html files that you've included in the href of the image maps
### Step 8:
Now push the folder and commit the changes in the github
## Code:
map.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Image Map Demo</title>
</head>
<body>
    <img src="Screenshot from 2023-11-24 17-04-14.png" usemap="#image_map">
    <map name="image_map">
  <area alt="Christ_University" title="Christ_University" href="christ.html" coords="1132,529,1301,612" shape="rect">
  <area alt="Nexus_Forum" title="Nexus_Forum" href="Nexus.html" coords="1246,618,1464,682" shape="rect">
  <area alt="St_Anthony" title="St_Anthony" href="Anthony.html" coords="1432,845,1565,909" shape="rect">
  <area alt="Srinivas_theater" title="Srinivas_theater" href="Srinivas.html" coords="1093,733,1283,811" shape="rect">
  <area alt="" title="" href="" coords="1285,809,1287,811" shape="rect">
  <area alt="truffles_hotel" title="truffles_hotel" href="truffles.html" coords="1477,696,1574,740" shape="rect">
</map>
</body>
</html>
```
Christ.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Christ University</title>
</head>
<style>
    body{
        text-align: center;
    }
    h3{
        font-size: 42px;
    }
    img{
        width:50%;
        height: 50%;
    }
    p{
        margin-left: 200px;
        margin-right: 200px;
        font-size: 24px;
        line-height: 30px;
    }
</style>
<body>
    <h3>
        Christ University
    </h3>
    <img src="1602070260phpQ9EWgb_1280x960.jpg">
    <p>Established in 1969, Christ University traces its roots to Christ College, a pioneering institution founded in 1921. Over the decades, the university has evolved into a multifaceted educational hub, offering a comprehensive range of undergraduate and postgraduate programs across diverse disciplines. With a focus on nurturing well-rounded individuals, Christ University emphasizes not only academic rigor but also character development, leadership skills, and a commitment to social responsibility.

        The university's sprawling campus reflects its dedication to providing an enriching learning environment. Lush greenery, state-of-the-art facilities, and a diverse student body contribute to the vibrant atmosphere that fosters intellectual growth and personal development. From well-equipped classrooms and research laboratories to modern libraries and recreational spaces, Christ University's infrastructure provides ample opportunities for students to pursue their academic aspirations.
        
        At the heart of Christ University's academic excellence lies its distinguished faculty. Comprising experienced scholars and industry experts, the university's professors are passionate about imparting knowledge and inspiring students to reach their full potential. Their dedication to teaching and research ensures that students receive a world-class education grounded in cutting-edge advancements and practical applications.
        
        Christ University's commitment to holistic education extends beyond the classroom, encompassing a wide range of extracurricular activities and initiatives. Students can engage in numerous clubs, societies, and sports teams, fostering their interests, talents, and leadership abilities. The university also organizes cultural events, seminars, and workshops, providing students with exposure to diverse perspectives and global issues.
        
        A testament to its commitment to social responsibility, Christ University actively engages in initiatives that address social and environmental concerns. The university's outreach programs extend to underserved communities, providing educational support, healthcare services, and vocational training. Christ University also promotes environmental sustainability through its campus-wide eco-friendly practices and conservation initiatives.
        
        As Christ University continues to strive for excellence, it remains committed to its core values of academic rigor, holistic education, and social responsibility. With its unwavering dedication to nurturing well-rounded individuals, Christ University stands as a beacon of hope and inspiration, shaping future leaders who will make a positive impact on the world.</p>
</body>
</html>
```
Antony.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>St. Antony's Friary Church</title>
</head>
<style>
    body{
        text-align: center;
    }
    h3{
        font-size: 42px;
    }
    img{
        width:50%;
        height: 50%;
    }
    p{
        margin-left: 200px;
        margin-right: 200px;
        font-size: 24px;
        line-height: 30px;
    }
</style>
<body>
    <h3>
        St. Antony Friary Church
    </h3>
    <img src="Screenshot from 2023-11-24 22-00-32.png">
    <p>
        St. Anthony's Friary Church is a Catholic church located at 85, Hosur Road, Kaveri Layout, Koramangala, Bengaluru, Karnataka 560095, India. It is a contemporary church featuring a courtyard, stained-glass windows, and a concrete steeple.

The church was founded in 1953 and is run by the Franciscan Friars (OFM). It is one of the largest parishes in the Archdiocese of Bengaluru and caters to the needs of over 5,000 families.

The church is open from 6:00 AM to 7:00 PM daily. Mass timings are as follows:

English: 6:00 AM, 9:30 AM, 12:15 PM, 5:00 PM
Kannada: 8:15 AM
Konkani: 11:00 AM
Malayalam: 6:15 PM
Tamil: 7:00 AM
The church also has a number of social outreach programs, including a soup kitchen, a clothing bank, and a medical clinic.

Here are some of the things that make St. Anthony's Friary Church a special place:

The church's beautiful architecture and stained-glass windows
The warm and welcoming atmosphere
The strong sense of community
The church's commitment to social justice
</p>
</body>
</html>
```
Nexus.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Nexus Mall</title>
</head>
<style>
    body{
        text-align: center;
    }
    h3{
        font-size: 42px;
    }
    img{
        width:50%;
        height: 50%;
    }
    p{
        margin-left: 200px;
        margin-right: 200px;
        font-size: 24px;
        line-height: 30px;
    }
</style>
<body>
    <h3>
        Nexus Forum Mall
    </h3>
    <img src="473px-The-Forum-Mall-BLR-2.jpg">
    <p>
        
        Forum Nexus Mall, formerly known as Forum Mall, is a shopping mall located on Hosur Road in Koramangala, Bengaluru, Karnataka, India. It is the first shopping mall in the city of Bengaluru. The mall is an attraction for tourists and locals alike, and it houses a wide variety of shops, restaurants, and entertainment options.
        
        The mall was opened in 2004 and is owned by the Prestige Group. It has a total area of 72,000 square meters (780,000 square feet) and is spread over five levels. The mall is anchored by a PVR multiplex, which has 12 screens.
        
        The mall is home to a wide variety of shops, including both national and international brands. Some of the popular brands that have outlets in the mall include Shoppers Stop, Pantaloons, Central, Lifestyle, Vero Moda, and Levi's. The mall also has a food court with a variety of cuisines, as well as a number of restaurants.
        
        In addition to shopping and dining, the mall also offers a variety of entertainment options. These include a bowling alley, a gaming arcade, and a children's play area. The mall also hosts a number of events throughout the year, such as concerts, fashion shows, and art exhibitions.
        
        Here are some of the things that make Forum Nexus Mall a popular destination:
        
        Wide variety of shops, restaurants, and entertainment options
        Convenient location in Koramangala, a popular neighborhood in Bengaluru
        Spacious and well-maintained facilities
        Regular events and promotions
        I hope this information is helpful. Please let me know if you have any other questions. </p>
</body>
</html>
```
Srinivas.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Srinivas Theater</title>
</head>
<style>
    body{
        text-align: center;
    }
    h3{
        font-size: 42px;
    }
    img{
        width:50%;
        height: 50%;
    }
    p{
        margin-left: 200px;
        margin-right: 200px;
        font-size: 24px;
        line-height: 30px;
    }
</style>
<body>
    <h3>
        Srinivas Theater
    </h3>
    <img src="Screenshot from 2023-11-24 21-43-11.png">
    <p>
        It is a local cinema with 2 digitally equipped movie theatres.
It is located at NO. 12, DRC Post, Venkateshwara Layout, S.G. Palya, Bengaluru, Karnataka 560029, India.
It has a rating of 3.8 on Google Maps.
It is open since 1975.
</p>
</body>
</html>
```
truffles.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Truffles</title>
</head>
<style>
    body{
        text-align: center;
    }
    h3{
        font-size: 42px;
    }
    img{
        width:50%;
        height: 50%;
    }
    p{
        margin-left: 200px;
        margin-right: 200px;
        font-size: 24px;
        line-height: 30px;
    }
</style>
<body>
    <h3>
        Truffles
    </h3>
    <img src="Screenshot from 2023-11-24 22-01-51.png">
    <p>
        IThe Koramangala branch is located at Apex Building 93/A Ground Floor, A Wing, 4th B Cross, 5th Block, Koramangala, Bengaluru, Karnataka 560095, India. It is open from 8:00 AM to 10:30 PM. The rating on Google Maps is 4.5 stars.

        The Indiranagar branch is located at 307, K. P Square , Ground Floor, 100 Feet Rd, Binnamangala, Stage 1, Indiranagar, Bengaluru, Karnataka 560008, India. It is open from 11:30 AM to 10:45 PM. The rating on Google Maps is 4.5 stars.
        
        The Sanjaynagar branch is located at 84, 80 Feet Rd, Sanjaynagar, Bengaluru, Karnataka 560054, India. It is open from 11:30 AM to 10:30 PM. The rating on Google Maps is 4.4 stars.
        
        Users reviewed Truffles restaurants as follows:
        
        Excellent 131. Very good 114. Average 23. Poor 5. Terrible 6.
        Excellent 26. Very good 32. Average 12. Poor 4. Terrible 6.
        Excellent. 133. Very Good. 115. Average. ... Poor. ... Terrible.
</p>
</body>
</html>
```

## Output:
#### Home Page
![Screenshot from 2023-12-19 10-02-42](https://github.com/Aditaayan/places-around-me/assets/147473394/a4e80e67-04ab-4058-b9fc-1b58cdfcd63c)

#### Sub Pages 
![Screenshot from 2023-12-19 10-07-48](https://github.com/Aditaayan/places-around-me/assets/147473394/f263902e-a9f5-4403-ac1e-86694206fa60)
![Screenshot from 2023-12-19 10-08-30](https://github.com/Aditaayan/places-around-me/assets/147473394/54e10160-88d7-4f81-bb44-e31048822a60)
![Screenshot from 2023-12-19 10-09-36](https://github.com/Aditaayan/places-around-me/assets/147473394/e9c6a415-bd84-4745-9c31-91d8da224fca)
![Screenshot from 2023-12-19 10-10-15](https://github.com/Aditaayan/places-around-me/assets/147473394/f6254f57-f8d1-4750-98aa-b97a6d742b27)
![Screenshot from 2023-12-19 10-10-37](https://github.com/Aditaayan/places-around-me/assets/147473394/5eb8ad56-0556-451f-8075-f62a8fee1c8b)



## Result:
Image maps have been sucessfully developed

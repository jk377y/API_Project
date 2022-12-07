# Two API's, One Sun
## **Description**
We built this webpage in order to create a quick and easy way for a user to access what time the sun will be rising or setting in their area. We realized that most people guess at what time these events take place and this webpage will solve that issue. All it takes is entering a zip code and a user will get location information and the specific time they can catch a sunrise or sunset.
## **Table of Contents**
- [**Installation**](#installation)
- [**Usage**](#usage)
- [**Credits**](#credits)
- [**License**](#license)
- [**Technologies**](#technologies)
## **Installation**
No installation steps are required. This application may be visited at ***https://calebgdavidson.github.io/Group-Project1/***
## **Usage**
**How it works:**
<br><br>**Step 1:** We begin by setting up our modal to accept an input value for any valid zip code in the united states.  Enter a zip code and press the "Submit" button.
<br><img src="./assets/images/zipInput.JPG" alt="initial modal input window image" width=600 height=450>
<br><br>**Step 2:** That input value is entered into a function that adds it to the url query to generate JSON returned data. 
<br><img src="./assets/images/zipcodeAPIusage1.jpg" alt="zippopotamus API parsed queried image" width=800 height=400>
<br>The following results will appear:
<br><img src="./assets/images/zipporesults.JPG" alt="zippopotamus API results image" width=400 height=300>
<br><br>**Step 3:**
<br>Now that you have obtained the information for your zip code, press the following button
<br><img src="./assets/images/getSunButton.JPG" alt="get sun button image" width=250 height=75>
<br>Next the latitude and longitude values retrieved from the Zippopotam.us API are stored into variables. These are then used to provide query parameters for the Sunrise Sunset API.
<br><img src="./assets/images/sunsetUseage.JPG" alt="sunrise sunset API parsed queried image" width=800 height=400>
<br>The following results will be displayed in the second window:
<br><img src="./assets/images/sunriseResults.jpg" alt="sunrise sunset API results image" width=400 height=300>
<br><br>**Step 4:**
<br>If you'd like to search a new zip code, press the following button.
<br><img src="./assets/images/resetButton.jpg" alt="reset button image" width=250 height=75>
<br><br>**Step 5:**
<br>Feel free to visit our teams links
<br><img src="./assets/images/gitLinks.JPG" alt="team repo links image" width=800 height=70>
## **Credits**
<br>**Caleb Davidson**
<br>***https://github.com/calebgdavidson***
<br>**Geneveve Perez**
<br>***https://github.com/genrp24***
<br>**Sam O'Cain**
<br>***https://github.com/samocain93***
<br>**Matthew Wessman**
<br>***https://github.com/JimblesMw***
<br>**James Kelly**
<br>***https://github.com/jk377y***
<br>**The Coding Train** ***https://www.youtube.com/watch?v=uxf0--uiX0I*** For technical assistance and walkthrough of working with data and APIs in JavaScript
<br>**Web Dev Tutorials** ***https://www.youtube.com/watch?v=uUCpopjPZdI*** For technical assistance and walkthrough of modal building.
<br>**Web Dev Simplified** ***https://www.youtube.com/watch?v=NIq3qLaHCIs*** For technical assistance and walkthrough of object deconstruction.
## **License**
<br>MIT License

Copyright (c) 2022 James Kelly

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
## **Technologies**
<br>**1). Bulma CSS styling Framework**
<br>***https://bulma.io/documentation/layout/tiles/***
<br>***https://www.youtube.com/watch?v=LBzZLzu2GKo***
<br><img src="./assets/images/bulma.JPG" alt="bulma css styling framework image" width=800 height=400>
<br><br>**2). Zippopotam.us Zip Code Galore! API**
<br>***https://api.zippopotam.us/***
<br><img src="./assets/images/zippoAPI.JPG" alt="zippopotamus API homepage image" width=800 height=600>
<br><br>**3). Sunset and Sunrise Times API**
<br>***https://sunrisesunset.io/api/***
<br><img src="./assets/images/sunsetAPI.JPG" alt="sunrise API homepage image" width=800 height=600>
<br><br>**4). Google Slides - used to preplan our project**
<br>***https://docs.google.com/presentation/u/0/***
<br>Phase 1:<br>
<img src="./assets/images/mockup1.JPG" alt="mockup 1 screenshot" width=800 height=400>
<br>Phase 2:<br>
<img src="./assets/images/mockup2.JPG" alt="mockup 2 screenshot" width=800 height=400>


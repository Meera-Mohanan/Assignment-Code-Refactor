# Assignment-Code-Refactor
Header,Main content ,Additional indirect content & Page footer Added to have clear information

Changed title to "Horiseon Webpage"

Changed <div>  for <header> tag

Changed <div>  for <nav> tag in HTML, and .header nav CSS rules

Changed hero to meetingMainImage, and included into the header section.

Added some empty lines for making the HTML sections easier to identify

Added <main> tag to group the main content

Added <footer> tag at the bottom of the page

Changed content class name for mainContent both in the HTML and CSS files

Included alt properties with related description for each image

Changed the class search-engine-optimization to id search-engine-optimization

Changed the classes  benefit-lead, benefit-brand and benefit-cost to id benefit-lead, benefit-brand and benefit-cost

Removed the online-reputation-management class and rules in CSS updated to id

Removed the social-media-marketing class and rules in CSS updated to id

The </img> was removed

Modifications to Starter Code

Structure and descriptive comments were added to the CSS file, and the css rules were clasified accordingly:

* {   /* Universal selector*/
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

body {
    background-color: #d9dcd6;
}

a {
    color: #ffffff;
    text-decoration: none;
}

p {
    font-size: 16px;
}

/* ---------- The Header ---------- */

.header {    /* Header format */
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}

.header h1 {
    display: inline-block;
    font-size: 48px;
}

.header h1 .seo {
    color: #d9dcd6;
}

.header nav {   /* Navigation bar format */
    padding-top: 15px;
    margin-right: 20px;
    float: right;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 20px;
}

.header nav ul {
    list-style-type: none;
}

.header nav ul li {
    display: inline-block;
    margin-left: 25px;
}

.meetingMainImage {
    height: 800px;
    width: 100%;
    margin-bottom: 25px;
    background: url("../images/digital-marketing-meeting.jpg") center / cover;
}


.mainContent {   /* Main content format (without aside or benefits content */
    width: 75%;
    display: inline-block;
    margin-left: 20px;
}

#search-engine-optimization,
#online-reputation-management,
#social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.float-left {
    float: left;
    margin-right: 25px;
}

.float-right {
    float: right;
    margin-left: 25px;
}

#search-engine-optimization img,
#online-reputation-management img,
#social-media-marketing img {
    max-height: 200px;
}

#search-engine-optimization h2,
#online-reputation-management h2,
#social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}


.benefits {   /* Aside content format */
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #2589bd;
}

#benefit-lead,
#benefit-brand,
#benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

#benefit-lead h3,
#benefit-brand h3,
#benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

#benefit-lead img,
#benefit-brand img,
#benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}


.footer {    /* Page footer content */
    padding: 30px;
    clear: both;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
}

.footer h2 {
    font-size: 20px;
}

The project was uploaded to GitHub at the following repository: https://github.com/Meera-Mohanan/Assignment-Code-Refactor.git

You can access the deployed application with the GitHup Pages link: https://meera-mohanan.github.io/Assignment-Code-Refactor/

# MIST 353 ASSIGNMENT 2
# MyEcoPlanner Web Application
## Project Overview
"In this project, I created a home page and an activities page for my web application called, “MyEcoPlanner”. MyEcoPlanner is an app that can look at your location and tell it a little bit about what you like and do not like and then it looks at the weather/climate and gives you ideas of activities, community service, events, and other things you can do around you that day that is weather permitting. It will give you live alerts as the weather changes as well. It can also use the weather to help you plan activities a little over a week in advance. It also just has a general handbook for each season with a list of ideas that are weather permitting."

## Page Descriptions

### Home Page
"On the Home page you can see a welcome message, what the site offers, and in italics I put “make planning stress free,” which is a slogan for the application. Also on the homepage, you can see a nav bar, that I implemented from bootswatch. It is not yet functionable but as you hover over it, it highlights places to navigate to as well as a search bar that is not yet functionable. I also put a picture on this page that I picked the size and filter of using CSS properties. To go to the activities page, I placed a link above the image. At the bottom of the homepage, there is some information about MyEcoPlanner and a drop-down feature for additional information. All the buttons on this page when hoovered over, turn light yellow. "


### Activities Page
"When you go to the activities page, there is a warning feature that alerts you of the weather coming soon, I implemented this using bootswatch as well. Once you click “x”, the warning sign goes away. Then you can see the title of the page, and what this page offers. There is a table that lists activities and the weather. Under the table I added a functional button that when clicked, alerts you that an activity was added. I did this using java script. "


### Competitive Analysis
- **1.	https://www.ironicreports.com/#:~:text=Ironic%20offers%20a%20personalized%20event,addressing%20challenging%20and%20favorable%20conditions** :This website, ironicreports.com, provides expert weather coverage and personalized plans to event professionals committed to growth, education, and embracing new technology. The website has a modern design and looks very clean. The layout is simple. The colors used are orange, white and blue. Different fonts are used and there is headings and a body. There is images, buttons, and graphics. The website offers testimonials, contact information and features that you can easily interact with. It is easy to navigate as well. ? and # are used in the URL. Upon inspection, I saw several HTML tags I recognized. This included <div>, <section>, <head> and <body>.  I also noticed it uses block elements by display:block. I actually did not see any bootstrap uses. I did see <script> used a lot as well as <style> that were custom CSS styles or JavaScript functions. 

- **2. https://www.weatherplanner.com/weather/plannability.php** : This website, weatherplanner.com, provides accurate weather forecast for up to a year in advance to help make planning things such as hiking, backpack trips, weddings and more easier to plan! The website is a little bit messy and does not use many colors except white, orange, and grey. The layout is simple with just headings and then paragraphs. There is no images on the main page, but there is on the weather planner team page. Some of the buttons do not work. They do provide contact information and a link to their twitter at the bottom of the page.  Upon inspection, I saw several HTML tags I recognized such as <header> , <div>, <body>. I noticed this site used block elements as well with display: block. <style> and <script> were used in the head a lot indicating CSS styles and JavaScript functions. The URL does not include # OR ?. 

- **3. 	https://www.windfinder.com/#3/39.5000/-98.3500** : This website, windfinder.com, provides live weather updates for outside activities such as kitesurfing, windsurfing, sailing, and fishing. The website has a clean look. The map takes up most of the page with interactive buttons on the side to get a look at different maps for different days and times. There is another page where you can put what country and region you want to look at and specify which activity or sport. It is interactive and easy to navigate and is presented neatly and with good colors. Upon inspection, I noted <div>, <header> , <body>, <button>, <nav> , border-radius, background-color and lots of other familiar code. I saw <style> and <script> were both used but did not identify any bootstrap. They used CSS and JavaScript. 

### GitHub Repository Research
- **1. https://github.com/comyar/Sol** : This repository is for an app called Sol for iOS, this app displays weather information so that you can easily plan your day. The README clearly describes how to use Sol as well as where the app gets its weather information. There is screenshots to show what the application looks like as well, it is very appealing to the eye. The type of iOS you need and Xcode you need is clearly defined as well. It looks like it was being worked on for years as well. 

- **2. https://github.com/MichelleGreensted/activity-todo-randomiser** : This repository is for an app that suggests activities for you to do based on the weather. The project used bootstrap. The README clearly shows you how to get started with the app and what you can run in the project directory. It shows you how to view it in your browser and run in which modes. There is even a link to learn more! This was informational and interesting to look at. 


### Future Enhancements 
"For the future, I would like to enhance my table to be bigger and include more information. I would like to add contact information to the website. I would like to have more graphics and maybe some testimonials. I also would like it to be more interactive with the user, more buttons. I would like to have a meet the owner page, as well. "

### Citations
"I used ChatGpt as well as w3schools.com/css and bootswatch."
"For ChatGpt I asked it to help me make a functional button for my application that says “Add Eco-friendly activity” 
And I used “ <button onclick=”addEcoActivity()”>Add Eco-Friendly Activity</button>
<p id=”message”></p> and 
Function addEcoActivity() {
const message= document.getElementById(‘message’);
message.textContent = ‘Eco-friendly activity added to MyEcoPlanner!’;"  
I also asked ChatGpt hot to properly use  <details> to have a drop down with more information. I used the following:
<details>
    <summary>More Information</summary>
    <p>This is the dropdown information.</p>
    <p>It can contain any HTML content.</p>
</details>  

## Reflection on Resources
I think if you use these resources correctly by just asking it for assistance and then applying your knowledge and making it relevant to your project, it can be very helpful and really enhance your website. I prefer ChatGpt because it is easy and fast, though sometimes you must watch as the information presented can include errors. As long as you do not rely on outside sources and have some insight on what you are doing, you should be good to go and you can just use them to further your website and knowledge! 








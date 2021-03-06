# Front End Challenge – IPL Data Visualization Dashboard

A data visualization challenge to build a web app with IPL (Indian Premier League) data provided in CSV files. Goal was to present stats and interesting information about IPL to someone who knows about cricket but has not seen IPL.

  - Great UI/UX
  - Responsive Design
  - Mobile friendly

![Screenshot of output](https://user-images.githubusercontent.com/79014447/178153990-13b913e8-4a47-4cf9-a5e6-2b7c1c0ecae5.png)

## Built With
  - [React](https://reactjs.org/) - the web framework used (as asked)
  - [Chart.js](https://www.chartjs.org/) - used to create charts
  - [jQuery](http://jquery.com) - javaScript library
  - [Papaparse](https://www.papaparse.com/) - for parsing CSV files to JSON

## Dataset
  - [Click Here](https://www.kaggle.com/harsha547/indian-premier-league-csv-dataset)  

## Link to Hosted Website
  - [Click Here](https://sahil-ipl-dashboard.netlify.app)  
  *(Hosted on Netlify)*

## Bonus Points Explanation
  - I used React instead of Vue solely because I'm more familiar with React, although I'm very keen on learning Vue as well.
  - Used a fast library, papaparser, for parsing all CSV data. I've used CSS whereever possible for best performance and used best practices for writing Javascript code. 
  - The website is fully mobile responsive, I've made sure that every little detail looks good on mobile! I focused on making an easy-to-use User Interface (UI) for great constrast and visual appeal. Added a fullscreen mode toggle to enhance User Experience (UX). Moreover, I've written all CSS code by myself without any library.
  - It is a progressive webapp as verified on [Lighthouse](https://developers.google.com/web/tools/lighthouse/). It is fast and reliable, installable, PWA optimized.
  - It is also usable offline.
  
## Thought Process
  - Idea was to use the crimson and dark grey color scheme as crimson also happens to be one of my favorite colors.
  - I searched through all the given datasets to look for attributes that would intrigue a person who knows cricket but has never watched IPL. 
  - I wanted the Navigation bar to initially be in 'full' state while browsing on desktop and in 'minimal' state while on mobile to give mobile users more space yet have menu items easily accessible in one click.
  - I was duelling over whether to choose Chart.js or D3.js for my charting library. I went with Chart.js as it provided many predefined graphs, just what I needed for my time constraint.
  - When looking for a CSV file parsing solution, papaparser was the best one I could find.
  - Making a mobile responsive website is a must in 2022. With mobile in-mind, I carefully planned my layout design. I used grid layout and flex box for most of my layout design process.
  - The top bar seemed empty, so I added a search bar that would fit in with the design scheme.
  - Used Poppins and Lato as fonts for this challenge, both being popular and modern choices. For the icons I used Font Awesome Pro.
  - I decided to add a fullscreen toggle button in the header bar because an admin panel is best viewed in fullscreen. Less clutter, the better. :)

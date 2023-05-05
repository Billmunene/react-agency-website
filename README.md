# react-agency-website
 a agency landing page created with react and typescipt
 
 
 
 
 
 
 install app's dependencies
$ npm install or $ yarn install

# Start local server
$ npm start

# demo(https://react-agency-website.vercel.app/)

# Edite template in your favorite code editor

# After editing is finished,build required files for server

$npm run build



Project Structure
This project is bootstrapped using Create React App.
Styled components is used as css preprocessor
All primary components are located inside src/components. Each component at the bottom has its own styled (CSS) section for styling. (Please install styled-components extension for your code editor.)
All images are located inside src/assets/img.
All svg icons are located inside src/assets/svg.
After build,all files required for hosting can be found inside /public folder
Credits

React library used React
Khula Google Font - Khula
Styled components is used as css preprocessor - Styled components
All images are from Unsplash
Navbar & Images
There is 2 components for navigation "TopNavbar.jsx" (top navigation) and "Sidebar.jsx" (mobile side navigation) make sure to properly set navigation in both components
Make sure to replace all placeholders found on /assets folder. Name and type of images should be exactly like placeholders.
Portfolio Section
All data and logic for portfolio can be found inside the /Components/Sections/Projects component.
Each project box require next properties:
img: image for preview imported from /assets/img folder.
title: title of the project
text: description of the project
action: click handler
Blog Section
All data and logic for blog can be found inside the /Components/Sections/Blog component.
Each post has its own:
title: (title for post.)
text: (short description of post.)
date: (date of post.)
tag:
author: author name and date
action: click handler
Build
After you finish with all editing you can run "npm run build" for building required files for server

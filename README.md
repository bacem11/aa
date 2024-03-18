####  Run the app locally
-npm run install-dependencies
-rename .env.temp to .env 
-setup values for -MONGO_URL , JWT_SECRET, JWT_LIFETIME 
-npm start
-visit url http://localost:3000/


###### setup react app
-create 'client' folder
-open terminal 
-cd client 
-npx create-react-app .
-npm start 
-set editor/browser side by side 
-copy/paste assests from complet project


#####  spring cleaning
- in src remove 
-App.css
-App.test.js
-logo.svg
-reportwebvitals.js
-setupTests.js
-fix App.js and index.js



######  title and favicon
-change title in public/index.html
-replace favicon.ico in public
-resource (favicons)(https://favicon.io/)



#### normalize.css and global styles
-css in js
-saves times on the setup
-less lines of css
-speeds up the development 
-normalize.css
-small css file that provides cross-browser consistency in the default styling of html elements.
-(normalize)(https://necolas.githu.io/normalize.css/)
-npm install normalize.css 
-import 'normalize.css' in index.js
-set before 'index.csss'
-if any question about normalize or specific styles
-coding addict (default satrter) [https://youtube/UDdyGNlqK5w]
-repo (Default starter)[https://github.com/john-smilga/default-starter]

##### Landing page
-zoom level 175%
-markdown preview extension 
-get something on the screen 
- react router and styled somponents right after 
-create pages directory in the source 
-for now Landing.js
-create component (snippets extension)
-setup basic return 



'' js
<h4>Landing page<h4>
''''''''


-import logo.svg ans main.svg 
-impot landing in app.js and render

######   styled components
-css in js 
-styled components 
-have logic ad styles in component
-no name collision
-apply javascript logic
-[Sttyled components Docs](https://styled-components.com/)
-[styled components course](https://www.udemy.com/course/styled-components-tutorial-course/?)
npm install styled-components  


-no name collision , since unique  class
-vscode-styled-componenets extension
-colors and bugs
-style entire react component


-only responsible for styling 
-wrappers folder in assers  
#### logo and images
-logo built in figma 
-cool  image
#### LOgo
-create components folder in source 
-create logo.js 
-move import and image logic
-export as default
-utilise index.js
#### React Router
-version 6
-React Routetr docs 

npm install history@5 react-router-dom@6

-import four components

-connect to browser's URL with browserRouter 
-routes instead of switch "# aa" 

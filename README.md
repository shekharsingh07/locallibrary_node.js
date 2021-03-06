## **Project Name:** Node.js - Local Library Tutorial

**Description:** <br>Express is a popular unopinionated web framework, written in JavaScript and hosted within the Node.js runtime environment. This project follows a tutorial on how to set up a development environment and how to perform common web development and deployment tasks. The completed project is deployed through Heroku and can be viewed through this [website](https://gentle-retreat-96753.herokuapp.com/catalog).

A further step was personally included in which I deployed the project through Microsoft Azure and can be viewed in this [web app](https://local-library-shekhar.azurewebsites.net).

**Table of Contents:**
<ol>
  <li>Installation & Usage</li>
  <li>Credits</li>
  <li>License</li>
</ol>

**Installation & Usage:**<br>The project can be cloned or donwloaded and set up to run locally on your computer. This can be done by:
<ol>
  <li> Set up a <a href="https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/development_environment">Nodes</a> development environment.</li>
  <li>Once node is setup, the following commands can be entered in the root of your clone of this repo:</li>

  ``` 
  npm install
  SET DEBUG=locallibrary_node.js:* npm run start   #For Windows
  
  npm install
  DEBUG=locallibrary_node.js:* npm run devstart   #For Linux
  ```
  <li>Open a browser to http://localhost:3000/ to open the library site.</li>
</ol>  

To deploy on Heroku, this repository can be cloned or you can create your own repository. The steps to complete the deployment can be followed on the [tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/deployment).

To deploy to [Microsoft Azure](https://portal.azure.com/), you would need to include the file "web.config" in your repository.


**Credits:**<br>The project follows the [tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction) provided by MDN Web Docs.

**License:** MIT license


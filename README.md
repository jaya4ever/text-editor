# PWA Just Another Text- Editor

## Description
 ### This is the module challenge 19 given assignment. J.A.T.E was created as a simple text editor app that can function both online and offline, with a variety of data persistence options in order to ensure that data is not lost in any scenario. The application first looks to use the data in the indexedDB to populate the editor, then if it cannot access that it will use local storage. For use offline, this application can be downloaded to your desktop as an application. The application is a web text editor where the user can create notes or code snippets with or without an internet connection and where the user can reliably retrieve them for later use. The integrated service worker and Cache API's ensure that the application will remain fully functional even without and active internet connection. This application allows the user to access visited pages even if the application is offline.


 ### This is my GitHub Repository 
 [GitHub](https://github.com/jaya4ever/text-editor)

### This is my link to Heroku
[Heroku](https://hidden-castle-72719.herokuapp.com/ "Heroku app")




## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

### Installation 
* npm install express (express.js)
* npm install webpack-dev-server --save-dev (webpack-dev-server)
* npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
* npm install babel (Babel)
* npm install --save-dev css-loader (CSS-loader)
* npm install --save-dev webpack (Webpack)
* npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
* npm npm install idb (IndexedDB)

## Credits 
* starter code
* Tutor Jose Lopez
* Instructor and TA's From Northwestern Boot Camp
* [learnPWA](https://web.dev/learn/pwa/getting-started/)




## License

  Copyright (c) 2023 [GitHub](https://github.com/jaya4ever)  **Note** This application is under the [MIT](https://MIT-license.org)

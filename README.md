<h1>Restaurant Reviews App</h1>
<br><br>

<h2>Technologies & APIs</h2>

 - CSS3, Flexbox and Media Queries for Responsive Design
 - [**Fontawesome**](https://fontawesome.com/) icons to enrich User Interfaces
 - Semantic HTML5 markup and ARIA atributes for Accessibility (Screen Reader & Assistive Technologies features)
 - Vanilla Javascript & JavaScript Promises following the ES6 JavaScript Syntax (arrow functions, destructuring, sting literals, sets, etc.)
 - Pulling data through Asynchronous Requests (AJAX) from live data sources with the use of the fetch() API
 - Cache API, ServiceWorker and IndexedDB for Offline-First capability
 - Progressive Web App features (Service Worker, App Manifest, Caching, Metatags, etc.)
 - Implementation of a build system with Gulp for a highly optimized and performant app (90+ Audit metrics for Performance, Accessibility, PWA)
<br><br>

<h2>Branches</h2>
This repository is split into the following branches based on the app's phase of development.

 - [**restaurant_reviews-stage_1**](https://github.com/katerina-tziala/restaurant/tree/restaurant_reviews-stage_1)**:** Building upon the provided restaurant reviews website, converts the existing static design into a fully responsive design that renders appropriately in any viewport including desktop, tablet, and mobile displays. Additionally, implements all standard accessibility features that are currently missing with the use of semantic markup and ARIA atributes. Finally, starts converting this website to a Progressive Web Application by caching some assets for offline use.


 - [**restaurant_reviews-stage_2**](https://github.com/katerina-tziala/restaurant/tree/restaurant_reviews-stage_2)**:** Building upon the responsive and accessible design that was developed in **restaurant_reviews-stage_1**, the app is converted to a fully-featured app that communicates with a backend server and handles asynchronous requests. The app now retrieves JSON data from an external server by using Asynchronous JavaScript requests with the use of the fetch() API. Received data are stored in the client side in order to be accessible offline using the IndexedDB API. Appropriate meta-tags and the app manifest are implemented to take a step further in the implementation of a PWA. The Gulp build system is utilized to bundle, optimize and build the app. Required performance benchmarks:
 
   - Progressive Web App >90
   - Performance >70
   - Accessibility >90

 - [**restaurant_reviews-stage_3**](https://github.com/katerina-tziala/restaurant/blob/restaurant_reviews-stage_3/README.md)**:** Building upon the responsive, accessible and connected application that was developed incrementally in the first two stages, the app should now provide additional functionality. Users should now be able to create their own reviews and add restaurants in their favorites list. If the app is offline, form submissions should defer updating to the remote database until a connection is established. Required performance benchmarks:
 
   - Progressive Web App >90
   - Performance >90
   - Accessibility >90

   <i>The app now must be run alongside with the [**mws-stage-restaurant-stage-3**](https://github.com/udacity/mws-restaurant-stage-3) back end data server.</i>
 
 - [**restaurant_reviews-stage_4**](https://github.com/katerina-tziala/restaurant/blob/restaurant_reviews-stage_4/README.md)**:** 
 Building upon the PWA that was developed incrementally in the three previous stages, the app should now connect to an online backend server (hosted NoSQL DB with a RESTful API) in order to facilitate a live demo of the app. Responsive design, accessibility, functionality and performance metrics should be retained.
 
  - [**master**](https://github.com/katerina-tziala/restaurant_reviews_app)**:** 
 The master branch contains the live demo of the app (*docs folder, bundled app*), the source code of the app (*app folder, currently synchronized to **restaurant_reviews-stage_4** branch*), and the images used to describe all README files of this repository (*repository_images folder*).


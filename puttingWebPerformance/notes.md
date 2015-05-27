## Putting web performance best practices together to create the perfect single page application

* Presenter: Chris Love, @chrislove, love2dev.com
* [Slides](http://slideshare.net/docluv)
* [Source](http://github.com/docluv)
* [A Example SPA](http://fastfurniture.love2dev.com/)

### Presentation

#### Overview
* What is a SPA?
   - View/Pages (has everything one single page)
   - CSS/JS
* Leverages
   - AJAX / Sockets
   - Storage
   - Hash Fragment
* Mobile Browsers
   - Aggressively Purge Cache
   - Less Memory
   - Weaker Processors
* Cellular Connnections
   - Slower
   - Unreliable
   - More Expensive
* Web is obese
   - http://httparchive.org/
   - [TWC Report](http://httparchive.org/viewsite.php?pageid=26847032)

#### What to do?

* Dump jQuery & What it Means
   - Faster Load Times
   - Master DOM APIs
   - Alternatives
   - Create Dolar Bill
   - Learn to be Modular
* MicroJS Libraries
   - small
* Architecture Goals
   - Performance
   - Modularity
   - Small Footpring
   - Scalability
   - Maintainability
   - Log Lifespan

#### Process of Page

* The Modern Web Hour Glass
   - HTML5, JS, CSS3
   - DB - SQL SErver/NoSQL
   - ASP.NET/ISS, NODE/JS
* 1st time a user visits they 'install' the application
* The Initial Request
   - Contains Critical Path Assests
      + Master Layout HTML + CSS Inline
      + Initial Possible Views
      + Initial View's CSS
      + Core Application JavaScript + Initial View's Controllers
* Routing
* See diagram in slide show above
* Read: http://bit.ly/H2qhZ2
* Cutting the Mustard
   - Feature Detections
   - Don't code for legacy browser
   - Don't use Polyfils
   - Improve SEO, Read: http://bit.ly/117sTgl
* Data Management
   - Cache Data in Storage
   - Assign Time to Live Value to all data
   - Elimiate Redundant HTTP request
* JQuery AJAX pre-filter : http://bit.ly/117p7E9

This repository was cloned from [here.](https://github.com/udacity/frontend-nanodegree-mobile-portfolio.git)

The first section below shows the original cloned course README text.

My **Student Notes** then follow..

## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository, inspect the code,

### Getting started

####Part 1: Optimize PageSpeed Insights score for index.html

Some useful tips to help you get started:

1. Check out the repository
1. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080
1. Download and install [ngrok](https://ngrok.com/) to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ngrok http 8080
  ```

1. Copy the public URL ngrok gives you and try running it through PageSpeed Insights! Optional: [More on integrating ngrok, Grunt and PageSpeed.](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/)

Profile, optimize, measure... and then lather, rinse, and repeat. Good luck!

####Part 2: Optimize Frames per Second in pizza.html

To optimize views/pizza.html, you will need to modify views/js/main.js until your frames per second rate is 60 fps or higher. You will find instructive comments in main.js. 

You might find the FPS Counter/HUD Display useful in Chrome developer tools described here: [Chrome Dev Tools tips-and-tricks](https://developer.chrome.com/devtools/docs/tips-and-tricks).

### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html">The fewer the downloads, the better</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html">Reduce the size of text</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html">Optimize images</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html">HTTP caching</a>

### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>

### Sample Portfolios

Feeling uninspired by the portfolio? Here's a list of cool portfolios I found after a few minutes of Googling.

* <a href="http://www.reddit.com/r/webdev/comments/280qkr/would_anybody_like_to_post_their_portfolio_site/">A great discussion about portfolios on reddit</a>
* <a href="http://ianlunn.co.uk/">http://ianlunn.co.uk/</a>
* <a href="http://www.adhamdannaway.com/portfolio">http://www.adhamdannaway.com/portfolio</a>
* <a href="http://www.timboelaars.nl/">http://www.timboelaars.nl/</a>
* <a href="http://futoryan.prosite.com/">http://futoryan.prosite.com/</a>
* <a href="http://playonpixels.prosite.com/21591/projects">http://playonpixels.prosite.com/21591/projects</a>
* <a href="http://colintrenter.prosite.com/">http://colintrenter.prosite.com/</a>
* <a href="http://calebmorris.prosite.com/">http://calebmorris.prosite.com/</a>
* <a href="http://www.cullywright.com/">http://www.cullywright.com/</a>
* <a href="http://yourjustlucky.com/">http://yourjustlucky.com/</a>
* <a href="http://nicoledominguez.com/portfolio/">http://nicoledominguez.com/portfolio/</a>
* <a href="http://www.roxannecook.com/">http://www.roxannecook.com/</a>
* <a href="http://www.84colors.com/portfolio.html">http://www.84colors.com/portfolio.html</a>

## My Student Notes
The prime purpose of this project is to test performance of this moblie-portfolio and to make needed changes in code to improve performance.  There are two parts to this project: 
- **Part One** - deals with basic changes to html, css, and js to improve performance in terms of the Critical Rendering Path (CRP).
- **Part Two** - deals with more detailed changes to the javascript code.

### Coursework Activity Log

**Tuesday April 19, 2016**

5:20 PM 
- [Cloned Mobile-Portfolio](https://github.com/udacity/frontend-nanodegree-mobile-portfolio.git)
- Edited README to include **My Student Notes** section and other text to get started.

6:52 PM
- Tried out Google [PageSpeed Website](https://developers.google.com/speed/pagespeed/insights/) on some of my completed project URLS... very cool
- Installed Google Canary (Development Browser) on Laptop
- Installed Google Chrome on iPhone 5s and iPad2
- Installed [iOS WebKit Debug Proxy](https://github.com/google/ios-webkit-debug-proxy) from Repository using Homebrew

8:28 PM
- Got some results, but not getting Canary to see device yet.
- All the feeds in the forums basically state that this is very buggy and a huge time sink.
- This [site](https://www.smashingmagazine.com/2014/09/testing-mobile-emulators-simulators-remote-debugging/2/) tells how to use Safari Dev Tools with my IOS device.
- May end up just using simulation modes in Chrome to make this project work.
- Sent bug report about this issue, should at least have a note saying what the forums are saying.

**Wednesday April 20, 2016**

11:07 AM
- Remote attachment works using Apple ecosystem with hints from this [site.](https://www.smashingmagazine.com/2014/09/testing-mobile-emulators-simulators-remote-debugging/2/)
- Safari Browser on laptop enabled for Developer Mode
- Safari Browser on iPhone enabled Web Inspector
- Attached iPhone and Laptop via USB cable
- Open browsers in each device (with more than one webpage open on iPhone)
- Select User Agent (Safari-IOS 9.3-iPhone) from Develop Menu
- Selected Web Page from Develop Menu on Safari to inspect on iPhone
- Web Inspector window appears and seems to work fine

11:39 AM
- Remote attachment for iPad2 established
- Instuctions basically as above
- Select User Agent (Safari-IOS 9.3-iPad) from Develop Menu
- USB cable has faulty connection, need to hold it firmly in place

2:26 PM
- Wasted some more time trying to get iPhone/Canary remote connection
- Definately giving up on this for now, don't really need it to complete projects
- Will use Canary and simulated device for timeline behaviour
- May also use Safari Dev tools for remote iPhone connection as well

**Thursday April 21, 2016**

12:10 PM
- Good News, Durant Schoon of Udacity Support implemented suggested changes above.

3:27 PM

- Finihed reading this [web optimization link](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/?hl=en) by Ilya Grigorik
- Recomend as resource for CRP

**Friday April 22, 2016**

2:23 PM

- These two links are keepers for Waterfall like web page activity.
- http://www.webpagetest.org/result/160422_FJ_84P/
- http://scatter.cowchimp.com/

3:19 PM
- Issues in lesson with outdated waterfall views
- Sent Issue Report to Udacity Support
- Updated [forum thread](https://discussions.udacity.com/t/important-note-re-devtools-timeline-visual-discrepancy-esp-if-youre-confused/28598/14?u=george_3439977859158) that deals with this issue.

3:47 PM
- Useful up-to-date timeline references from Google
- [Timeline Event Reference](https://developer.chrome.com/devtools/docs/timeline#timeline-event-reference)
- [Chrome Dev Tools Timeline](https://developers.google.com/web/tools/chrome-devtools/profile/evaluate-performance/timeline-tool)

**Saturday April 23, 2016**

9:54 PM

- Following Instructors
- +Ilya Grigorik, @igrigorik, @cwpittman

**Sunday April 24, 2016**

12:54 AM

- [This Lesson Segment](https://classroom.udacity.com/nanodegrees/nd001/parts/00113454012/modules/273584856175460/lessons/1464158642/concepts/15290985670923) requested contibution to forum on Expensive Websites
- [My Forum Contribution](https://discussions.udacity.com/t/expensive-layouts/16165?u=george_3439977859158)

**Monday April 25, 2016**

4:30 PM

- In the lesson we are asked to make website optimization suggestions
- [My Forum Contribution](https://discussions.udacity.com/t/optimization-suggestions/16163/91?u=george_3439977859158)

5:08 PM

- Sent Udacity Support an Issue
- The CSS reference links are out of date in the Instructor Notes at the bottom of the page for this [lesson section frame.] (https://classroom.udacity.com/nanodegrees/nd001/parts/00113454012/modules/273584856175460/lessons/1464158642/concepts/16127785370923)
- PageSpeed Service was turned off on August 3rd, 2015. 

5:25 PM

- Finished Lesson 1 - The Critical Rendering Path
- Starting Lesson 2 - Optiimizing the CRP

9:42 PM

- In the [lesson segment](https://classroom.udacity.com/nanodegrees/nd001/parts/00113454012/modules/273584856175460/lessons/1469569174/concepts/16119285370923) we are asked to make two CRP diagrams
- [My Forum Contribution](https://discussions.udacity.com/t/quiz-crp-diagrams/16162/134?u=george_3439977859158)

**Tuesday April 26, 2016**

11:59 PM

- This [lesson quiz](https://classroom.udacity.com/nanodegrees/nd001/parts/00113454012/modules/273584856175460/lessons/1469569174/concepts/16053485360923) requested a CRP for one of my projects
- [My Forum Contribution](https://discussions.udacity.com/t/crp-diagrams-any-site/25810/44?u=george_3439977859158)

**Wednesday April 27, 2016**

1:23 AM

- Made error corrections to last forum contribution
- [My Forum Contribution](https://discussions.udacity.com/t/crp-diagrams-any-site/25810/45?u=george_3439977859158)

8:59 PM

- Added Timeline and Network Dev Tool Analysis Graphics to previous Forum entry
- [My Forum Contribution](https://discussions.udacity.com/t/crp-diagrams-any-site/25810/48?u=george_3439977859158)

### Project Part 1 Activity Log

**Wednesday April 27, 2016**

9:39 PM

- Finished Lesson 2, and now ready to start P6-Website Performance Optimization
- I just [Forked Cameron's Repo](https://github.com/udacity/frontend-nanodegree-mobile-portfolio)
- However, will use the clone that I previously made from his repo (which this README file that you are looking at is a part of)
- The goal is to get a Google Pagespeed Insights score of at least 90/100 before project submission
- Right now mobile is at 28/100 and desktop is 30/100
- Preliminary analysis with tools tells me that the first thing to take care of is the pizza image which is over 2 MB
- We are also supposed to make this portfolio are own, so I will probably just start by using a different smaller image that is relevant to my own portfolio
 
10:23 PM

- **Created gh-page**
- To Webserve my latest repo version of Portfolio for analysis
- Just created a gh-page from the cloned repository master, URL at http://geosynchronous.github.io/P6-Mobile-Portfolio/
- Ran Pagespeed Insights and got the same result as for Cameron's original forked version
- As needed, I will delete the previous gh-pages and create new ones from the updated master before testing with Pagespeed, etc
-  **Mobile 28 (red) and Desktop (yellow) 30**

**Thursday April 28, 2016**

11:16 PM

- **Navigation Timing** 
- already available in Cmaeron's code with permatters.js
- dcl (time elapsed for document content loaded) and onload (time elasped for DOM to be created) times shown on bottom of page
- **DCL: 68ms, onload: 128ms**
- the above times vary some each time a reload is done
- dcl varies a bit more than onload... netowrk latencies probable causes

11:58 PM

- **Very Large Graphic Replaced**
- Replaced pizza.pgn 2 MB with sashimi.jpg 5k
- Renamed pizza.html to shogun.htiml
- deleted old gh-pages and created a new one to test with results below
- **Mobile 76 (yellow) and Desktop 89 (green)** *(A HUGE IMPROVEMENT IN PAGESPEED MEASUREMENT!!!)*
- **DCL: 90ms, onload: 171ms** *(This hasn't really changed, variance larger with multiple tries.)*

**Friday April 29, 2016**

1:04 AM

- **Revert back to Pizza**
- This theme is needed in Part 2, so I went back to it
- Compressed pizza.jpg from 2 MB down to 9 KB
- Stats are still the same as in previous entry

1;36 AM

- **Media & Meta Changes**
- made print.css a media event
- filled in <meta> categories
- Page Speed & Nav Timing Results not changes

2:49 AM

- **Google Analytics Installed**
- Has not change Pagespeed or Nav Time Stats
- Created the analytics ID
- not exactly sure what I am doing at this point
- https://moz.com/blog/absolute-beginners-guide-to-google-analytics

3:08 AM

- **Made Analytics,js async**
- Pageview Stats still the same
- **CL: 58ms, onload: 180m** might be improving

11:27 AM

- **Comment Out Google Analytics**
- Need to learn more about this before I use it
- Was not in context of lessons viewed so far
- Will comment it out for now and see what happens
- Then work on other aspects of code

12:23 PM

- **Improved Pagespeed & Nav Times
- **Mobile 77 (yellow) and Desktop 90 (green)** *(Slight Improve, 90 on Desktop!!!)*
- **DCL: 4ms, onload: 136ms** *(DCL improved the most)*
- Need to make profilepic smaller 80 x 80 to 40 x 40

1:57 PM

- **Test Commented Out Google Fonts"
- Not used anyway
- **Mobile 87 (yellow) and Desktop 94 (green)** *(Huge Gains!!!)*
-  **DCL: 4ms, onload: 171ms**

2:28 PM

- **Minified**
- html, css, js
- Page Speed & Nav Time stayed almost same
- **Mobile 87 (green) and Desktop 94 (green)** *(same as before)*
- **DCL: 3ms, onload: 81ms** *(improved)*
 
3:05 PM

- **Inlined style.css**
- **Mobile 95 (green) and Desktop 96 (green)** *(Dramatic Mobile Improvement!!!)*
- This exceed the requirement of at least achieving a 90/100 on Page Speed
- **DCL: 3ms, onload: 87ms** *(no real change)*
- Time to move onto **BROWSER RENDERING OPERATIONS**, and then improve code some more
- Also Google Analytics Condundrum needs to be worked on

4:08 PM

- **Submitted Current Status to Forum**
- [My Forum Contibution](https://discussions.udacity.com/t/optimized-portfolios/16161/90?u=george_3439977859158)

### Coursework Activity Log (Continued)

**Friday April 29, 2016**

8:01 PM

- **OMG found a little GEM**
- THE **"W" key** expands the timeline views!!!
- Sent support a suggestion
- Happens in this [video.](https://classroom.udacity.com/nanodegrees/nd001/parts/00113454012/modules/273584856175461/lessons/4146058564/concepts/41516686300923)  In the video, Paul mentions using the “W” key to zoom in on the graphics in the Chrome Dev Tool TImeline.  I don’t believe it was mentioned before, and it really makes using the newest version of the timeline a lot easier to use.  Likewise just clicking on the top graph takes it back to the default view.  I believe this is one of those things that should have been mentioned much earlier in the previous lessons when talking about timelines.  Maybe just adding this info to applicable Instructor Notes would help students get more comfortable with using timeline, especially since you still use the older version of timeline with it’s very different layout.

8:26 PM

- **WASD KEYS RULE**
- As above, made another support email, though I just figured the W, A, S, D keys allow timeline view manipulation.
- [Devtools Timeline Full Story](https://developers.google.com/web/updates/2015/03/devtools-timeline-now-providing-the-full-story?hl=en)
- [How to Use Time Tools](https://developers.google.com/web/tools/chrome-devtools/profile/evaluate-performance/timeline-tool?hl=en)

9:39 PM

- **MOBILE DEVICE TESTING**
- [Optimized Website](http://geosynchronous.github.io/P6-Mobile-Portfolio/) worked fine on my iPhone 5s and iPad2
- Safari Browser was used
- Navigation Timing results similar on these devices compared to my desktop results

9:54 PM

- **SAFARI WEB INSPECTOR**
- [Optimized Website](http://geosynchronous.github.io/P6-Mobile-Portfolio/) worked fine on Safari Web Dev Tools
- Not nearly as powerful as Chrome Dev Tools
- Has some interesting features, and presents info from different perspectives
- Worth using as a tool

**Saturday April 30, 2016**

11:00 AM

- **Webworker Quiz Coding**
- On this [Forked REPO](https://github.com/Geosynchronous/web-workers-demo)

**Sunday May 1, 2016**

4:58 PM

- **Problems Solving Quiz**
- Made changes to image-app.js to implement Web Worker Thread
- Get this error: image-app.js:9 Uncaught SecurityError: Failed to construct 'Worker': Script at 'file:///Users/geo/version-control/web-workers-demo/scripts/worker.js' cannot be accessed from origin 'null'.
- path seem to be correct... hmmm WHAT IS GOING ON?

5:18 PM

- **Moving On**
- [Cameron's Latest Solution](https://github.com/udacity/web-workers-demo/tree/solution)
- Spent enough time on this for now...
- Web Workers are indeed very cool, and will need to learn how to implement them.
- Set-up of Web WOrkers and hand shanking routing between threads is basically understood at this point.


5:32 PM
- **Resolved Problem**
- Problem using fork from local disk, instead created working repo [gh-page](http://geosynchronous.github.io/web-workers-demo/)
- Probably has to do file permissions and git-hub metadata???

**Monday May 2, 2016**

7:00 AM

- **JANK Quiz Timeline**
- Seperate traces for Web Worker shown on Timeline in sync with main trace
- Closer Inspection of **"onmessage"** timeline item shows: **Warning - Not optimized: TryCatchStatement**, *(not worried about error at this point)*
- Pretty Cool to see Web Worker actually verified by Dev Tools

7:26 AM

- **Observed Big Bug**
- Creating a new object inside the image manipulation loop everytime creates a lot of overhead and slows things down
- Observed Memory Timeline too see js Garbage Collect frequently
- Did not implement improved changes in my code... moving on...

7:39 AM

- **Garbage Collection Resources**
- I am sure I will be needing [this](https://classroom.udacity.com/nanodegrees/nd001/parts/00113454012/modules/273584856175461/lessons/4138168623/concepts/41645386230923) in the future... moving on... information overload... synapse are melting...
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Memory_Management
- https://www.smashingmagazine.com/2012/11/writing-fast-memory-efficient-javascript/
- http://buildnewgames.com/garbage-collector-friendly-code/

**Tuesday May 3, 2016**

10:53 AM

- **Quiz Problem Set-UP
- Forked and cloned [this repo.](https://github.com/udacity/qrcode)
- Set up NPM and GULP CLI

2:27 PM

- **Original QR Code Running**
- Finally!  Forums helped.
- Running gulp serve on local qrcode App dir creates a URL at localhost:3000, request allow to run
- Will need to learn GULP for sure
- Timeline for QRCODE is real ugly
- Control-C terminates gulp serve

8:19 PM

- **Request Animation Frame**
- Made changes just like Cameron showed on VIEW ANSWER frames.
- Compared timelines, before and after, they look exactly the same.
- The complexity of the code is beyond the scope of the lesson intent, therefore I will not dig further...
- **A bug report needs to be sent to support about this**
- will move on to part 2 of the QR quiz
- Neat to see that npm and gulp serve can run an web app on localhost
- Lot of cool code used here to use my laptop camera
- This error also appeared on the console: 
- main.js:260 MediaStreamTrack.getSources is deprecated. See https://www.chromestatus.com/feature/4765305641369600 for more details.
localhost/:98 Service Worker Registered
:3000/scripts/main.min.js:1 GET http://localhost:3000/scripts/main.min.js 404 (Not Found)
1886qrclient.js:14 Couldn't find enough finder patterns
main.js:317 Uncaught TypeError: localStream.stop is not a function(anonymous function) @ main.js:317
30144qrclient.js:14 Couldn't find enough finder patterns


**Tuesday June 7, 2016**

4:28 PM

- **Gone for a Month**
- Family Roadtrips
- Entodontal Work
- Review progress and continue with lesson

4:57 PM

- **Ran QR Code Again**

![Image of Screenshot](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/img/qr_example.png)

6:51 PM

- **Finished Javascripte Section**
- Sent a few bug reports in to support
- One UI problem
- One messy code example problem, large differences in code between video example and student repository code, and not enough context, seems like a hube time sink, so I did not try an implement.

8:56 PM

- **Styles & Layout**
- **Selector Matching Section Started**
- BEM: Block, Element, Modifier - a method of organizing CSS, like it, been wondering about how to do this with my code
- SMACSS, OOCSS also look interesting
- [THis link](https://www.sitepoint.com/bem-smacss-advice-from-developers/) put the above in a useful perspective. 
- Also watched [this video](https://vimeo.com/44773888) and liked it. 
- Use classes avoid IDs
- Keep Layout seperate from content style
- Define layout classes to be re-usable, so less layout code is invoked

10:25 PM

- **FSL - Forced Synchronous Layout**
- If layout needs to be re-calcuolated because of style change, this causes more time to be used than needed
- Dev Tools in Chrome will give warning messages about this with little red triangles in the corner of the recalculate timeline blocks and yellow warning signs on associated elements
-  refactoring code to read styles first before layout will solve the problem
-  Use DEV TOOLS to find FSL in code and fix
-  https://csstriggers.com/

**Wednesday June 8, 2016**

10:00 AM

- **Painting and Compositing**
- **Quiz Paint Rectangles**
- Sent Bug Report
- issue URL: https://classroom.udacity.com/nanodegrees/nd001/parts/00113454012/modules/273584856175461/lessons/4129068601/concepts/41506686430923

Omission of instructional detail, the Paint box also needs to be checked off for the following series of instructions to make sense. You might add this info and/or image below to the instructor notes at this point of instruction.

![Image of Bug](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/img/paintfix.png)

10:10 PM

- **MY BAD**
- Above INFO actually does occur in frames that follow
- Forwarded Update to support

10:36 PM

- **Coercing Composite Layer**
-  This [link](https://classroom.udacity.com/nanodegrees/nd001/parts/00113454012/modules/273584856175461/lessons/4129068601/concepts/41395386460923) gives details about how to do this
-  Browsers inherently take care of layering, however sometimes to optimize website updates, the CSS can be updated to cause a new layer to probably happen
-  EXAMPLE: .box{will-change: transform;}
-  can also use transform: transform Z(0) as well cquse not all browsers use the above, so use both for now... HACK,HACK,HACK

12:02 PM

- **Layers**
- In D EV TOOLS with PAINT Toggled ON, then recording timeline of scrolling, clicking on any of of the time duration graphic boxes, will invoke LAYER info to appear in the details at the bottom
- this is a good way to find out how many layers there are and what they are

**Thursday June 9, 2016**

7:48 PM

- **Final Project Quiz**
- I made a bunch of the suggested changes via Camerons solutions
- Noted how each change optimized performance
- Fairly intimidating coding examples
- Great way to learn how to use DEV TOOLS to increase performance
- Quite instructive on how to make specific layout changes to optimize

9:00 PM

- **FINALLY!!! - READT TO START PROJECT 2**
- Will record progress on Project in a next section..

### Project Part 2 Activity Log

**Thursday June 9, 2016**

9:16 PM

- **Setup Project Part 2**
- Follow [Project Details](https://classroom.udacity.com/nanodegrees/nd001/parts/00113454012/modules/273584856175461/lessons/2735848561239847/concepts/26641385370923) directions to complete this project.
- Using same repo as Project Part 1 and continuing on with Project Part 2 requirements.

9:51 PM

- **PageSpeed Insights**
- Used my gh-page in repo to test pizza.html
- Mobile User Exerience 72 (yellow) & Speed 82 (green) and Desktop Suggestions Summary 92 (green)
- Use as a benchmark for now
- Will follow up on suggestions later
 
**Friday June 10, 2016**

8:00 AM

- **Refactor Code Focus**
- [Assessment Review Rubric](https://review.udacity.com/?_ga=1.100937729.1099881078.1443828986#!/rubrics/16/view) asks to make pizza.html page more performant by optimizing the scrolling and sliding effects.
- I will focus first on the scrolling
- Already used DEV TOOLS TIMELINE on both effects to get an overview of the situation.
- Earlier this year I was baffled by Chrome Dev Tools, now I thinking I am falling in love with this incredibly sexy tool...
- Forced Synchronous Layouts seem to be an issue with scrolling.  This [link](https://developers.google.com/web/tools/chrome-devtools/profile/rendering-tools/forced-synchronous-layouts?hl=en) has a useful methondology for fixing FSL.

**Basic Methodology:**
- Get Data
- Identify Problem
- Apply Fix within Dev Tools
- Verify with another Timeline Recording

8:21 AM

- **USER Scrolling Experience**
- Hardware testing platform is **Macbook Pro 13", Early 2011, 2.3 GHz i%, 16 GB RAM, SSD Drive, and 10.11.5 OSX**
- Browser testing platform is up to date at **Chrome Version 51.0.2704.84 (64-bit)**
- Scrolling seems to run smooth already, but from previous DT Timeline I know the animation frame rate is too long.
- Amazing how well browsers work today.  If I were in production, I would look at other browser platforms too.

9:12 PM

- **Initial Scrolling Timeline Data**
- js Profile enabled timeline record, scrolling down & up ![Image of Scroll Initial](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Initial.png)
- Then 111 ms 9 fps Animation Frame zoomed in on ![Image of Scroll Initial Zoom 1](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Intial_Zoom1.png)
- Then layout zoomed in on revealing jank error at main.js 507 ![Image of Scroll Initial Frame](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Intial_Zoom2.png)
- [Raw Timeline Data found here](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines)

10:07 AM

- **Scrolling JANK Error Located**
- Clicking on error location in timeline opens main.js file ![Iamge of Jank Code Error Location](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Main_js_507.png)
- AWESOME!!
- BUt WAIT... HMMMM.... Now what does this mean???
- I know... **MUSH ALARM INVOKED**... my head has turned to mush... so it is time to take a break... before I make too many mistakes!

7:30 PM

- **Scrolling Fix 1: JANK Code**
```
505  var items = document.querySelectorAll('.mover');
506  for (var i = 0; i < items.length; i++) {
507    var phase = Math.sin((document.body.scrollTop / 1250) + (i % 5));
508    items[i].style.left = items[i].basicLeft + 100 * phase + 'px';
509  }
```
- In line 507,  `i` is the only parameter that changes in the for loop, whereas `document.body.scrollTop` never changes, so there is no need to compute this for every loop iteration.  The big problem with this is that `document` is having it's style (`body`) changed which causes a time consuming Forced Synchronous Layout to happen each time the loop is iteratated.
- By refactoring the code to take `document.body.scrollTop` out of the for loop, the repetitive FSL will not occur, and thus make this web page more performant.  I will change the above code to cache `scrollTop` (now line 506) outside the for loop, and replace `document.body.scrollTop` with `cachedScrollTop` (now line 507) :
```
505  var items = document.querySelectorAll('.mover');
506  var cachedScrollTop = document.body.scrollTop;
507  for (var i = 0; i < items.length; i++) {
507    var phase = Math.sin((cachedScrollTop / 1250) + (i % 5));
508    items[i].style.left = items[i].basicLeft + 100 * phase + 'px';
509  }
```
- this change should fix the **LAYOUT THRASHING**
- [Illya's link](https://www.igvita.com/slides/2012/devtools-tips-and-tricks/jank-demo.html) mention above in the original code help me see this solution more succintly.

9:06 PM

- **Scrolling FIX 1: Verified**
- This definately made a noticable perfomance improvement, it roughly doubled the fps.  It went from 111 ms and 9 fps to about 50 ms and 20 fps or even better.
- Running the timeline again results in: ![Image of FIX1 Timeline](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix1.png)
- Compare with the first Initial timeline graphic above and note how much less red time animation segments there are (60 fps or better), before they were all red (lower fps).
- Also note that scripting and rendering take up proportionality much less of the piechart space in relation to paining
- Also note that the built-in code **USER TIMING API - Average times to generate last 10 frames** has improved greatly, it is now on the order of 1.5 ms or less, and before FIX 1 it was on the order of 50 ms. (This information is shown in the the CONSOLE on DEV TOOLS everytime, as part of the `window.performance` code that is in the `updatePositions` function.)
- I am happy with this result.
- Now I need to take a closer look at this current timeline data to figure out what else is gumming up the works.
- I didn't see a requestAnimationFrame in this chunk of code, and I suspect that is what I will focus on next.

9:49 PM

- **Scrolling FIX 2 Problem: Initial Timeline Data**
- I zoomed in on a time frame that was less performant than 60 fps (a red segment) and it looks like this: ![Image of FIX 2 Problem](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix1_Zoom1.png)
- updatePositions @ main.js:501 is the function of interest, which is where we made our previous changes for FIX 1 above.
- THis function needs a requestAnimationFrame since animations are occuring here.
- Now I need to figure out how to do that...

**Saturday June 11, 2016**

10:16 AM

- **Scrolling Fix 2: requestAnimationFrame**
-  added rAF after `updateposition` function (see last lines of code below)
```
// Moves the sliding background pizzas based on scroll position
function updatePositions() {
  frame++;
  window.performance.mark("mark_start_frame");

  var items = document.querySelectorAll('.mover');

  // OLD CODE:
  // (Expensive Forced Synchronous Layout)
  // for (var i = 0; i < items.length; i++) {
  //   var phase = Math.sin((document.body.scrollTop / 1250) + (i % 5));

  // Scrolling FIX 1:
  // (See Repo README file for detailed explanation)
  var cachedScrollTop = document.body.scrollTop;
  for (var i = 0; i < items.length; i++) {
    var phase = Math.sin((cachedScrollTop / 1250) + (i % 5));

    items[i].style.left = items[i].basicLeft + 100 * phase + 'px';
  }

  // User Timing API to the rescue again. Seriously, it's worth learning.
  // Super easy to create custom metrics.
  window.performance.mark("mark_end_frame");
  window.performance.measure("measure_frame_duration", "mark_start_frame", "mark_end_frame");
  if (frame % 10 === 0) {
    var timesToUpdatePosition = window.performance.getEntriesByName("measure_frame_duration");
    logAverageFrame(timesToUpdatePosition);
  }
}

//Scrolling FIX 2:
// (See Repo README)
requestAnimationFrame(updatePositions);
```
- It seemed to improve performance

11:45 AM

- **Scrolling FIX 2: Verified**
- Timeline of fix results in: ![Image of Fix2 Timeline](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix2.png)
- Comparing this timeline to the most recent ones previous to this fix, it is apparent that the fix is probably a keeper.
- There are fewer time frames that are too long (red ones), and the timing results shown in the console have also improved some for the 10 frame averages.
- Zooming in on a green time frame, it appears that rendering pipeline has improved with shortened times as well when compared to the timelines before the fix.![Image of Fix2 Zoom1 Timeline](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix2_Zoom1.png)
- Zooming in on a red time frame, it appears that there still are jamk problems lurking about the code.![Image of Fix2 Zoom2 Timeline](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix2_Zoom2.png)
- I will look into this JANK problem to try and figure out what is going on.

1:20 PM

- **Thinking Out Loud**
- in an Animation Frame the rendering pipeline seems to framgmented for a nice clean delivery.
- This [slick Google Development Site on Rendering Performance](https://developers.google.com/web/fundamentals/performance/rendering/) looks like it will help me review, and strengthen what I need to work on to fix the pipeline fragementation and other performance issues.  I will spend some time reviewing it soon.
- I suspect that the layers are a problem, and it may be that I need to coerce layout in the `updatePositions` function.
- Need to implement `will-change` and `transform Z(0)`...  So I will try to implement this next...


**Wednesday June 15, 2016**

8:30 PM

- **Temporary Scrolling Change**
```
.mover {
  /*  TODO - REMOVE TEMP CHANGE*/
  /*  added this attribute */
  will-change: transform;
  transform: transform Z(0);

  position: fixed;
  width: 256px;
  z-index: -1;
}
```
- this was an attempt to coerce the layout and get a more performant less fragmented  render pipeline. ![Image of TempChange1](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_TempChange1.png)
- It did indeed make the pipeline less fragmented, however it made a whole bunch of new layers, and as a result the COMPOSITE rendering time went way up, this in turn created too many long frames again at low fps.
- For now I will remove this change and look elsewhere.

10:18 PM

- **Scolling FIX 3 Layout Thrashing**
- The read and write styles need to be seperated as shown here to prevent the layout from being recalulated too often:
```
  var cachedScrollTop = document.body.scrollTop;
  for (var i = 0; i < items.length; i++) {
    var phase = Math.sin((cachedScrollTop / 1250) + (i % 5));

    // OLD CODE for FIX 3:
    // items[i].style.left = tems[i].basicLeft; + 100 * phase + 'px';

    // Fix 3
    // Layout Thrashing
    // Seperate READ Styles form WRITE Styles
    // READ Style
    var cachedBasicLeft = items[i].basicLeft;
    // WRITE Style
    items[i].style.left = cachedBasicLeft + 100 * phase + 'px';
  }
```

### Udacity Reviews

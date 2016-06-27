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
- **IMPORTANT NOTE: THIS IS GARBAGE**
- **SEE BELOW at Saturday June 18 for NEW FIX**
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

- **Scolling FIX 3: Layout Thrashing**
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

10:39 PM

= **Scrolling FIX 3: Verified**
- The fix did indeed make tha app more performant, there are few red indicators now, and the timing stats are much improved to around 60 fps with some +/- variance.  The Timing API in the console window shows the improvemenet as well: ![Image of FIX3 Timeline](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix3.png)
- The pipline still is fragmented, and needs more looking into.  Perhaps the will-change coercion will work better now, need to check that, ![Image of FIX3 Timeline Zoom1](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix3_Zoom1.png)

11:02 PM

- **Scrolling FIX 4: Coerced Layout**
- Previouslytried this code, results were not great, (see attempt results above) now I am trying it again.
```
.mover {
  /*  FIX 4: */
  /*  Coerced layout */
  /*  Added this code */
  will-change: transform;
  transform: transform Z(0);

  position: fixed;
  width: 256px;
  z-index: -1;
}
```
11:15 PM
- **Scrolling FIX 4: Verified**
- With Painting Mode on in Dev Tools performance is greatly effected, and this is probably due to the fact that a large number of layouts are being made, which I was in the layout graphic window.  But with Painting modw off, much better results are realized:
- This made the rendering pipeline much less fragmented, even though the Timing API stats don't look as good, the DEV TOOL Stats look better as a result, the 60 fps target for scrolling is beginning to look pretty good: ![Iamge of FIX$ Timelime](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/0aa584e3a5abd5c04f7afb4e993388d7664ce937/timelines/Scroll_Fix4.png)
- ![Iamge of Fix4 Zoom 2](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix4_Zoom2.png)

**Thursday June 16, 2016**

12:08 AM

- **WEB WORKERS**
- As a next steo may try to put `updateLocations` function contents in a Web Worker, to try and improve response time in RECALCULATING STYLES.
- On the otherhand, aside from a few hiccups, the timeline is hovering around the targeted 60 fps already.

8:51 AM

- **What's Next Besides Coffee**
- BTW when I turn on paint flashing, and scroll up and down, the only thing that now hightlights is the scrollbar, at the beginning of this project everything was highlighted.
- Seems to me that implementing **Web Workers** could shorten the js script and recalculating style times, and thus up the fps, if I split up the pizza's into multiple for loops for the location calculation and style change.  However, that will require some additional code for the WW's and putting the item array back together.  I will defer that for now, and look into speeding up the code by cleaning up the `item.basicleft` calculations.
- Also note that the frame rate meter is now consistently showing 60 fps when the page is scrolled: ![Image of Fix4 Frame Meter](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix4_FrameRateMeter.png)
- Further, it seems like the **Timing API**, is really not that useful anymore, and does not exactly reflect the dynamic frame rate info as well as Chrome Dev Tools Timelines and the Frame Meter.  It is probably time to remove that code, which might speed things up a tad as well.
- **WOW, what does this mean?**  With painting turned on there are about a couple hundred rendered pizza layers (when I scroll down), about 13 of them closest to the viewed rendered window are about 320 kb in size, all the rest are 0 kb: ![Image of Fi4 Layers](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix4_Layers.png)
- Perhaps all 200 `items[i]` are depicted here as wire frames, and only the ones closest to the viewed web page background are filled, will need to look at the code some more to see if something can be optimized here.
- When I run Profiles for JS I get the following results: ![Iamge of Fix4 JS Profiles](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix4_JSProfiles.png)
- Not sure what all this means, but the yellow warning sign indicates **_wrapObjectVM43 - Not Optimized, TryCatchStatement**.  When I look at all the times, removing the Timing API might give me a 10% boost in perf in relation to `updateLocation` times???
- Maybe I am beating a dead horse to death here.

11:30 AM

- **Why: Too Many Damn Moving Pizzas?**
- looking at the active HTML in DevTools, it is apparent that all the moving pizzas I detected in the LAYERS analysis above are generated by the `appendChild(elem)` statement shown here:
```
document.addEventListener('DOMContentLoaded', function() {
  var cols = 8;
  var s = 256;
  for (var i = 0; i < 200; i++) {
    var elem = document.createElement('img');
    elem.className = 'mover';
    elem.src = "images/pizza.png";
    elem.style.height = "100px";
    elem.style.width = "73.333px";
    elem.basicLeft = (i % cols) * s;
    elem.style.top = (Math.floor(i / cols) * s) + 'px';
    document.querySelector("#movingPizzas1").appendChild(elem);
  }
  updatePositions();
});
```
- Active html, showing a plethora of the moving pizzas, probably 200 of them: ![Image of Too Many Pizzas Code](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix4_TooManyPizzas.png)
- Is this really necessary???
- The top position starts at 0 px for the first 8 pizzas, and then increases in value (256 px) for every 8 pizzas until the last 8 moving pizzas and ends up at 6144 px: `<img class="mover" src="images/pizza.png" style="height: 100px; width: 73.333px; top: 6144px; left: 55.0011px;">`
- Can we do with less moving pizzas?

12:36 PM

- **Scrolling Fix 5: Less Moving Pizzas**
- Changed main.js code:
```
// Generates the sliding pizzas when the page loads.
document.addEventListener('DOMContentLoaded', function() {
  var cols = 8;
  var s = 256;
  // Scrolling FIX5
  // Reduced loop from 300 inc to 33
  // Plenty of moving pizzas to cover large screen lengths
  for (var i = 0; i < 33; i++) {
    var elem = document.createElement('img');
    elem.className = 'mover';
    elem.src = "images/pizza.png";
    elem.style.height = "100px";
    elem.style.width = "73.333px";
    elem.basicLeft = (i % cols) * s;
    elem.style.top = (Math.floor(i / cols) * s) + 'px';
    document.querySelector("#movingPizzas1").appendChild(elem);
  }
  updatePositions();
});
```

12:39 PM

- **Scrolling Fix 5: Verified**
- Even with a bunch of Dev Tools attributes turned on, the Timeline results seemed to improve: ![Iamge of Fix5 Timeline](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix5_.jpg)
- In the layout graphic, you can see there is just one row extra of moving pizzas to accomadate longer screens if needed.  The timing on the rendering pipeline has improved as well,
- Zooming in we can see this better, and see the Timing API results in the console window have improved as well: ![Image of FIX5 Zoom1](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix5_Zoom1.png)
- Turning off the unneeded sampling attributes in Dev Tools we see even a better picture, with much better pipeline times, though the main page seems to be painting twice (not sure why): ![Image of Fix5 Min Dev Tools](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix5_MinDevTools.png)

1:00 PM

- **MUSH ALERT!!!**
- My head has turned to MUSH
- Time for a break and some movement

9:11 PM

- **Change Background Color**
- Red to Greeen
- Better Contrast

9:30 PM

- **Smooth as Silk Scrolling**
- 60 fps is 16.67 ms
- It is interesting to note that when not running Dev Tools timeline the Timing API shows even faster times to move the Pizzas on scroll:![Image of Timing API Results](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_60FPS.png)
- Moving the pizzas is on the order of about 0.5 ms
- Chrome Dev Tools is showing 60 fps range consistently when scrolling, as can be seen from the recent timeline graphics depicted above.
- **I think this meets the 60 fps Scrolling requirements in the rubric.**
- Time to move on to **Re-Size Pizza with Slider** performance issues.

11:02 PM

- **Resize Pizza Issue**
- When using the slider on the pizza.html web page, one can select small or medium or large pizza sizes to be displayed on the page for the pizzas that positioned on the menu.  Note that the sliding pizzas do no change size when the slider is moved.
- The goal from the rubric states that the Pizzas must resize in **5 ms**.
- The Timing API for resizing the pizzas will display the resize times in Browser Console Window anytime the slider changes pizza sizes: ![Image of Resize Pizza Stats1](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/ResizePizza_Stats1.png)
- Right now results are around **150 ms** or so to resize the pizza as shown above.
- That is about 30x longer than it needs to be.
- The image file for the resized pizzas is pizza.png and it is about 50 Kb in memory size, and 232 x 300 px in graphics size.
- The image has a bunch of blank space around the pizza, cropping that away might help reduce the file size alone, but then I will have to mess with the offsets in the code to get the pizzas to be located properly.
- Pizza size is also effected by the document window width, and re-sizing the window, this makes things even more complicated.
- WIll need to look at the code some more... but first I will compress the graphic file size

**Friday June 17, 2016**

12:10 AM

- **Resize Pizza Fix 6: Compress Grapics Files**
- [TinyPNG](https://tinypng.com/) is a compression website that I used to compress the two graphic files.
- The file `pizza.jpg` and pizzaria.jpg were both compressed about 60% each.
- Both new compressed files will be uploaded into the repo to use and replace the old larger ones.
- It will probably help perf for where both of these files are used.


12:38 AM

- **Resize Pizza Fix 6: Verify**
- Not too much of an improvement:

![Image of Resize Pizza Stats2](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/ResizePizza_Stats2.png)

8:20 AM

- **Resize Pizzas Timeline Analysis**
- Resizing the Pizzas via the slider 3x yields this timeline: ![Iamge of Resize Pizza Stats3](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/ResizePizza_Stats3.png)
- The behaviour seems to be consistent amongst all three trials
- There is obviously a lot of repetitive JANKING going on here.
- The function called is at pizza.html 101
- `<input id="sizeSlider" type="range" min="1" max="3" value="2" step="1" onchange="resizePizzas(this.value)"></input>`
- All the little red tabs are on RECALCULATE STYLE and LAYOUT.
- The Summary Message in Tools indicated:
```
Layout Forced
determineDx	@	main.js:426
First Layout Invalidation
changePizzaSizes	@	main.js:456
```
- So this is the first chunk of code I need to ponder for FSL: ![Image of Resize Pizza Stats3 Code](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/ResizePizza_Stats3_Code.png)
- Hmmmm... Now that I have found the source of the problem... What does it mean?

9:29 AM

- **Resize Pizzas Fix7: Layout Thrashing**
- Looking at the above code, at lines 451-457, it seems like a READ& & WRITE STYLE iteration on `randomPizzaContainer` that is causing the FSL:
```
  // Iterates through pizza elements on the page and changes their widths
  function changePizzaSizes(size) {
    for (var i = 0; i < document.querySelectorAll(".randomPizzaContainer").length; i++) {
      var dx = determineDx(document.querySelectorAll(".randomPizzaContainer")[i], size);
      var newwidth = (document.querySelectorAll(".randomPizzaContainer")[i].offsetWidth + dx) + 'px';
      document.querySelectorAll(".randomPizzaContainer")[i].style.width = newwidth;
    }
```

- **I think that if I change the code to do all the READS first, and then all the WRITES after, it will not cause as many repetitve FSL's to occur. To do this, I will need two for loops, and need to create an array 'newWidth' to cache `newwidth` so it can be accessed in the WRITE for loop:**

```
 // Resize Pizzas Fix 7:
 // Iterates through pizza elements on the page and changes their widths
 // READ and WRITE Styles seperate tasks to avoid FSL
  function changePizzaSizes(size) {
    var newWidth =[];
    // READS all widths first
    for (var i = 0; i < document.querySelectorAll(".randomPizzaContainer").length; i++) {
      var newDx = determineDx(document.querySelectorAll(".randomPizzaContainer")[i], size);
      newWidth.push((document.querySelectorAll(".randomPizzaContainer")[i].offsetWidth + newDx) + 'px');
    }
    // WRITES changes to all widths
    for (var i = 0; i < document.querySelectorAll(".randomPizzaContainer").length; i++) {
      document.querySelectorAll(".randomPizzaContainer")[i].style.width = newWidth[i];
    }
  }
```
- Also note nomenclature changes, `dx` is declared in two seperate functions, so I will change the later to `newDx` for clarity purposes.

11:32 AM

- **Resize Pizza Fix 7: Verify**
- It speed up the resize about 10x as seen by the stats in the console window, it also remove a lot of layout thrashing, and improved the rendering pipeline phases considerably: ![Iamge of Resize Pizza Verfied1](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/ResizePizza_Stats3_Verified1.png)
- Zooming we can see this in more detail: ![Iamge of Resize Pizza Verfied1](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/ResizePizza_Stats3_Verified2.png)
- Note that we are still being flagged for Forced Layouts (red tab)

11:48 AM

- **Resize Pizza another Forced Layout Issue**
- From the zoomed in timeline above we can see that main.js 426 is forcing a layout ![Image of Resize Pizza Verifired1 Code](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/ResizePizza_Stats3_Verified1_Code.png)
- Hmmmn...

1:48 PM
- **AHA!!!**
- Turns out after tracking things down, and playing with code, I realized that all `newWidth[]` are the same for a given slider change and initial conditions.
- So an array will not be needed, as one size fits all, just a single variable will do
- So FIX 7 can be redone... it will be called FIX 7(NEW)

4:24 PM

- **Serious Mush Alert and Good Progress**
- My brain in fried
- I have made some progress
- Am thrown off a bit by `elem.offsetLeft` triggering a forced layout, but it only does it once and may not be that bad
- It sure sucked up a bunch of my time trying to get rid of it
- I put a few constant values in place to test and eliminate' forced layout, it got rid of the Tools Warning, but did not increase perf
- So I left the `elem.offsetLeft` in the code, as it is really not an issue
- Realized that there are many width values that are the same between all the `randomPizzaContainer` items
- so refactored the code to eliminate thrashing cause by iterating over the `elem.offsetLeft`
- this improved the resize pizza time down to about 4-6 ms... when the Dev Tools window is seperate from browser window
- probbably good enough to pass the rubric requirement of 5 ms

5:14 PM

- **Resize Pizzas Fix7 (NEW): Impreoved Layout Thrashing FIx**
```
 // Resize Pizza Fix 7 (NEW):
  // Note changes all the way down thhrough changePizzaSizes function
  // Returns the size difference to change a pizza element from one size to another. Called by changePizzaSlices(size).
  // Function name chamged from determineDx, as it now implements more functionality
  // This reduces the complesity of the code below in changePizza Size function
  function determineNewWidth (size) {

    // Note only one offsetWidth value is needed, as they are sawme for all containers
    // The elem.offsetWidth triggers a FSL warning, but it only happens once
    // Iteration overn all container values will cause major thrashing
    // FSL warning does not seen to be an issue
    var oldWidth = document.querySelectorAll(".randomPizzaContainer")[0].offsetWidth;
    var windowWidth = document.querySelector("#randomPizzas").offsetWidth;
    var oldSize = oldWidth / windowWidth;

    // Optional TODO: change to 3 sizes? no more xl?
    // Changes the slider value to a percent width
    function sizeSwitcher (size) {
      switch(size) {
        case "1":
          return 0.25;
        case "2":
          return 0.3333;
        case "3":
          return 0.5;
        default:
          console.log("bug in sizeSwitcher");
      }
    }

    var newSize = sizeSwitcher(size);
    var dx = (newSize - oldSize) * windowWidth;
    // updateWidth added to simplify code that follows
    var updateWidth = oldWidth + dx + 'px';
    // dt no longer returned, instead updateWidth is
    return updateWidth;
  }

  // Iterates through pizza elements on the page and changes their widths
  // READ and WRITE Styles seperate tasks to avoid FSL
  function changePizzaSizes(size) {

    // READ newWidth
    // Itereations eliminated because of the refactoring
    var newWidth = determineNewWidth(size);

    // WRITES changes to all widths
    // Simplified because fo refactoring
    for (var i = 0; i < document.querySelectorAll(".randomPizzaContainer").length; i++) {
      document.querySelectorAll(".randomPizzaContainer")[i].style.width = newWidth;
    }
  }
```
5:29 PM

- **Resize Pizzas Fix7 (NEW): Verfified**
- The layout thrashing is now clearly gone, (compare to above timelines): ![Image of FIX7 Timeline](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/ResizePizza_Stats4_Fix7NEW.png)
- The resize times have greatly improved: ![Image of NEW FIX 7 Stats](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/ResizePizza_Stats4_Fix7NEW_%20Stats.png)
- This warning may not be an issue, as it only happens once, and using constant values in place of the elements did not improve the perf: ![Image of Fix7 TImeline Zoom](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/ResizePizza_Stats4_Fix7NEW_Zoom1.png)

**Thursday June 23, 2016**

1:54 PM

- **Scrolling Fix 2 (NEW): Code**
- The previous Fix2 was garbage, and this supersedes it.
- Basically created `var requestID;` to START and STOP animations in the `updatePositions` function.
```
// Scroll Fix 2 (NEW);
// Supersedes origingal Fiz 2
// Uses "reqyestID" to Start and Stop rAF
// (See README notes in Repo)
var requestID;

function updatePositions() {

  // Fix 2 (NEW continued):
  requestID = requestAnimationFrame(updatePositions);

  frame++;
  window.performance.mark("mark_start_frame");

  var items = document.querySelectorAll('.mover');
  var cachedScrollTop = document.body.scrollTop;

  for (var i = 0; i < items.length; i++) {
    var phase = Math.sin((cachedScrollTop / 1250) + (i % 5));

    // READ Style
    var cachedBasicLeft = items[i].basicLeft;
    // WRITE Style
    items[i].style.left = cachedBasicLeft + 100 * phase + 'px';
  }

  // User Timing API to the rescue again. Seriously, it's worth learning.
  // Super easy to create custom metrics.
  window.performance.mark("mark_end_frame");
  window.performance.measure("measure_frame_duration", "mark_start_frame", "mark_end_frame");
  if (frame % 10 === 0) {
    var timesToUpdatePosition = window.performance.getEntriesByName("measure_frame_duration");
    logAverageFrame(timesToUpdatePosition);
  }
  // Fix2 (NEW continues):
  cancelAnimationFrame(requestID);
};
```
- NOTE: Time to tidy up... Removed some previous fix comments from previous code, all the refactors were getting to messy.  Refer to this README file for previous changes, and the git commits for more specific info on those changes.

2:15 PM

- **Scrolling Fix 2 (NEW): rAF Verified**
- The Tools image shows an improved timeline, better render pipeline times, and the console shows some better average times to generate pizzas: ![Image of Fix2 NEW](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Scroll_Fix2_NEW.png)

4:12 PM

- **Cosmetic Tweaks**
- Bored with old appearance
- Text and Backgroumd color
- New Pizzeria graphic
- Text Changes

11;45 PM

- **Resize Pizzasas FIX 8: Preliminary Entry**
- Some pretty **TRICKY STUFF**
- Tryed a bunch of things till I figured out what was going on
- Got great results
- Will document changes here tommorrow and clean up code comments
- Dumped this change, Fix 9 instead...

**Saturday June 18, 2016**

10:46 PM

- **Resize Pizzasas FIX 8: Code**
- Made a mess of things and had to clean it up...
- Refactored DetermineNewWidth and ChangePizzaSizes

```
//FIX 9
  // Refactored putting var elem back into the next two functions
  // Moved 'px' to a more appropriate place
  function determineNewWidth (elem, size) {
    var oldWidth = elem[0].offsetWidth;  // All pizzas same width, so read first
    var windowWidth = document.querySelector("#randomPizzas").offsetWidth
    var oldSize = oldWidth / (windowWidth);

    // Optional TODO: change to 3 sizes? no more xl?
    // Changes the slider value to a percent width
    function sizeSwitcher (size) {
      switch(size) {
        case "1":
          return 0.25;
        case "2":
          return 0.3333;
        case "3":
          return 0.5;
        default:
          console.log("bug in sizeSwitcher");
      }
    }

    var newSize = sizeSwitcher(size);
    var dx = (newSize - oldSize) * windowWidth;
    // updateWidth added to simplify code that follows
    var updateWidth = oldWidth + dx;
    // dx no longer returned, instead updateWidth is
    return updateWidth;
  }

  // Iterates through pizza elements on the page and changes their widths
  // READ and WRITE Styles seperate tasks to avoid FSL
  function changePizzaSizes(size) {

    var elem = document.querySelectorAll(".randomPizzaContainer");

    // READ newWidth
    // Itereations eliminated because of the refactoring
    var newWidth = determineNewWidth(elem, size);

    // WRITES changes to all widths
    // Simplified because fo refactoring
    for (var i = 0; i < document.querySelectorAll(".randomPizzaContainer").length; i++) {
      elem[i].style.width = newWidth + 'px';
    }
  }

  changePizzaSizes(size);

  // User Timing API is awesome
  window.performance.mark("mark_end_resize");
  window.performance.measure("measure_pizza_resize", "mark_start_resize", "mark_end_resize");
  var timeToResize = window.performance.getEntriesByName("measure_pizza_resize");
  console.log("Time to resize pizzas: " + timeToResize[timeToResize.length-1].duration + "ms");
};
```

10:52 PM

- **- **Resize Pizzasas FIX 8: Verify**
- This improved things and now the times are around 5 ms or less.
- These times meet the rubric requirement targeted time limit of 5 ms.
- The `elem.offset` are still triggering a forced layout once, might be nice to fix that too.
```
Time to generate pizzas on load: 39.05ms
main.js:478 Time to resize pizzas: 3.680000000000291ms
main.js:478 Time to resize pizzas: 3.1400000000003274ms
main.js:478 Time to resize pizzas: 5.229999999999563ms
main.js:478 Time to resize pizzas: 5.565000000000509ms
main.js:478 Time to resize pizzas: 4.975000000002183ms
main.js:478 Time to resize pizzas: 5.330000000001746ms
main.js:478 Time to resize pizzas: 5.475000000002183ms
main.js:478 Time to resize pizzas: 5.295000000001892ms
```
11:14 PM
- **Possible .offsetWidth refactor**
```
var element = document.getElementById('foo');
var positionInfo = element.getBoundingClientRect();
var height = positionInfo.height;
var width = positionInfo.width;
```
- The result should be truncated, as they give fractional answers
- Try this tomorrow...

11:24 PM
- **Getting R A I L (or L I A R as Cammeron would say) L = LOAD**
- Actually it takes about 50 ms for the code to run and do all the rendering once the the slider is clicked
- This is less than the 100 ms when us humans begin to notice the reload
- My user experience makes me think the response shows no jank
- So  won't play with the forced layout workaround for `.offsetWidth` refactor as it really doesn't matter
- will clean upcode and optimize files next...
 
11:45 PM
- **FIX 9 Timeline**
- Zoomed in on one changePizza size event: ![Image of Fix9 Timeline](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Fix9_Results.png)
- The fist cluster  (16 ms) of events is what happens when the user changes the slider position with a click
- Then there is a (104 ms) Idle
- Then there is the actual resize of Pizzas (47 ms)
- Note that the red flagged layout doesn't seem to trip things up and only takes about .53 ms
- **THINGS TO DO?**
- Can the Idle time be reduced with intiating `will-change` somehow for the slider change and the pizza size change?
- Can the render pipline for resizing the pizzas be reduced by using using `transform: Scale(x,y)`?
- Can refactoring `.offsetwidth` remove the forced layout?
- Looking closer I see that the 100 ms idle is mostly due to the time between the mouse is pressed down and the mouseup, so no need to coerce layout with will-change.

**Friday June 24, 2016**

12:44 PM

- **Resize Pizzas Fix 10: Code**
- `elem` to `element` where needed in `changePizzaSizes` and `determineNewWidth` functions to avoid prior use of elem for background pizzas

1:04 PM

- ** Resize Pizzas Fix 10: Verified**
- This removed the timeline jank warning, but forced reflow because of `.offset` is still there: ![IMAGE OF FIX10 TIMELINE](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Fix10_Results.png)
- And the time to resize pizzas looks good it average around 5 ms or less:
```
Time to generate pizzas on load: 36.074999999999996ms
main.js:482 Time to resize pizzas: 4.434999999999945ms
main.js:482 Time to resize pizzas: 5.205000000000382ms
main.js:482 Time to resize pizzas: 3.914999999999054ms
main.js:482 Time to resize pizzas: 3.800000000000182ms
main.js:482 Time to resize pizzas: 4.524999999999636ms
main.js:482 Time to resize pizzas: 3.4249999999992724ms
main.js:482 Time to resize pizzas: 6.595000000001164ms
main.js:482 Time to resize pizzas: 6.295000000000073ms
main.js:482 Time to resize pizzas: 3.2849999999998545ms
main.js:482 Time to resize pizzas: 4.734999999998763ms
```

9:21 PM

- **Resize Pizzas FIX11: Code**
- Implemented a major refactor of the code to use `transform: scale` to speed up rendering
- This allowed me to get rid of the `.offset` which forced synchronous layout
- This change suprersedes a some of the previous fixes
- This also simplified the code greatly
- LESS is MORE
```
// FIX 11
  // Major refactor to use style 'transform scale'
  // Replace style 'width' change
  // Adjusted percentages in 'sizeSwithcer'
  function determineNewScale (size) {
    // Changes the slider value to a percent width
    function sizeSwitcher (size) {
      switch(size) {
        case "1":
          return 0.5;
        case "2":
          return 0.6666;
        case "3":
          return 1.0;
        default:
          console.log("bug in sizeSwitcher");
      }
    }
    return sizeSwitcher(size);
  }

  // READ and WRITE seperate tasks to avoid FSL
  function changePizzaSizes(size) {
    // READ - Load all pizza image elements
    var element = document.querySelectorAll(".img-responsive");
    // Sets value of newScale
    var newScale = determineNewScale(size);
    // WRITE - New transforms for pizza size updated here
    for (var i = 0; i < element.length; i++) {
      element[i].style.transform = "scale(" + newScale + ")";
    }
  }

```

9:31 PM
-**Resize Pizzas FIX11: Verification**
- The resize pizzas time have improved about 5x with this change, and are now around 1 ms (5 ms or less rubric target)
```
Time to generate pizzas on load: 28.470000000000006ms
main.js:468 Time to resize pizzas: 1.7849999999998545ms
main.js:468 Time to resize pizzas: 1.9200000000005275ms
main.js:468 Time to resize pizzas: 1.2150000000001455ms
main.js:468 Time to resize pizzas: 1.2050000000008367ms
main.js:468 Time to resize pizzas: 1.055000000000291ms
main.js:468 Time to resize pizzas: 1.609999999998763ms
main.js:468 Time to resize pizzas: 1.1050000000013824ms
main.js:468 Time to resize pizzas: 1.0799999999999272ms
main.js:468 Time to resize pizzas: 1.1200000000008004ms
main.js:468 Time to resize pizzas: 1.3249999999989086ms
main.js:468 Time to resize pizzas: 0.8950000000004366ms
main.js:468 Time to resize pizzas: 1.25ms
main.js:468 Time to resize pizzas: 1.2549999999973807ms
```
- The forced synchronous layouts from `.offset` are now gone, and the render times have improved: ![Image of FIX11 TIMELINE](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Fix11_Results.png)
- Zooming in we can see how much quicker things are now and again without the FSL: ![](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Fix11_Results_Zoom.png)

10:05 PM

- ## What's Next**
- The performance rubric taget times have been met and/or exceeded for scrolling and slider actions.
- Some media queries could be built in to better scale the page for various pagewidths, minimally 400 px and maybe 800 px or so could be added in
- The slide starts off in the middle position, indicating "medium" pizzas,  but "Large" is written on the screen, and Large pIzzas are shown, the slider button really needs to be on the far right position for Large.
- I think next I will take one last look at the comments in the source files, and make improvements as needed,
- Then I will jsHint, jsBeautify and minify files,
- Will create new gh-pages in repository, so that this can be run direcctly from the repo
- Then I will turn this prohect in for review.

**Saturday June 25, 2016**

9:45 AM

- **FIX 12: GRID BOX not Wrapping**
- Grid Box would not wrap all the 100`randomPizzaContainer` elements
- Changed style from 33.33% to `width = 375px;`, in index.html file and main,js File
- This allowed the wrapping response to work from bootstrap-grid.js
- For even more control over the Grid Wrap see [Cool Bootstrap Grid Examples](http://www.minimit.com/articles/solutions-tutorials/bootstrap-3-responsive-centered-columns)

10:47 AM
- **Final Steps before Review Submission**
- Changed pizzeria.jpg to [open source file](https://upload.wikimedia.org/wikipedia/commons/4/43/Pizza_al_taglio.jpg)
- TODO: Stiil an error in init of slider, MEDIUM Label, but Large Pizza Image and slider position, and updates to proper settings after first use of slider
- [jsbeautifier](http://jsbeautifier.org/) on main.js
- [jshint](http://jshint.com/) on main.js
- [csslint](http://csslint.net/) no errors no warnings on style.css
- [css beautify & minify](http://codebeautify.org/css-beautify-minify) on style.css and created style.min.css
- [js minify](https://javascript-minifier.com/) on main.js to main.min.js
- [html beautify](http://www.cleancss.com/html-beautify/) on pizza.html
- [css beautify & minify](http://codebeautify.org/css-beautify-minify) on bootstrap.grid.css to bootstrap.grid.min.css
- [csslint](http://csslint.net/) showed warnings in above file, made two changes, ignored the rest
- updated pizza.html to reference minified files
- OK... so I am PAST DUE for using a task runner like Grunt or Gulp for this

1:43 PM

- **Github gh-pages recreated**
- [See pizza.html in action](http://geosynchronous.github.io/P6-Mobile-Portfolio/views/pizza.html)
- The scrolling & sliding performance works well as before, though the loading of the page could use some work, but it is not part of this project on pizza.html: ![Timeline Loading](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Timeline_Loading.png)
- (index.html in the first part of this project, had requirements to fix loading)
- At beginning and end of pizza.html optimization Pagespeed Insights reveals:
```
Started @   Mobile User Exerience 72 (yellow) & Speed 82 (green) and User Experience 92 (green)
Ended @     Mobile User Exerience 77 (yellow) & Speed 83 (green) and User Experience 100 (green)
```
-  All the ratings increased, though again page loading optimization is still needed to make this page really sweet

2:49 PM

- **BROWSER & DEVICE Results**
- On mobile safari and chrome, on iphone 5s & iPad2, the page only renders to the first two pizza and the slider does not function...
- On my i5 Macbook Pro, Safari acts just like on the mobile devices, and then everthing seems to work on Chrome, Canary, Firefox and Opera.
- These results do not worry me as the intent of the project was Performance Optimization, not Browser Optimization

2:56 PM
- **PRESENT CONCLUSION**
- I really learned a lot about how to use Chrome Dev Tools, and am beginning to understand Performance Optimizations.  What I learned most so far is that Front End Web Development is a humbling BLACK HOLE for developer time...


### Udacity Reviews

**Saturday June 25, 2016**

3:04 PM

- **Project Submitted and Received by UDACITY**

6:10 PM

- **Project Reviewed**
- Returned within a half hour
- [First Project Review Here](https://review.udacity.com/#!/reviews/171397)
- One required change before resubmitting
- Twelve others suggested
- Will work on all 13 changes one at a time

### Coursework Activity Log (continued)

8:18 PM

- ** Working Backwards**
- THe one change I need to make change the original UI/UX
- I need to restore that look and feel
- FIX 13 revert back to original 33.33% from 375 px in pizza.html and main.js
- FIX 14 BRAND NEW UPDATE FROM UDACITY REPO: replaced col-md-6 with 33 and 35% in two main.js locations and four html locations to fix incorrect PIZZA SIZE
-PROBLEM!

9:12 PM

- FIX15 removed .ing-responsive from style.css to return to orignal settings
- FIX16 restored `determineDX` and `changePizzaSizes` back to original Udacity Repo Code
- Also edited html text to keep pizza desciptor word lenght within original limits
- **UI/UX RESTORED** by FIXES 13-16
- **This was the only change that was a required fix**
- So now I will need to reoptimize this and tend to the other 12 suggested changes
- **MORE THAN EVER, I REALLY WANT TO KNOW HOW TO USE GITHUB BETTER**
- Reverting commits or forking would probably have been a lot easier, plus I had to install a recent UDACITY FIX with cut and paste, being able to PULL(?) the change woud be awesome... lot to learn here...

10:05 PM

- **Timing API STATS**
- The scolling stats are still intack, less than 1 ms, no surprise, didn't rehash that code
- The sliding stats to resize the pizzas are back up around 150 ms... right back where we started as the original code for that functtionality has been restated.
- Too tired right now to redo the resize pizza code, but there are plenty of the 12 simple suggested changes that I can make right now...
- BTW the TIMELINE GRAPHS for resize pizzas are just as ugly as they were when I first started this project

10:28 PM

- **FIX17: Replaced Web API**
- First suggested change to main.js
- replaced 3 occurances of`querySelector()` with `getElementById()` in the `changeSizeLabel()`
- didn't break it, the labels still appear when the slider is changed
- it may have helped speed up resize data, 25 ms  (should have done better sampling)

10:44 PM

- **FIX18: Replaced Web API**
- Second suggested change to main.js
- replaced 3 occurances of`querySelector()` with `getElementByClassName()` in the `changePizzaSizes()`
- didn't break it, the pizzas still resize
- it may have helped speed up resize data, 25 ms  (should have done better sampling)

11:04 PM

- **FIX19: JS Web API Out of Loop**
- THird suggested change to main.js
- In `changePizzaSizes` stored value of JS WEB API in var len
```
    var len = document.getElementsByClassName("randomPizzaContainer").length;
    for (var i = 0; i < len; i++) {
```
` seems to work, may have improve resize data by 10 ms

11:14 PM

- **Skipping 4th Main.js Change for Now that is required**
- it was previously set back to the original as requested in Fixes 13-16
- it will require a bit of refactoring
- besides I want to see what perf boost will come from the other suggested changes

11:25 PM

- **FIX20: JS Web API Out of Loop**
- Fifth suggested review change, in main.js
```
 // FIX20 declared var outside loop, only call JS WEB API once
var pizzasDiv = document.getElementById("randomPizzas");
for (var i = 2; i < 100; i++) {
    pizzasDiv.appendChild(pizzaElementGenerator(i));
}
```
- seems to work


11:42 PM
- **FIX21: JS Web API Out of Loop**
- Sixth suggested review change, in main.js
```
    var items = document.querySelectorAll('.mover');
    var cachedScrollTop = document.body.scrollTop;
    //FIX21 read length outside loop
    var len = items.length;

    for (var i = 0; i < len; i++) {
        var phase = Math.sin((cachedScrollTop / 1250) + (i % 5));
```
- seems to work, scrolling perf is 0.5 ms or less

11:50 PM
- **FIX22: JS Web API Out of Loop**
- Seventh suggested review change, in main.js
```
    // FIX22 var declared outside loop
    var phase;

    for (var i = 0; i < len; i++) {
        phase = Math.sin((cachedScrollTop / 1250) + (i % 5));
```
**Sunday June 26, 2016**

10:31 PM

- **FIX23: Moving maxPizzasNeeded Code**
- Eighth suggested review change, in main.js

```
// Generates the sliding pizzas when the page loads.
document.addEventListener('DOMContentLoaded', function() {
    var cols = 8;
    var s = 256;
    // FIX 23
    // Determing an efficient upper limit for number of pizzas to render
    // Better than guessing, and/or setting value too high, as previous code did
    var rows = Math.trunc(window.screen.height / s);
    var maxPizzasNeeded = rows * cols;
    for (var i = 0; i < maxPizzasNeeded; i++) {
        var elem = document.createElement('img');
        elem.className = 'mover';
        elem.src = "images/pizza.png";
        elem.style.height = "100px";
        elem.style.width = "73.333px";
        elem.basicLeft = (i % cols) * s;
        elem.style.top = (Math.floor(i / cols) * s) + 'px';
        document.querySelector("#movingPizzas1").appendChild(elem);
    }
```
- works well
- for continued reference, TIMING API logs:

```
Average time to generate last 10 frames: 0.40300000002025627ms
main.js:563 Average time to generate last 10 frames: 0.5059999999997672ms
main.js:563 Average time to generate last 10 frames: 0.3680000000167638ms
main.js:563 Average time to generate last 10 frames: 0.34999999999417925ms
main.js:563 Average time to generate last 10 frames: 0.39099999999743884ms
main.js:563 Average time to generate last 10 frames: 0.3695000000006985ms
main.js:563 Average time to generate last 10 frames: 0.3724999999976717ms

Time to generate pizzas on load: 35.97999999999999ms
main.js:534 Time to resize pizzas: 128.70499999999993ms
main.js:534 Time to resize pizzas: 129.73499999999967ms
main.js:534 Time to resize pizzas: 122.10500000000047ms
main.js:534 Time to resize pizzas: 112.95000000000073ms
main.js:534 Time to resize pizzas: 136.71000000000004ms
main.js:534 Time to resize pizzas: 120.67500000000018ms
main.js:534 Time to resize pizzas: 106.55500000000029ms
```

11:06 AM

- **FIX24: More efficient Moving Pizza Load**
- Ninth suggested review change, in main.js
- Moved some vars out of loop etc...

```
    // FIX24
    // Declared var elem outside loop
    // Declared Pizza ID outside loop and used getElementById
    var elem;
    var movingPizzaId = document.getElementById("movingPizzas1");
    for (var i = 0; i < maxPizzasNeeded; i++) {
        elem = document.createElement('img');
        elem.className = 'mover';
        elem.src = "images/pizza.png";
        elem.style.height = "100px";
        elem.style.width = "73.333px";
        elem.basicLeft = (i % cols) * s;
        elem.style.top = (Math.floor(i / cols) * s) + 'px';
        movingPizzaId.appendChild(elem);
    }
```

- Seems to work, no noticable Timing API changes
- May effect initial load: ![Iamge of FIX24 Load TImeline](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/FIX24_Timeline.png)
- compare previous results to present, some render pipeline times have improved the perf some, and resturctured the events, notice how more HTML parsing is occuring earlier in the pipeline
- line 585 is causing a recalulate style and layout, both with forced reflow warnings: `var cachedScrollTop = document.body.scrollTop;`
- notice a maybe slight possible increase `Time to generate pizzas on load: 33.41500000000001ms`, but not sure

1:47 PM

- **TODO**
- Is there a replacement for `document.body.scrollTop` that doesn't FSL???
- It is causing FSL as indicated in the previous entry
- I could not find one after a bit of searching and playing around with code

1:50 PM

- **FIX25 Moved var out of loop**
```
    //FIX 25 var array declared outside loop
    var cachedBasicLeft;

    for (var i = 0; i < len; i++) {
        phase = Math.sin((cachedScrollTop / 1250) + (i % 5));

        // READ Style
        cachedBasicLeft = items[i].basicLeft;
        // WRITE Style
        items[i].style.left = cachedBasicLeft + 100 * phase + 'px';
    }
```
- The pipeline for loading looks a little tighter: ![Image of FIX25 Timeline](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/FIX25_Timeline.png)
- The Timing Stats look like this:
```
Time to generate pizzas on load: 33.965ms
main.js:563 Average time to generate last 10 frames: 4.663000000000018ms
main.js:563 Average time to generate last 10 frames: 0.6040000000000191ms
main.js:563 Average time to generate last 10 frames: 0.5050000000000182ms
main.js:563 Average time to generate last 10 frames: 0.4690000000000964ms
main.js:563 Average time to generate last 10 frames: 0.4579999999998563ms
main.js:563 Average time to generate last 10 frames: 0.4075000000000273ms
main.js:563 Average time to generate last 10 frames: 0.4115000000001146ms
main.js:563 Average time to generate last 10 frames: 0.5010000000000673ms
main.js:563 Average time to generate last 10 frames: 0.41249999999990905ms
main.js:563 Average time to generate last 10 frames: 0.43700000000008005ms
main.js:534 Time to resize pizzas: 95.95999999999913ms
main.js:534 Time to resize pizzas: 112.21499999999651ms
main.js:534 Time to resize pizzas: 113.55999999999767ms
main.js:534 Time to resize pizzas: 127.52999999999884ms
main.js:534 Time to resize pizzas: 123.54999999998836ms
main.js:534 Time to resize pizzas: 126.72000000000116ms
```

5:21 PM

- **FIX26-28 Remove FSL and JANK on Load**
- THe problem with document.body.scrollTop causing FSL on load is gone
- THe problem with JANK on Load seems to be gone
- FIX26 - Added `defer` to script for main.js in pizza.html, this makes the CRP better, though the main.js could probably use some refactoring andf maybe Web Workers to make it load faster, all 100 pizzas don't need to be delivered in the first stage of loading to the DOM, they could be split up
- FIX27 - removed an uneeded occurance of updatePositions;
- FIX28 - Moved eventListener for Scroll to bottom of main.js
- The timeline looks a lot cleaner on load, with no warnings: ![Image of FIX26-28 Timeline](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Fix26-28.png)
- THis really has not effected the scrolling and sliding TIming API stats much:
```
main.js:550 Time to generate pizzas on load: 31.825000000000003ms
main.js:563 Average time to generate last 10 frames: 0.6735000000000426ms
main.js:563 Average time to generate last 10 frames: 0.800000000000091ms
main.js:563 Average time to generate last 10 frames: 0.6645000000000436ms
main.js:563 Average time to generate last 10 frames: 0.6230000000001382ms
main.js:563 Average time to generate last 10 frames: 0.5985000000000582ms
main.js:563 Average time to generate last 10 frames: 0.4780000000002474ms
main.js:563 Average time to generate last 10 frames: 0.5354999999999563ms
main.js:563 Average time to generate last 10 frames: 0.47050000000053843ms
main.js:563 Average time to generate last 10 frames: 0.5090000000001964ms
main.js:563 Average time to generate last 10 frames: 0.5780000000002474ms
main.js:563 Average time to generate last 10 frames: 0.5365000000001601ms
main.js:563 Average time to generate last 10 frames: 0.5654999999998835ms
main.js:563 Average time to generate last 10 frames: 0.5035000000001674ms
main.js:563 Average time to generate last 10 frames: 0.5780000000000655ms
main.js:534 Time to resize pizzas: 86.46000000000095ms
main.js:534 Time to resize pizzas: 101.68000000000029ms
main.js:534 Time to resize pizzas: 111.71000000000095ms
main.js:534 Time to resize pizzas: 131.5899999999965ms
```

9:32 PM
- **FIX29 Refactor changePizzaSize & determineDx**
```
  function determineDx (elem, size) {
    var oldWidth = elem[0].offsetWidth;         // FIX29 elem[0] refactor
    var windowWidth = document.querySelector("#randomPizzas").offsetWidth;
    var oldSize = oldWidth / windowWidth;

    // Changes the slider value to a percent width
    function sizeSwitcher (size) {
      switch(size) {
        case "1":
          return 0.25;
        case "2":
          return 0.3333;
        case "3":
          return 0.5;
        default:
          console.log("bug in sizeSwitcher");
      }
    }
    var newSize = sizeSwitcher(size);
    var dx = (newSize - oldSize) * windowWidth;
    return dx;
  }

  // Iterates through pizza elements on the page and changes their widths
  // FIX18 Replace all querySelectors() with getElementsByClassName()
  function changePizzaSizes(size) {
    // FIX 19 stored length as var len and took out of for loop
    // *.length only called once now
    var len = document.getElementsByClassName("randomPizzaContainer").length;
    // FIX29
    // Moved dx and newWidth out of the loop
    // All values are the same, so elem[0] is all that is needed
    // Refactored with the array var elem
    // READ outside of loop
    // WRITE inside of loop
    var elem = document.querySelectorAll(".randomPizzaContainer");
    var dx = determineDx(elem, size);
    var newWidth = (elem[0].offsetWidth + dx) + 'px';

    for (var i = 0; i < len; i++) {
      elem[i].style.width = newWidth;
    }
  }
  ```
  - This refactor greatly improved the resize pizzas performance now the results are 2 ms or less for the Timing API results: ![Image of FIX29 Timeline](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/FIX29.png)
  - In determineDx the `var oldWidth = elem[0].offsetWidth;` is triggering an FSL
  - The rendering pipeline is looking good
  - The 5 ms or less requirement is now again met and exceeded

  11:03 PM
  
  - **FIX30 Change to getElementById**
` var windowWidth = document.getElementById("randomPizzas").offsetWidth;  //FIX30 change to getElem...`
- Timing results are about the same in FIX30 above
- THe `offsetWidth` is causing FSL
- TODO find a work around fot .offsetWidth

11:49 PM

- **FIX31 CSS and Comment Changes**
- added padding around pizzeria.jpg
- added vendor prefixes

**Monday June 27, 2016**

3:07 PM

- **FIX32 Refactored items[] to mover[]**
- `items[]` only needed to be loaded once, renamed refactor to `mover[]`, see code for specific changes:
```
function updatePositions() {

    // Fix 2 (NEW continued):
    var requestID = requestAnimationFrame(updatePositions);

    frame++;
    window.performance.mark("mark_start_frame");

    //FX32
    // NO LONGER NEEDED: var items = document.querySelectorAll('.mover');
    // Occurance of var "items" replaced with "mover"
    // Create only once mover[] after DomContentLoaded
    // (See DOMContentLoaded below for more changes)

    var cachedScrollTop = document.body.scrollTop;
    // FIX21 read length outside loop
    var len = mover.length;
    // FIX22 var declared outside loop
    var phase;
    //FIX 25 var array declared outside loop
    var cachedBasicLeft;

    for (var i = 0; i < len; i++) {
        phase = Math.sin((cachedScrollTop / 1250) + (i % 5));

        // READ Style
        cachedBasicLeft = mover[i].basicLeft;
        // WRITE Style
        mover[i].style.left = cachedBasicLeft + 100 * phase + 'px';
    }

    // User Timing API to the rescue again. Seriously, it's worth learning.
    // Super easy to create custom metrics.
    window.performance.mark("mark_end_frame");
    window.performance.measure("measure_frame_duration", "mark_start_frame", "mark_end_frame");
    if (frame % 10 === 0) {
        var timesToUpdatePosition = window.performance.getEntriesByName("measure_frame_duration");
        logAverageFrame(timesToUpdatePosition);
    }
    // Fix2 (NEW continues):
    cancelAnimationFrame(requestID);

}

// FIX32 (continued)
var mover =[];
// Generates the sliding pizzas when the page loads.
document.addEventListener('DOMContentLoaded', function() {
    var cols = 8;
    var s = 256;
    // FIX 23
    // Determing an efficient upper limit for number of pizzas to render
    // Better than guessing, and/or setting value too high, as previous code did
    var rows = Math.trunc(window.screen.height / s);
    var maxPizzasNeeded = rows * cols;
    // FIX24
    // Declared var elem outside loop
    // Declared Pizza ID outside loop and used getElementById
    var elem;
    var movingPizzaId = document.getElementById("movingPizzas1");
    for (var i = 0; i < maxPizzasNeeded; i++) {
        elem = document.createElement('img');
        elem.className = 'mover';
        elem.src = "images/pizza.png";
        elem.style.height = "100px";
        elem.style.width = "73.333px";
        elem.basicLeft = (i % cols) * s;
        elem.style.top = (Math.floor(i / cols) * s) + 'px';
        movingPizzaId.appendChild(elem);
    }
    // FIX32 (continued)
    mover = document.querySelectorAll('.mover');

    // FIX27
    //This is not needed here, removing got rid of FSL on load
    // updatePositions();
});
```
- The TIMIMG API shows improved results, and the render pipeline looks good: ![IMAGE OF FIX32 Timeline](https://github.com/Geosynchronous/P6-Mobile-Portfolio/blob/master/timelines/Fix32.png)
- The following [UDACITY FEND LINK](https://github.com/udacity/fend-office-hours/tree/master/Web%20Optimization/Effective%20Optimizations%20for%2060%20FPS) that was just provided in the review feedback helped enormously in locating this fix.







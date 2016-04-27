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

### Activity Log
The prime purpose of this log is to que Udacity Reviewers in on my incremental observations and changes to make their job a bit easier.

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

https://discussions.udacity.com/t/crp-diagrams-any-site/25810/44?u=george_3439977859158

### Udacity Reviews

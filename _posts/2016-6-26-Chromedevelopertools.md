**The Chrome Developer Tools(DevTools)** are a set of web authoring and debugging tools built into Googgle Chrome. The DevTools provide developers deep access into the internals of the browser and their web application. The DevTools are used to effectively track down layout issues, set JavaScript breakpoints and get insights for code optimization.

## Accessing the DevTools

Open your web page or web app using Google Chrome. Select the Chrome menu at the top right corner of your browser. Select _More Tools > Developer Tools_. Otherwise you can use powerful shortcuts to open the DevTools.

* `Ctrl` + `Shift` + `i` to open the DevTools from where you can navigate to other tabs like the *Console*, *Elements*, *Sources*, *Network*, *Timeline* etc

### The DevTools Window

The DevTools are organised into task-oriented groups in the toolbar at the top of the window. Each toolbar item and corresponding panel let you work with a specific type of page or app information, including DOM elements, resources, and sources. 
![DevTools window](https://developer.chrome.com/devtools/images/devtools-window.png)

Overall, there are eight main groups of tools available in Developer Tools:
* Elements
* Resources
* Network
* Sources
* Timeline
* Profiles
* Audits
* Console

#### Inspecting the DOM and styles

The **Elements** panel lets you view structured information about the current page. In today's applications, the HTML markup served on an initial page load is not necessarily what you'll see in the Document Object Model ([DOM](http://docs.webplatform.org/wiki/dom)) tree. Having a real-time representation of the page can be a powerful tool when debugging and authoring web pages.

##### DOM

The DOM tree view displays the DOM structure of the current web page. The DOM tree is a tree of DOM nodes that represent individual HTML elements, such as <body> and <p>. For ease of reading, the DOM tree view displays the HTML element tags instead of the DOM node types: for example, <p> instead of HTMLParagraphElement.

#### Inspecting Elements

![#](https://developer.chrome.com/devtools/docs/dom-and-styles#inspecting-elements)

Simply right-click the content and select `Inspect` from the drop-down command prompt.

[Read more about inspecting the DOM and styles](https://developer.chrome.com/devtools/docs/dom-and-styles)



#### Working with the Console

Utilizing the console gives you the ability to:

- Log diagnostic information to help debug your web page or application.
- Enter commands that interact with the document and the Chrome DevTools.

To open the console, hit `Ctrl` + `Shift` + `i`

[Here](https://developer.chrome.com/devtools/docs/console) is a resource that expounds on how to work with the console.


#### Debugging JavaScript

![#](https://developer.chrome.com/devtools/images/js-debugging.png)

As the **complexity** of JavaScript applications increase, developers need powerful debugging tools to help quickly discover the cause of an issue and fix it efficiently. The Chrome DevTools include a number of useful tools to help make **debugging** JavaScript less painful.

The Sources Panel[#](https://developer.chrome.com/devtools/docs/javascript-debugging/javascript-debugging-overview.jpg)

The Sources panel lets you debug your JavaScript code. It provides a graphical interface to the V8 debugger. Follow the steps below to explore the Sources panel:

* Open a site such as the Google Closure hovercard demo page or the TodoMVC Angular app.
* Open the DevTools window.
* If it is not already selected, select Sources.

Click [Debugging JavaScript](https://developer.chrome.com/devtools/docs/javascript-debugging) to learn more.


#### Improving network performance

The Network panel provides insights into resources that are requested and downloaded over the network in real time. Identifying and addressing those requests taking longer than expected is an essential step in optimizing your page.

![Network panel](https://developer.chrome.com/devtools/images/network-panel.png)

This [link](https://developer.chrome.com/devtools/docs/network) provides a comprehensive coverage on how to improve network performance.


#### Audits

The Audit panel can analyze a page as it loads. Then provides suggestions and optimizations for decreasing page load time and increase perceived (and real) responsiveness. For further insight, we recommend using [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/).

![Audit](https://developer.chrome.com/devtools/images/audits-panel.png) panel


#### Improving rendering performance

The **Timeline** panel gives you a complete overview of where time is spent when loading and using your web app or page. All events, from loading resources to parsing JavaScript, calculating styles, and repainting are plotted on a timeline.

![Timeline](https://developer.chrome.com/devtools/images/timeline-panel.png) panel

[Here](https://developer.chrome.com/devtools/docs/timeline) is a useful [link](https://developer.chrome.com/devtools/docs/timeline) to read more on how to improve rendering performance.


#### JavaScript & CSS performance

The Profiles panel lets you profile the execution time and memory usage of a web app or page. These help you to understand where resources are being spent, and so help you to optimize your code. The provided profilers are:

* The CPU profiler shows where execution time is spent in your page's JavaScript functions.
* The Heap profiler shows memory distribution by your page's JavaScript objects and related DOM nodes.
* The JavaScript profile shows where execution time is spent in your scripts

![Profile panel](https://developer.chrome.com/devtools/images/profiles-panel.png)

[Read more about using how to improve JavaScript and CSS performance »](https://developers.google.com/web/tools/chrome-devtools/)


#### Inspecting storage

The Resources panel lets you inspect resources that are loaded in the inspected page. It lets you interact with HTML5 Database, Local Storage, Cookies, AppCache, etc.

![Resources](https://developer.chrome.com/devtools/images/resources-panel.png) panel

[Read more about inspecting storage resources »](https://developer.chrome.com/devtools/docs/resource-panel)
# 🌐 Intro to the web 🌐


## 📚 Learning Goals 📚
- Differentiate between a static and dynamic website
- Differentiate between the front-end and the back-end of a web application
- Understand relationship between clients and servers
- Be aware of web standards & browser compatibility



## Static vs Dynamic websites

Most modern sites are dynamic. You are interacting with **a dynamic website** every time you sign-in to a site and are given custom content based on your preferences, like who you follow. These sites have logic that is involved in serving content, thus requiring the use of programming languages like ruby, python or PHP.
Common Examples: Facebook, Gmail and Medium

**A static site** presents the same content to every visitor. Everybody that visits the site will be given the same content. The content will rarely change, and if it does, it is typically by only one or few people manually. These sites will only use HTML, CSS and possibly basic JavaScript.
 Common Examples: restaurants, small business and individual's portfolio sites.


### ACTIVITY: Static vs Dynamic
With each site listed below, answer the following questions:
Is the site most likely static or dynamic?
What makes these sites static or dynamic?

- [Space Jam](http://www.warnerbros.com/archive/spacejam/movie/jam.htm)
- [Twitter](http://www.twitter.com)
- [Medium](https://medium.com/)
- [Awwwards](http://www.awwwards.com/)
- [Molamil Business Site](http://www.molamil.com/frontpage)


## Front-end vs Back-end

Web applications are dynamic websites that can be broken down into two main parts, the front-end and the back-end.

**Front-end** refers to everything that a user actually sees on the website, in the browser (and is often called "client-side"). It is responsible for organizing and styling the content to make it easier for users to interact with. Front-end languages include HTML, CSS and JavaScript.

**Back-end** refers to "the brains", or logic, of a web application. This code remains "server-side" and often interacts with a database. The back-end utilizes programming languages such as ruby, python, PHP, java or JavaScript.

**Example:** When ordering lunch from Grubhub, All the content you see is being organized and styled with front-end code. When you order items from a restaurant, the back-end is calculating your total based on the items you selected, any deals based on your total cost and the delivery fee for your area.

The back-end is responsible for a lot of other things like showing you all the restaurants that deliver to your area, alerting the restaurant about your order and sending you texts on the status of your delivery.


**Fun-Fact:** You may hear the phrase 'full-stack developer' thrown around. A full-stack developer is familiar with and prefers to work on both the front-end and back-end of a web application.


## How the Internet Works

In order for us to access a website,  it's files need to be stored on a computer that is constantly online. This computer is known as a [web server](https://www.cloudyn.com/blog/10-facts-didnt-know-server-farms/).

![HTTP Response and Request](https://mdn.mozillademos.org/files/8659/web-server.svg)

 A **web server** uses a protocol called HTTP to take requests from 'clients'. For example, when you type in 'google.com', your browser (the client), will make a request to google's servers. Google's servers will find the files based on the request and send them back to the client, the browser.

 ![How Information Travels on the Web](imgs/netdiag.gif)

### Learn more about how the internet Works
Of course there is _a lot_ more to how the internet works, but that is enough surface level information to guide us through this unit! If you're aching to learn more, the links below are great resources to start:  

 - [How the Internet Works in 5 Minutes Video](https://www.youtube.com/watch?v=7_LPdttKXPc)
 - [How the Internet Works Khan Academy Course](https://www.khanacademy.org/partner-content/code-org/internet-works)

## Browser Compatibility

The internet has changed a lot since Sir Tim Berners Lee made the first [web page](http://info.cern.ch/) in 1991. In turn, HTML and CSS have evolved from when they were first used in the 90's. As these front-end languages evolve, browsers need to evolve with them.

The current versions of browsers we are using right now  understand HTML5 and CSS3, which utilize the newest web development standards we will be learning.

Be aware that some older browsers do not understand the newest versions of HTML or CSS. One day you many need to develop a site that needs to be accessed by a demographic that is using older technology. Your site may break, or look a lot different on those computer's browsers.

There are also many different browsers (Safari, Internet Explorer, Chrome, Firefox etc). A browser's job is to translate the code that will be displayed. Each browser does this a little bit differently. To ensure a site is widely accessible, developers use browser [compatibility tools](http://www.catswhocode.com/blog/15-techniques-and-tools-for-cross-browser-css-coding).

As we begin learning about HTML and CSS, we are not going to be concerned about our sites' browser compatibility. Instead we are only going to focus on developing with the most recent version of [Chrome](https://www.google.com/chrome/).  


## Vocab ✅
  - Web application
  - Static
  - Dynamic
  - Front-end
  - Back-end
  - Client
  - Server


## 🔑 Key Takeaway
This week we will be focusing on creating static sites with front-end languages, HTML and CSS. In order to view the sites we create on the internet, we have to store them on a web server.

### Additional Resources

- [MDN What is a Web Server](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_web_server) (Highly Recommended)
- [Front-end vs Backend Udacity Article](http://blog.udacity.com/2014/12/front-end-vs-back-end-vs-full-stack-web-developers.html)
- [Static vs Dynamic Websites](http://www.codeconquest.com/website/static-vs-dynamic-websites/)

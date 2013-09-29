flowtest
========

Flow test for prototypical discussion system for Wikimedia


Ideas & Notes
=======
For this project I implemented jQuery primarily, but also had to test out the AJAX via a PHP pipe. Due to the Single Origin Policy I got a 200 response from discussion.json but the browser wouldn't go through with the GET request. 

Threaded discussions should "flow" just like the title of your prototype says. Discussions happen fluidly, so a fluid design is what I would go for to facilitate that. As an example of this, I have the Reply button pop up as text on hovering over a thread so that as users are scrolling through they naturally see the Reply button. 

Time & Further Ideas
=======

I did spend about 3 hours on this. This was partly due to the AJAX SOP error mentioned above and trying to find a way around it. Eventually I just copied and pasted the JSON into the code for faster testing. If I had more time, I would experiment with JSONP and ways around the issue, possibly creating Node.js or PHP code to act as a pipe.

Design - there are always areas for improvement. Colorful backgrounds coupled with responsively scaled images would help a lot to entice users to stay on the page.

Functionality - Having a working reply form that also did POST requests to the main JSON server to save the data would be better. Using a backend like Ruby on Rails or your CMS would be optimal, and the Javascript would act as a kind of JSON filter and parsers on top of that engine. 

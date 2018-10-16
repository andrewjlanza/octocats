![](https://i.imgur.com/XS2isCi.png)
Above is a screenshot of my app. 


As a recreation of a previous assignment where I was tasked with using just CSS and HTML in an attempt to mirror the github Octocat index webpage, I had to use React and "Reactify" the assignment by using javascript inside React. 

"Reactifying" a page is the process of taking javascript elements from the app (inside App.js) and breaking them into components to organize the app's code, in addition to making it easier to edit pieces of the app in the future if needed.

For this process, you must give these components values by passing them props, which are properties inside the library React. 

I have the component "Gallery.js", which is where all of the Octocat numbers, names, name links, images, and links to authors are. These are essentially all of the content on the webpage, minus the header and footer, which both are separate, individual components. I then use the "Octocat.js" component I have to dynamically import the data from the "Gallery.js" component, which allows me to put all of the Octocat info listed above into a display template that reads something like : 


-Octocat image- 

(number) the -insert cat name- by -insert author avatar image-

-image footer of a 1px line separating the Octocat sections-


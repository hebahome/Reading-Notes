![](https://www.chartjs.org/img/chartjs-logo.svg)
#  EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS


## Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

## Chart.js


# Installation
You can get the latest version of Chart.js from npm , the GitHub releases , or use a Chart.js CDN . Detailed installation instructions can be found on the installation page.

# Creating a Chart
It's easy to get started with Chart.js. All that's required is the script included in your page along with a single <canvas> node to render the chart.

- In this example, we create a bar chart for a single dataset and render that in our page. You can see all the ways to use Chart.js in the usage documentation.


# Contributing

Before submitting an issue or a pull request to the project, please take a moment to look over the contributing guidelines first.

For support using Chart.js, please post questions with the chartjs tag on Stack Overflow .

# License
### Chart.js is available under the MIT license .

# Canvas

![Canvas ](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRjl6vC4xS-5TXF32ArAZ9kA-rhgk2tBW5wgQ&usqp=CAU)

### At first sight a  looks like the  element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the  element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.



>Note: If your renderings seem distorted, try specifying your width and height attributes explicitly in the canvas attributes, and not using CSS.



### The id attribute isn't specific to the canvas element but is one of the global HTML attributes which can be applied to any HTML element (like class for instance). It is always a good idea to supply an id because this makes it much easier to identify it in a script.

### The canvas element can be styled just like any normal image (margin, border, background…). These rules, however, don't affect the actual drawing on the canvas.


 > Providing fallback content is very straightforward: just insert the alternate content inside the canvas element. Browsers that don't support canvas will ignore the content inside the container, and just render the canvas normally. 



 ## The rendering context

- The canvas element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering context. Other contexts may provide different types of rendering; for example, WebGL uses a 3D context based on OpenGL ES.

- The canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it. The canvas element has a method called getContext(), used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context. For 2D graphics, such as those covered by this tutorial, you specify "2d" to get a CanvasRenderingContext2D.



- ### And You can complete mastering the Canvas from [Here ](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)




[Learn more ](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
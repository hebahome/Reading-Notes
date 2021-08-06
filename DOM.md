

# DOM 


> “First, solve the problem. Then, write the code.” John Johnson






![](https://www.tutorialstonight.com/assets/js/dom-tutorial.webp)


## . The Document Object Model is a model that defines HTML and XML documents as a tree structure, where each node of the tree is an object which represents a part of the document.

##  . The DOM acts as an interface between document and Javascript. Using DOM + Javascript developers can access and modify each and every element of the document using DOM.

##  . See in the picture below, the document has represented a tree where 'html', 'body' etc are the branch that ends with a node like 'p', 'li', 'td', etc.


### The DOM has a hierarchical structure. The lower elements are children of upper connected elements and side elements having the same parents are called siblings.

![](https://www.tutorialrepublic.com/lib/images/html-dom-illustration.png)




## HTML DOM

## When a webpage is loaded the browser creates a Document Object Model, which is an object-oriented representation of HTML document. The Node of document organised in the tree structure is called the Document Object Model.

## Every HTML element in the document is an object. The text inside the elements is also an object as well.

## You can see in the above image (in HTML DOM tree) how elements are structured in the HTML document in form of the tree structure, where each branch of tree ends with a node, which contains objects.



* ##  Nodes In HTML DOM

![](https://www.tutorialstonight.com/assets/js/html-dom-node-type.webp)

 1. ### Element Nodes - Element nodes are themselves called objects in DOM. It comprises most of the DOM which holds other data like text and attributes. Example p, h1, h2, ul, li etc. The element nodes may have other elements nested inside it which are known as children of that element.



2. ### Attribute Nodes - Attribute nodes are attached to the element node and add extra information to the element. Example title attribute, class attribute etc.
3. ### Text Node - Text nodes are contents of the elements and have no children like element nodes.


* ## Difference Between Node And Element

Node is a generic name for any type of object in the DOM. A node can be any object within the document, like any element, attribute, text etc.


Whereas an element is a node with a specific node type, which is equal to one.

Every element is a node in DOM but every node is not an element.

- ## Accessing DOM Elements

### Nodes in HTML DOM are accessed by using javascript.
There are many DOM access methods using which you can access HTML elements, example - getElementById("id1"). We will discuss more of these methods later in the chapters.


### Let's see what we can do with these elements using javascript :

1. Javascript can change and add nodes in the DOM
Javascript can add or change style (CSS) of the DOM element
2. Javascript can set new attributes to the DOM element and can remove and modify older attributes
3. Javascript can add new element in the DOM structure
 4. Javascript can create and add events to the DOM element
 5. Javascript can delete elements from the DOM tree
Visualising Elements in DOM Tree
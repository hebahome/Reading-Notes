![Creating links Between Pages by HYML ](https://community-cdn-digitalocean-com.global.ssl.fastly.net/variants/K22rBJbMUGkCPLZq2YTtGeNM/035575f2985fe451d86e717d73691e533a1a00545d7230900ed786341dc3c882)


## When building a website, you may want to have more than one webpage. If you want to add and link to additional pages, you’ll need to first create a new html file in your website project directory. In this tutorial, we’ll learn how to create and link to an additional webpage on your website



## Our demonstration website includes an “About” webpage. In this tutorial, we’ll walk you through the process of creating and linking to an “About” webpage, but you may change the title and the content of this page to fit your needs.

## To add a new page to your website, create a new file named about.html and save it in your project directory html-practice.

## Make sure to change the highlighted text with a title you want for you page. For an explanation of each of the HTML tags, please visit the earlier tutorial in this series Adding an HTML <head> Element To Your Webpage. Save the file before you continue.

## Before adding any content to this page, let’s walk through the steps of adding a link to this page on your homepage.

## First, return to your index.html file and add the following snippet below the subtitle of your site and above the closing </div> tag:
...
## Change the highlighted file path to the relative file path of your “about.html” file. The relative path refers to the file location relative to the current working directory (as opposed to the absolute path, which refers to the file location relative to the root directory.) If you are using the Visual Studio Code text editor, you can copy the relative file path by CTRL + Left Click (on Macs) or right-clicking' (on Windows) on the file icon and selectingCopy Relative Path.`

Note that we have also specified a font-size and color using the style attribute. Save your index.html file and reload it in the browser.


 ### You should now have a link that directs to your about.html web page like this:
 ![](https://assets.digitalocean.com/django_gunicorn_nginx_2004/articles/new_learners/added-link.png)




# How Web Pages Work


### Linking to Other Sites
One of the best parts about Web pages is the ability to create links to other pages on the Web. Using the following anchor tags, you can reference other people's work, point to other pages you like, etc:

<a href="URL">

Type in the title of the page after the anchor tag, and close the anchor with:

</a>

Example:

<a href="https://www.howstuffworks.com"> HowStuffWorks </a>



# HTML - Email Links

## It is not difficult to put an HTML email link on your webpage but it can cause unnecessary spamming problem for your email account. There are people, who can run programs to harvest these types of emails and later use them for spamming in various ways.

You can have another option to facilitate people to send you emails. One option could be to use HTML forms to collect user data and then use PHP or CGI script to send an email.

A simple example, check our Contact Us Form. We take user feedback using this form and then we are using one CGI program which is collecting this information and sending us email to the one given email ID.

# HTML Email Tag
HTML <a> tag provides you option to specify an email address to send an email. While using <a> tag as an email tag, you will use mailto: email address along with href attribute. Following is the syntax of using mailto instead of using http.

# How to Position HTML Elements Using CSS
### When it comes to positioning content on a page there is a handful properties to use that can help you manipulate the location of an element. This article will show you some examples containing different positioning element types using the CSS position property. To use positioning on an element, you must first declare its position property, which specifies the type of positioning method used for an element. Using the position property values, the elements are positioned using the top, bottom, left, and right properties. They also work differently depending on their position value.

There are five types of positioning values:

static
relative
fixed
absolute
sticky
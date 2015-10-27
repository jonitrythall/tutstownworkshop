# Tuts+ Town Workshop

## Getting Started: What is Web Design Exactly?
* Well, it’s tricky….it can mean a lot of different things and it’s not uncommon for 2 web designers to have few overlapping skillsets. 
* For example, while some designers are completely focused on a user’s experience of a site, others are tasked with actually building these designs with code, which is what we are going to focus on today.  

## How The Web Works
* Now, since we are going to build a website that will eventually be accessible through the Internet it’s helpful to have a general idea of how the web works. 
* When two computers are connected to the Internet (which is shown as a yellow line in the picture below) they can talk to each other.
* A server (the blue box) is a special computer that contains web page files. Your computer at home or school is not a server, because it is not connected directly to the Internet. We connect to the Internet through an Internet Service Provider (ISP).
* A site’s content (all that stuff a website talks about) is organized within a special set of rules that computers understand; sort of like speaking in a secret, coded language, except we will soon be in on this little secret as well!
* In this picture the browser is asking to view www.tutsplus.com from the server where the site’s files live. The server is sending the files back and the browser is translating them to display a page on the screen. And this happens very quickly!
* Because of all this, a site you write locally (on your computer) can’t be seen by other people on a different computer, until you move the files to a server. 

## Quick Note on Files 
* A website is just a bunch of connected files. 
* It’s essential that all the files for our project live in the same folder so that the browser can access them. 

## Folders: Our Structure (Let’s open up our folders!)
* For our website we have an HTML and CSS file with an images folder containing 4 images. 
* The “file extention” references to the descriptive letters that come after the period in a file name. 

## What is HTML and CSS?
* Hypertext markup language is a way of structuring a document in a way that the browser can understand. For example, we will learn that we can’t just type up a paragraph in our text editors and expect the browser to understand what it is; we have to put it in a paragraph element!
* Cascading style sheets is a separate document that allows us to style our HTML document by adding coloring and moving things around in a more appealing and usable way. 

## Linking These Two Files
* In order for our CSS to impact our HTML they have to be properly linked together, which you can see has already been done at the top of our HTML document. 

## HTML Intro: Syntax & Structure Basics
* This is what HTML looks like! 
* HTML is written with elements that have important meaning. All of our content has to live within the right elements in order to be understood by the browser, so creating a solid structure or foundation in our document is an excellent first step. 
* Most elements require both an opening and closing tag, with the content written within these tags. 

## HTML Intro: Planning a Structure 
* Once we know what we want to create we can start mapping out the site and building our structure with HTML. 
* Within the `<body>` element of the file we will have several additional elements to nest inside to prepare to add content into. 
* Nesting refers to the act of indenting when placing an element inside of another element; so the outer element contains the indented element, and so on. 

## HTML: Adding Content *(Longest Section)* 
* Containers. We heard about these briefly so far but we will be creating more and more containers as we nest more elements inside each other to include our content. 
* Full Preview: So while we previously added a header, main, and footer, we now need to further nest (or indent!) additional elements within these ones. 

### Header
* For example, within our header we need a heading and an image, requiring a heading and an image element. 
* We need to get “Welcome to Tuts+ Town” on the page, which is the website’s main heading.
* There are six different levels of headings for a site; `h1` is the most important, `h6` is the least important. In HTML the text for headings is written within heading elements:`<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, or `<h6>`.
* IMAGES: In our project’s folder we have an images folder. In order to include these images on our site we need to call on them through the `<img>` element and include a path to the particular image we want
* Within the opening tag of this element we will add an attribute that specifies where to get the image we want to include. Attributes are things we can add to elements which help further explain them, or tell them how to work. Only certain attributes work within certain elements. An `<img>` element will always have a src and an alt attribute.
* Important! An `<img>` element is self-closing. This just means that the opening tag is also the closing tag : `/>`
### Main
* The main section of our website includes the bulk of the information. We’ll contain all the super useful content about our town within this <main> element, which we have already included. 
* We have three related groups on our website that we will organize into three sections. A section is a standalone piece of a website that contains information and also has its own element: `<section>`.
* More Structuring! Within our sections we have more smaller frames to build, like containers for the small bits of text next to the images. Each section has a nested image and and an element that contains some text.
* Let’s take a look at our base markup before we add content!
* We talked about adding images a bit already so let’s look at what an unordered list looks like 
* Now, when we put all this together each section is going follow the same structure with slightly different content. 

### Footer
* Our footer is the first element after the closing of main; so it’s not nested inside of it!
* The only content we have within our footer is a sentence about who made our site (we did!). This content will be wrapped within a `<p>` (paragraph) element that is nested within the footer.

## Full Preview
* So we don’t have a background-color and everything is left aligned by default, but all our content is there! 
* Practice time!
* *Review all content* 
* So while someone could totally use our site at this point, but let’s dive into some CSS basics to make this look a bit better. 

## CSS Intro: Properties & Values
* Just as with HTML, CSS needs to be written in the correct way in order to work. 
* So we can call on a class name (refer as additional reading) or full element name here. 
	* The styling instructions are contained within curly brackets, `{ }`. 
	* What we will be styling (`background-color`) is immediately followed by a colon `:` 
	* Then we add the value (which is `blue` in this case). 
	* Each style must end with a semicolon `;` 
* Practice time!

## CSS: Colors 
* So we have a green background but it’s not very pretty. There are some colors you can use by writing out their names in CSS, but to achieve such a unique color as the light yellow we designed for Tuts+ Town we need to include its hex value. 
* All colors have a hex number to match. So while browsers do not understand many colors when they are written out, they do understand hex numbers very well. The hex number for our light yellow color is `#FAF8DA` 
* Practice Time! 

## CSS: Sizing *(Time permitting!)*
* We also have the power to change the sizing of text and images with CSS. There are lots of units of measurement that can be recognized by the browser, but we are going to work with pixels, which is basically dots filled with color on the screen. 
* If we take a look at our header again we may find that we need to make changes to the size and color of our primary heading and image. 
* The first thing we will want to do here is add class to these elements in our HTML….we can then save this and then hop over to our CSS, target these classes, and declare some sizing specifics; and change the font color while we are at it to the Tuts+ Town blue used throughout the project. 

## Where To Go From Here!
* Review what we learned today
	* We built our very first website by learning how to properly markup and HTML document and add our content in a way that the browser can understand.
	* After understanding the role CSS plays here we were able to get a glimpse into the styling possibilities for our site.  
* Review what rest of series will cover 
	* The remainder of this series will cover the remaining CSS styling and layout required to complete the site, and also touches on things like typography, color theory, and some general design concepts we didn’t have time to go over today. 
* Provide link to [the Tuts+ Town full curriculum](http://webdesign.tutsplus.com/series/web-design-for-kids--cms-823)

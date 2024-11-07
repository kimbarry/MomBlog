# MomBlog
This is a simple practice project putting together a basic Static frontend site and an unchanging backend API.

This project will be goal driven, with a list of objectives for each day and week. Evem of am pbjective can't be achieved, working towards it can provide great learning potential.

The project theme will be for an imaginary mom-blog, since that is a reasonable and easy site to create a basic prototype. Ultimately the project will consist of a basic website and an API which uses a flat file as a database. The website will have a handful of basic pages like home, about us, and ask a question, with consistent styling. the About us Page will eventually have a "Post a picture" File selector and a caption text box and send a post request to the API, submitting the picture and its caption.The Gallery page will make a get call to the API, requesting all questions, and then the questions Page will display the results. Colin will help guide the setup of the API, file read/write and storage, and the API calls, for now we are focusing on baseline functionality and skeleton.

The project will be split into 3 folders: 
1. ./Website/ - The frontend static website
1. ./API/ - The C# .Net basic API we are making
1. ./Assets/images - Where we are storing any pictures we are submitting, With the file-names being in a 000-{caption} format
# Here is the planned todos:

Day 1 - Initial skeleton setup.
With the Git repository created we begin stubbing out some basic skeleton of a realistic website. Even if it will look like a 90s site by the end of the day, it will still be a working static webpage. 
* Create index.html, 
* Create index.css
* Add a title and h1 tag for the page title
* Create a div with the class "header", 
* fill the header with the following content
    * An unordered list with 5 list items
        1. Any placeholder image
        1. Either "Index" or "Home"
        1. "About us"
        1. "Gallery"
        1. "post a picture"
    * make each of these a link, but don't link anywhere yet
* create a div with class "content"
* Fill the "content" div with some placeholder content in appropriate tags:
    * An welcome message that says "Welcome to My blog!" or similar
    * An empty image tag, we will add an image of our family to it later 
    * A paragraph of some filler info on why this made up mom blog exists
    * A Ordered or ordered list of the mom's kids
    * any other content that would be expected in a main page of a quick novice parenting blog
Next, we will add some super basic styling. 
* Import or reference the Site.CSS file so it can style the page
* Set page background to a different color
* set Header background to different color
* Give header a 1px dark grey outline, give content a 2px slate-gray outline,
* Center the Content Div on the page,
* Make the "header" div span the full left-right on the page
Discuss with Colin if you reach this far or need help.




## Day 2:
### Placeholder Gallery and captains log and submission forms
* convert UL to single line
* Get header all in single line 
* add border around header items in order to appear as inline menu
* make each li an <a>
* create gallery.html
* create galleryForm.html
* create personalLog.html
* create personalLogForm.html
* copy code from index.html except content and paste onto new html pages
* log entry form needs stardate and text box
After we learnt about all of those basic element in html and css, now we're gonna make a simple navigation bar for our profile web.

Before we start, please make a file with name index.html, and syle.css in your directory file or you can use 

the previous file that you've made.

# NAVBAR

                    +---------------------+-----------------------+------------------------------+
                    |                     |           <navbar>    |                              |                
                    |<div class=left-nav> |                       |     <div class=right-nav>    |
                    |                     |                       |                              |
                    +---------------------+-----------------------+------------------------------+
                    |                                                                            |
                    |                                                                            |
                    |                                                                            |
                    |                                                                            |
                    |                                                                            |
                    |                              /* CONTENT */                                 |
                    |                                                                            |
                    |                                                                            |
                    |                                                                            |
                    |                                                                            |
                    |                                                                            |
                    |                                                                            |
                    +----------------------------------------------------------------------------+

Navigation bar or we usually call it navbar is often used to give a navigation in web so user can go to some sub-page at the web. Usually you can see navbar at above of the web page.

Now let's start with making the skeleton (HTML).

---

Let's say in our profile web, we want to set the margin of the web with `max-width` of `1170px` (`max-width` will give the margin set with maximum width of `1170px`, so it can have a smaller width when minimized but cannot have a width more than 1170 px).

We want to make a navbar that in a left-nav contain: HOME. and in the right-nav contain: SKILL, EXPERIENCE, CONTACT.

so the structure now wil be:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="style.css">
    <title>Document</title>
</head>
<body>
    <nav>
        <div class="container">
            <!-- container class will be use to set the margin of the web -->
            <div class="left-nav">
                <a href="#home">HOME</a>
            </div>
            <!-- Add a menu icon here -->
            <!--<span class="fa fa-bars menu-icon"></span>-->
            <div class="right-nav">
                <a href="#skill">SKILL</a>
                <a href="#exp">EXPERIENCE</a>
                <a href="#contact">CONTACT</a>
            </div>
        </div>
    </nav>
</body>
</html>
```

#### <mark>Preview:</mark>
        +-------------------------------------------------+   
        |HOME                                             |  
        |SKILL EXPERIENCE CONTACT                         |  
        |                                                 |  
        |                                                 |  
        |                                                 |  
        |                                                 |  
        |                                                 |  
        |                                                 | 
        +-------------------------------------------------+

Now, the skeleton has done. Let's move to the next section to style it!!.

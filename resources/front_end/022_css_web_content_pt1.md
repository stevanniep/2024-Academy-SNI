
               +----------------------------------------------------------------------------+
               |                                 <navbar>                                   |                
               +----------------------------------------------------------------------------+
               |                                                                            |
               |                              <div class="title">                           |
               |         +--------------------------------------------------------+         |
               |         | +------------+      +--------------------------------+ |         |
               |         | |            |      |                                | |         |
               |         | |   <div     |      |                                | |         |
               |         | |class=myPic>|      |       <div class=myBio>        | |         |
               |         | |            |      |                                | |         |
               |         | +------------+      +--------------------------------+ |         | 
               |         +--------------------------------------------------------+         |
               |                                                                            |
               |                                                                            |
               +----------------------------------------------------------------------------+

## RESPONSIVE

Now we're gonna make your bio in your profile web responsive to the size of the browser, like when it's minimized to a phone size it'll become.

               +-----------------------------+
               |           <navbar>          |          
               +-----------------------------+
               |     <div class="title">     |
               |    +-------------------+    |
               |    |                   |    |     
               |    |                   |    |     
               |    |                   |    |     
               |    | <div class=myPic> |    |    
               |    |                   |    |     
               |    |                   |    |     
               |    +-------------------+    |   
               |    +-------------------+    |
               |    |                   |    |     
               |    |                   |    |     
               |    |                   |    |     
               |    |<div class=myBio>  |    |    
               |    |                   |    |     
               |    |                   |    |     
               |    +-------------------+    |   
               |                             |
               +-----------------------------+

How to? we're gonna use `display: flex` to make the box flexible to it's web size.

---
Like we've done it nav, we're gonna make the skeleton first.

at the plan above, there's two box that we're gonna make, so the skeleton will be.
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
        <section id=aboutMe>
            <div class="container">
                <div class="title">ABOUT ME</div>
                <div class="bio-container">
                    <div class="myPic">
                        <img src="https://media.tenor.com/-DLSPvHR808AAAAC/troll-trolldespair.gif" alt="myCoolPhoto">
                        <p>TROLL THE STROLLER</p>
                    </div>
                    <div class="myBio">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Facilis, consectetur? Rerum temporibus ea laudantium nihil odit
                        facere quibusdam quam consectetur voluptates optio. Alias expedita
                        reiciendis omnis quisquam consequatur, ut sapiente.
                    </div>
                </div>
            </div>
        </section>
    </body>
</html>
```

Next section we're gonna start styling it!

> For the image source, it's up to you, maybe if you confused which photo you want to use, you can set the source

with https://media.tenor.com/-DLSPvHR808AAAAC/troll-trolldespair.gif

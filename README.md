# Responsive Photography Web site

<img  src="https://raw.githubusercontent.com/StuartSmith/PhotographyWebSite/master/WebsiteImage.JPG">

This is a simple web site that follows along Brad Traversties tutorial on creating a responsive web sites.

The tutorial that was followed for creating this web site can be found here. 

https://www.youtube.com/watch?v=XsEnj-1hG2o

## Demo

To see a demo of the website go to the following URL

http://htmlpreview.github.io/?https://github.com/StuartSmith/PhotographyWebSite/blob/master/index.html

## Font

The font used in this project is Roboto Condensed from google fonts.

https://fonts.google.com/specimen/Roboto+Condensed'

## Unsplash photo library

All the images for this web site come from unspash. A great web site to find stock photos
https://source.unsplash.com

## CSS Trickery 

The gradient for the HTML is coming from the following CSS. There is a box shadow around the bottom, left and right of the page. 

box-shadow: 30px 0px  40px rgba(0,0,0,0.1), -30px 0px  40px rgba(0,0,0,0.1);

Responsiveness is create by using the following media queries

@media(min-width:500px)
{
    #landing
    {        
        display:flex;
    }
    #landing-text
    {
        height: 100vh;
    }
    #landing-image
    {
        height: 100vh;
    }
}

@media(max-width:500px)
{
    #landing
    {        
        display:block;
    }
    #landing-text
    {
        height: 50vh;
    }
    #landing-image
    {
        height: 50vh;
    }
}

## JQUERY

Press the show work button to create smooth scrolling  Jqueury effect down the screen to show the first photo in the array of 


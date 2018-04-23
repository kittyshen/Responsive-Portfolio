# Responsive-Portfolio
UC Berkeley coding assignment 2-2
Using media query to recreate the assignment basic portfolio to make it responsive to different size media screen. required size is 980px 768px and 640px. 

## Code Example
@media(max-width:768px){
    #content960{ 
        clear:both;
        width:95%;
        float: left;
        margin:2%;
    }
    #sideBar{
        display:none;
    }
}


## Key learning points
Be sure to clear both after the navigation section to make the main content start on a new row.
display:none (get rid of the element) visibility: hidden(elements are hidden but still take up space)
background-img better placed in body to make sure it covers whole web page.
be sure to add "<meta name="viewport" content="width=device-width, initial-scale=1">" to make page render normal on mobile devices.

## Installation
Download the zip file, unzip on the desktop, open index.html

## Link to the site
[Click me](https://kittyshen.github.io/Responsive-Portfolio/)

## Author 
[Kitty Shen ](https://github.com/kittyshen)

https://github.com/kittyshen

## License
Standard MIT License

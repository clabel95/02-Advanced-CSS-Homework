# 02 Advanced CSS: Portfolio
The point of this assignment was to create a portfolio page for myself based on the requirements provided.
## Wireframe
![The image shows a wireframe mockup of the porfolio website the autor planned to design.](https://github.com/clabel95/02-Advanced-CSS-Homework/blob/79280ea3c06d81b7121d8e9dfcaa56cf16a08f60/assets/images/Wireframe.png?raw=true)

## Application
```


This Webpage is a mock portfolio page. The header bar is stuck to the top of the screen and displays my name, an image of me, and the nav bar. The nav bar takes the user to each labled section. The final option in the nav bar provides the user with a copy of my resume.


```
![The image shows the header bar of the portfolio website.](https://github.com/clabel95/02-Advanced-CSS-Homework/blob/7a9cc5eada3305f5d8529a75984113854577a8b0/assets/images/Header.PNG?raw=true)



```


Below the header is the "About Me" section which has a title on the left and the info on the right.


```
![The image shows the About Me section of the portfolio website.](https://github.com/clabel95/02-Advanced-CSS-Homework/blob/7a9cc5eada3305f5d8529a75984113854577a8b0/assets/images/About_me.PNG?raw=true) 



```


Below that is my "work" section. It has 5 example projects with the first one being larger than the rest. Each project can be clicked to navigate the user to the corrosponding project. (This will be updated as I complete projects.)


```
![The image shows the Work section of the portfolio website.](https://github.com/clabel95/02-Advanced-CSS-Homework/blob/7a9cc5eada3305f5d8529a75984113854577a8b0/assets/images/work.PNG?raw=true)



Below the work section is the contact section. This section has three Icons that corospond to github linkedin and mail. By clicking any of the icons it will take the user to the authors corosponding website. I have also made it so that when you press the mail icon it opens up in gmail to send an email. I might change this later. 

I got the icons from a the website [ionicon](https://ionic.io/ionicons)




![The image shows the contact section of the portfolio website](https://github.com/clabel95/02-Advanced-CSS-Homework/blob/7a9cc5eada3305f5d8529a75984113854577a8b0/assets/images/Contact.PNG?raw=true)




I tried my best to make the website mobile friendly however, I think I went about it the wrong way. 

What I did was add the following media query to css.
```
@media (max-width:850px){
    header img{
        display:none;
    }
    .sections_contact h2{
        display:none;
        
    }
}
@media (max-width:630px){
    header h1:before{
        content: "C. Abel";
    }
    .Author_name{
        display: none;
    }
    
    #outer_box h4{
        display:none;
    }
}
```

What this does it if the screen gets smaller than 850px wide then it removes the image of me from the header bar and it also removes the h2 from the contacts section. 

![The image shows the portfolio page whith a width less than 850px]()


Lower than 630px then the authors name at the top gets shortened from Clayton Abel to C. Abel 

![The image shows the portfolio page with a width less than 630px]()
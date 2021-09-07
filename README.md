# Marketing Agency SEO

## Description
In this project a marketing agency requires their existing website to be updated inline with modern accessiblity and Search Engine Optimisation standards.

This project is deployed using GitHub pages at https://josephdaw.github.io/marketing-agency-seo/. 

The final webpage should resemble this: ![Page Mockup](assets/images/01-html-css-git-homework-demo.png)

## Lessons Learned
### - Avoid excessive CSS nesting
One of the main take aways from this project is learning to balance classes and element styling. For example, this was part of my CSS file to style the navigation section:
```
header nav ul li {
     display: inline-block;
     margin-left: 25px;
 }
 ```
 While this keeps my HTML code clean, it starts to make the CSS a bit cumbersome. Also, I learned that browsers read the CSS from right to left. This means that they would find all the `li` elements, then look to see if they were a child of a `ul`, then check if that was in the `nav` tag located in the `header`. 

 I ended up creating a class `header-nav` targeting the `ul`. This meant I could condense the above section down to:
 ```
 .header-nav li {
     display: inline-block;
     margin-left: 25px;
 }
 ```
### - Version Control with Git and GitHub
I don't know how it has taken me this long to become acquainted with Git. Version control is something I have always taken seriously. You learn how important it is pretty quickly when one small change somehow breaks everything! In the past my version control has been saving multiple copies of my files using v0.0.1 convention. 

Getting used to using Git and GitHub is a bit of a learning curve, but one that I am excited to continue practicing. Even during this project, I reset the code back to a previous commit a couple of times when broke the CSS while consolidating classes.

## Credits
This user story is part of the [Adelaide University Coding Boot Camp](https://bootcamps.adelaide.edu.au).
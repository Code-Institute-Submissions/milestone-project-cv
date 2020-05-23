# Gediminas Valevicius Resume  
<img src="https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png" style="margin: 0;">

## UX
&nbsp;&nbsp;The Gediminas Valevicius Resume website was created as one of my assignments for Code Institute. I had an option to choose my own Idea for the project. <br>
I tought that the resume website could be useful not only to show my skills and pass the test, but to use the website in the future for a potential employer. 
<br><br>I thought about the resume as a tool for marketing myself, so I have to think of what would be interesting for my potential employees to know. How to sell myself.
<br> I looked for a lot of different resume websites online in order to learn from the other developers what they would consider as main, important points to showcase. I think it is important to learn from other people too. 
<br><br>&nbsp;&nbsp;During the research I found out that it is most important for the employee to know your skills, to what projects you have contributed or worked on your own and resume itself. So, I have decided that I am going to create a five-page website:
*  Home Page – will be the main page.
*  Resume Page – will show education/qualification along with work experience
*  Projects Page – will display showcase all my projects.
*  Skills Page – will show all my strongest skills.
* Contact Page – will be used for contact form.
  
****
### Home Page <br>
&nbsp;&nbsp;The first page, home page I will dedicate as a short introduction about myself along with a picture. Like most good brands on the market it has its slogan which helps to sell, attract customers, so I have to sell myself with a short paragraph about who I am and what I do for a living. <br>
&nbsp;&nbsp;Home Page’s header and footer, I am going to use for all other pages, so it will be created as a barebone for the entire website, only the content of the home page will be changed. In programming reusability is very important, because of simplicity to test and coding in general. <br>

****

### Resume Page <br>
&nbsp;&nbsp;The home page was created using only HTML, CSS and my own JS in order to show my coding skills. For all other website pages, I thought I will be using bootstrap, so all other pages suppose to use bootstrap except the home page. Once I started using bootstrap I noted that alignment of my navigation bar is different comparing home page with all other, so I changed my own version of navigation bar to bootstrap. It was quicker to create new comparing with looking for conflicts.<br><br>
&nbsp;&nbsp;The resume page I decided to use for showcasing my Education and Experience.  I think the best way to display such an information would be timelines. I found two potential sources on how to build timelines. One of which W3schools and another one is the bootstrap documentation.   
### Wireframes for each of the page on the site
* [Home](https://wireframe.cc/pro/pp/0801205c0338940)
* [Resume](https://wireframe.cc/pro/pp/81eb5d3d3338950)
* [Projects](https://wireframe.cc/pro/pp/f7029f065342644)
* [Skills](https://wireframe.cc/pro/pp/836bbaef8341165)
* [Contacts](https://wireframe.cc/pro/pp/ac20b1579342638)

****
### User stories
[Navigation Button](https://miro.com/app/board/o9J_ksemU64=/)
<br>
[Footer Icons](https://miro.com/app/board/o9J_ksemFzo=/)

****
## Features Left to Implement
&nbsp;&nbsp; Another future idea would be to add an extra tab in the navigation bar for my blog page. Where I could post my thoughts, publish my pictures or hobbies. 
 That page would have to have a sing in link for myself to edit it and the page itself would display content.

****
## Testing
### Home Page testing.
&nbsp;&nbsp;CSS, HTML codes I had tested using “validator.W3.org”. During the test I found only one warning in HTML, it recommended to use the h1 heading in article. CSS styling, I have passed with out of errors or warnings.
During the testing on different browsers like Firefox, Chrome, Opera and Explorer I found out that Internet Explorer do not accept the background colour opacity with RGB colour coding as a fourth parameter. So, it ignores background colour with four parameters like:<br>
&nbsp;&nbsp;Background-color: rgb(12,12,12, 0.5);<br>
Instead it has to be written in rgba format. Like:<br>
&nbsp;&nbsp;Background-color: rgba(12,12,12,0.5);<br>
&nbsp;&nbsp;Another problem was that Internet Explorer do not accept a linear gradient value as a background colour. I found a code solution on Stack overflow:<br>
( https://stackoverflow.com/questions/4961651/does-ie9-support-css-linear-gradients )<br>
I did run a test on the Chrome browser, in an audit section. At first result wasn’t so good, but after some minor improvement I got very good result as you can see from the imgage down below. <br>

Test result: <br> <br>
![alt text](./assets/images/home-page-test-results.jpg "Home page test result image")

****
### Resume Page testing.

&nbsp;&nbsp;During the resume web page testing, I had discovered that the “Best Practice” parameter is very poor because the image sizing. As you can see from the images below.<br>
![alt text](./assets/images/image-resizing-problem.jpg "Resume page poor best practices parameter image") <br>
![alt text](./assets/images/resume-failing-best-practices.jpg "Resume page poor best practices parameter image") <br>
&nbsp;&nbsp;I decided to resize the image to the required size, it would improve page rendering speed and the best practice parameter. As you can see from the image below the test result was improved.<br><br>
![alt text](./assets/images/resume-test-result.jpg "Resume page poor best practices parameter image")
## Images Reference

The home image, background image was taken from:<br>
(https://pixabay.com/images/search/)<br>
Programing images where taken from :<br>
(https://www.pngfuel.com/search?q=programming+Languages)





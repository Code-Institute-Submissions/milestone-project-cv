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
  

### Home Page <br>
&nbsp;&nbsp;The first page, home page I will dedicate as a short introduction about myself along with a picture. Like most good brands on the market it has its slogan which helps to sell, attract customers, so I have to sell myself with a short paragraph about who I am and what I do for a living. <br>
&nbsp;&nbsp;Home Page’s header and footer, I am going to use for all other pages, so it will be created as a barebone for the entire website, only the content of the home page will be changed. In programming reusability is very important, because of simplicity to test and coding in general. 
### Wireframes for each of the page on the site
* [Home](https://wireframe.cc/pro/pp/0801205c0338940)
Home page will be created as a bearbone for the entire wesite only its content will be changed in each of the pages 
* [Resume](https://wireframe.cc/pro/pp/81eb5d3d3338950)
* [Projects]()
* [Skills](https://wireframe.cc/pro/pp/836bbaef8341165)
* [Contacts]()




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

Inline-style: <br>
![alt text](./assets/images/home-page-test-results.jpg "Logo Title Text 1")






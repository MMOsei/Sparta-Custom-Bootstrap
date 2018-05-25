# Sparta-Custom-Bootstrap

## Task

We (Rizwan and Marian) were tasked with creating a 3 page website, using HTML and CSS, and make it responsive using the Bootstrap 3 framework. 

The step were as follows:

1. Create a GitHub repository and get local access:

	a) Create the repository<br>
	b) Protect the master<br>
	c) Add collaborators<br>
	d) Clone the repository to computer<br>
	e) Create a dev branch<br>
	
2. Create the file structure:

	a) Make sure that you create all files and folders while in the Dev branch.<br>
	b) Using Bash, create the various files and folders for HTML, CSS, JavaScript, Images, JQuery and Bootstrap documents.<br>

3. Create a theme for your website:

	a) Discuss what the website will be about<br>
	b) Consider layout ideas and colours<br>
	c) Design wireframes<br>
	d) Delegate features to team members<br>
	
4. Create the starter code:

	a) Working from wireframes, previously created, write the code for the `<head>`, `<nav>` and `<footer>` and any other common features all the pages will share.<br>
	b) Make sure to check the file paths of links and images to make sure all of the common features, images, links work.

5. Create the rest of the website:

	a) Using Gitflow, work individually on designated features.<br>
	b) Create feature branches to work on each feature on the website using Bash.<br>
	c) Remember to commit changes to features only on the feature branch.<br>
	d) Once done, `git pull` from the dev branch to make sure the most current version is available.<br>
	e) Merge Dev branch onto feature branch, resolve all merge conflicts.<br>
	f) Merge feature branch onto dev branch then push to GitHub.

###File structure

Below is the file structure that we used to store our documents.

```
Index.html
CSS
	bootstrap
	custom
Images
JS
	query
Pages
	About.html
	Contact.html
```

##[Subject of the site](https://github.com/MMOsei/Sparta-Custom-Bootstrap "Link to GitHub page")

This website is a simple recruitment page that directs prospective clients or students to contact the relevant team lead. It also gives information on the kinds of pathways available with some testimonials of past students and current clients.

##Challenges

Marian - The main challenges I faced was that I felt the need to complete the task all in one go. This caused me to feel frustrated and made be feel a little unmotivated during this task. I did find that if I took a break and stepped away from the task for a few moments, I allowed me to come back with fresh eyes.

The other challenge that I had was with making the index.html be responsive. I had tried playing around with it and realised that the columns were split unevenly when it got to the extra small screen size. Once I had corrected this issue, I found that my code worked well.

Rizwan - On  About us Getting the testimonial videos directly under the jumbrotron. Sometimes it overlapped due to not closing div tags properly
 
Forms on Contact Us Page. Mainly the CSS so getting the email, full name etc. centre  on the page and making sure the submit button is in the centre of the input fields.
 
 
#How to Download files from github
 
1. First we needed to make a directory for the task so we did 'mkdir bootstrap task'
 
2. next it was important in our terminal that we would be in that file we made so we did cd bootstrap task
 
3. Going onto github we clicked on the code tab on github,  we clicked on  the green button called 'clone or download.'
 
4. Next we Copied the URL link underneath the clone with SSH
 
5. Next we made sure we were in the correct directory in our terminal. Once in the correct place we typed ' git clone (link of url)'. In our case: git clone git@github.com:MMOsei/Sparta-Custom-Bootstrap.git
 
6. After we needed to 'git checkout dev' to make a branch called dev and then switch to that to make changes
 
7. Lastly we needed to git pull to gain the information and complete our download
 
#Challenges
 
1)On  About us Getting the testonimial videos directly under the jumbratron. Sometimes it overlapped due to not closing div tags properly
 
2) forms on Contact Us Page. Mainly the CSS so getting the email, full name etc. centre  on the page and making sure the submit button is in the centre of the input fields.
 
 

#Some Code Snippets
 

1) First we created a jumbatron which goes across the whole width of the page:
 
````
<div class="jumbotron">
</div>
````
 

2) we needed to create a box in the middle which again goes across th whole width of the page which sits inside the Jumbatron. So we need to create a div container and inside needed to specify the rows and the columns. since we wanted the whole page inside the Jumbatron we needed the col-md-12(12 because the page is divided into 12 parts and selecting 12 will be the full width). Col-sm-12 specifies it for mobiles aswell to makes it responsive when viewed on small screens.
 
```html
<div class="container">
    <div class="row">
      <div class="col-sm-12 col-md-12">
      </div>
    </div>  
</div>
```    
      
```html
    <h2> Who are we ? </h2>
    <p>  A definition of Spartan is:<br>
 
            1) A native or inhabitant of ancient Sparta<br>
 
            2) a person of great courage and self-discipline<br>
 
            3) <strong>A digital warrior, or technology consutant, built for the digital age;rigiorously trained through the Sparta Global Academy</strong>
 

```
 
3) After the structure was sorted out. The code above shows our content. h2 is the heading size. p is the paragraph, br tag breaks the line and strong makes the writing bold
 
#css
 
```css
h2 {
  text-align: center;
  color: red;
  padding: 30px 0px 30px 0px;
 
}
 
h3 {
  color: red;
  text-align: center;
 

/* changed p and h3 alignment and height for line */
 
h3 {
  text-align: center;
}
 

}
 
p {
  text-align: left;
  line-height: 40px;
}
```
 
for the CSS we targeted elements to style them indivdually. For example p for the paragraph we can align the text on the left and the line height. For the h2 and h3 we changed colour to red.
We can do padding 
 

#Images of site
 
`[image-id]: path/or/url/to.jpg "Optional Title"`
 
![pic](https://i.imgur.com/iexf8fK.png)
 

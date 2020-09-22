# DevFolio 
<a href = "https://github.com/achaljhawar/DevFolio/graphs/contributors"><a href="https://github.com/achaljhawar/DevFolio/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/achaljhawar/DevFolio"></a><a href="https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fachaljhawar%2FDevFolio"><img alt="Twitter" src="https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2F"></a><a href="https://github.com/achaljhawar/DevFolio/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/achaljhawar/DevFolio"></a><br />
This is a simple responsive portfolio website template . You can use it and make it yours by changing things and colors to your style and liking! I made it with a lot of hard work, love and of course with code :) I'm not a professional coder, but i tried my best to make it look cool and yet still keep it simple. 

> Mistakes are proof that we are trying!

I learned so much while making this template, if you use it, please let me know. I would love to see how amazing people can make it! I hope you'll like it!

## I have used:
+ **HTML5** for markup
+ Pure **CSS3** for styling 
+ Bit of **Jquery** to make header animation effects work
+ Bit of **JavaScript** to make a hamburger menu to work on mobile devices 
+ **Font Awesome** for Icons 
+ **Unsplash** for Images 


## Sections
✔️ About me and summary\
✔️ Contact Info\
✔️ Projects
✔️ CV

## Getting Started 🚀
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
## Downloading Template
To download and use this template you could use `git clone` or `npx degit` to download this template to fill it out. You could also just fork this repository on Github.

```bash
# Clone this repository
$ git clone https://github.com/gytislaukaitisi/DevFolio.git

# Go into the repository
$ cd DevFolio

# Install dependencies
$ npm install

#Start's development server
$ npm start
```
## Template Instructions:
Go to `/index.html` and fill your information, there are 3 sections:
### Home Section
- Add your Name and a short description about yourself
- Add your social media links 
```html
<div id="home">
	<div class="filter"></div>
	<section class="intro">
		<h3>Your Name<hr></h3>
		<p>Short Description.</p>
		  <p>Something more about yourself.</p>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
<!--────social media links─────-->		 
		  <div class="social-media">
			  <a href="#" target="_blank"><i class="fab fa-codepen"></i></a>
			  <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
			  <a href="#" target="_blank"><i class="fab fa-github"></i></a>
			  <a href="#" target="_blank"><i class="fab fa-linkedin-in"></i></a>
			  <a href="#" target="_blank"><i class="fab fa-youtube"></i></a>
		    </div>
			 
	</section> 
</div>  
```
### Projects Section
- Add your short description ,the image of your projects and their links you can change the number of projects.
```html	 
	  <div id="projects"> 
		 <h3>My Projects.<hr></h3>
		  <p>Here are some of my projects, you may like.</p>
		  <div class="work-box">
		  <div class="work">
		<!--───────────────card───────────────-->
			<div class="card">
			    <img class="work-img" src="https://images.unsplash.com/photo-1518611507436-f9221403cca2?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1225&q=80">
			    <a href="" target="_blank"> <!--Link to project-->
				<div class="work-content">Lorem ipsum dolor sit amet consectetur.</div></a>
            </div>
			<div class="card">
			    <img class="work-img" src="https://images.unsplash.com/photo-1462642109801-4ac2971a3a51?ixlib=rb-1.2.1&auto=format&fit=crop&w=1266&q=80">
				<a href="" target="_blank"> <!--Link to project-->
				<div class="work-content">Lorem ipsum dolor sit amet consectetur.</div></a>
            </div>
            <div class="card">
			    <img class="work-img" src="https://images.unsplash.com/photo-1485815457792-d1a966f9bde0?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80">
				<a href="" target="_blank"> <!--Link to project-->
				<div class="work-content">Lorem ipsum dolor sit amet consectetur.</div></a>
            </div>
            <div class="card">
			    <img class="work-img" src="https://images.unsplash.com/photo-1517842645767-c639042777db?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80">
				<a href="" target="_blank"> <!--Link to project-->
				<div class="work-content">Lorem ipsum dolor sit amet consectetur.</div></a>
            </div> 
			<div class="card">
			    <img class="work-img" src="https://images.unsplash.com/photo-1535556116002-6281ff3e9f36?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=781&q=80">
				<a href="" target="_blank"> <!--Link to project-->
				<div class="work-content">Lorem ipsum dolor sit amet consectetur.</div></a>
            </div>
			<div class="card">
			    <img class="work-img" src="https://images.unsplash.com/photo-1483546416237-76fd26bbcdd1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80">
				<a href="" target="_blank"> <!--Link to project-->
				<div class="work-content">Lorem ipsum dolor sit amet consectetur.</div></a>
            </div> 	  
		  </div>
		  </div>
	  </div>
```
### Contact Section
- Add your social media links 
```html
	  <div id="contact">
		  <!--────social media links─────-->
		   <h3>Contact.<hr></h3>
		   <p>Feel free to contact me on my social media.</p>
		    <div class="social-media">
			  <a href="#" target="_blank"><i class="fab fa-codepen"></i></a>
			  <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
			  <a href="#" target="_blank"><i class="fab fa-github"></i></a>
			  <a href="#" target="_blank"><i class="fab fa-linkedin-in"></i></a>
			  <a href="#" target="_blank"><i class="fab fa-youtube"></i></a>
		    </div>
		  </div>
```
## Deployment 📦

Once you have done with your setup. You need to put your website online!

I highly recommend to use [Github Pages](https://pages.github.com/) to achieve this on the EASIEST WAY.

## Author

- **Achal Jhawar** - [https://github.com/gytislaukaitisi](https://github.com/gytislaukaitisi)

## License 📄 <a href = "https://github.com/achaljhawar/DevFolio/blob/master/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/achaljhawar/DevFolio?style=flat-square"></a>

This project is licensed under the Apache-2.0 License - see the [LICENSE](LICENSE) file for details

## 🤝 Contributing

Any idea on how we can make this more awesome ? [Open a new issue](https://github.com/gytislaukaitisi/DevFolio/issues)!  I need all the help I can get to make this project awesome!

### Don't forget to ⭐ and 🍴 the repository and share it with others.







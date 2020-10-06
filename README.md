# C.I. WebDev Course Milestone Project No.1

<img src="/assets/images/ak_autograph.png" alt="autograph" style="zoom: 33%;" />

##### <u>Project:</u> Personal Portfolio

### Project Goals

The customer (myself) would like to get employed and would like generate interest about himself using showcasing personal traits and abilities in an online presence other than the usual Social Media sites.

The end goal is to let the potentional employers have a closer look on a professional level on the applicant's skillset. Also it is quite important for the customer to leave a positive visual impact in the potentional employer and stand out.

### UX design / Presentation

**Wireframing**

I had a multiple page layout structure in my mind when I first started thinking about this project. The pages would show thematically their own content while having cross-reference sections as well. 

<u>The pages would be the following:</u>

- Home

> The index page of the website would contain a navbar, profile picture, description text, links to other projects, and a footer section.

<img src="/assets/images/wireframes/home_wireframe.png" alt="home wireframe" style="zoom: 67%;" />



- Resume

> The resume page would have the navbar a full-size image of the customer on the left side and would have a scrolling text section on 2/3 of the screen listing details of education and previous employment.

<img src="/assets/images/wireframes/resume_wireframe.png" alt="resume wireframe" style="zoom:67%;" />



- Gallery

> The gallery page would contain a tile-style gallery showing more of the personality of the customer while trying to generate sympathy from the potentional employers. Some basic CSS effect would be nice on the actual picture selected.

<img src="/assets/images/wireframes/gallery_wireframe.png" alt="gallery wireframe" style="zoom:67%;" />

**Update:** CSS hover effect used to highlight a single image tile from the group.



- Contact

> The contact page would show a short introductory video from the customer further emphasizing why would the potentional employer consider an invitation for an interview and getting in touch with the customer. Below the video there would be contact information listed.

<img src="/assets/images/wireframes/contact_wireframe.png" alt="contact wireframe" style="zoom:67%;" />



- Direct download link to the customers CV

> This would be the last item in the navbar giving an option for the potentional employer to download a CV of the customer in a more traditional form. There would be a PDF file linked up to this which would open in a new window separate from the rest of the content.



**Navigation**

<u>Navbar</u>

> The navbar would have a logo on the left linked to the index page. The navigation links will be on the right side. All navigation elements would have basic animation applied to. On a mobile device the navbar would collapse from a certain screen width and the user would be able to get to the navigation links pressing a hamburger icon.

<u>Footer</u>

> The footer would have basic copyright information displayed as well as icons linked to the various social media platforms and contact forms of the customer.



**Color scheme and typography**

I wanted to present the customer (who is myself again) in the most professional manner while also keeping it not too formal. I wanted to showcase the end user the professional side of things but also the young and energetic aspect. 

I have operated with mostly darker tones in the background and lighter colors in the foreground. The most dominant colors are black and shades of blue mixed with white. 

I gave the pages a black frame on the top and bottom with the navbar and the footer, emitting a lampshade-like white effect on the fancy blue striped wallpaper background.

I used opaque black background on the images that are showing up on the pages. 

I have chosen #whitesmoke as a main color of text, the only exception is on the resume page.

I have chosen the Overpass font-family imported from Google Fonts CDN having Sans-Serif as a fall-back.



##### Images and video of the customer 

<img src="/assets/images/ak_p.png" alt="ak_profile" style="zoom: 25%;" />

> I have asked my partner to shoot the images of myself that I had in mind to put to this project. She was also helping me recording the introductory video. For the logo in the navbar and for the favicon I used a digital drawing tablet to capture my handwriting. I have used Adobe Photoshop to edit these images and https://favicon.io/ for the favicon.



### Technologies Used

- HTML5
- CSS3
- Javascript
- GitHub
- GitPod
- Bootstrap CDN https://getbootstrap.com/
- JavaScript
- Balsamiq Wireframes - used in the design process for wireframing
- Typora - The README.md file was edited in Typora - https://typora.io/



### **Version Control**

I was using Git for version control, uploading the project to GitHub.

My GitHub repository for this project: 

https://github.com/Adamsky94/milestone1

### Testing write-up

.html documents validated on - https://validator.w3.org/

.css document validated on - https://jigsaw.w3.org/css-validator/

Responsivity for mobile devices tested on - http://www.responsinator.com/ and in Google Chrome Developer Tools

Used online autoprefixer for maximum browser compatibility - https://autoprefixer.github.io/

Used online code formatter in order to achieve optimal syntax - https://webformatter.com/

Used online image compressor for achieving the fastest image loadtimes from the server - https://imagecompressor.com/



**Technological limitations/Barriers**

- <u>JavaScript</u> - Because my current limited knowledge of JavaScript I kept to using it as little as possible throughout the project.

- <u>Hover Grow Shadow</u> - This was my original choice of animaton of the navigation links but the navlink text was overfloving on mobile devices with the text coming off the screen during animation under the collapsed navbar. 

​	**Solution:** Replaced animation with a simpler one, which is underline from center.

- <u>Layout of resume.html</u> - The original idea was to have a full-size image of the customer being on the 1/3 of the page on the left and having text-scrolling on the other 2/3 on the right. I could not have it looking good on mobile devices like this.

​	**Solution:** Implemented a vertical timeline insted original idea taking up the whole container width with the full-size image now being at the end of the timeline at the bottom of the page. Looks much better on mobile devices now and in general as well.

### Deployment write-up

To deploy the website to GitHub Pages I had to go into the settings on my repository. There scroll down to the GitHub Pages section, select the branch and choose the root folder to publish it. Then save the whole setting and it was live. I have done it a few days ago to the request of my Mentor so He could see how I was doing. 

#### The live project page: https://adamsky94.github.io/milestone1/

![](/assets/images/landing.png)



GitHub document for deploying to GitHub Pages: https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

If you'd like to see and work on my code locally feel free to clone the repository. You can check out how to do that in the following GitHub document: https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository

### Credits

***Antonio Rodgrigez*** - My mentor at Code Institute - for checking up on me and my project and giving me feedback and directions

***Matt Rudge*** - Lecturer/Developer at Code Institute -  https://github.com/Code-Institute-Org/gitpod-full-template - for template used with GitPod IDE for developing this project

***Anna Greaves*** - Developer at Code Institute - for releasing helpful PDF documents regarding how to preapre MS1 project

***Bootstrap*** - https://getbootstrap.com/docs/4.5/getting-started/introduction/ - for providing documentation on the framework

***Ian Lunn*** - hover.css - http://ianlunn.github.io/Hover/ for the animation on navigation links

***Carlos Delgado*** - https://ourcodeworld.com/articles/read/480/how-to-create-a-html-link-that-interacts-with-skype-call-chat-view-profile-add-to-contacts for linking skype account to contact a person

***Shuvendu Dhenki*** - https://bootsnipp.com/snippets/p1qAD - for code segment used in gallery.html

***Kevin Powell*** -  https://www.youtube.com/watch?v=yc2olxLgKLk&ab_channel=KevinPowell - for help in positioning the footer

***bestjquery*** - https://bestjquery.com/tutorial/timeline/demo19/ - for code segment used in resume.html

***W3schools*** - https://www.w3schools.com/ - for various code segments, examples and explanations used throughout the project

***Font Awesome*** -  https://fontawesome.com/ - CDN for icons used in the project

***Google Fonts*** - https://fonts.google.com/ - CDN for fonts used in the project
 # Bark & Stride 
 Bark & stride is a site that hopes to build up a small business for a local dog walker in the North County Dublin region. 
 The site will be targeted towards local dog owners who are looking for a way to keep their dog active, social or trained. 
 Offering a wide range of services for the dog owner who is short on time but want to give their pet the very best. 
  
 ****** 
 ![Responsive Mockup](assets/images/mockup-image/amiresponsive-day.png)
 [View the live site here] (https://davetrev.github.io/bark-and-stride/)
  
 ## Features   
  
 ### Existing Features 
  
 - __Navigation Bar__ 
  
   - Featuring on all three pages, a fullly responsive navigation bar. It includes a logo, links to the Home page, Gallery and Contact page. It is identical in each page to allow for easy navigation for the user.
   - This section allows each user to easiliy navigate from each page across all devices without having to revert back to the previous page via the 'back' button.  
  
 ![Nav Bar](assets/images/mockup-image/nav-bar.png) 
  
 - __The landing page image__ 
  
   - The landing includes a photograph with text overlay to allow the user to see a aspirational scene of a happy dog relaxing in a park/ forest scene.
   - This section introduces the user to Bark & Stride with a large high impact image, grabbing the attention of dog owners.
   - the image is selected to create a connection with the users/customers and the service being offered
  
 ![Landing Page](assets/images/mockup-image/hero.png) 
  
 - __About Section__ 
  
   - The about section will allow the user to see the benefits of availing of the services of Bark & Stride, what services are offered and the areas covered
   - This user will see the value of contacting and availing of the service, to engage the dog owner with not just dog walking services but also the love of animals from the service but also trustworthiness.
  
 ![Index page / About section](assets/images/mockup-image/index-page-layout.png) 
  
   
 - __The Footer__  
  
   - Featuring on all three pages, a fullly responsive footer navigation bar. It includes links to social media. It is identical in each page to allow for easy navigation for the user.  
   - The footer section includes links to the relevant social media sites for Bark & Stride. The links will open to a new tab to allow easy navigation for the user.  
   - The footer is valuable to the user as it encourages them to keep connected via social media
  
![Footer](assets/images/mockup-image/footer.png) 
  
 - __Gallery__ 
  
   - The gallery will provide the user with supporting images to see aspirational images of happy dogs on walks, as the business grows, I would plan to add testimonials of happy customers but also bios of staff and pups that use the service
   - At present, at the top of the gallery page, I have placed some simple tweet reviews from customers, again looking to build a connection for the buisness and their target market.
   - This section is valuable to the user as they can identify with what they want for their pet and can identify with the service offered
  
  
 ![Gallery](assets/images/mockup-image/gallery.png) 
  
 - __The Contact Page__ 
  
   - This page will allow the user to contact the business owner to arrange walks for their dog and to send queries regarding the service.
  
 ![Sign Up](assets/images/mockup-image/contact.png) 
  

  
 ### Features Left to Implement 
  
 - On the gallery page I would like to add a section of "Favourite dogs" or "Dog of the month", highlighting happy dogs and little bios on each pet.
 - Adding a map of nearby parks that are used.
 - Adding video content of dogs engaged with the walker and the surrounding area via youtube links
  
 ## Testing  

 ### Validator Testing  
  
 - HTML 
   - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?useragent=Validator.nu%2FLV+http%3A%2F%2Fvalidator.w3.org%2Fservices&acceptlanguage=&doc=https%3A%2F%2Fdavetrev.github.io%2Fbark-and-stride%2F) 
 - CSS 
   - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdavetrev.github.io%2Fbark-and-stride%2Fcontact.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

 - Lighthouse
  
 ### Unfixed Bugs 
  
 While trying to build a website that is responsive across all devices, using the dimensions of a galaxy fold, the break point of 280 px in width would cause a gap on the right side of the screen. the image sizing and media queries need to address this.

 The index page, I would like to have figured out a way to have the dog be the central focus of the photo across all devices, using flexbox, the image is shifting in place depending on the device used.   
 I had originally built the site desktop first and in learning more about responsive design, I realise from the project outset, I should build mobile first and work out as it is easier to deal with issues in that manner. 
  
 ## Deployment 
  
 - The website was deployed to Github pages. The steps to deploy are as follows:
    - Login to Github and find the Github repository 'bark-and-stride'
    - Click on the 'Settings' button at the top of the repository
    - Click on 'Pages' on the left hand side navigation menu
    - Select 'Deploy from a branch' under 'Source' if this is not already selected
    - Under the 'Branch' drop down menus, select 'main' and 'root'
    - Click 'Save'
    - Once the page refreshes, the live link should appear underneath the 'Github Pages' title
  
 The live link can be found here - https://davetrev.github.io/bark-and-stride/index.html 
  
  
 ## Credits  
  
 ### Content  
  
 - All content was written by myself but was inspired by Dublin based dog walker websites, which I used for inspiration are as follows:
 - https://all-dogz-go-walkies.business.site/?utm_source=gmb&utm_medium=referral
 - https://www.dogwalking.ie/
 - https://www.borrowmydoggy.com/dogs-near-me/dublin
 - http://www.pawfit.ie/

 - As a guide to learning flexbox and building layouts with css, I used the youtube video series from [Netninja] (https://www.youtube.com/watch?v=xPuYbmmPdEM)
 - Building a responsive contact form was taken from / used as a follow along guide [Plant pot works blog](https://plantpot.works/2827) 
 - Used a example of a flexbox design incorporating text and images helped build the index page and contact page format [Codepen](https://codepen.io/paulobrien/pen/baobra)
 - For a flexbox designed image gallery I used the following as a example [Logrocket blog](https://blog.logrocket.com/responsive-image-gallery-css-flexbox/)
 - As a guide to building up a responsive hero image the following links were used to learn how to use flex box [Codepen](https://codepen.io/njericooper/pen/NVRQLe) 
 - (https://nicolaslule.com/responsive-full-width-hero-image-using-flex/) 
 - (https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Aligning_Items_in_a_Flex_Container)
 - Using the follwoing guide to help create a responsive navigation bar and using the lessons learned to create a responsive footer to match (https://adiati.com/how-to-create-a-responsive-navigation-bar-with-flexbox-and-media-queries)
 - The icons in the footer were taken from [Font Awesome](https://fontawesome.com/) 
 - Created responsive mockups with [amiresponsive] (https://ui.dev/amiresponsive)
  
 ### Media 
  
 - All images were taken from [Pexels](https://www.pexels.com/), [Unsplash](https://unsplash.com/)











# South Coast SUP
___

## Project Synopsis


Stand-up paddleboard club based on the south coast with the goal of providing information and connecting local surfers and stand up paddleboarders. 
Will have details of regular meet-ups, information on the local area and the ability to sign up to a newsletter. 

[See the live site here!](https://timmorrisdev.github.io/south-coast-sup/)

___
## User Experience (UX)

### User Stories

- First time user goals
    1. As a first time user, I want to easily gain information about the local paddleboard community.
    2. As a first time user, I want to easily find information about the sport and some of the benefits to taking part.
    3. As a first time user, I want to find out where I can paddleboard in the local area and advice on the best times to go.
    4. As I first time user, I want the option of signing up to a newsletter to receive updates on club activities.

- Second time user goals
    1. As a returning user, I want to be able to connect with the clubs social media pages.
    2. As a returning user, I want up-to-date information about weather and water conditions.

- Frequent user goals
    1. As a frequent user, I want to easily navigate the site to find information about meet-ups and events.

### Business Goals

- Immediate
    1. To create a paddlebaord community and provide information.
    2. To gain subscriptions to the newsletter.
    3. To attract people to take part in organised events, both paid and free.

- Future goals
    1. To gain sponsorship  from local business and paddleboard brands.
    2. To drive up social media followers and engagement to both build the club visibility and attract partnerships with brands. 

### Design

- Colour Scheme
    - Blues and dusky greys, sunset orange details. Soft greens when appropriate for imagery. [View colour palette](https://github.com/TimMorrisDev/south-coast-sup/blob/master/assets/images/SurfSUP3.png)
    - Light grey text with white hover.

- Fonts
    - Montserrat / Lato / Quicksand

- Wireframes
    - [Landing Page](https://github.com/TimMorrisDev/south-coast-sup/blob/master/assets/wireframes/Landing%20Page.png)
    - [About the club](https://github.com/TimMorrisDev/south-coast-sup/blob/master/assets/wireframes/About.png)
    - [Why / Where / Event pages](https://github.com/TimMorrisDev/south-coast-sup/blob/master/assets/wireframes/Why_%20_%20Where%20_%20Events%20pages.png)
    - [Signup page](https://github.com/TimMorrisDev/south-coast-sup/blob/master/assets/wireframes/Signup.png)


___
## Features
- Responsive across all devices and screen sizes.
- Adaptive to modify content shown to be appropriate for user device or screen size.
- Have appropraite, real-time information for the user.


___
## Technologies Used
### Languages Used
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/CSS)

### Frameworks, Libraries & Programs Used
- [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
    - Bootstrap was used for the responsive 'grid'. Code snippets from the Bootstrap documentation were used in various places and modified to suit the purpose and design of the site.
- [jQuery](https://jquery.com/)
    - jQuery came as part of Bootstrap and was used for Javascript plugins such as the responsive nav bar and modals.
- [Google Fonts](https://fonts.google.com/)
    - Google Fonts was used to import the 'Montserrat', 'Lato' and 'Quicksand' fonts, which were used throughout the site.
- [Font Awesome](https://fontawesome.com/)
    - Used to source images for the 'why SUP' card headings.
- [Hover.css](https://ianlunn.github.io/Hover/)
    - Hover.css was used in the nav bar to animate the menu items.
- [Git](https://git-scm.com/)
    - Git was used for version control using the terminal in Gitpod to 'add' and 'commit' to Git and to push changes to the GitHub repository using 'git push'.

- [Gitpod](https://gitpod.io/)
    - Gitpod.io was used as the primary development environment when coding for the site. It's terminal was used to preview the site via temporary server, and for version control using Git commands.
- [Github](https://github.com/)
    - GitHub was used to store the code pushed from Gitpod and as deployment for the [published site.](https://timmorrisdev.github.io/south-coast-sup/)
- [Balsamiq](https://balsamiq.com/)
    - Balsamiq was used to create the wireframes for the site while in the 'skeleton' stage of my UX process.

___
## Testing
### Lighthouse testing
I used Lighthouse performance reports genrated in Google dev tools during the later stages of site development to identfiy any areas that I could improve the performance, accessibility, best practices and SEO across the site. 

Issues identified and actions taken:
- Large image files slowing down performance.
    - I fould that my background image and imagees displayed in other areas of the site were too large and affecting performance. By using [tinypng.com](https://tinypng.com/) I was able reduce the files sizes and fix the performance issue.

- Headings not arranged in a sequentially-descending order.
    - Due to my use of some code copied from the Bootstrap documentation, my heading elements were not sequential in their order. I was able to change this in my HTML and override the bootstrap styling using CSS to keep the styles and sizing as I wanted across the site.

- Readability issue with signup and register buttons across the site.
    - Lighthouse found that the contrast between the background colour and text colour of the .btn-signup button class to have readability issues. I used [webaim.org](https://webaim.org/resources/contrastchecker/) to input the current colour scheme and find an appropriate alternative that both fit my colour palate, and scored well on accessibility.

### Testing UX user stories
- First time user goals
    1. As a first time user, I want to easily gain information about the local paddleboard community.
        - I was able to find that there is an active community in the area that encourages group participation and social events, both on and off the water.
    2. As a first time user, I want to easily find information about the sport and some of the benefits to taking part.
        - I found several examples of reasons to participate in the sport as well as some positive results I may see from doing so.
    3. As a first time user, I want to find out where I can paddleboard in the local area and advice on the best times to go.
        - There were several examples of places in the local area to paddlebaord and it was easy to see the real-time conditions at each as well as a google maps link to easily locate the places being referenced.
    4. As I first time user, I want the option of signing up to a newsletter to receive updates on club activities.
        - I was promped to sign up to the newsletter to receive regular updates and there were easy-to-see buttons across the site to link to where I could sign up. 

- Second time user goals
    1. As a returning user, I want to be able to connect with the clubs social media pages.
        - Links to the club's social media pages were clear across the site and easy to identify and navigate.
    2. As a returning user, I want up-to-date information about weather and water conditions.
        - Using the information about suggested routes I could see detailed, real-time weather and water conditions at each of the locations.

- Frequent user goals
    1. As a frequent user, I want to easily navigate the site to find information about meet-ups and events.
        - The events page allowed me to see what oranised group events were upcoming and it was easy to register me and my friends to take part. 

___
## Deployment
### GitHub Pages
The project was deployed to GitHub pages using the following method. 
1. Log in to [GitHub.com](https://github.com/) and locate the south-coast-sup reposotory in my account.
2. Selct the repo 'settings' menu and navigate to the 'pages' tab on the left hand side.
3. In the 'source' section, select the master branch as the source for the site deployemnt. 
4. Hit 'save' and wait a few mins for GitHub to process. The 'pages' settings tab will now show a message to confirm the reposotory is being published to the address https://timmorrisdev.github.io/south-coast-sup/.

### Forking the reposotory in GitHub
Forking the repository creates a copy of the original repository in your own account to allow chages to be made without affecting the original repository.
1. Log in to GitHub and navigate to the GitHub repository page.
2. In the top-right of the page, below the user avatar, locate the "fork" button.
3. Click the "fork" button and you should now have a copy of the repository in your own account. 

### Making a Local Clone
Details of how to make a local copy of the GutHub repository can be found [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). To clone using HTTPS follow these steps.
1. Navigate to the GitHub repository.
2. Click the "Code" drop-down menu above the list of files.
3. Copy the HTTPS address to the clipboard using the button provided.
4. Open Terminal.
5. Change the current directory to the location you wish to copy the directory.
6. Type 'git clone' and then paste the HTTPS url you copied earlier. 
7. Press enter and your local clone will be created. 

___
## Credits
### Code
- Bootstrap nav bar, card, signup form, modal and button template code used in places and modified to suit purpose of the site.
- [css-tricks.com](https://css-tricks.com/perfect-full-page-background-image/) article inspiration for 'min-height' solution to background image display issues on index.html.
### Content
- All content written by the developer.
- [British Canoeing](https://www.britishcanoeing.org.uk/membership) website used to research part of the routes offered in 'where to SUP'.
### Media
- Main background image by [Sebastian Voortman](https://www.pexels.com/photo/man-and-woman-boat-rowing-in-sea-during-golden-hour-165505/) found on Pexels.com.
- aboutImage1 by [Paddle North](https://unsplash.com/photos/BDK_ytyH-PA) found on unsplash.com.
- aboutImage2 by [Paddle North](https://unsplash.com/photos/FslRftM-CtM) found on unsplash.com.


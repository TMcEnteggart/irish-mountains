# Irish Mountains

Irish Mountains is a site for beginner hikers that will provide the information they need to get started hiking in Ireland. Irish Mountains provides resources to users such as lists of hiking equipment they will need, hiking locations ranging in difficulty, as well as a newsletter users can sign up for to keep up to date on new locations and info. This site will be targeted at hiking beginners, but will also be useful for outdoors oriented tourists who wish to see some of Irelands natural beauty. The live site can be visited [here](https://tmcenteggart.github.io/irish-mountains/index.html)

![Mockup](/docs/snippets/mockup.png)

## Features

### Site Wide
* Navigation Menu
    * Contains links to the Home, Locations and Newsletter pages for quick site navigation on all devices.
    * Link to the users current page has a different color so the user knows what page they are currently viewing.

![Nav Menu](/docs/snippets/nav_bar.png)
* Footer
   * This will contain icon links to social media websites. These websites will open in a new tab and be accessable to screen reader users by aria labels.
   * This will allow users to follow the Irish Mountains community on social media that may contain more up to date information than the site.

![Footer](/docs/snippets/footer.png)

* Unique Landing Page Image
   * Each page will have a unique landing image.
   * The landing images show the user some of the landscapes that hiking has to offer.
   * Each landing image will be animated to catch the users attention.
   * The Newsletter landing image instills a sense of community in the user appropriate to the goal of the page.

#### Home Page Landing Image
![Home Landing Image](/docs/snippets/home_landing_image.png)

#### Newsletter Page Landing Image
![Newsletter Landing Image](/docs/snippets/newsletter_landing_image.png)

### Home Page
![Home Page](/docs/snippets/home_page.png)
* Welcome Section
   * This section welcomes the user to the site, details the sites purpose and contains the essential items lists for hiking preparation.
   * Includes links to other pages of the site to encourage user interaction.
  
![Welcome](/docs/snippets/welcome.png)
* Essentials Sections
   * Briefs the user on why hiking specific gear is needed.
   * This will include a link to Amazon for user convinience.

#### Essentials Section
![Essentials](/docs/snippets/essentials.png)

#### Link to Amazon
![Amazon Link](/docs/snippets/amazon_link.png)

* Items Lists
   * A pair of lists containing "Essential" hiking gear and "Optional" hiking gear respectively.
   * These lists will allow the user to determine what gear they need for their hike as well as acting as a checklist for the user while preparing for a hike.
   * When viewed on a small sized device, these lists will display in a column for increased responsiveness.

#### Essentials Checklist
![Essentials List](docs/snippets/essential_list.png)

#### Optional List
![Optional List](/docs/snippets/optional_list.png)

#### Standard List View
![Horizontal Lists](/docs/snippets/both_lists.png)

#### Column List View
![Vertical Lists](/docs/snippets/list_column.png)

* What Now Section
   * Simply acts as a signpost guiding users to the location page upon finishing the essentials guide.
   * Contains a link to the locations page.

#### Locations Link
![Locations Link](/docs/snippets/locations_link.png)

### Locations Page
![Locations Page](/docs/snippets/locations_page.png)

* Locations
   * The locations page is designed to provide the user with Irish Mountains top 3 hiking trails to experience. Each trail section will contain the name, location,  image of the trail, trail length, trail difficulty and a brief description of the trail.
   * The 3 trails are structured in ascending order of difficulty, starting from easy. This allows users new to hiking quick access to the easy trail, while giving the page a natural progression in trail size and difficulty. 

![Easy Trail](/docs/snippets/trail_1.png)

![Moderate Trail](/docs/snippets/trail_2.png)

![Hard Trail](/docs/snippets/trail_3.png)

* Locations Intro
   * A brief introduction to the locations page.
   * Outlines to the user that the trails are listed in ascending order of difficulty.

![Locations Intro](/docs/snippets/locations_intro.png)

### Newsletter Page
![Newsletter Page](/docs/snippets/newsletter_page.png)

 * Newsletter
   * The newsletter page is designed for users to sign up for the Irish Mountains newsletter to stay updated on new info and trails.
   * This page contains a form element wherein users fill ot their first name, last name and email address. Completion of the form brings the user to a signup successful confirmation page.
   * The input fields for the form will have the required property, to ensure form submissions are functional.
 
 * Newsletter Form
   * This form will allow users to sign up for an optional newsletter using their name and email address.
   * This will encourage users to join the Irish Mountains community and keep them informed on future updates.
 
 ![Newsletter Form](/docs/snippets/form.png)
 
 ### Successful Sign-up Page
 ![Form Complete](/docs/snippets/form_complete.png)
 
 * Successful Sign-up Page
   * This page will appear when a user has successfully completed the newsletter form.
   * This page will contain the same header and footer as all other site pages, allowing the user to return to any point of the site using the nav bar.
 
### Existing Features

* Hiking supplies guide with external link to Amazon
* Hiking locations list arranged by trail difficulty 
* Responsive design on all site pages
* Newsletter form with success page upon completion

### Features To Be Implemented

* A map to each trail location will be implemented to the locations page using Google Maps for user convenience.
* Automated email generation confirming a users newsletter subscription.
* Group event meeting and planning page for Irish Mountain community members.

## Technologies

* HTML
   * HTML was used as the main language for the sites structure,
* CSS
   * The website was styled using CSS a style sheet.
* GitHub
   * Used to store the repository for the site.
* GitPod
   * Used as the workstation for coding the HTML and CSS stylesheet as well as uploading image files to the site.
* GitPages
   * Used to deploy the finished site.

## Testing

### Responsiveness

Each page of the site was tested for responsiveness on screen sizes of 320px upwards using Chrome developer tools.

How it was tested:

1. Open browser and go to [Irish Mountains](https://tmcenteggart.github.io/irish-mountains/)
2. Open the developer tools by right clicking anywhere and selecting "inspect"
3. Set the dimensions to "Responsive" and set width to 320px
4. Set zoom to 50%
5. Slowly drag the responsive window to max width, checking for deviations in site structure
6. If a deviation occurs, navigate to a different page of the site to check if the deviation persists

Expected: 

Website responsive on all screen sizes from 320px upwards. No pixelated or stretched images, no horizontal scroll and no overlapping of site contents.

Actual:

Website was responsive as expected, however when viewing at 320px width an overlap of the navigation menu and hero image occurred. This issue disapeared when refreshing the page and re-booting developer tools.

![Bug Screenshot](/docs/bugs/320px_bug.png)

## Accessibility

Accessibility for the site was tested using [Wave Accessibility](https://wave.webaim.org/) followed by manual testing using a keyboard only.

Wave did not detect any errors when tested throughout the website. Manual testing was successful, as I could navigate all facets of the site using a keyboard alone.

#### Home Page Wave Results
![Home Wave Test](/docs/snippets/home-wave.png)

#### Locations Page Wave Results
![Locations Wave Test](/docs/snippets/wave-locations.png)

#### Newsletter Page Wave Results
![Newsletter Wave Test](/docs/snippets/newsletter_wave.png)

#### Signup Page Wave Results
![Signup Wave Test](/docs/snippets/signup_wave.png)

## Functional Testing

### Navigation Links

All navigation links on the site were tested for correct link location and to open in a new tab if linked to a site other than Irish Mountains.

All links functioned as expected when tested.

### Form Testing

The newsletter signup form was tested to ensure all required fields were functional and that the success page would load once details were entered. 

The newsletter formed functioned as expected when tested.

## Validator Testing

* HTML
   * HTML was tested using [W3C Validator](https://validator.w3.org/)
   * One consistent error occured when checking the HTML of the site. I incorrectly used a "section" element for my hero image when I should have used a "div", as the HTML did not contain a heading for the section element. This was fixed post validation.
   * I also incorrectly applied an "alt" attribute to a div as the div contained an image file. This was also corrected post validation.
 
![HTML Validation Errors](/docs/snippets/w3_newsletter.png)

* CSS
   * CSS was tested using [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
   * No errors occured when testing CSS

![CSS Test](/docs/snippets/css_test.png)

## Deployment

### Version Control

The site was created using GitPod and pushed to GitHub to the repository "irish-mountains'.

The following git commands were used through development to add, commit and push code to the repo:

* 'git add .' - Used to add file(s) to the staging area before commitment.
* 'git commit -m "commit message"' - Used to commit changes to the repository with an accompanying message.
* 'git push' - Used to push all committed code to the repository.

### Deployment to GitHub Pages

* The site was deployed to GitHub Pages using the following steps:
   * In the GitHub repository, click the Settings tab
   * Select 'Pages' from the left menu
   * From the source drop-down menu, select the "main" branch
   * Click Save
   * After a couple of minutes, the site is deployed and a link to the site will be displayed in a green banner if successful.

The live link to Irish Mountains can be found here - https://tmcenteggart.github.io/irish-mountains/

## Credits
* [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
   * Flex styles used in the site were learned from this site.

* [CSS Lists](https://www.w3schools.com/css/css_list.asp)
   * Square bullet point list styles used in '.trail-info' was learned from this site.

### Content & Media

All content and media on the site was taken from open source site [Pixabay](https://pixabay.com/) 

 








 
 
 
 
 


 
 







  


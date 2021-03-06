
# Themepark Finder
## Interactive Front-End Milestone Project 2 

Themepark Finder is a website created with HTML, CSS and JS utilising the Google Maps API to allow a user to search for an amusement, theme park and accommodation and view additional information about that park.

The website was created to enable a visitor to search, view and plan a trip (vacation) to an amusement or theme park in the United Kingdom.

THe website is deployed [here](https://barrydalton.github.io/ThemeparkFinder/)


<div style="text-align:center;">
<img src="https://i.imgur.com/31489CF.png">
</div>




 
## UX
 
The website was created as a single page that is split over 4 pages (landing page, about us, carousel, Google Map with some filtering and results and a contact form to allow a visitor to the site to make enquiries)

As a user to the site:
- As a visitor, I want to perform an action, so that I can achieve a goal.
- As a visitor, I want to be able to search for a city in the United Kingdom and see a list of themeparks.
- As a visitor, I want to be able to search for a city in the United Kingdom and see a list of corresponding hotels.
- As a visitor, I want to be able to filter the search results between themeparks and hotels.
- As a visitor, I want to be able to find additional information about a theme park or hotel by selecting the name from search results.


### Wireframes

<div style="text-align:center;">
<img src="https://i.imgur.com/DnUcEZ8.png">
</div>


## Features

    The design started out on paper and I did a quick mockup to get some ideas down, from there I moved over to Balsamq and finalised the design.
    My plan was to have a simple navigation that was responsive and intuitive for a user. 

- Landning page / top image of a rolldercoater and some text
- About us / intro to to why and how the website was created.
- Find a theme park / using Google Maps API to create a searchable country list that autocompletes and lists the avaialbe themeparks.
- Contact Form / to make enquires or to make a booking.

### Features to Implement
- Enhancements to the search function.
- Add additional countries to expand coverage.
- Add additional filters and navigation.
- Add FAQ and additional page with information about different theme parks and their attractions.
- Add function to allow visitors to submit reviews, recommendations and tips.


## Technologies Used

This website uses HTML, CSS and JS programming languages.

- [Gitpod](https://www.https://www.gitpod.io/) IDE Editor
- [Bootstrap](https://www.https://getbootstrap.com/) The project uses **Bootstrap 4** to create a responsive website.
- [Bootstrap 4 with CDN Boilerplate extension](https://www.https://github.com/Eventyret/vscode-bcdn/) to provide Bootstrap 4 starter template. With jQuery, popper.js and Font-Awesome 5
- [Google Fonts](https://fonts.google.com/) The project uses **Google fonts** to style the website fonts.



## Testing

For this project I checked to ensure the website would work with 3 popular web browsers Chrome, Firefox and Edge (although this will be deprecated)
To check the website is responsive and sizes correctly deepening on the size of the browser window.

1. Website navigation and functionality 
    1. Try to click on each button in the navigation menu and that each button links to the relevant section (About Us Find/Google Map and Contact form).
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit an invalid city in the UK and only shows an overview map of the United Kingdom.
    4. Try to submit the form with all inputs valid and verify that a success message appears.
    5. Try to enter a UK city name, such as London, Manchester, Blackpool and the map populates with locations.
    6. Try and click on the amusement button and 

- Interesting bugs or problems you discovered during your testing.
    - Testing the contact form - the required fields are not working as intended and am troubling shooting this. (this is likely an issue with the html tags)
    
- The developer used **W3C CSS Validation Service** and **W3C  Markup Validation Service** to check the validity of the website code.
    - [W3C CSS validation](https://jigsaw.w3.org/css-validator/)
    - [W3C Markup Validation]( https://validator.w3.org/)
    - [Font Awesome](https://fontawesome.com/) - Social Media Logos
    - [GIT](https://git-scm.com/) - Version Control
    - [GitHub](https://github.com/) - to host the repositories for this project and the live website preview


## Deployment

This project was developed using the [Gitpod Cloud IDE](https://gitpod.io/), committed to git and pushed to GitHub using the built-in function within Gitpod.

To deploy this page to GitHub Pages from its [GitHub repository](https://barrydalton.github.io/ThemeparkFinder/), the following steps were taken: 
1. Log into GitHub. 
2. From the list of repositories on the screen, select **barrydalton/ThemeparkFinder**.
3. From the menu items near the top of the page, select **Settings**.
4. Scroll down to the **GitHub Pages** section.
5. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
6. On selecting Master Branch the page is automatically refreshed, the website is now deployed. 
7. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.

At the moment of submitting this Milestone project the Development Branch and Master Branch are identical. 

### How to run this project locally

To clone this project from GitHub:
1. Follow this link to the [Project GitHub repository](https://barrydalton.github.io/ThemeparkFinder/).
2. Under the repository name, click "Clone or download".
3. In the Clone with HTTPs section, copy the clone URL for the repository. 
4. In your local IDE open Git Bash.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/USERNAME/REPOSITORY
```
7. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://help.github.com/en/articles/cloning-a-repository).


## Credits

### Content
- [W3Schools](https://www.w3schools.com/) for its endless resources
- [Google Place autocomplete hotel search](https://developers.google.com/maps/documentation/javascript/examples/places-autocomplete-hotelsearch)
- [Bootstrap Modal] (https://getbootstrap.com/docs/4.0/components/modal/)
- [Place Autocomplete Hotel Searc] (https://developers.google.com/maps/documentation/javascript/examples/places-autocomplete-hotelsearch) I adapteted the example Google provided to find hotels"
- [Google Maps API Places ](https://developers.google.com/places/supported_types)
- [Bootstrap 4 with CDN Boilerplate extension](https://www.https://github.com/Eventyret/vscode-bcdn/) provied the boilerplate template for Gitpod.

### Media
- The photos used in this site were obtained from Google image search.

### Acknowledgements

- I received inspiration for this project from many travel programs and watching rollercoaster videos on YouTube.
- My mentor Brian Macharia - for his guidance.
- Code Institute Slack Community!




## DISCLAIMER - THIS WEBSITE IS FOR EDUCATIONAL PURPOSES ONLY.

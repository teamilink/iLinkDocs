# T3A2 - Part A

## R1 Description

### Purpose

iLink is an application that offers digital marketing professionals the tool to optimise their social media presence by linking all their social media platforms and promotion links (landing page) together under one main URI link endpoint. 

Below are the benefits that offered by iLink:
- The application allows users to add multiple landing page links or call to action buttons.
- Users can direct their web traffic to specific landing pages (promotion) or other target pages on their website and add as many links as they want. 
- Businesses can enhance their brand identity with a custom image and links.

By having this capability of iLink, users such as small business owners or digital marketers are able to better manage their social media presence by giving their followers a convenient way to and one-click process to all their online contents on the internet.


### Functionality / features

Account Creation
- User Login/Logout and New Account Registration
- Image uploaded for user profile picture
- Random image from a batch of images via unsplash API if no profile image is uploaded by the user. 
- Fill up basic information of the user 
- **Optional** - Premium (paid) service for a custom link, custom background, remove service logo, etc

Account Dashboard
- Create and generate new card (main URI endpoint link)
- Add new URI links with title and description into the card
- View, update or delete existing links to the card
- **Optional** - Payment with Stripe


### Target audience

This app aims at social media influencers, marketing and branding professionals and other social media content creators that are looking to grow and gather all their followers across multiple different platforms into one single platform for their web visitors. 


### Tech stack

The following is the technology stack used for this project.

**Programming Language:** Ruby and Javascript

**Client Side:** React.js library, Material UI & Styled components. 

**Server Side:** Ruby on Rails framework 

**Testing:** RSpec, Jest

**Database:** PostgreSQL

**Cloud Storage:** Amazon S3

**Cloud Hosting:** Netlify for Client side and Heroku for server side

**Utilities:** Balsamiq Wireframes, Draw.io

**DevOps:** Github, Git Version Control, Visual Studio Code

**Project Management Tools:** Trello and Discord 


## R2 Dataflow Diagram

![](/docs/T3A2-DFD.png)

### ERD for reference

![](/docs/T3A2-ERD.png)

## R3 Application Architecture Diagram

![](/docs/T3A2-AAD.png)


## R4 User Stories

1. As a digital marketer, he/she should be able to register for a new account with his/her information and profile image, so that he/she could use the service for my marketing purposes. 

2. As a digital marketer, he/she should be able to log in with secure authentication into his/her account, so that he/she could manage all their social media and landing pages links with the service.

3. As a digital marketer, he/she should be able to upload his/her profile image, so that they could make a personalised page.

4. As a digital marketer, he/she should be able to choose a random image, so that they could create the page look better.

5. As a digital marketer, he/she should be able to create a new card in his/her account, so that he/she could gather all his/her links and add everything into the card.

6. As a digital marketer, he/she should be able to see the preview of the page, so that he/she could check what the links look like and update them if needed.

7. As a digital marketer, he/she should be able to view all the links that he/she has added into the system, so that he/she could make any changes of links and descriptions to make sure all are correctly added. 

8. As a digital marketer, he/she should be able to remove or edit any existing links, so that he/she could change the links that he/she had added incorrectly previously.

**Optional**
9. As a digital marketer, he/she should be able to register for the premium service, so that he/she could use the additional features of the service.
 
10. As a digital marketer, he/she should be able to use the payment service, so that he/she could proceed with the purchase of the premium service.


## R5 Wireframes

### Home Page

![](/docs/wireframes/HomePage.png)

- The username typed in the input field will be taken to the register page
- The username will be the endpoint of the created link
  eg. `https://iLink.in/yourname`

### Sign up Page

![](/docs/wireframes/RegisterPage.png)

- If the sign up is successful, the new user will be taken to the dashboard
- Otherwise, it shows an error message to the user

### Login Page

![](/docs/wireframes/LoginPage.png)

- If the login succeeds, the new user will be taken to the dashboard
- Otherwise, it shows an error message to the user

### Dashboard - Link

![](/docs/wireframes/Dashboard-Links.png)

- Dashboard has a separate navigation bar
  - Links and Appearance tabs for creating a card in the Dashboard
  - Upgrade and Logout tabs take the user outside of the Dashboard
- By default, there are three input fields for creating links
- A user can control the visibility of each link using the switch button
- Each link can be reset once clicked a trash icon
- Users can preview the card while creating on the right side of the screen. For mobile view, there will be the Preview button instead
- Once Save button is clicked the input data is stored in the database

### Dashboard - Appearance

![](/docs/wireframes/Dashboard-Appearance.png)

- A profile photo can be uploaded
- User can manipulate their bio
- Background colour can be changed using a colour picker
- A background image can be set using Random button
- Add Background Image will be a paid feature
- Remove Image button resets the background images and uses just a colour
- Likewise Link tab, users can see the preview

### Upgrade

![](/docs/wireframes/UpgradePage.png)

- Upgrade page is an extra feature after completing MVP
- Get Primium button is linked with Stripe for payment
- Upgrade page will connect to additional features
  - Add extra links
  - Add a background image file or set a custom background image

## R6 Screenshots of the Trello board

Trello project management tool is being used throughout the entire project from planning stage to implementation.

We started off the project by planning and designing the system documentation that covers the application architectural and wireframe of the site. By keeping track of the process, we took advantage of the trello management tool which allows us to create a board with multiple cards that represents each task that needs to be included in the system documentation. Then, each task is being allocated fairly to each member of the group with a deadline.

Each member of the group will then be responsible for the task assigned to them and mark off the task once completed. The group is working on the project remotely from Brisbane and Sydney. The following screenshot showed the progress of our work throughout the planning process. For more information, you could preview the full version of our trello board at [**here**](https://trello.com/b/vwtGNhLx/t3a2-part-a)


Stage 1 - Design planning
![](/docs/trello/Stage1-Planning.PNG)

Stage 2 - Progressing
![](/docs/trello/Stage2-Progressing.PNG)

Stage 3 - Completed
![](/docs/trello/Stage3-Completed.PNG)

Stage 4 - Project implementation start (Part B)
![](/docs/trello/Stage4-Project-Implementation.PNG)
# T3A2 - Part A

## R1 Description

### Purpose

### Functionality / features

### Target audience

### Tech stack

## R2 Dataflow Diagram

![](/docs/T3A2-DFD.png)

### ERD for reference

![](/docs/T3A2-ERD.png)

## R3 Application Architecture Diagram

![](/docs/T3A2-AAD.png)

## R4 User Stories

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

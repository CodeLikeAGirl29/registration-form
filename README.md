# Online Registration Form

[![Netlify Status](https://api.netlify.com/api/v1/badges/a39bae06-e6a0-4717-a2a4-100fe1c0b000/deploy-status)](https://app.netlify.com/sites/my-registration-form23/deploys)

This project is the [third project](https://teamtreehouse.com/projects/an-online-registration-form) for Team Treehouse's Frontend Development course.

In this project, you'll build a responsive, mobile-friendly registration form using a wide variety of HTML form input types and attributes. Using the supplied mockup files, you'll build a mobile and desktop version of the form using media queries, and a "mobile-first" approach.

> Live link for this project can be found [here](https://my-registration-form23.netlify.app/)

  ## Screenshot

  ![screenshot](https://res.cloudinary.com/codelikeagirl29/image/upload/v1681316430/projects/Treehouse-Online-Registration-Form_kpmvov.pngg)

## Instructions
1. Build the layout using __mobile first design__:
- Make sure the HTML file includes the viewport meta tag in the head of the document, see Configuring the Viewport to understand why and how to add this tag.
- Look at the provided mockup (mobile-form.png) and add the same content to your index.html file.

2. Create the form structure:
Only use one ```<form>``` tag. The ```<form>``` tag should contain all the form elements. Add a ```fieldset``` and ```legend``` for each of the following sections:
- "Contact Information" section of the page, and
- The "Newsletter" section of the page

3. Make sure you include the following form field types:
- text input
- email input
- telephone input
- select menu
- checkboxes
- radio buttons
- textarea
- submit button

4. Form fields should include the following attributes:
- ```input```: should include ```id```, ```type``` and ```name``` attributes.
- ```select``` and ```textarea```: should include ```id``` and ```name``` attributes.

5. Add labels to each form element using the HTML ```<label>``` tag. The text inside the labels should match the names of the form fields in the mockups.
- Make sure you properly pair each ```<label>``` element with its corresponding form control via the ```for``` attribute. See the link above for an example. And don't forget about the textarea element. That needs a functioning label too.

6. Use the input field's ```placeholder``` attribute to add the text "required" to:
- the Full Name field
- the Email address field

7. Once you have everything in place for the mobile layout, use a media query to add a breakpoint to adjust the layout for wider tablet and desktop screens.
- Match the design as it should look on a tablet or desktop that is 768px wide using the desktop-form.png mockup.
- Use a mobile-first approach by writing your media queries using the ```min-width``` property in your CSS.

8. Once all your breakpoints are in place, double check your layout matches both the mockups.
- Check that the label text position matches both mockups:
  - ***Mobile***: Text should be above the form field.
  - ***Desktop***: Text should be to the left side of the form field.

9. Use a Google Font for the text

10. Add ```:focus``` states to the form for when a user clicks or tabs into a text field.

11. Make sure to check your code is valid by running it through an HTML and CSS validator.
- Links to the validators can be found in the Project Resources. This will help you spot any errors that might be in your code.
- There are a few exceptions that you don’t need to fix:
  - Don’t worry about any warnings, we just need you to check any errors that might be there.
  - If CSS validator flags use of calc, vendor prefixes or pseudo-elements/pseudo-classes these errors should be ignored.
  - If HTML validator flags use of pipe (‘|’) in Google font links/URLs this error can also be ignored.

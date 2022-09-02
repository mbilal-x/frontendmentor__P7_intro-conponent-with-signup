# Frontend Mentor - Intro component with sign up form solution

This is a solution to the [Intro component with sign up form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/intro-component-with-signup-form-5cf91bd49edda32581d28fd1). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - Any `input` field is empty. The message for this error should say *"[Field Name] cannot be empty"*
  - The email address is not formatted correctly (i.e. a correct email address should have this structure: `name@host.tld`). The message for this error should say *"Looks like this is not an email"*

### Screenshot

![](./images/Capture.PNG)
![](./images/capture_iPhone%20SE.png)

### Links

- Solution URL: [Solution](https://github.com/mbilal-x/frontendmentor__P7_intro-conponent-with-signup)
- Live Site URL: [Live Site](https://mbilal-x.github.io/frontendmentor__P7_intro-conponent-with-signup)

## My process
My focus on this design was to practice BEM naming system for classses.
I thought this would be an easy design for me to code. However, I still learned a few new things that I didn't know before.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned
flexbox justify-content doesn't center the stuff inside the flex-items,
if you give these children of flex-items a width less than their parents, they will be justified to the left of the space [default]. Also, it's better to not use width and just adjust the padding, the element width remains the same, yet the content space is changed[or you can also say that it's the white space thats changing]. 

### Continued development
- This code still only use html validation, I will add Js validation after I get the hang of it.
- The form submit method is the defualt Get method. That too, I will change later.

## Author

- Frontend Mentor - [mbilal-x](https://www.frontendmentor.io/profile/mbilal-x)

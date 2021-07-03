Single-Price Grid Component | Front-End Mentor

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Links

- Solution URL: https://www.frontendmentor.io/solutions/responsive-mobilefirst-solution-with-flexbox-IJqc-1a4u
- Live Site URL: https://rspatz.github.io/Single-Price-Grid-Component/

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow

### What I learned

This is my first Front-End Mentor challenger using Flexbox, which I have only recently learned. When I first viewed the project, I immediately recognized that I would use 'flex-direction: row' for the wide-screen version, and 'flex-direction: column' for the mobile version. I created a container to hold the two sections, 'cta' and 'why' for the bottom part of the design, and then gave the container 'display: flex.' Being new to Flexbox, I wasn't sure how well everything would work, but I was surprised to find that everything came together well the first time:

```html
<div class="container">
  <section id="cta">
    <h3>Monthly Subscription</h3>

    <div class="priceQuote">
      <h1>&dollar;29 <span>per month</span></h1>
    </div>

    <h4>Full access for less than &dollar;1 a day</h4>

    <button>
      <h4><a href="#">Sign Up</a></h4>
    </button>
  </section>
  <!-- END cta -->

  <section id="why">
    <h3>Why Us</h3>
    <ul>
      <li>Tutorials by industry experts</li>
      <li>Peer &amp; expert code review</li>
      <li>Coding exercises</li>
      <li>Access to our GitHub repos</li>
      <li>Community forum</li>
      <li>Flashcard decks</li>
      <li>New videos every week</li>
    </ul>
  </section>
  <!-- END why -->
</div>
<!-- END Container -->
```

This is also one of my first attempts at a Mobile-First workflow, which I am finding a bit ackward at the moment. I have tried this with other Front-End Mentor projects I am working on, and I have had the experience of the mobile version working perfectly, but the wide-screen version giving me problems that are not easy to resolve. I have had to start over 2 or 3 times and change sections of the HTML5 markup to try to accomodate both versions at the same time.

### Continued Development

I am continuing to learn everything I can about Flexbox, and I will be using Sass and learning CSS Grid in the near future. I am trying to build a portfolio of development projects, as I will be applying for my first Junior Web Developer job shortly.

I have been learning very basic JavaScript, and I am developing small projects with JavaScript, which I will be adding to some of my websites, such as simple contact and signup forms with basic form validation. I am working on a website for a fictional restaurant, and I would like to develop an interactive online menu with JavaScript when I gain more knowledge.

### Author

Robert Spatz
https://www.linkedin.com/in/robertbspatz/


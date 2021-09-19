# Feedback

_Right click on the file and click Open Preview or `ctrl/cmd + shift + v` to open preview_

## Goals

1.  Working portfolio:

    - For a working portfolio, I think you are close to reaching this in terms of how it looks. You code needs a little bit of tidying up.

2.  Practice using Git / Github Flow:

    - You have practiced committing and branching, you should take this forward for the next project.

3.  Application of morning topics

    - I think you are close on this front, you have used grid, flex and to an extent SCSS. You are just not making use of all of the features that SCSS gives you. I will add more on improvements at the end.

---

## Specification

1. README - not done

   - Get in the habit of writing README's for every project, you can also add more to this one.
   - Add in the link to your Figma design
   - If you are adding links in a md file you can do it like this [example link](https://www.markdownguide.org/basic-syntax/#links) rather than a URL

2. BRANCHING - kinda done

   - Try a focus on what you are doing once you are done add commit etc then move onto the next part.
   - Perhaps each section is a branch?

3. SCSS - kinda done

   - All of your styles have been written in your main.scss file I can see you started creating separate files to bring in carry on with it will make your life easier. Try writing smaller files and bring them into main.
   - SCSS gives us variables as well which you set up in your base.scss file but haven't used.

4. Mobile First - almost done

- I can see media queries in your main.css
- In your index.html you are trying to bring in \_responsiveness.scss in the style tag, this wont work as the browser can only read css files so you will need to compile it first.
- You are almost there with just some tweaks

5. 25 commits - not done

   - You have 13 so just over half way there.

6. BEM - not done

---

## Overall

I think we need to catch up as in terms what have produced is good and looks like your figma which is great but you haven't applied what we have been learning. With the spec you were given you haven't hit all the targets. If you are struggling you need to let me know, what we are teaching you need to apply as they are standard practices that you will use through out the course.

I think adding in the Jquery was good but you really need to be able to explain it e.g you are getting the carousel file with a cdn and then passing in a object with all of the options you wanted added in.

I am going to give you some constructive feedback to take on to this project and to take forward to your next projects.

---

## To work on

I think you need to work on semantic HTML, Adding SCSS, BEM and media queries to the project.

For Semantic HTML:

- Look over your [semantic tags](https://www.w3schools.com/html/html5_semantic_elements.asp)

You have to many div's, you can replace them with tags with more meaning.

For BEM:

- Have a read of the [BEM docs](http://getbem.com/naming/).
- Do a little refresher with [Kevin
  Powell](https://www.youtube.com/watch?v=SLjHSVwXYq4)

The nav could be named like this below.

```html
<nav class="navigation">
  <div class="navigation__logo">
    <img src="images/logo.png" alt="logo" />
  </div>

  <div class="navigation__socials navigation__socials--mobile">
    <img src="images/linkedin.png" alt="" />
    <img src="images/insta.png" alt="" />
    <img src="images/facebook.png" alt="" />
    <img src="images/twitter.png" alt="" />
  </div>

  <ul class="navigation__links">
    <li><a href="#work">Work</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#resume">Resume</a></li>
  </ul>

  <div class="navigation__socials navigation__socials--desktop">
    <img src="images/linkedin.png" alt="" />
    <img src="images/insta.png" alt="" />
    <img src="images/facebook.png" alt="" />
    <img src="images/twitter.png" alt="" />
  </div>
</nav>
```

With SCSS

- You need to use it more in this project
- set up a base file, layouts and components file import them into main
- try and break your main.scss file into these parts.
- Look over notes from the lesson / re watch parts you are unsure about.

With GIT:

- Break your jobs down and Write a list of big todo's, then break them into little ones
- Treat each big one as a branch then ach of the little ones as a commit, you go in do that one thing commit and then move onto the next. Once the branch is done push merge and move to the next one.

With Media Queries:

- You need to add them in so your website works on different devices.
- Recap with [Kyle](https://www.youtube.com/watch?v=yU7jJ3NbPdA)

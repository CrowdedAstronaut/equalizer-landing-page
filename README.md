# Frontend Mentor - Equalizer Landing Page solution

This is a solution to the [Equalizer Landing Page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/equalizer-landing-page-7VJ4gp3DE/hub/responsive-landing-page-using-css-grid-SkSmE1PU9).

## Table of contents

- [About this project](#about)
- [Screenshots](#screenshot)
- [Technologies](#technologies)
- [Learning Experience](#learning)
- [Author](#author)

## About <a name="about"></a>

Equalizer Landing Page is a deployed, mobile first, website that allows the user to view the site on various devices in different states. This project was an exercise in:

- Semantic HTML5 markup
- CSS variables
- Flexbox
- CSS Grid
- Mobile-first workflow

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

## Screenshots <a name="screenshot"></a>

### Mobile Preview

![Mobile Preview]()

### Desktop Preview

![Desktop Preview]()

# Technologies <a name="technologies"></a>

<table>
  <tbody>
    <tr>
      <td>Front End Languages</td>
      <td>
        <img alt="HTML" src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white" />
        <img alt="CSS" src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white" />
        <img alt="SASS" src="https://img.shields.io/badge/sass%20-%231572B6.svg?&style=for-the-badge&logo=sass&logoColor=pink" />
      </td>
    </tr>
      <td>Design</td>
      <td>
        <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
      </td>
    </tr>
    <tr>
      <td>Utilities</td>
      <td>
        <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
      </td>
    </tr>
    <tr>
      <td>Deployment</td>
      <td>
          <img alt="Github Pages" src="https://img.shields.io/badge/github-100000?style=for-the-badge&logo=github&logoColor=white"/>
      </td>
    </tr>
  </tbody>
</table>

<hr />
<br />

## What I learned <a name="learning"></a>

This exercise tested pixel perfect design and adjusting font-size, line-height, and line-spacing for the mobile vs. desktop views.

I used an anchor tag as opposed to a button for the click listener.

```html
<div class="apple-button">
  <a
    role="button"
    tabindex="0"
    class="social-button"
    aria-label="click here to download from the Apple app store"
    rel="noopener"
    href="https://www.apple.com/app-store/"
  >
    <div class="apple-icon">
      <img
        src="./assets/icon-apple.svg"
        alt="this is an apple icon"
      />
      <span>iOS Download</span>
    </div>
  </a>
</div>
```

I used css color variables to make things easy to read and easy to change.

```css
html {
  --teal: #66e2dc;
  --orange: #fa7453;
  --mustard: #ffb964;
  --white: #fcfaf9;
  --black: #191826;
}
```

## Author <a name="author"></a>

- Website - [John Ross Phillips](https://www.johnrossphillips.com)
- Frontend Mentor - [@CrowdedAstronaut](https://www.frontendmentor.io/profile/CrowdedAstronaut)

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### Overview 
### Screenshot

![QR-code-finished-example](https://user-images.githubusercontent.com/95522156/189535641-ccdab226-9693-4a4b-a2d1-d32ad593a10b.jpeg)


### Links

- Solution URL: https://github.com/Ablueremote/qr-code1
- Live Site URL: https://ablueremote.github.io/qr-code1/

## My process

- I kept my workflow as simple as possible (from top to bottom). Starting with the background color, I then opened a container where my elements where going to go in. After sizing my container roughly, I inserted my image(s) and sized as close to optimal as i could. From there, my text needed some slight modifiations such as spacing, font-family and color. Ive changed them to match and added spacing. With all my content in place, I adjusted some more sizing to taste.
**UPDATES**
--  -removed all height (px) properrties from all css
    -removed div class = text (condense/not needed)
    -changed .container from grid-display to flex-display, added flex direction-column
    -added padding inside  .container for spacing new flex
    ** Thanks to Miranlegin on frontend mentor for suggestions, using flex in 3 commands centered my element and removed all height properties i had before **

 -- -added main tag
    - replaced div with article tag
    - added alt"" to img with definition
    - removed div element from img
    - got rid of all margin properties in css (replaced with flex properties & padding)
    -added min-height to body
    - replaced px with rem on elements
    ** Thanks to denielden on frontend mentor for suggestions, the accessibility changes are vital and i noted moving forward to include where possible.
      Going to include rem, vh, vth instead of px (easier to understand).**   

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned
  <-- Importing google fonts 2 steps-->
  @font-face {
    font-family: Outfit;
    src: url(https://fonts.google.com/specimen/Outfit);
}
.container {
    background-color: hsl(0, 0%, 100%);
    display: grid;
    width: 350px;
    height: 550px;
    margin: auto;
    border-radius: 20px;
    text-align: center;
    margin-top: 10em;
}

## Author

- Twitter - [@ablueremote](https://www.twitter.com/ablueremote)


## Acknowledgments

I would like to give a special thank you to Frontend Mentor for being free for people like me looking to learn how to code!
#qr-code

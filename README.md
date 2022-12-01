#  The station project

This is a personal project as a final test of my skills by  ALX as a Software Enginee

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See the latest updates of games
- Able to read complete details of a selected game
- Have a community to share thoughts


### Links

- Source Code: [source code](https://github.com/muubaraq/insidious)
- Live Site URL: [live url](https://insidious-games.netlify.app/)

## My process
Create some rough designs. Before i get into the website creation process, it helps to have the basic layout and visual style worked out. Creating these sketches can range from drawing them on a napkin to creating mockups in Photoshop. Create a flowchart to show how the basic navigation of the site will work.



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Styled Components](https://styled-components.com/) - For styles




```html
 <section className='header'>
          <div className='hero-container'>
            <div className='text'>
              <p>
                Play amazing game and connect with all your friends all at once.
              </p>
            </div>
          </div>
          <div className='grid-container'>
            <div className='grid-item'>
              <p>Games for all platforms</p>
              <img src={gamepad} alt='gamepad' />
            </div>
            <div className='grid-item'>
              <p>Amazing community of gamers</p>
              <img src={community} alt='gamepad' />
            </div>
            <div className='grid-item'>
              <p>Top notch customer service</p>
              <img src={serviceShield} alt='gamepad' />
            </div>
          </div>
        </section>
```
```css
.grid-container {
  position: absolute;
  bottom: 100px;
  left: 5%;
  display: grid;
  grid-template-columns: repeat(1, 1fr);
  width: 90%;
  margin: 4rem auto;

  .grid-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 1rem 0;

    p {
      text-align: center;
      font-size: 1.4rem;
      width: 90%;
      margin-bottom: 0.3rem;
    }
  }
}

```
```js
import React, { useEffect } from "react";
import Sidebar from "../components/Sidebar";
import Footer from "../components/Footer";
import { BiPlusCircle } from "react-icons/bi";
import { RiEqualizerLine } from "react-icons/ri";
import { myGames } from "../data";
import { useGlobalContext } from "../components/Context"; proudOfThisFunc = () => {
  console.log('🎉')
}
```


## Author

- Twitter - [@muubaraq](https://www.twitter.com/muubaraq)
- LinkedIn - [mubaraq](https://www.linkedin.com/in/mubaraq-a-a20b1518b/)


## Acknowledgments
 I will like to show appreciation to Austin Tonayam. He has been a great help, time and again. 

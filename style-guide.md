# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

Bright orange: hsl(31, 77%, 52%)
Dark cyan: hsl(184, 100%, 22%)
Very dark cyan: hsl(179, 100%, 13%)

### Neutral

Transparent white (paragraphs): hsla(0, 0%, 100%, 0.75)
Very light gray (background, headings, buttons): hsl(0, 0%, 95%)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca)
- Weights: 400

- Family: [Big Shoulders Display](https://fonts.google.com/specimen/Big+Shoulders+Display)
- Weights: 700
 height: 400px;
    width: 700px;



    
body {
    background-color: hsl(0, 0%, 95%);
   width: 90%;
}
.container {
    height: 400px;
    width: 705px;
    margin: auto;
    margin-top: 100px;
}
.column {
    grid-template-columns: 1fr 1fr 1fr;
    display: grid;
    box-sizing: border-box;
}

.card1 {
    width: 235px;
    padding: 30px 30px 30px 30px;
    background-color:  hsl(31, 77%, 52%);
    height: 400px;
    font-size: 15px;
    font-weight: 400;
}

.card1 h2 {
    font-weight: 700;
    color: hsl(0, 0%, 95%);
    letter-spacing: 0px;
    line-height: 50px;
}
.card1 p {
   letter-spacing: 1px;
   line-height: 23px;
    color: hsla(0, 0%, 100%, 0.75);
}
.learnmore1 {
    border-radius: 20px;
    color: hsl(31, 77%, 52%);
    background-color: hsla(0, 0%, 100%, 0.75);
    margin-top: 70px;
    height: 40px;
    width: 150px;
    outline: none;
    font-weight: 700;
    border: none;
    letter-spacing: 1px;
}
.learnmore1:hover {
    background-color: black;
}
.card2 {
    padding: 30px 30px 30px 30px;
    background-color:   hsl(184, 100%, 22%);
    height: 400px;
    width: 235px;
}
.card2 h2 {
    font-weight: 700;
    color: hsl(0, 0%, 95%);
    letter-spacing: 0px;
    line-height: 50px;
}
.card2 p {
   letter-spacing: 1px;
   line-height: 23px;
    color: hsla(0, 0%, 100%, 0.75);
}
.learnmore2 {
    border-radius: 20px;
    color:  hsl(184, 100%, 22%);
    background-color: hsla(0, 0%, 100%, 0.75);
    margin-top: 70px;
    height: 40px;
    font-weight: 700;
    width: 150px;
    outline: none;
    border: none;
    letter-spacing: 1px;
}
.learnmore2:hover {
    background-color: black;
}
.card3 {
    width: 235px;
    padding: 30px 30px 30px 30px;
    background-color:  hsl(179, 100%, 13%);
    height: 400px;
}
.card3 h2 {
    font-weight: 700;
    color: hsl(0, 0%, 95%);
    letter-spacing: 0px;
    line-height: 50px;
}
.card3 p {
   letter-spacing: 1px;
   line-height: 23px;
    color: hsla(0, 0%, 100%, 0.75);
}
.learnmore3 {
    border-radius: 20px;
    color:  hsl(179, 100%, 13%);
    background-color: hsla(0, 0%, 100%, 0.75);
    margin-top: 70px;
    height: 40px;
    width: 150px;
    font-weight: 700;
    outline: none;
    border: none;
    letter-spacing: 1px;
}
.learnmore3:hover {
    background-color: black;
}
.attribution {
    margin-top: 100px;
}
@media screen and (min-width) {
    
}
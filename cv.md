# Lisovyi Hennadii
<image src="/assets/photo.jpg" alt="My photo">

## Contacts

#### Email
glisovuy@ukr.net
#### Discord
Genu4 (@Genu4)

## Summary
I am a beginner in front-end development. I have completed my training courses and now I continue to develop in this direction on my own.

## TECH SKILLS
* HTML5 / CSS3 / SCSS / SASS
* JavaScript
* React.js
* Redux / Redux Toolkit
* Figma
* Git

## WORK EXPERIENCE
* Car blog https://teal-fox-4073f1.netlify.app/
* Small shop https://rad-kringle-418e40.netlify.app/

## EDUCATION
* Kyiv National Technical University 
"Kyiv Polytechnic Institute"
Radio engineering faculty, master
* Skill-UP School - Front End Developer
* Web Developer Fundamentals at Sololearn

## CODE EXAMPLE

```
const products = [
  { name: "Radar", price: 1300, quantity: 4 },
  { name: "Scanner", price: 2700, quantity: 3 },
  { name: "Droid", price: 400, quantity: 7 },
  { name: "Grip", price: 1200, quantity: 9 },
];

function getAllPropValues(propName) {
  // Change code below this line
  const keys = Object.keys (products);
  const names= [];
for (const product of keys) {
  if(product[propName]) {
  names.push(product[propName])
    return names;
  }
}
return [];
}
```
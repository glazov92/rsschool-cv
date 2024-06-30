# Ilya Glazov

## Contacs
**email**: glazov92@gmail.com

## About Myself
In the heat of hating his job, he decided to change his occupation and start studying. I started with courses that were held in my city, finished, but did not develop further. I decided to start with a clean slate in RS Scool.

## Skills
- HTML 
- css 
- js (base)

## Code example
I dont have a Codewars accaunt, but I have a sample code from my last courses. It was necessary to find a number from the series and record the number of iterations:
```javascript
const year1 = 1800;
const year2 = 2020;
const searchYear = 1961;

if (searchYear < year1 || searchYear > year2) {
  
  console.log("Некорректный год");
}

let counterY = 0;
let y = (year1 + year2) / 2; 
y = Math.round(y); 
let yOld = 1; 

if (y > searchYear) {
  while (y > searchYear) {
    yOld = y; 
    y = (year1 + y) / 2;
   
    y = Math.round(y); 
    counterY++;
  }
} else {
  while (y < searchYear) {
    yOld = y;
    y = (year2 + y) / 2;
   
    y = Math.round(y); 
    counterY++;
  }
}

let yOld2 = yOld; 

while (searchYear - y !== 1 && searchYear - y !== -1) {
  if (y > searchYear) {
    while (y > searchYear) {
      yOld = y; 
      y = (yOld2 + y) / 2;
     
      y = Math.round(y); 
      counterY++;
    }
  } else if (y < searchYear) {
    while (y < searchYear) {
      yOld = y;
      y = (yOld2 + y) / 2;
      
      y = Math.round(y); 
      counterY++;
    }
  } else {
    console.log(y);
    break;
  } 
  yOld2 = yOld;
  counterY++;
}

if (y > searchYear) {
  y = y - 1;
} else {
  y = y + 1;
}

console.log(y + " - год первого полета человека в космос");
console.log(counterY + " Итераций");
```

## Experience
No work experience

## Education
Higher education in construction. Retraining courses in the specialty web developer at the Lobachevsky University.

## English 
My English is an entry-level.
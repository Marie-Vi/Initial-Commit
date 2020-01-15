# Solved-Tasks
```javascript

let basa = [];

let i;
for (i= 1; i<20; i+=2){
  basa.push (i);
}
console.log(basa);

let dama = [];
for (i= 1; i<11; i++){              
  dama.push(i % 2 === 0 ? -i: i);
}
console.log(dama);

numbers = [2, 13, 7, 6, 41, -7, 12, -4, 89, 5];
for (i = 0; i < 10; i++) {
  if (numbers[i] % 2 === 0) console.log(numbers[i])
  
for (i = 0; i > -10; i++) {
  if (numbers[i] < 0) console.log(numbers[i])
    }
  
  let nn = [];
  
  for (i = 0; i < 10; i++){
    if (numbers[i] > 10) nn.push(numbers[i])
  } 
  console.log(nn);
  console.log(nn.length);}

let numbers = [2, 13, 7, 6, 41, -7, 12, -4, 89, 5];


for (i = 0; i > -10; i++) {
  if (numbers[i] < 0) console.log(numbers[i])
    }

for (i = 0; i < numbers.length; i++) {
  if (numbers[i] < 0) numbers[i] = - numbers[i]
}

console.log(numbers)
{
    let arr = [];
    
    for (i = 20; i<= 30; i++) {
      arr.push(i)
    }
    console.log(arr);
    
    for (i = 5; i >= 1; i--) {
      arr.unshift(i)
    }
    console.log(arr);
}
;

for (i = 30; i < 25; i--) {
  arr.pop(i)
  console.log(i);
}
console.log(arr);

let str = '';
i = 0;
while (i < 27){
  str += 'Z'
  i++;
}
console.log(str);

i = 0;
while (i < 10 ) {
  console.log('Marie');
  i++;
}

i = -7;
while (i < 8) {
  console.log(i);
  i++;
}


for (i = 10; i >= 0; i--) {
  if (i === 0) i = 'start!';
  console.log(i);
}

for (let i = 10; i >= 0; i--) {
  if (i === 0) i = 'start!';
  console.log(i);
}

function numbersEvenOdd(a){
  if(a % 2 == 0) return ('Even')
  else return ('Odd')
    }
console.log(numbersEvenOdd(a));

let arr = [];
let arr2 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
function reverse (arr2) {
  for(i = arr2.length-1; i >= 0 ; i--) {
    arr.push(arr2[i]);
  }
  return arr;
}

console.log( reverse (arr2));

let x = 5;
let y = 10;
let arrXX =[];
let arrX =[0,1,2,3,4,5,6,7,8,9,10];
function newArray (x,y) {
    for (i = 0; i < arrX.length; i++) {
      if(arrX[i] <= y && arrX[i] >= x) arrXX.push(arrX[i]);
  }
  return arrXX;
}
console.log(newArray (x,y));

let arr1 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
let a = 0;
function sum (arr1) {
  for(i=0; i < arr1.length; i++) {
    a = a + arr1[i];
  }
  return a;
}
console.log(sum (arr1));

a = 'Even';
d = 'PasV';

// function str(a){
//   for(value of a){
//     return (value);
//     break;
//   }
// } - this way also can be used, but it is longer

function str(a){
  return (a[0]);
}

console.log(str(a));
console.log(str(d));

let c = 25;
let d = 4;

function mult (c, d){
  return c * d;
}
console.log(mult(c, d));

function absValue(e){
  return Math.abs(e);
}
console.log(absValue(e));

{
    let arr = [21,22,23,24,25,26,27,28,29,30,31,32,33,34,35];
    let temp = [];
    
    for(i = 0; i < arr.length; i++) {
      temp.push(1.8*arr[i] +32);
    }
    console.log(temp);
   
}

{
    let x = 5;
    let y = 10;
    let arrXX =[];
    function newArrayX (x,y){
      if (x < y){
        for (i = x; i <= y; i++)
          arrXX.push(i);
      } else if (x > y){
        for (i = y; i <= x; i++)
          arrXX.push(i);
      } else if (x === y) arrXX.push(x);
      return arrXX;
    }
    console.log(newArrayX (x,y));
}

i = 0;
while (i < 15) {
 i+=2;
 console.log(i);
}
console.log('---------------');
```
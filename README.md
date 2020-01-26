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

let arr4 = ['apple', 'orange', 'grape', 'banana', 'mango', 'peach'];
let arr4X = [];

function countWords (arr) {
  let count = 0;
  for (let i = 0; i < arr.length; i++){
    if(arr[i].length === 5) count++;
  }
    return count;
}

console.log(countWords (arr4));

const arr = [1,5,7,3,2,8,0,9];
let temp;
for (let i = 0; i < arr.length-1; i++) {
  for(let j = i+1; j < arr.length; j++){
    if(arr[i]> arr[j]){
      temp = arr[i];
      arr[i]= arr[j];
      arr[j]= temp;
    }
  }
}
console.log("Hello, world!")

function sum (a, b){
    return a + b;
}
function mult(a, b){
    return a*b;
}
module.exports = {sum, mult};

const assert = require('assert');
const {sum, mult} = require('./index.js');

describe('function sum', () => {
    it('should function sum equals 6', () => {
        assert.equal(sum(2, 4), 6);
    })

    it('should function sum not equals 0', () => {
        assert.notEqual(sum(2, 4), 0);
    })
})


it('should mult equals 8', () => {
    assert.equal(mult(2, 4), 8)
})

function greet() {
let str = 'hello world!';
return str;
}

function createPhoneNumber(arr) {
  let a = '';
  let c = '';
  let d = '';
  for(i = 0; i < 3; i++) {
    a = a + arr[i];
  }
  for(i = 3; i < 6; i++) {
    c = c + arr[i];
  }
  for(i = 6; i < arr.length; i++) {
    d = d + arr[i];
  }
  return `(${a}) ${c}-${d}`
}

{
    var v1=50;v2=100,v3=150,v4=200,v5=2,v6=250
    function equal1(){
      var a=v1;
      var b=v1;
      return a+b;
    }
    //Please refer to the example above to complete the following functions
    function equal2(){
      var a=v3;   //set number value to a
      var b=v1;   //set number value to b
      return a-b;
    }
    function equal3(){
      var a=v1;   //set number value to a
      var b=v5;   //set number value to b
      return a*b;
    }
    function equal4(){
      var a=v4;   //set number value to a
      var b=v5;   //set number value to b
      return a/b;
    }
    function equal5(){
      var a=v6;   //set number value to a
      var b=v3;   //set number value to b
      return a%b;
    }
}

{
    let h, m, s;
    function past(h, m, s){
      h = h * 60 * 60 * 1000;
      m = m * 60 * 1000;
      s = s * 1000;
      return(h + m + s)
    }
}
```
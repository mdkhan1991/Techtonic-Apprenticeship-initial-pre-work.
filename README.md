# techtonic-apprenticeship-initial-pre-work

## Which freeCodeCamp lessons were most difficult for you and why? Please be as in-depth as possible. There is no limit to the number of responses or lessons mentioned. We have provided you with the template below and expect you format any additional entries in the same way, so simply copy and paste the following three lines for each lessons you struggled with, change the subject title and the lesson title, and fill out your answers under the lessons you struggled with below:

### Basic HTML and HTML5
** Use the value attribute with Radio Buttons and Checkboxes

 ### Problem : I was doing the " Radio Buttons and Checkboxes" and I faced Problem with The checkbox sequence problem.
### My code : 
  <label >
  <input id="indoor" value="indoor" type="radio" name="indoor-outdoor">Indoor
</label>
<label>
  <input id="outdoor" value="outdoor" type="radio" name="indoor-outdoor">Outdoor
</label>

<label>
    <input id="loving" value="loving" type="checkbox" name="personality">loving
</label>
<label>
    <input id="lazy" value="lazy" type="checkbox" name="personality">lazy
</label>
<label>
    <input id="energetic" value="energetic" type="checkbox" name="personality">energetic
</label>
 **

### Basic JavaScript
** Replace Loops using Recursion

### Problem : I was tryed to make replacing the loop using the recursion but some issue is not solved in example i have attached my code.
Code : 
function sum(arr, n) {
  // Only change code below this line
if(n >= 0){
  return arr[0];
} else {
  return sum(arr , n - 1) + arr[n];
}
  // Only change code above this line
}
console.log(sum([1], 0));
console.log(sum([2, 3, 4], 1));
console.log(sum([2, 3, 4, 5], 3));

**

### Basic JavaScript
** Use Recursion to Create a Countdown

### Problem : I was tryed to make Recursion to Create a Countdown but i can't understand the properly this example please help me to solve this problem.
**

### Basic JavaScript
** Use Recursion to Create a Range of Numbers

### Problem : I was tryed to make Recursion to Create a Range of Numbers but i can't understand the properly this example please help me to solve this problem.
**


### ES6
** Use Destructuring Assignment to Assign Variables from Objects

### Problem : I was tryed to solved this example "Destructuring Assignment to Assign Variables from Objects" but i don't understand to assign variabkes from objects so please explain the whole example.
**

### ES6
** Use Destructuring Assignment to Assign Variables from Nested Objects

### Problem : I was tryed to solved this example "Destructuring Assignment to Assign Variables from Nested Objects" but i don't understand to assign Variables from Nesting the Objects so please explain the whole example.
**

### ES6
** Use getters and setters to Control Access to an Object

### Problem : I was tryed to solved this example  but i don't understand how using the getters and setters to conteol access to and object so please explain the whole example.
**

### ES6
** Complete a Promise with resolve and reject

### Problem : I was tryed to solved this example  but conditions cant becomed true and flase please check my code ans explain
Issue Code :
 const makeServerRequest = new Promise((resolve, reject) => {
  let responseFromServer=true ;  
  if(responseFromServer) {   
     resolve("We got the Data");
  } else {  
     reject("Data not Received");
  }
});
**
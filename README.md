//Starting with Arrays = collection of items

//Examples
 let heroes = [ "ironman","spiderman","kiyo"];
 let into = [ "Gautam Jangir","21","Hamirpur"];

// arrays indices arr[0], arr[1], arr[2]......

//LOOPING OVER AN ARRAY

//ARRAY METHODS

push() //add to end 
pop()  //delete from end & return
toString()  //converts array to string 
concat()  //joins multiple arrays & returns
unshift()  //add to start
shift()  //delete from start & return
slice()  //returns a piece of the array ** slice( startldx, endldx)
splice()  //change original array( add, remove, replace) ** splice( startldx, delCount, newEli...)

//functions
Block of code that performs a specific task can be invoked whenever needed

** Function Call 

functionName();

** function definition


//COMPACT WAY OF WRITING A FUNCTION

// forEach loop in array

arr.forEach(CallBackFunction)
// CallBackFunction : Here,it is a function to execute for each element in the array 

arr.forEach( (val) => {
  console.log(val);
  })

// SOME MORE ARRAY METHODS\

//Map

**create a new array with the results of some operation. The value its call back returns are used to form new array **

arr.map( callbackfnx ( value, index, array))
 let newArr = arr.map((val) => {
    return val*2;
    })

//Filter

**create a new array of elements that give true for a condition/filter.**

let newArr = arr.filter((val) => {
 return val*2 === 0;
 })

 //Reduce

 **performs some operations & reduce the array to a sinngle value. It returns that single value

 const array1 = [1,2,3,4];
 const initialValue = 0;
 const sumWithI = array1.reduce ( accumulator, currentValue) => accumulator + currentValue, initialValue);
 console.log(sumWithI);

 THE 3 MUSKETERS OF WEB DEV *******************************************************************************

 HTML
 (Stucture)
 
 CSS
 (Style)

 JS
 (Logic)

 //Window Object
 The window object represents an open window in a browser. It is browser's object (not JavaScript's) & is automatically created by browser
  It is a global object with lots of properties & methods

//WHAT IS DOM
when a web page is loaded, the browser creates a Document Object Model (DOM) of the page.

Window--->Document--->html--->head --- ( meta, meta, title, link )
                          --->body ( ---> div ---> (img, h1, p, div )
                                   ( ---> script  )

// DOM Manipulation

// Selecting with Id
   document.getElementsById ("myID")

// Selecting with Class
   document.getElementsByClassName ("myClass")

// Selecting with Tag 
   document.getElementsByTagName ("p")

//Query Selector
   document.querySelector("#myId/.myClass/tag")
   //returns first elements
   document.querySelectorAll("#myId/.myClass/tag")
   //returns a Nodelist

//Properties

tagName : returns tag for element nodes
innerText : returns the text content of the element and all its children
innerHTML : returns the plain text or HTML contents in the elements
textContent : returns textual content even for hidden elements

//Attributes 

getAttribute(attr)  // to get the attribute value
getAttribute(attr,value)  // to set the attribute value

//Style

node.style

//Insert Elements
                  let el = document.createElement("div")

node.append(el) //adds at the end of node(inside)
node.prepend(el) //adds at the start of node(inside)
node.before(el) //adds before the node(outside)
node.after(el) //adds after the node(outside)

//Delete Elements

node.remove()  //removes the node


let start from todahy again

 

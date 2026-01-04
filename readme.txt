ReactJs - The Complete ReactJs Course For Beginners

Section 01 Introduction


Topic 01 Introduction of React. 
What is React? 
react is one of the most popular front end JavaScript library in the field of web development. it is mainly 
maintained by Facebook and a large community of developers. react widely used for the building user interface, 
for UI components, for single page applications. react make it easier to manage and update the UI, providing a 
more efficient and interactive user experience.

Why use React?
key objective of Reactjs is to develop user interface that enhance the speed and performance of applications by 
using the virtual dom.

react applications are building using component. And a component is a reusable self contained module that represent 
a part of the user interface. component can be nested making it easy to compose compare UI.

Another key feature is jsx syntax. It is syntax extension for js and recommended by react and similar to xml
and html. You can write html and component in js code.  

The react uses a virtual dom to optimize the rendering of components. instead of directly updating real dom 
react first update a virtual representation of the dom. in this the virtual dom is then compared with actual 
dom and only the differences are updated for making the process more efficient.

React History
It was first released for public in JUly 20, 2023.


Topic 02 Introduction of React ES6
The basic of react JS and how integrate with ES6 and the latest version of a script.
React JS is a JavaScript library for the building user for interface, and it allows you to create readable 
UI component that update efficiently and in response to data changes. React Follow a component based architecture 
and making it easy to manage and scale your applications.

Main Features 

Arrow Functions
arrow function provide a concise syntax and the lexical scoping. And in react they are commonly used for 
defining component and event handler okay.

Classes
classes are used to define react component. And they offer a cleaner syntax for creating and extending components.

Destructing Assignment
structuring simplifies process of stacking values from object or array, and commonly used in react for props 
and state.

Template literals 
template literals is allow for the embedding expression inside string literal. And they are used for dynamic 
content in JSX.


Topic 03 Install React
Before starting have npm and nodejs in pc. search on browser and download from website. 
npx create-react-app app-name
cd app-name
npm start 

Main is app.js. 
index.js file has auto code for index file.  



Section 02. Getting Started

Topic 01. React render method 
React render for HTML to web page by using function called create route and the method for the render. 
create function takes on argument an HTML element and in. The purpose of the function is to define 
the HTML element via a react component should be displayed. 
The next one is the render method. then called to define the react component that should be rendered.

index.js and app.js and index.html. 
index.js what you write here in code gets displayed on screen. 
const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
    <p>Hello Kashan</p>
)

Topic 02. React JSX

Topic 03. React Class 

class car extends React.component {

    constructor(){
        super();
        this.state={color:"yellow"}
    }
    render(){
        <h2>Hi, This is {this.state.color} car class component</h2>
    }
}

Pass component as props in constructor. 


Topic 04. React Props. 
Props are the argument passed into the react component. props are passed to component via HTML attribute.
prop stand for the properties. react props are like a function argument in JavaScript and attribute in HTML.


Topic 05. React Events

Topic 06. React Conditional
in react you can conditionally render components. there are several way to do this. So first is If and else, 
and then ternary operator (? and :) and last logical AND operator (only calls if condition is true and not 
need for false).


Topic 07. React Lists
lists are a core part of the many applications and understanding how to efficiently handle them in react is 
the crucial. we often use list to display collections of data.

const fruits = ['Apple', 'Banana', 'Orange', 'Gauva'];
    <ul>
    {
        fruits.map((fruit, index) => {
            <li key={index}>{fruit}</li>
        })
    }
    </ul>

we can add also multiple like create student array object and student with name and id. 


Topic 08. 

Topic 09. 

Topic 10. 

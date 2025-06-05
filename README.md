Disclaimer:
This video is the property of its original creator and is shared here for educational/informational purposes only. All rights belong to the original content owner,

Codevolution
.
Original video: https://www.youtube.com/watch?v=b4ba60j_4o8&list=PLC3y8-rFHvwhIEc4I4YsRz5C7GOBnxSJY&index=1
If you are the copyright owner and would like this content removed, please contact me directly.
rhidzkhan.ahmad99@gmail.com

#what is npx

- npm package runner

#component

- its a code inside a .js file
- components describe part of the user interface
- they are reusable and can be nested inside the other components

#component types

- stateless functional
- stateful class component

#functional components

- its a js function that recieves object ( props ) return html that describes the ui
- the html is called JSX

#name export

- export conts Greet = () => <div><div>

#Functional

- simple function
- use function components
- absence of this keyword
- solution without using state
- mainly responsible for the UI
- stateless/ dumb / presentational

#Class

- feature rich
- maintain their own private data - state
- complex ui logic
- provide lifecycle hooks
- stateful/ smart container

#Props vs State

- props get passed to the component
- state is manage within component
- props are immutable

- props FC
- this.props Class component
- state cam be change

#Hooks

- lets you use state and other react feature without using Class

Tips:

- dont directly change the state use the set state
- if you want to do something after the setstate is updated, you can use the callback which is the second paramater
- when you have to update state base on previous state value, use a function as an argument of the regular object

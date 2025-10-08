
gotchas:
- cannot be nested
- only used in funcs

`const [count, setCount = useState(4)`

What the array means:
`[current state, function to update state]`
[0] - current state
[1] - function that allows you to update that current state


Ways to pass in the state:

1. 
`useState(4)`: can be used for simple/hardcoded values

When state gets more complex, it can slow down your system to define a state like this because it will be rendered every time the component is rendered.


2. Function Version:

`useState(() =>){
}`

`useState(() => countInitial){
}` 
function that calls the function


This runs the state only the very first time the component is rendered. 

Now you can use a function, and let it run on every render. This can be done like this

`useState(countInitial())`



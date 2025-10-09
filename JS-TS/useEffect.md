
``` js
useEffect(() => {
	console.log('render')
}, [resourceType])
```
`useEffect` takes a second parameter, whatever you pass into this array
will be values that whenever they change, the app will re-render.

EXAMPLE: whenever `resourceType` changes, we will re-render the app.

We can modify our code and set new states by just using `useEffect`

``` js
useEffect(() => {
	console.log('Say what you want it to do')
}, [wheneverThisChanges])
```

A good way to think of `useEffect` would be that you write out what you want your code to do in `{}`, for the whenever the values you pass (in the array`[]`) change.




Clean Up

```js
useEffect(() => {
	console.log('Hi')


	return () => {
		console.log('Return from resource')
	}
}, [resourceType]

```

The return statement here is the clean up. In code the return will run first!
This is because you want it to clean up anything from before, before you run the `useEffect`
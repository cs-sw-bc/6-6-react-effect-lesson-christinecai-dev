useEffect
- used to run a code based on certain event
- when the page loads for the first time
- on every state change
- on specific state changes
- API calls

- two parameters
- one is a fat arrow function with async function (await for the value to become available)-- function you wanna call
- second is the frequency (empty: called on all state changes or the first time only) (state changes)

useReducer
- single action has several state changes and effects

const [state, dispatch] = useReducer(reducer, initialArg, init?)
- state: (track all changes) track items, number of items, discounts, total cost -- combine items
- dispatch() calls the reducer function (handle your changes)
- initialArg: initial set of states
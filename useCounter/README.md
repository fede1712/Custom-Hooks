# useCounter

### Example of use

```javaScript
const {  counter, add, substract, reset } = useCounter(10)
```

useCounter has a default value of 0

### Functions 

```javaScript
const add = () => {
        setCounter(counter + 1)
    }

    const substract = () => {
        setCounter(counter - 1)
    }

    const reset = () => {
        setCounter(initialState)
    }

```
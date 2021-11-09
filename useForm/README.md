# useForm

### Example of use:

```javaScript
const [values, handleInputChange, reset] = useForm({})
```

useForm has as default value an empty object

### Functions

```javaScript

    const reset = () => {
        setValues(initialState)
    }

    const handleInputChange = ({ target }) => {
        setValues({
            ...values,
            [target.name]: target.value

        })
    }
```
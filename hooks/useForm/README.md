# Hook: useForm

Ejemplo: 

```
    const initialForm = {
        name: 'John Doe',
        age: 23,
        email: 'johndoe123@gmail.com'
    };
    
    const [ formValues, handleInputChange, reset ] = useForm(initialForm);
```
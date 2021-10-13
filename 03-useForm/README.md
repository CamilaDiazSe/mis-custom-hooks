# useForm hook

Custom hook para formularios

Ejemplo de uso: 

```
    const initialState= {
        name: '',
        age: 0,
        email: ''
    };
    const [values, handleInputChange, handleSubmit, reset] = useForm(initialState);
```
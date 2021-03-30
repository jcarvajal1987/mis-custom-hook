# useForm 

Ejemplo:

```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    }
    const [ values , handleInputChange, reset ] = useForm( initialForm )

```

useForm() // recibe un objeto y se desestructura en un arraeglo.

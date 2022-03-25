# Notas

Este repositorio contiene varios customHooks.

Tambien es para ahorrar tiempo al escribirlos!

# useCounter

```sh
const { counter, increment, decrement, reset } = useCounter( 10 );
useCounter() // recibe un valor por defecto
```

# useFetch

```sh
const url = 'endpoint de una api';
const { data: null, loading: true, error: null } = useFetch( url );
```

# useForm

```sh
const initialForm = {
    name: '',
    age: 0,
    email: '',

}
const [ formValues, handleInputChange, reset ] = useForm( initialForm );
```

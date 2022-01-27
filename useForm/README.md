# useForm

Ejemplo de uso: 

```
    const inputs = {
        name: '',
        description:''
        age: 000
    };
    const = [ values, handleInputChange, reset ] = useForm( inputs );
```
## valores

- values -> contiene el initialState enviado en 'inputs'
- handleInputChange -> es la función que se lanza cuando el input cambia su valor, debe recibir un evento de tipo 'change'
- reset -> Restablece el state a su valor inicial 

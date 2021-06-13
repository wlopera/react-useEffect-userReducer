# react-useEffect-userReducer
Ejercicio de recat con useEffect y useReducer

Formulario de login mediante react con useEffect y useReducer
- Ejercicio react con useEfect
- Ejercicio react con useReducer

## Salida
![Captura](https://user-images.githubusercontent.com/7141537/121817857-87536300-cc49-11eb-91ad-d5d571b9c134.PNG)
##### En algunas oportunidades se debe enviar información de un componente interno a otro componente a través del padre
    - Ejemplo: validar conexión (login)
    - Ejemplo: enviar producto a un carrito de compra
![Captura](https://user-images.githubusercontent.com/7141537/121818414-a7d0ec80-cc4c-11eb-943f-cd28ff03696d.PNG)

##### En nuestro ejercicio se pasan funciones login/logout del padre (App.js) a MainHeader.js a la Navigation.js para iniciar o cerrar conexión del aplicativo en la vista principal.
![Captura](https://user-images.githubusercontent.com/7141537/121818462-e5357a00-cc4c-11eb-9d42-88f0e22dd597.PNG)

##### En vez de enviar data de componente a componente (props) se puede usar 'useContext' para pasar contexto directo al componente que lo requiera.

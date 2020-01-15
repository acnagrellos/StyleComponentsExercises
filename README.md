# Ejercicios Javascript de Componentes

1. Haz que el componente App.tsx sea de tipo funcional. Usa el tipo React.FC como tipo del componente.
2. Crea dentro de la carpeta src otra carpeta llamada _modules_. Para nuestros componentes usaremos la estructura fractal. Crearemos tres componente: HeaderApp, MainApp y FooterApp. Todos los componentes deberán ser funcionales. Que los componentes solo tengan un div que diga "Soy el X de la App". Importa y exporta los componentes por nombre y no por defecto.
3. Añade como propiedades al componente Header el nombre de la app y una url del logo. Destructura las props al recibirlas en el HeaderApp. Añade al Header un elemento imagen de logo y un nombre dentro de un elemento header. En el nombre de la app deberá poner "Esta es la app <nombre>". Por último dales un valor en App.tsx (Para el logo puedes usar: https://www.ajedreztomelloso.com/img/logo.86b73570.png)
4. En el componente App.tsx crea una lista de links de esta manera:

```
const links = [
    { link: 'https://www.ajedreztomelloso.com/', text: 'Blog' },
    { link: 'https://www.ajedreztomelloso.com/', text: 'Prensa' },
    { link: 'https://www.ajedreztomelloso.com/', text: 'Contacta' },
    { link: 'https://www.ajedreztomelloso.com/', text: 'Términos' }
];
```

Pasalos como prop al footer. El Footer también deberá recibir una prop que sea copyright. El Footer deberá tener un ul que contenga li con a que sean los enlaces que se han pasado por prop. El texto deberá ser el texto del objeto que le hemos pasado. El Copyright será un string con valor "Copyright Plain 2020" que se pondrá a la derecha del todo. Los links irán a la izquierda.

5. Haz que el componente Main sea una arrow function de una línea que devuelva un div que ponga "Este es el Main de la aplicacion".

# Ejercicios Emotion

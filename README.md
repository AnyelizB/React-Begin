Recommended Install to React
https://gist.github.com/Klerith/4a4abfd88a88b2d1f16efd95fea41362
https://gist.github.com/Klerith/b0111f52ba16451d095f38d4c995605b
REACT is:
- Library
- App all Type
- Declarative
- Efficient
- Predictable
- Components
- Server-side with Node
JSX = JS + XML
-----
BABEL - https://babeljs.io/

nos permite utilizar caracteristicas actuales de JS, usar ese codigo  en navegadores web que no utilizan en esa caraceristicas

-------
Project in React 
Have some commands:
1. npx create-react-app my-app

si es la primera vez entonces aceptar la creación de react app

------
Link of study
1. https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/map --> MAP
2. https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment --> desestructuración
3. arreglos -> https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
4. promesas -> https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Promise
5. Fetch API https://developer.mozilla.org/es/docs/Web/API/Fetch_API
6. Giphy https://developers.giphy.com/
7. doc de js https://developer.mozilla.org/es/
8. crear app con vite en react https://vitejs.dev/guide/ 
colocar en la consola dentro del proyecto

yarn create vite

y luego 

yarn o yarn install para instalar las dependencias

La forma de cambiar modulos en caliente es mucho mas rapido que webpack
las configuraciones son las mas basicas

react-dom -> esta relacionado a la parte del HTML document Object model
vite configuraciones globales de react

como es yarn se ejecuta con yarn dev
---
9. Robots txt https://developers.google.com/search/docs/crawling-indexing/robots/intro?hl=es&visit_id=638138052457717610-4032027159&rd=1
10. PWA https://web.dev/learn/pwa/
11. react script https://create-react-app.dev/docs/available-scripts/
12. Short cut
racf exporta una funcion para retornar una salida 
13. PROPS son los prototype, es información que fuye entre componente padre y componente hijo
 Que son los Props Los "props" en React son un mecanismo para pasar datos de un componente padre a un componente hijo. "Props" es una abreviatura de "propiedades" en inglés.

En React, un componente puede aceptar "props" como argumentos de su función y utilizar estos valores para renderizar su salida. Por ejemplo, un componente de "Botón" podría aceptar una "propiedad" "color" para especificar el color del botón que se renderiza.

Los "props" son objetos inmutables (es decir, no se pueden modificar directamente en el componente hijo) que se pasan desde el componente padre al componente hijo. Esto ayuda a mantener un flujo de datos unidireccional en la aplicación, lo que facilita la comprensión del estado y la lógica del flujo de datos.

En resumen, los "props" en React son un mecanismo importante para la comunicación entre componentes y para la creación de componentes reutilizables y modulares.
se puede ir al navegador y en la seccion del components podemos ver todos los componentes con sus props
para instalar los proptypes usamos 
yarn add prop-types


15. Documentación de React https://es.reactjs.org/docs/events.html#keyboard-events
16. unitarias y de integración

Unitarias estan enfocadas en pequeñas funcionalidades
Integración Enfocadas en como reaccionan varias piezas en conjunto

AAA
Arrange: preparar el estado inicial
Act: aplicar estimulos para las pruebas 
Assert Observar el comportamiento resultante

17. Pruebas en js https://jestjs.io/

yarn add --dev jest

crear este script en el package.json
"scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview",
    "test": "jest"
  },

yarn test
para ejecutar las pruebas
19. Si quiero observar simpre las pruebas


  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview",
    "test": "jest --watchAll "
  },
  
  
18. para las pruebas es necesario adicionar babel
yarn add --dev babel-jest @babel/core @babel/preset-env

crear el archivo de babel seguir https://jestjs.io/docs/getting-started

19. agregar desde la terminal yarn add -D jest-environment-jsdom
20. se puede hacer uso del snapshot praa asegurase de los cambios y las pruebas 
    test('mostrar en el titulo Hola, lili bonita', () => { 
        const title = 'Hola, Soy lili'
        const {container} = render(<FirstApp title={title} />)
        expect(container).toMatchSnapshot();
     });
     esto crea una carpeta de esos cambios 
21. Para actualizar el snapshot en la terminal se coloca la letra 'u'
22. tipos de test

toBe:  que todo sea identico, espacios,contenido
toContain: no me importa los espacios, debe contener esa palabra no mas
toBeTruthy: que el contenido exista
23. REact no tiene lineamientos, se es libre de estructurar como quieran 
24. estructura de archivos https://es.reactjs.org/docs/faq-structure.html
25. https://hackernoon.com/structuring-projects-and-naming-components-in-react-1261b6e18d76 estructura de proyectos
26. https://gist.github.com/Klerith/e4fca6ac127ccb9abd1e8ad77fcd52f1 estilos
27. 




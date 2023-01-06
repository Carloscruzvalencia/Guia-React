# Guia-React

<details open>
<summary>⚙️ Instalacion de React ⚙️</summary>

1. Primero instala ```NPM```
   - [Link a la pagina web de Node.js](https://nodejs.org/es/) 
   - Descarga la version ```LTS``` (Long Term Support) o (Last Stable version)
2. En la terminal ```CMD``` (Windows + X despues presionamos A) ponemos el siguiente codigo
    - ```npx create-react-app``` nombreDeNuestroProyecto
3. third




</details>





## Atomic Desing Methodology
![atomic desing image example](assets/AtomicDesingReact.png)

###  ATOMOS
- los átomos de nuestras interfaces ```son los componentes básicos de todas nuestras interfaces de usuario.``` Estos átomos incluyen ```elementos HTML básicos.```


- Cada átomo tiene sus propias ```propiedades únicas```

### MOLECULAS
- Las moléculas ```son grupos relativamente simples de elementos de interfaz de usuario``` que ```funcionan juntos como una unidad.``` Por ejemplo, una etiqueta de formulario, una entrada de búsqueda y un botón ```pueden unirse para crear una molécula de formulario de búsqueda.```
  
- ```Cuando se combinan, estos átomos abstractos de repente tienen un propósito.``` El átomo de etiqueta define ahora el átomo de entrada. Al hacer clic en el átomo de botón, se envía el formulario. ```El resultado es un componente sencillo, portátil y reutilizable que puede colocarse en cualquier lugar``` donde se necesite una función de búsqueda.
  
### ORGANISMOS
- Los organismos ```son componentes relativamente complejos de  IU compuestos por grupos de moléculas y/o átomos y/o otros organismos.``` Estos organismos ```forman secciones diferenciadas de una interfaz.```

- ```Los organismos muestran esos componentes más pequeños y sencillos en acción``` y sirven como patrones distintivos que ```pueden utilizarse una y otra vez.``` El organismo de la cuadrícula de productos puede emplearse en cualquier lugar donde sea necesario mostrar un grupo de productos, desde listados de categorías a resultados de búsqueda o productos relacionados.

### PLANTILLAS
- Las plantillas ```son objetos a nivel de página``` que colocan componentes en un diseño y ```articulan la estructura de contenido``` subyacente del diseño.

### PAGINAS
- Las páginas son ```instancias específicas de plantillas que muestran el aspecto de una interfaz de usuario con contenido representativo real.```
   


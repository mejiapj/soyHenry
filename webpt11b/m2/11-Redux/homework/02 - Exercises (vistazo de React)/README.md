# HW 10 - Redux | Ejercicios 02

## Duraci贸n estimada 馃晵

1 hora y media

---

## Intro

En este proyecto, te facilitaremos el c贸digo b谩sico de una peque帽a aplicaci贸n Redux. La aplicaci贸n en s铆 misma es s贸lo un contador. Tiene un bot贸n de incremento y otro de decremento. La idea es que en tu navegador se renderice el n煤mero correspondiente dependiendo de qu茅 bot贸n toques.

---

## Consigna de la homework

- Crear un reducer.
- Crear distintas _Actions_.
- Darle funcionalidad a los botones de incremento y decremento.

---

## Pasos b谩sicos para realizar la homework

En esta Homework no hay testing ya que no son necesarios. Podr谩s verificar desde tu navegador si la aplicaci贸n est谩 funcionando o no.

---

## Conociendo la estructura

馃敼 Dentro de la carpeta `02 - Exercises (vistazo de React)` , vas a encontrar la siguiente estructura:

- Carpeta **_public_**
- Archivo **_package.json_**
- Archivo **_README.md_** que ahora mismo est谩s leyendo. 馃
- `src`
  - **_index.js_**
  - `actions`
    - **_index.js_**
  - `reducer`
    - **_index.js_**
  - `components`
    - **_Counter.js_**

---

## 馃懇鈥嶐煉? Ejercicios

La metodolog铆a para este ejercicio ser谩 distinta. Comenzar谩s en el archivo `src/components/Counter.js`. All铆 encontrar谩s comentado las primeras tareas a realizar. Si te fijas, dentro de todos los archivos de esta Homework encontrar谩s comentado las instrucciones para trabajar.

T贸mate tu tiempo para caminar por la c贸digo de la aplicaci贸n. Hay un mont贸n de peque帽os detalles informativos en los comentarios que no querr谩s perderte. Te animo a que mires cada archivo antes de intentar escribir cualquier c贸digo. 馃槂

隆Buena suerte y que te diviertas!

---

## Recordemos que...

- Los componentes de React no pueden pasarse informaci贸n entre s铆 (al menos que sea de padres a hijos). Redux viene a resolver este problema con su estado global. 隆Podremos guardar y adquirir la informaci贸n de all铆 desde cualquier parte de nuestra aplicaci贸n!
- Las **_Actions_** son funciones que nos permiten enviar informaci贸n a nuestro reducer.
- El reducer nos permite gestionar la informaci贸n de nuestro estado global.

---

## Recursos adicionales

- Documentaci贸n de [Redux](https://redux.js.org/introduction/getting-started)

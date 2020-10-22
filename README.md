[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=3442414&assignment_repo_type=AssignmentRepo)
# Act 3.1 - Operaciones avanzadas en un BST

## <span style="color: rgb(26, 99, 169);">¿Qué tengo que hacer?</span>
Diseña e implementa en forma <span style="text-decoration-line: underline;">forma individual</span>, las funciones que resuelvan los problemas que se describen a continuación.

En la parte superior del archivo coloca, en comentarios, tus datos. Por ejemplo:
```
// =========================================================
// File: bst.h
// Author:
// Date:
// =========================================================
```
Las funciones que debes implementar son:

 - ``` template <class T> string BST<T>::byLevel()```
 Devuelve un string conteniendo el recorrido por niveles del árbol.

2. ```template <class T> uint Node<T>::leaves() const```
Regresa la cantidad de hojas que están por debajo del nodo actual. Recuerda que un nodo sin hijo es una hoja. En caso contrario, se deberá regresa la cantidad de hojas del hijo izquierdo más las hojas que están en el lado derecho.
3. ```template <class T> bool Node<T>::isFull() const```
Regresa verdadero si el nodo actual es la base de un subárbol completo. En cualquier otro caso, regresa falso. Un árbol se considera completo si:
	- El nodo es una hoja.
	- El nodo tiene ambos hijos, sus dos hijos son la base de un subárbol completo y ambos hijos tienen la misma profundidad.
4. ```template <class T> T Node<T>::ancestor(T val) const```
Regresa el valor almacenado en el nodo padre del nodo que contiene *val*. Si *val* no se encuentra en el árbol, deberá lanzar la excepción *NoSuchElement*. **Tip:** La estrategia más sencilla para resolver este problema es que el padre pregunte por el valor almacenado del hijo.

<br>Todas las funcionalidades deberán de estar correctamente alineadas y documentadas.&nbsp; Recuerda que todas las funcionalidades deberán pasar exitosamente todas las pruebas. Como parte de la documentación deberá incluirse la complejidad de cada una de ellas.

## <span style="color: rgb(26, 99, 169);">**¿Bajo qué criterios se evalúa mi evidencia?**</span>

- **80%** - Para cada una de las funcionalidades se evaluará:

    - **Excelente (80%)** - pasa correctamente todos los casos de prueba.
    - **Muy Bien (60%)** - pasa correctamente el 75% de los casos de prueba.
    - **Bien (40%)** - pasa correctamente el 50% de los casos de prueba.
    - **Insuficiente (20%)** - pasa correctamente menos del 50% de los casos de prueba.


- **10%** - El código deberá seguir los lineamientos estipulados en el estándar de codificación: <span class="instructure_file_holder link_holder">[liga_estándar_codificación](estandar.pdf)</span>
- **10%** - Se respetan los nombres de las funciones en la aplicación.

## <span style="color: rgb(26, 99, 169);">**¿Dónde la entrego?**</span>
Entrega los archivos correspondientes de la actividad, en el sitio de Github. Coloca la liga del repositorio en Canvas.

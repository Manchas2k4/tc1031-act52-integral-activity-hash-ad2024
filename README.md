![Tec de Monterrey](images/logotecmty.png)
# Act 5.2 - Actividad Integral sobre el uso de códigos hash (Evidencia Competencia)

## <span style="color: rgb(26, 99, 169);">¿Qué tengo que hacer?</span>
En este repositorio encontrarás los archivos de entrada, así como las salidas esperadas que podrás usar para probar tu implementación. También encontrarás un archivo "main.cpp". Ahí deberás implementar tu solución. En el archivo deberás colocar en la parte superior, en comentarios, tus datos. Por ejemplo:
```
// =========================================================
// File: main.cpp
// Author: Edward Elric - A00123456
// Date: 01/01/2021
// =========================================================
```
<span style="text-decoration: underline;">De manera individual</span>, desarrolla la solución del siguiente problema:

Recientemente, mientras navegabas por un foro de programación, encontraste una discusión sobre un concurso bastante interesante. El concurso se llama "anagramas digitales" y el reto consiste en encontrar todos los anagramas de una palabra dada dentro de una cadena más larga. Los anagramas, como bien sabes, son palabras o frases formadas reorganizando las letras de otra palabra, utilizando todas sus letras originales exactamente una vez.

Fascinante, ¿verdad? Y el premio es aún más asombroso: ¡El Premio Nobel de la Paz!

Con el Premio Nobel de la Paz ya visualizado en tus manos, te sumerges en la resolución de este "sencillo" problema utilizando todos tus conocimientos de programación.

## <span style="color: rgb(26, 99, 169);">**Entrada**</span>
Puede haber múltiples casos de prueba. La primera línea del archivo de entrada contiene el número de casos de prueba, *T* (1 ≤ *T* ≤ 25). A continuación, se presentan *T* casos. Cada caso consta de dos líneas: la primera línea contiene una cadena de caracteres, *s*, y la segunda línea contiene una palabra, *p*.

## <span style="color: rgb(26, 99, 169);">**Salida**</span>
Muestra una lista de los índices de inicio de cada anagrama de *p* en *s*.

## <span style="color: rgb(26, 99, 169);">**Ejemplo de entrada**</span>
```
3
cbaebabacd
abc
abab
ab
acdbacdacb
abc
```

## <span style="color: rgb(26, 99, 169);">**Ejemplo de salida**</span>
```
[0, 6]
[0, 1, 2]
[3, 7]
```

Para probar tu implementación, compila tu programa con el comando:
```
g++ -std=c++11 main.cpp -o app
```
Posteriormente, prueba con cada uno de los archivos de entrada de prueba que encontrarás en este repositorio (input1.txt, input2.txt, input3.txt, input4.txt). Los resultados que debes obtener se encuentran en los archivos llamados output1.txt, output1.txt, output1.txt y output1.txt. Para realizar las pruebas, puedes usar las siguientes líneas de código. Por ejemplo, si queremos probar con el archivo de prueba "input1.txt".
```
./app < input1.txt > mysolution1.txt
diff mysolution1.txt output1.txt
```
Si el segundo comando no tenga ninguna salida, sabrás que los resultados que obtuviste son los esperados. 

Por último, realiza una investigación y reflexión en forma individual de la importancia y eficiencia del uso de los diferentes algoritmos de ordenamiento y búsqueda en una situación problema de esta naturaleza, generando un documento llamado **"ReflexAct5.2.pdf"**

## <span style="color: rgb(26, 99, 169);">**¿Bajo qué criterios se evalúa mi evidencia?**</span>

- **65%** - Para cada una de las funcionalidades se evaluará:

    - **Excelente (65%)** - pasa correctamente todos los casos de prueba.
    - **Muy Bien (44%)** - pasa correctamente el 75% de los casos de prueba.
    - **Insuficiente (22%)** - pasa correctamente menos del 50% de los casos de prueba.
      
- **10%** - El código deberá seguir los lineamientos estipulados en el estándar de codificación: <span class="instructure_file_holder link_holder">[liga_estándar_codificación](https://github.com/Manchas2k4/tc1031)</span>
- **10%** - Especifican en cada uno de las funcionalidades la complejidad computacional como parte de su documentación.
- **15%** - Emplea los algoritmos y estructuras de datos más eficientes para la solución del problema.

## <span style="color: rgb(26, 99, 169);">**¿Dónde la entrego?**</span>
Esta actividad forma parte tanto de tu calificación final del curso, así como del portafolio de evidencias de las competencias a desarrollar del curso, por lo que se te pide que en forma individual:
* Realices una entrega de  los archivos correspondientes de los algoritmos de ordenamiento y búsqueda, en la sección correspondiente dentro de esta plataforma, así como el documento de reflexión individual (**ReflexAct5.2.pdf**).
* Generes una carpeta en forma personal llamada **TC1031(Portafolio_Final)** que servirá como preparación para la entrega del portafolio de competencias que se realizará al final del curso, esta carpeta debe contener 5 carpetas:
    * Act1.3
    * Act2.3
    * Act3.4
    * Act4.3
    * **Act5.2** - coloca aquí tus archivos que solucionaron la <span style="text-decoration: underline;">actividad 1.3</span> así como el documento de reflexión individual (**ReflexAct5.2.pdf**).

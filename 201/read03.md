# READ 03: CSS LAYOUT

## 1. Qué es el box model en CSS y cuáles son sus componentes principales❓

***box model*** en CSS describe cómo se calculan y organizan los elementos en una página web. Cada elemento en HTML es tratado como un ***"bloque"*** rectangular y el box model define las dimensiones de este bloque.

Los componentes principales del box model son:

- ***Content:*** área donde se muestra el contenido (texto, imágenes, etc.).
- ***Padding:*** espacio que rodea el contenido, dentro del borde.
- ***Border:*** Un borde alrededor del contenido y del padding.
- ***Margin:*** El espacio exterior al borde, que separa el elemento de otros elementos.

## 2. Cuál es la diferencia entre ```box-sizing: content-box``` y ```box-sizing: border-box```, y cómo afecta esto al diseño de una página web❓

- ```box-sizing: content-box``` (valor por defecto), define el tamaño de un elemento y solo se refiere al área de contenido, manteniendo al padding y el borde fuera de este.

- ```box-sizing: border-box``` nos indica que al definir el tamaño de un elemento incluiremos tanto al padding como el borde dentro del ancho y alto establecidos.

- ***Impacto*** ```border-box``` es más fácil de manejar cuando se desean tamaños exactos para los elementos, ya que no se necesitan cálculos adicionales para el padding y el borde.

## 3. Cuáles son las propiedades principales que se utilizan para configurar un contenedor flex y cómo afectan la disposición de los elementos dentro de él❓

Las propiedades principales para configurar un contenedor flex son:

- ```display: flex:``` Establece el contenedor como un contenedor flex, permitiendo organizar los elementos hijos en una fila o columna.

- ```flex-direction:``` Determina la dirección en la que los elementos se organizan. Puede tomar valores:

    ***row(predeterminado), column, row-reverse o column-reverse.***

- ```justify-content:``` Alinea los elementos a lo largo del eje principal (horizontal en row, vertical en column). Los valores comunes son:

 ***flex-start, flex-end, center, space-between, space-around, space-evenly.***

- ```align-items:``` Alinea los elementos a lo largo del eje transversal (vertical en row, horizontal en column). Los valores comunes son:

 ***flex-start, flex-end, center, stretch (por defecto).***

- ```align-self:``` Permite a un solo elemento flex sobrescribir la alineación definida por align-items.

## 4. Cómo se utiliza la propiedad flex para controlar el tamaño y el crecimiento de los elementos flexibles dentro de un contenedor❓

Con estas tres propiedades: ***flex-grow, flex-shrink y flex-basis.***

- ***flex-grow:*** Define el factor de crecimiento de un elemento dentro del contenedor flex. Si todos los elementos tienen ```flex-grow: 1```, compartirán el espacio adicional disponible de manera igual.

- ***flex-shrink:*** Define el factor de reducción de un elemento cuando el espacio es insuficiente. Un valor de ```flex-shrink: 1``` permite que el elemento se reduzca si es necesario.

- ***flex-basis:*** Establece el tamaño inicial del elemento antes de distribuir el espacio disponible. Puede ser un valor en píxeles, porcentajes o auto (usando el tamaño del contenido).

sintaxis de la propiedad:

```css
flex: flex-grow flex-shrink flex-basis;
```

## 5. Cuáles son las diferencias entre los formatos de color RGB, RGBA, hexadecimal y HSL en CSS, y en qué situaciones sería más conveniente utilizar cada uno❓

- ***RGB:*** Representa los colores mediante tres valores que indican la intensidad de los colores rojo, verde y azul (en valores de 0 a 255). => rgb(rojo, verde, azul). Util cuando queremos especificar colores en terminos de luz.

- ***RGBA:*** Similar a RGB, pero incluye un cuarto valor que representa la opacidad del color (alfa), en un rango de 0 a 1. => rgba(255, 0, 0, 0.5) (rojo con 50% de opacidad). Ideal cuado necesitamos manejar transparencias.

- ***Hexadecimal:*** Representa los colores con un valor hexadecimal. Los primeros dos caracteres representan el rojo, los siguientes dos el verde y los últimos dos el azul. Ejemplo: #FF0000 (rojo). Muy utilizado por su compatibilidad.

- ***HSL:*** Representa los colores mediante tres componentes: H (tono, de 0 a 360 grados), S (saturación, de 0% a 100%) y L (luminosidad, de 0% a 100%). Ejemplo: hsl(0, 100%, 50%) (rojo). Muy conveniente cuando queremos manipular saturacion y luminosidad .

🏠 [***Regresar***](../README.md)

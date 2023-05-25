
# Notas generales del curso

#### Para buscar
HTML

'fielset' 'legend' 'value' 'iFrame'

CSS
'transition'
'transform'
'float'
pesudo clases
¡Alternativa correcta! Tanto el float:left como el float: right sirven para que el elemento se destaque en la pantalla, la superficie del elemento continúa siendo utilizada y los otros elementos de texto o elementos en línea se posicionan alrededor de él.
'background: linear-gradient radial-gradient'
pseudo elementos

Opacidad

opacity: #000000;    o     color: rgba(0, 0, 0, 0.5);

Sombras
    box-shadow: 10px -10px 25px 5px #000000, -10px -10px #c78c19;
    box-shadow: inset 0 0 30px #c78c19;


# CSS
### CSS Avanzado
.titulo-principal:before {
    content: "{";
}
.titulo-principal::after {
    content: "[";
}

Selector > , para acceder a los hijos de determinado elemento. Por ejemplo, para acceder todos los p dentro del main:
'h3 > p {
    background: yellow; 
}'

Selector +, para acceder al primer hermano de determinado elemento. Por ejemplo, para acceder el primer p después de una img:
Para señalar solo el primer elemento luego de la primera etiqueta señalada.
' h3 + p {
    background: yellow;
}'

Selector ~, para acceder a todos los hermanos de determinado elemento. Por ejemplo, para acceder todos los p después de una img:
Para señalar todos los elementos luego de la primera etiqueta señalada.
'img ~ p {
    background: yellow; 
}'

Selector not, para acceder a los elementos, excepto algunos. Por ejemplo, para acceder a todos los p dentro de main excepto el p que tiene id missao:
A todos menos al ID
.principal p:not(#mision) {
    background: #088c19;
}
#### Calculos con CSS
Es una función que se puede aplicar para manejar diversas dimensiones de los elementos
'calc(40% - (26px))'

#### Responsive

@media screen and (max-width:480px) {
    body {
       background: red;
    }
}

## Simbolos 

~ 'Alt + 126'
' 'Ctrl + 39'


### Recursos

unicode-table.com 
mobileinputtypes.com 
boxshadow generator de mozilla
screencastify
screenrecorder

'clear'
# **NVIM**
## **Atajos de teclado para neovim**
### **Navegacion:**

* cheakhealth - revisa si hay fallas con los paquetes en vim

* H - Recorre hacia la derecha
* J - Recorre hacia abajo
* K - Recorre hacia arriba
* L - Recorre hacia la izquierda 
* i - insertar texto
* W - Salta de palabra en palabra hacia adelante
* B - Salta de palabra en palabra hacia atras
* shift + 4 - NOs lleva al final de la linea
  - 0 - Nos lleva al incio de la linea
* Ctrl + C - Salir de insertar
* Numero + (H,J,K,L) - Recorrera tantas lineas como indiques y junto a la direccion que queremos que recorra
  - :(numero) - Nos llevara a la linea especificada
* D + D - Borra la linea actual
* D + W - Borra una palabra hacia adelante
* D + B - Borra una palabra hacia atras
  - (En la linea de arriba si le agramos una B mas borraria dos palabras y asi sucesivamente)
* } - Salta hasta la proxima linea en blanco hacia abajo
* { - Salta a la linea en blanco pero hacia arriba
* Shift + A - Inserta texto al final
* Shift + I - Inserta texto al inicio
* O - Salta una linea hacia abajo y se pone en insertar.
* Shift + O - Salta una linea hacia arriba y se pone en modo insertar.
* G + G - Me manda a la primera linea
* Shift + G - Dirige hacia la ultima linea
* U - Funciona como Ctrl Z
* Ctrl + R - Rehace lo que borramos con el Ctrl Z
* C + W - Cambia la palabra y nos coloca en modo insertar
* T + shift + (letra) - Nos llevara a la incial de la letra a la que queremos ir
  - Le podemos agregar un numero antes del T por si una letra se repite
  - shift + T + (Letra) - Hace lo mismo solo que hacia atras

### **Mover, copiar pegar**
* V - Nos pone en modo visual y nos permite seleccionar codigo
* shift + V - Selecciona toda la linea
* Y - Copia el la linea cuando esta esta seleccionada
* D - borra la linea (Tambien funciona para mover)
* P - Pega el codigo
  - shift + P - Pega el codigo en la parte superior

### **Expresiones regulares**
* :%s/Key/qtile/g
* :nohlsearch
### **Macros**
Los macros repiten diversos comandos
* . - Literal repite el ultimo comando que usaste
* Q + (letra) - Graba todo lo que hagas y con q para de grabar
  - @ + (letra) - Aplica el comando grabado
* :%norm! (@nombre del macro) - Aplica el macro global
* :(linea),(linea)norm! (@macro) - Aplica el macro especificando la linea que le mandemos
### **atajaos de teclado**
* :split + (ruta) - Abrira otra ventana de vim
* :vsplit + (ruta) - Abrira otra ventana pero en vertical 
* :bd - cierra una ventana
* ctrl + (H,J,K,L) - Para cambiar de ventana
* alt + (H,J,K,L) - cambia el tamaño de la ventana

### **Moverse dentro del Entorno**
* space + n abre el Nerdtree
* space + f abre un buscador
* space + r abre el ranger
* (space + /) or (space + shift + /) comenta la linea
* space + p Formatea el codigo con prettier
* shift + i muestra archivos ocultos
* M crear un archivo en el Nerdtree

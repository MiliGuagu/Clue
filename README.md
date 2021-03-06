# Impostor

One suspect, one room, one weapon.
Mr. Boddy is found death in one of the rooms of his mansion.
All you need to do is answer who killed them, where and how.
Go and find the impostor...
SHHHHHH......

Impostor is a Among Us flavored Clue game.
· - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - ·
## How to install

Using Cmake in Windows:

>cmake -G "MinGW Makefiles" -D CMAKE_C_COMPILER="C:/Program Files/mingw-w64/x86_64-8.1.0-posix-seh-rt_v6-rev0/mingw64/bin/x86_64-w64-mingw32-gcc.exe" ..

Where CMAKE_C_COMPILER is the route to your MinGW32-gcc.exe. You need to have installed the 64-bits MinGW.
Then you can run:

>minGW32-make

In Linux(Ubuntu):
>sudo apt install build-essential git

>sudo apt install cmake

>sudo apt install libasound2-dev mesa-common-dev libx11-dev libxrandr-dev libxi-dev xorg-dev libgl1-mesa-dev libglu1-mesa-dev
Then go to usr/local/lib and: 

>cd /usr/local/lib
>git clone https://github.com/raysan5/raylib.git raylib
>cd raylib
>sudo mkdir build && cd build
>sudo cmake -DSHARED=ON -DSTATIC=ON ..
>sudo make
>sudo make install

Compile in MAC:
>make clean
>make 
>./main 

· - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - ·

# Requerimientos 
## Requerimientos funcionales

#### Color-code

Gráficos (red) (green)

![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No`
![#49F262](https://via.placeholder.com/15/49F262/000000?text=+) `Yes`

Gráficos/Mecánico (orange) (blue)

![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No`
![#5E6AF3](https://via.placeholder.com/15/5E6AF3/000000?text=+) `Yes`

Mecánico (pink) (light green)

![#F471CD](https://via.placeholder.com/15/F471CD/000000?text=+) `No`
![#CDF471](https://via.placeholder.com/15/CDF471/000000?text=+) `Yes`

Manejo de Datos (purple) (yellow)

![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No`
![#F4D434](https://via.placeholder.com/15/F4D434/000000?text=+) `Yes`


#### 'Start Menu'
| Area | Requirement | Notes | Pruebas | Done? |
|-|-|-|-|-|
| Gráficos | Mostrar Menú de 'Start Menu' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | Menú de 'Start Menu' Interactivo | Que el menú sea interactivo | Revisar que se vea el mouse y que se puedan seleccionar los botónes | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'New Game' en 'Start Menu' Funcional | Que el botón de 'New Game' lleve a la ventana indicada | Revisar que el botón lleve a la ventana de 'New Menu' o a la ventana de 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Load Game' en 'Start Menu' Funcional | Que el botón de 'Load Game' lleve a la ventana indicada | Revisar que el botón lleve a la ventana de 'Load Menu' o a la ventana de 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Settings' en 'Start Menu' Funcional | Que el botón de 'Settings' lleve a la ventana indicada | Revisar que el botón lleve a la ventana de 'Settings' o a la ventana de 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botones en 'Settings' Funcionales | Que los botones en 'Settings' puedan ser seleccionados | Revisar que los botones hagan su función correspondiente | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Manejo de Datos | Cambios hechos 'Settings' Guardados | Que al hacer un cambio en 'Settings' se tomen en cuenta las decisiones del usuario | Revisar que al salirse de 'Settings' se guarde la información dada por el usuario | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Return' en 'Settings' Funcional | Que el botón de 'Return' en 'Settings' pueda ser seleccionado y lleve a la pantalla indicada | Revisar que el botón pueda ser seleccionado y lleve a la ventana de 'Start Menu' o 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Credits' en 'Start Menu' Funcional | Que el botón de 'Credits' lleve a la ventana indicada | Revisar que el botón lleve a la ventana de 'Credits' o a la ventana de 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Return' en 'Credits' Funcional | Que el botón de 'Return' en 'Credits' pueda ser seleccionado y lleve a la pantalla indicada | Revisar que el botón pueda ser seleccionado y lleve a la ventana de 'Start Menu' o 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |

#### 'New Menu'
| Area | Requirement | Notes | Pruebas | Done? |
|-|-|-|-|-|
| Gráficos | Mostrar Menú de 'New Menu' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | Menú de 'New Menu' Interactivo | Que el menú sea interactivo | Revisar que se vea el mouse y que se puedan seleccionar los botónes | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botones de 'New Menu' Funcionales | Que los botones en 'New Menu' puedan ser seleccionados | Revisar que los botones hagan su función correspondiente | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botones de 'Characters' en 'New Menu' sean Únicos | Que los botones de 'Characters' en 'New Menu' solo contengan 1 personaje por usuario | Revisar que los botones solo puedan seleccionar 1 personaje y sea único por usuario | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Manejo de Datos | 'Characters' en 'New Menu' Guardado | Que los personajes ingresados en 'Characters' en 'New Menu' se guarden | Revisar que los personajes puestos en 'Characters' se guarden en el juego (todas las instancias) | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Name' en 'New Menu' Funcional | Que el botón de 'Name' en 'New Menu' sea funcional | Revisar que el botón de 'Name' funcione, que el usuario pueda ingresar su nombre | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Manejo de Datos | 'Name' en 'New Menu' Guardado | Que nombre ingresado en 'Name' en 'New Menu' se guarde | Revisar que el 'Name' se guarde en el juego (todas las instancias) | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Start Game' en 'New Menu' Funcional | Que el botón de 'Start Game' lleve a la ventana indicada | Revisar que el botón lleve a la ventana de 'SHH' o a la ventana de 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Manejo de Datos | 'Start Game' en 'New Menu' Guardado | Que al iniciar un 'Game' se tomen en cuenta las decisiones del usuario | Revisar que al iniciar el botón 'Start Game' se guarden toda la información dada por el usuario | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Cancel' en 'New Menu' Funcional | Que el botón de 'Cancel' en 'New Menu' pueda ser seleccionado y lleve a la pantalla indicada | Revisar que el botón pueda ser seleccionado y lleve a la ventana de 'Start Menu' o 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |

#### 'Load Menu'
| Area | Requirement | Notes | Pruebas | Done? |
|-|-|-|-|-|
| Gráficos | Mostrar Menú de 'Load Menu' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | Menú de 'Load Menu' Interactivo | Que el menú sea interactivo | Revisar que se vea el mouse y que se puedan seleccionar los botónes | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botones de 'Load Menu' Funcionales | Que los botones en 'Load Menu' puedan ser seleccionados | Revisar que los botones hagan su función correspondiente | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botones de 'Save...' en 'Load Menu' Funcionales | Que los botones de 'Save...' en 'Load Menu' lleven a la ventana indicada | Revisar que los botones lleven a la ventana de 'SHH' o a la ventada de 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Manejo de Datos | 'Save...' Guardado en 'Load Menu' Corre | Que el save hecho en 'Save...' hecho por el usuario este guardado y se pueda correr | Revisar que al precionar 'Save...' se pueda correr el juego seleccionado por el usuario | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Cancel' en 'Load Menu' Funcional | Que el botón de 'Cancel' en 'Load Menu' pueda ser seleccionado y lleve a la pantalla indicada | Revisar que el botón pueda ser seleccionado y lleve a la ventana de 'Start Menu' o 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |

#### 'Extra'
| Area | Requirement | Notes | Pruebas | Done? |
|-|-|-|-|-|
| Gráficos | Mostrar Menú de 'Loading' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos | Mostrar Movimiento en el Menú de 'Loading' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | Menú de 'Loading' Funcional | Que el menú de 'Loading' lleve a la ventana indicada | Revisar que el menú de  'Loading' lleve a la ventana que deba de ir dependiendo de cual sea la situación | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos | Mostrar Menú de 'SHH' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | Menú de 'SHH' Funcional | Que el menú de 'SHH' lleve a la ventana indicada | Revisar que el menú de 'SHH' lleve a la ventana de 'Game' o a la ventana de 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |

#### 'Game'
| Area | Requirement | Notes | Pruebas | Done? |
|-|-|-|-|-|
| Graficos | Mostrar ventana de 'Game' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos | Mostrar Tablero en 'Game' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Graficos | Mostrar personajes en Tablero en 'Game' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de los personajes | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos | Mostrar 'Cards' en el Tablero en 'Game' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de las cartas | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | 'Cards' en el Tablero en 'Game' Interactivo | Que las cartas en el tablero puedan ser seleccionadas | Revisar que el usuario pueda seleccionar las cartas en 'Cards' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Mecánico | 'Cards' dadas por el juego | Que las cartas en el tablero puedan ser seleccionadas | Revisar que el usuario pueda seleccionar las cartas en 'Cards' | ![#F471CD](https://via.placeholder.com/15/F471CD/000000?text=+) `No` |
##### 'Pause' in 'Game'
| Area | Requirement | Notes | Pruebas | Done? |
|-|-|-|-|-|
| Graficos | Mostrar botón de 'Pause' en 'Game' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia en la ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Pause' Interactivo | Que el menú sea interactivo | Revisar que se vea el mouse y que se puedan seleccionar el botón | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Graficos | Mostrar ventana de 'Pause' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | Botones en 'Pause' Funcionales | Que los botones en 'Pause' pueda ser seleccionado | Revisar que los botones hagan su función correspondiente | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Change Settings' en 'Pause' Funcional | Que el botón de 'Settings' en 'Pause' pueda ser seleccionado y lleve a la ventana correcta | Revisar que 'Change Settings' lleve a la ventana de 'Settings' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Save' en 'Settings' Funcional | Que el botón de 'Save' en 'Settings' pueda ser seleccionado y lleve a la pantalla indicada | Revisar que el botón pueda ser seleccionado y lleve a la ventana de 'Pause' o 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Manejo de Datos | Cambios hechos 'Settings' Guardados | Que al hacer un cambio en 'Settings' se tomen en cuenta las decisiones del usuario | Revisar que al salirse de 'Settings' se guarde la información dada por el usuario | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Return to Game' en 'Pause' Funcional | Que el botón de 'Return to Game' en 'Pause' pueda ser seleccionado y lleve a la pantalla indicada | Revisar que el botón pueda ser seleccionado y lleve a la ventana de 'Game' o 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Restart' en 'Pause' Funcional | Que el botón de 'Restart' en 'Pause' pueda ser seleccionado y lleve a la pantalla indicada | Revisar que el botón pueda ser seleccionado y lleve a la ventana de 'Game' nueva o 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Manejo de Datos | 'Botón de 'Restart' en 'Pause' Borre | Que el botón de 'Restart en 'Pause' borre los hechos realizados por el usuario | Revisar que los hechos que el usuario tenía se borren y reinicien, que empiece desde 0 y se cambién las cartas | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
##### 'Notebook' in 'Game'
| Area | Requirement | Notes | Pruebas | Done? |
|-|-|-|-|-|
| Graficos | Mostrar botón de 'Notebook' en 'Game' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia del cuaderno | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | Botón en 'Notebook' en 'Game' Funcional | Que el botón de 'Notebook' en 'Game' sea funcional | Revisar que el botón de 'Notebook' lleve a la ventana de 'Notebook' o a 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Mecánico | Botón en 'Notebook' en 'Game' Funcional en TODO MOMENTO | Que el botón de 'Notebook' en 'Game' sea funcional en TODO MOMENTO | Revisar que el botón de 'Notebook' siempre funcione | ![#F471CD](https://via.placeholder.com/15/F471CD/000000?text=+) `No` |
| Graficos | Mostrar ventana de 'Notebook' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | Botones en 'Notebook' Funcionales | Que los botones en 'Notebook' pueda ser seleccionados | Revisar que los botones hagan su función correspondiente | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Return to Game' en 'Notebook' Funcional | Que el botón de 'Return to Game' en 'Notebook' pueda ser seleccionado y lleve a la pantalla indicada | Revisar que el botón pueda ser seleccionado y lleve a la ventana de 'Game' o 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Manejo de Datos | Cambios hechos 'Notebook' Guardados | Que al hacer un cambio en 'Notebook' se tomen en cuenta las decisiones del usuario | Revisar que al salirse de 'Notebook' se guarde la información dada por el usuario | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
##### In 'Game'
| Area | Requirement | Notes | Pruebas | Done? |
|-|-|-|-|-|
| Gráficos | Mostrar 'Moves' en el Tablero en 'Game' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de 'Moves' | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | 'Moves' en el Tablero en 'Game' Funcional | Que los 'Moves' que se mostrados correspondan al número de movimientos que tiene el usuario | Revisar que se muestre el número correcto de movimientos | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos | Mostrar 'Dice' en el Tablero en 'Game' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de 'Dice' | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | 'Dice' Funcional | Que al precionar el 'Dice' este de un número | Revisar que al precionar 'Dice' este de un número válido (1-6) el cual pueda ser usado por el usuario | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | 'Moves' en Tablero en 'Game' dados por 'Dice' | Que los números dados por 'Dice' se reflejen y correspondan al número de 'Moves' disponibles | Revisar que el número de 'Moves' disponibles sea el mismo al dado por 'Dice' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Mecánico | 'Dice'-'Moves' Funcional | Que el usuario solo se pueda mover la cantidad de espacios dada por 'Dice' | Revisar que el usuario solo se pueda mover la cantidad de espacios que dio el 'Dice' | ![#F471CD](https://via.placeholder.com/15/F471CD/000000?text=+) `No` |
| Gráficos/Mecánico | Movimiento Funcional | Que al precionar las teclas de movimiento el personaje se mueva | Revisar que al precionar las teclas el personaje se mueva a la dirección que el usuario indico | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Movimiento Único | Que el usuario solo pueda mover su personaje | Revisar que el usuario solo sea capaz de mover su personaje | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | 'Moves' en Tablero en 'Game' Decreciente | Que la cantidad de 'Moves' restante decrezca cada vez que el usuario se mueva a través del tablero | Revisar que el número de 'Moves' bajen cada vez que se mueva | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Sin 'Moves' en Tablero en 'Game' Correcto | Que si el usuario se queda sin 'Moves', este ya no se pueda mover a traves del tablero | Revisar que si el usuario ya no tiene movimientos disponibles, ya no se pueda mover | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos | Sin 'Moves' en Tablero en 'Game' Retardo | Mostrar 0 movimientos y mostrar delay para que el usuario sepa que ya no tiene movimientos | Revisar que se muestren la falta de movimientos disponibles y que el usuario entienda que ya termino su turno | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | 'Turns' Funcional | Que si el usuario se queda sin movimientos, se pase al siguiente turno | Revisar que si el usuario no tiene movimientos disponibles, se mueva al siguiente turno | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
...
##### 'Suggestion' in 'Game'
| Area | Requirement | Notes | Pruebas | Done? |
|-|-|-|-|-|
| Graficos | Mostrar botón de 'Suggestion' en 'Game' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de 'suggestion' | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | Botón en 'Suggestion' en 'Game' Funcional | Que el botón de 'Suggestion' en 'Game' sea funcional | Revisar que el botón de 'Suggestion' lleve a la ventana de 'Suggestion' o a 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Mecánico | Botón en 'Suggestion' en 'Game' Funcional en MOMENTOS ESPECÍFICOS | Que el botón de 'Suggestion' en 'Game' sea funcional en momentos específicos | Revisar que el botón de 'Suggestion' funcione SOLO AL ENTRAR A 'Rooms' y que este NO sea Cafeteria | ![#F471CD](https://via.placeholder.com/15/F471CD/000000?text=+) `No` |
| Graficos | Mostrar ventana de 'Suggestion' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Graficos | Mostrar 'Characters' y botones en la ventana de 'Suggestion' | De la siguiente manera (inserte imagen) | Revisar que se cree la personajes y botones | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | Botones en 'Suggestion' Funcionales | Que los botones en 'Suggestion' pueda ser seleccionados | Revisar que los botones hagan su función correspondiente | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botones de 'Character' en 'Suggestion' Único | Que solo se pueda cambiar los valores de un solo 'Character' a la vez | Revisar que solo se puedan cambiar los valores 1 personaje al la vez | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Place' en 'Suggestion' Estático | Que no se puedan modificar el valor | Revisar que no se pueda modificar el valor de 'Place' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Place' en 'Suggestion' Correcto | Que 'Place' muestre el lugar donde esta el usuario | Revisar que en 'Place' diga el cuarto en donde esta el usuario | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Death' en 'Suggestion' Interactivo | Que el botón de 'Death' en 'Suggestion' pueda ser seleccionado | Revisar que el botón sea interactivo y cambie según el input del usuario | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Death' en 'Suggestion' Funcional | Que el botón de 'Death' en 'Suggestion' muestre las muertes y funcione como elección | Revisar que la información puesta en el botón se tome en cuenta | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Manejo de Datos | 'Character' en 'Suggestion' Guardado | Que el input dado por el usuario sea tomado en cuenta para mostrar las cartas en 'Game' | Revisar que el valor dado por el usuario en 'Character' sea el correcto | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
| Manejo de Datos | 'Death' en 'Suggestion' Guardado | Que el input dado por el usuario sea tomado en cuenta para mostrar las cartas en 'Game' | Revisar que el valor dado por el usuario en 'Death' sea el correcto | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
##### 'Accusation' in 'Game'
| Area | Requirement | Notes | Pruebas | Done? |
|-|-|-|-|-|
| Graficos | Mostrar botón de 'Accusation' en 'Game' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de 'accusation' | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | Botón en 'Accusation' en 'Game' Funcional | Que el botón de 'Accusation' en 'Game' sea funcional | Revisar que el botón de 'Accusation' lleve a la ventana de 'Accusation' o a 'Loading' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Mecánico | Botón en 'Accusation' en 'Game' Funcional en CAFETERIA | Que el botón de 'Accusation' en 'Game' sea funcional en cafeteria | Revisar que el botón de 'Accusation' solo funcione cuando el usuario esta en CAFETERIA | ![#F471CD](https://via.placeholder.com/15/F471CD/000000?text=+) `No` |
| Graficos | Mostrar ventana de 'Accusation' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Graficos | Mostrar 'Characters' y botones en la ventana de 'Suggestion' | De la siguiente manera (inserte imagen) | Revisar que se cree la personajes y botones | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Gráficos/Mecánico | Botones en 'Suggestion' Funcionales | Que los botones en 'Suggestion' pueda ser seleccionados | Revisar que los botones hagan su función correspondiente | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botones de 'Character' en 'Accusation' Único | Que solo se pueda cambiar los valores de un solo 'Character' a la vez | Revisar que solo se puedan cambiar los valores 1 personaje al la vez | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Place' en 'Accusation' Interactivo | Que el botón de 'Place' en 'Accusation' pueda ser seleccionado | Revisar que el botón sea interactivo y cambie según el input del usuario | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Place' en 'Accusation' Funcional | Que el botón de 'Place' en 'Accusation' muestre los cuartos y funcione como elección | Revisar que la información puesta en el botón se tome en cuenta | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Death' en 'Accusation' Interactivo | Que el botón de 'Death' en 'Accusation' pueda ser seleccionado | Revisar que el botón sea interactivo y cambie según el input del usuario | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Gráficos/Mecánico | Botón de 'Death' en 'Accusation' Funcional | Que el botón de 'Death' en 'Accusation' muestre las muertes y funcione como elección | Revisar que la información puesta en el botón se tome en cuenta | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Manejo de Datos | 'Character' en 'Accusation' Guardado | Que el input dado por el usuario sea tomado en cuenta para mostrar las cartas en 'Game' | Revisar que el valor dado por el usuario en 'Character' sea el correcto | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
| Manejo de Datos | 'Place' en 'Accusation' Guardado | Que el input dado por el usuario sea tomado en cuenta para mostrar las cartas en 'Game' | Revisar que el valor dado por el usuario en 'Place' sea el correcto | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
| Manejo de Datos | 'Death' en 'Accusation' Guardado | Que el input dado por el usuario sea tomado en cuenta para mostrar las cartas en 'Game' | Revisar que el valor dado por el usuario en 'Death' sea el correcto | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
| Manejo de Datos | 'Correct' en 'Accusation' Valorado | Que el input dado por el usuario sea valorado, y si el usuario da las opciones correctas se termina el juego y gana dicho usuario | Revisar que el valor dado por el usuario, si es correcto, cause el fin del juego y un 'ganar' del juego | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
| Mecánico | 'Win' causa el fin del 'Game' | Sí un usuario da un 'Accusation' correcto, 'Game' termina | Revisar que si un usuario da un 'Accusation' donde todos sus datos son correctos, 'Game' termina | ![#F471CD](https://via.placeholder.com/15/F471CD/000000?text=+) `No` |
| Gráficos/Mecánico | 'Ganar' lleva al usuario a pantalla de 'Win' | Que al ganar el juego, lo lleve a la pantalla de 'Win' | Revisar que el usuario sea llevado a la pantalla de 'Win' | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Graficos | Mostrar pantalla de 'Win' | De la siguiente manera (inserte imagen) | Revisar que se cree la instancia de ventana | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Manejo de Datos | 'Incorrect' en 'Accusation' Valorado | Que el input dado por el usuario sea valorado, y si el usuario da las opciones incorrectas se termina los turnos por el usuario y este pierde | Revisar que el valor dado por el usuario, si es incorrecto, cause el fin de sus turnos y un 'perder' del juego | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |
| Mecánico | 'Lose' causa el fin de turnos para el usuario en 'Game' | Sí un usuario da un 'Accusation' incorrecto, ya no tiene turnos en 'Game' | Revisar que si un usuario da un 'Accusation' donde todos sus datos son incorrectos, sus turnos en 'Game' terminan | ![#F471CD](https://via.placeholder.com/15/F471CD/000000?text=+) `No` |


| Area | Requirement | Notes | Pruebas | Done? |
|-|-|-|-|-|
| Graficos | ... | ... | ... | ![#F0170F](https://via.placeholder.com/15/F0170F/000000?text=+) `No` |
| Mecánico | ... | ... | ... | ![#F471CD](https://via.placeholder.com/15/F471CD/000000?text=+) `No` |
| Gráficos/Mecánico | ... | ... | ... | ![#F4993E](https://via.placeholder.com/15/F4993E/000000?text=+) `No` |
| Manejo de Datos | ... | ... | ... | ![#B434F4](https://via.placeholder.com/15/B434F4/000000?text=+) `No` |


- [ ] Mecanica de movimiento => move(int, int)
- [ ] Mecanica de los dados => int dice(int) // (1234142214213) success: 5,6,4,3,2,1 || fail: 12, -1, 0


## Requerimientos no funcionales

### Sprites
- [x] Clue Map similar to "Skeld"
- [ ] 'Shhh' Screen
- [ ] 'Winner' Screen
- [ ] 'Loser' Screen
- [x] 'Main Menu' Screen
- [x] 'Load' Screen
- [ ] 'Settings' Screen
- [x] 'Credits' Screen
- [ ] HUD
- [ ] 'Notebook' Screen
- [ ] 'Loader' Screen
- [ ] 'Loader' Screen
- [ ] Sprite Card Upper Engine
- [ ] Sprite Card Weapons
- [ ] Sprite Card Medbay
- [ ] Sprite Card Storage
- [ ] Sprite Card Reactor
- [ ] Sprite Card Cafeteria
- [ ] Sprite Card Navigation
- [ ] Sprite Card Admin
- [ ] Sprite Card Electrical
- [ ] Sprite Card Lower Engine
- [ ] Sprite Card Shields
- [ ] Sprite Card Colonel Mustard
- [ ] Sprite Card Miss Scarlet
- [ ] Sprite Card Professor Plum
- [ ] Sprite Card Mr. Green
- [ ] Sprite Card Mrs. White
- [ ] Sprite Card Mrs. Peacock
- [ ] Sprite Card Gun Shot
- [ ] Sprite Card Stabbing
- [ ] Sprite Card Neck Snap
- [ ] Sprite Card Throat Saber
- [ ] Sprite Card Thrown into Space
- [ ] Sprite Card Disconected from Server
- [x] Spritesheet Yellow Astronaut
- [x] Spritesheet Red Astronaut
- [x] Spritesheet Purple Astronaut
- [x] Spritesheet Green Astronaut
- [x] Spritesheet White Astronaut
- [x] Spritesheet Blue Astronaut

## Animaciones
- [ ] Deaths

### Botones que envian a otras ventanas
- [x] New Game -> Ventana de Opciones de nuevo juego
- [ ] New Game Options -> Ventana de Shhh(inicio de juego)
- [x] Load -> Ventana de Carga
- [ ] Settings -> Ventana de Opciones
- [x] Credits -> Ventana de Creditos

- [ ] Quit Game -> Main Menu
- [ ] Save Game -> Ventana de Guardado
- [ ] Load Game -> Juego Cargado
- [ ] Options -> Ventana de Settings
- [ ] Restart -> Volver a iniciar el juego desde el inicio
- [ ] Cancel -> Volver al Juego

### Funciones o Mecanicas
- [ ] SaveGame()
- [ ] LoadGame()
- [ ] SetGame()
- [ ] FillPackage()
- [ ] Accusation(player,character, weapon, place)
- [ ] Suggestion(self,character, weapon, place)
- [ ] GenerateTurnGameList()
- [ ] Movement()
- [ ] Teletransport()
- [ ] EnterRoom()
- [ ] ExitRoom()
- [ ] CalculateRandomMovements()
- [ ] HatONames()

### Estructuras necesarias
- [ ] GameState
- [ ] GameInitialState
- [ ] GameHistory
- [ ] Board
- [ ] Player
- [ ] Notebook
- [ ] Accusations


· - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - ·


## Base Information

###### Sprites to do
######      sprite for the card
The mansion has 11 rooms.
- Hall -> Reactor
- Ballroom -> Navigation
- Conservatory -> Shields
- Dining Room -> Medbay
- Kitchen -> Weapons
- Lounge -> Upper Engine
- Study -> Lower Engine
- Library -> Electrical
- Billiard Room -> Storage
- Pool -> Cafeteria

###### Sprites to do
######      sprite for the playable characters on the game's board 
######      sprite for the card
There are 6 suspects for the murder
- Colonel Mustard
- Miss Scarlet
- Professor Plum
- Mr. Green
- Mrs. White
- Mrs. Peacock

###### Sprites por hacer
######      sprite en forma de figuras movibles por el juego y los usuarios sobre el tablero
######      sprite en forma de carta manejable
There are 6 weapons
- Rope
- Lead Pipe
- Knife
- Wrench
- Candlestick
- Revolver

· - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - ·

## Before the Game Starts
###### mecánica de elegir personaje: cartas que seleccionar/clickear? 
######      mostrar personajes y el usuario elige el que desea 
######      el personaje seleccionado es la pieza que el usuario juega
######      el usuario es capaz de mover su personaje solamente
You choose one of the six characters, all represented with a color related to their names. 
- Colonel Mustard -> yellow
- Miss Scarlet -> red
- Professor Plum -> purple
- Mr. Green -> green
- Mrs. White -> white 
- Mrs. Peacock -> blue

###### mecánica de inicio
######      mostrar tablero
######      mostrar a todos los personajes en el tablero
######      mostrar a todas las armas puestas random en el tablero
######      mostrar el sobre en medio < explicado posteriormente >
######            el sobre ya debe de incluir las cartas correspondientes
######      mostrar cuaderno en el lado derecho
######            poder manipular el cuaderno en cualquier momento
######      mostrar el botón de "accusation" en cualquier momento
######      mostrar la existencia de otras personas/AI
######      mecánica del sobre
######            contiene una carta que indica el personaje 'culpable' (random)
######            contiene una carta que indica el arma 'culpable' (random)
######            contiene una carta que indica el lugar 'culpable' (random)
######            el sobre se muestra al centro del tablero
######            el contenido del sobre solo se muestra después de una "accusation"
######            el sobre NO es clickeable ni interactivo
######      mecánica de repartir cartas
######            el resto de las cartas que NO estan incluidas en el sobre son distribuidas entre los participantes
######            las cartas se dividen lo más equitativamente posible entre los personajes
######            se muestran las cartas del usuario en su 'mano' (parte inferior del tablero)
######            las cartas son interactivas
######            si se selecciona una carta sin estar en "suggestion", nada pasa
######      mecánica del cuaderno
######            mostrar cuaderno en el lado derecho de la pantalla
######            cuaderno interactivo
######            se puede manipular el cuaderno en cualquier momento
######            mostrar las secciones necesarias
######            – – – – – – – – – – – – – – – – – – – – – – –
######            | SUSPECTS                                  |
######            |   Professor Plum     [X]  [ ]  [ ]  [ ]   |
######            |   Colonel Mustard    [ ]  [ ]  [ ]  [ ]   |
######            | WEAPONS                                   |
######            |   Lead Pipe          [ ]  [ ]  [ ]  [ ]   |
######            |   Candlestick        [ ]  [ ]  [ ]  [ ]   |
######            | ROOMS                                     |
######            |   Conservatory       [X]  [ ]  [ ]  [ ]   |
######            |   Library            [X]  [ ]  [ ]  [ ]   |
######            – – – – – – – – – – – – – – – – – – – – – – –
######            esto es independiente del juego, lo que sea tachado o no NO afecta en nada el juego
######            el juego no lee las decisiones del jugador
######      2) mecánica del AI -> Roberto
######            Roberto es capaz de saber cuales son sus cartas

All the characters are to be present on the board, whether they represent a player or not. They all start at a specific place on the map.

All weapons will be randomly placed on a room. 

There are 21 total cards divided in three groups: suspects with 6 cards, Rooms with 9 cards and Weapons with 6 cards. Each card representing the already mentioned suspects, rooms and weapons. 

In the middle of the map there is be an enveloped with the marking "Case File Confidential”, it is placed at the center of the map. This envelope holds the information about the murderer, the crime scene and the murder weapon. These are randomly selected. 

The cards for the remaining suspects, rooms and weapons are shuffled and distributed as equally as possible (as there are 18 cards left) among all the players. 

You will also be provided with a notebook that has all the characters, all the rooms and all the weapons with some boxes you can cross off when you consider they are *guilty*. It is advisable to cross off one’s cards upon receiving them as, if in your hand, they are not in the envelope. 

**For example:**

Suspects
- [x] Professor Plum
- you can cross this because you have this card in you hand and *you know* the envelope cannot contain it.
- [ ] Mrs. Peacock 
- you decide not to cross this because you *do not know* if this card is in someone else's hand or in the envelope.

· - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - ·

## Game Play
Now the game starts!

###### mecánica de juego :D
######      mecánica del turnos
######            primero inicia la pieza roja o la correspondiente a _Miss Scarlett_
######            si no hay _Miss Scarlett_, el orden es aleatorio
######            el resto se mueve con las manecilals del reloj: clock-wise
Miss Scarlett opens the game, the turns continue clockwise around the board. If no one chose Miss Scarlett, the choice is random. 

###### mecánica de juego :D
######      mecanica de movimiento
######            mecánica de tirar dados // minijuego de clickear rapido para crear la semilla de random
######            en cada turno, el usuario 'tira el dado'
######            el usuario se puede mover cierto número de casillas dadas por el dado
######            el usuario se mueve con las teclas < ^ v >
######            el movimiento es adelante, atrás, derecha e izquierda
######            el movimiento NO es en diagonal
######            NO puedes pasar sobre otro personaje
######            NO puedes pasar a través de otro personaje
######            NO puedes pasar dos veces por la misma casilla
######            existencia de paredes -> no puedes cruzar una pared
######            existencia de puertas -> puedes cruzar una puerta
######                  limites: no puedes cruzar la puerta si hay otro personaje adentro
######                  limites: no puedes cruzar la puerta si hay un usuario adelante de la puerta
######            existencia de cuartos -> puedes estar dentro de un cuarto
######                  un cuarto, aunque compuesto de varias casillas, se toma en cuenta como 1
######                  no puedes moverte dentro de un cuarto -> sus casillas no son casillas 'usables'
######                  adentro de un cuarto puedes hacer una "suggestion" < explicado posteriormente >
######                  un cuarto puede contener un mínimo de 0 armas y un máximo de 6 armas
######                  un cuarto puede contener un mínimo de 0 usuarios/personajes y un máximo de 6 personajes
######                        cuando se llama una "suggestion", se mete al personaje llamado
######                        este es la única instancia donde el cuarto puede contener a más de 1 personaje
######                        el usuario llamado puede llamar a una "suggestion"
######                  si el usuario esta en un cuarto, o pasa por un "Secret Passage" o se sale
######                  el usuario NO puede permanecer en un cuarto depués de una "suggestion"
######                  el usuario NO puede permanecer en un cuarto depués de su turno
######                  el usuario NO puede entrar dos veces al mismo cuarto en el mismo turno 
######                        a menos que sea llamado por una "suggestion"
######                  existencia de "Secret Passages"
######                        ciertas casillas que te transportan a otras casillas
######                        las casillas receptoras estan del lado opuesto del tablero
######                        requiere turno
######                        no se necesita tirar dados
######                        al pasar por un "Secret Passage" ingresas a otro cuarto
######                        misma reglas del cuarto
######            el área del sobre es tomada como pared
######            2) mecánica del AI -> Roberto
######                  Roberto es capaz de moverse según un dado random individual
######                  Roberto es capaz de entrar a cuartos
######                  Roberto es capaz de impedir que el usuario entre a un cuarto
######                  Roberto es capaz de llamar a una "suggestion"
######                  Roberto es capaz de seguir las reglas de movimiento

On each turn, a player will try to reach a different room of the mansion to investigate.

To move your character, you need to either roll the die or use a Secret Passage when in a corner room.

If you roll the die, you move however many spaces the die says. Your character can move horizontally or vertically, forward or backward, but never diagonally.

If you move through a Secret Passage, you don't need to roll the dice, you just move to the other room, ending your movement.

You are not allowed to enter the same room twice on the same turn nor pass through a square more than two times in the same turn.

You are not allowed to jump or pass through another character. This includes if the character is blocking an entrance to a room. You also cannot get out of a room if all the entrances are blocked. If this were to happen, you need to wait until someone moves and un-blocks a door. 

If the room you are trying to enter already has someone inside, you cannot do in. 

· - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - ·

### Suggestion

###### mecánica de juego :D
######      mecanica de "suggestion"
######            adentro de un cuarto puedes hacer una "suggestion"
######            mecánica de elegir sospechoso [ ] [X] [ ] [ ] [ ] [ ]
######            mecánica de elegir arma       [ ] [ ] [ ] [ ] [X] [ ]
######            el cuarto elegido es donde el usuario se encuentra
######            aparecera: 
######                  "The crime was committed by **Mrs. Peacock** in the **library** with a **wrench**".
######            ... con las opciones elegidas por el usuario
######            la pieza del personaje seleccionado entra al cuarto donde esta el usuario
######            la pieza del arma seleccionada se mete al cuarto donde esta el usuario
######            el resto de los usuarios te enseñaran sus cartas
######                  empieza el de la izquierda -> clock-wise
######                  botón de "continuar"
######                  si el usuario NO tiene ninguna carta de las mencionadas
######                        el botón "continuar" se podrá presionar
######                        ninguna carta se podrá seleccionar
######                  si el usuario SÍ tiene alguna carta de las mencionadas
######                        el botón "continuar" NO se podrá presionar hasta seleccionar una carta
######                        se podrán seleccionar SOLO las cartas mencionadas
######                        se tendrá que seleccionar 1 carta de las mencioandas
######                              si solo se tiene 1, se muestra esa 1
######                              si se tiene más de 1, el usuario elige cual enseñar
######                              se puede enseñar cartas ya enseñadas
######                        después de seleccionar la carta se presiona el botón de "continuar"
######                        solo se muestra la carta al que hizo la "suggestion"
######            mecánica de poder ver las cartas de otros usuarios
######            se usa para saber que cartas NO estan en el sobre
######            se puede hacer una "accusation" en cualquier momento < explicado posteriormente >
######            si eres un sospechoso y estas en el cuarto
######                  puedes decidir hacer una "suggestion"
######                  o puedes tirar los dados y salir del cuarto
######            2) mecánica del AI -> Roberto
######                  Roberto es capaz de mostrar cartas al usuario
######                  Roberto es capaz de ver cartas y tomarlas en cuenta
######                  Roberto es capaz de saber si tiene cartas o no
######                  Roberto es capaz de tratar de ganar
######                  Roberto es capaz de seguir las reglas de "suggestion"

When you enter a room, you can make a suggestion by naming a suspect, murder weapon and the room *you just entered*.

> "The crime was committed by **Mrs. Peacock** in the **library** with a **wrench**".

Both the suspect and the weapon are moved into the room you entered.

Then your opponents (starting by your left) must – if possible – prove that your suggestion is false by showing you, and **only you** one card that matches your suggestion. If one player hold more than one of the suggested cards they have to chose which card to show, they must show one but only one. 

If the player can't disprove, the next player must try it, until all players have passed.

You use this to mark as many boxes as you can to be certain who is and is not *guilty*.

If no one is able to prove your suggestion false, you may either end your turn or make an accusation.

Once your turn ends the suspect, when their turn happens, can chose to stay in that room or roll the dice. 

There is no limit to the number of weapons that a room holds, yet one room cannot hold more than two people (the one who made a suggestion and the suspect) -> change. 

· - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - ·

### Accusing

###### mecánica de juego :D
######      mecanica de "accusation"
######            se puede hacer en cualquier momento durante el juego
######            solo se puede hacer una vez durante todo el juego
######            una vez hecha se gana o se pierde el juego
######            mecánica de elegir sospechoso [ ] [X] [ ] [ ] [ ] [ ]
######            mecánica de elegir arma       [ ] [ ] [ ] [ ] [ ] [X]
######            mecánica de elegir cuarto     [ ] [ ] [ ] [X] [ ] [ ]
######            aparecera: 
######                  "I accuse **Mrs. Peacock** of committing the crime in the **library** with the **wrench**".
######            ... con las opciones elegidas por el usuario
######            después de hecha la "accusation" se abrirá el sobre
######                  si el sobre SÍ contiene las cartas que el usuario dijo, se gana el juego
######                  si el sobre NO contiene las cartas que el usuario dijo, se pierde el juego
######            2) mecánica del AI -> Roberto
######                  Roberto es capaz de llamar una "accusation"
######                  Roberto es capaz de asumir cuales cartas estan en el sobre
######                  Roberto es capaz de tratar de ganar
######                  Roberto es capaz de seguir las reglas de "accusation"

If you think you have solved the crime, you can end your turn at any time during the game by making an accusation and name your suspicions elements.

> "I accuse **Mrs. Peacock** of committing the crime in the **library** with the **wrench**".

Then, the contents of the envelope will be shown to you. If you are correct, Congratulations! You won! If not, you lose.

You are only able to make **one** accusation per game, so make sure you are *certain* that you are right. 

You need to be faster than the rest or they might find the killer sooner! 

· - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - · - ·


# Installation of needed libraries

## Raylib

> Raylib is a simple and easy-to-use library to enjoy videogames programming. Raylib is highly inspired by Borland BGI graphics lib and by XNA framework. Do you want to see all functions available in raylib? [Check cheatsheet](https://www.raylib.com/cheatsheet/cheatsheet.html)

> NOTE for ADVENTURERS: raylib is a programming library to enjoy videogames programming; no fancy interface, no visual helpers, no auto-debugging... just coding in the most pure spartan-programmers way. Are you ready to learn? Jump to [code examples!](http://www.raylib.com/examples.html)

> Raylib at https://www.raylib.com/

## libmpeg2

> http://bedroomcoders.co.uk/using-libmpeg2-with-raylib/

## ulfius

> https://github.com/babelouest/ulfius
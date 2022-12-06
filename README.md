# Wizard Chess 🪄♟️

### Descripción: 
Wizard Chess es un ajedrez en realidad virtual por control de voz cuyo objetivo principal es incentivar a personas que han tenido poco contacto con el ajedrez a jugarlo de una manera más entretenida. Para ello se creó un juego multijugador cooperativo en el cual el usuario puede comandar las fichas por medio de su voz en un escenario con un ambiente mágico.

![imagen](https://user-images.githubusercontent.com/53950535/205774857-7ce345ff-964d-4128-8205-65379b1c9b34.png)




> 📺 Ver Trailer: https://www.youtube.com/watch?v=2rnAn1-6BMY

---

## Prerrequisitos, descarga y ejecución:

A continuación, se describen los prerequisitos, las instrucciones y consideraciones adicionales para poder correr Wizard Chess en tu propia maquina.

### Prerrequisitos
Hardware:
- [x] Meta Quest 2
- [x] Un computador desde el cual se instalará el juego. Este debe tener minimo un procesador de +2.0GHz y 2GB de RAM.
- [x] Cable USB C compatible con el Meta Quest 2

Software:
- [x] Git Bash
- [x] Unity Hub (De preferencia 3.x.x)
- [x] Unity 2021.3.8f1 
- [x] Android SDK
- [x] Aplicación Oculus Escritorio
- [x] Aplicación Oculus Dispositivo Móvil 


### Instrucciones para configurar ambiente de trabajo: 

1. **Git Bash**: Para instalar Git bash, dirijase a la siguiente página https://git-scm.com/downloads y seleccione la versión correspondiente a su sistema operativo. Siga las instrucciones que se presentan en el instalador hasta terminar la instalación.

2. **Unity Hub**: Para instalar Unity, se debe dirigir a la página de Unity e instalar [Unity Hub](https://unity.com/download). Asegurese de elegir el archivo correspondiente a su sistema operativo.

3. **Unity 2021.3.8f1**: Una vez tenga instalado Unity Hub en su computador, dirijase a [esta pagina](https://unity.com/releases/editor/archive) y seleccione la version solicitada de unity, en este caso la 2021.3.8. Haga click en la opción de Unity Hub para instalar.
![imagen](https://user-images.githubusercontent.com/53950535/205778534-3322b416-9c5f-4c03-93f2-db4ac49ccf45.png)

4. **Android SDK**: Al seleccionar la opción de Unity Hub en el último paso, se abrirá su aplicación de Unity Hub con más detalles y opciones para instalar la versión solicitada de Unity. En esta pestaña, seleccione las opciones de *Android Build Support* como se muestra en la imagen de abajo y de click en continuar.
![imagen](https://user-images.githubusercontent.com/53950535/205779138-c3c68cf4-cb0a-4c8b-aeaa-e33dd536ce56.png)

5. **Oculus Escritorio**: Descargue e instale la aplicación de [Oculus para escritorio](https://www.meta.com/quest/setup/). Una vez iniciada la aplicación, verifique que la conexión entre su dispositivo Quest 2 y escritorio funcionan al conectar estos y verificar la sección de dispositivos. En esta se debería mostrar el dispositivo y el estado "conectado".

6. **Oculus Móvil**: Descargue e instale la aplicación de Oculus en su dispositivo móvil. 

**Una vez se sigan estos pasos de configuración, se puede seguir a descargar e importar el proyecto en Unity**

### Instrucciones para descargar e importar el proyecto de Wizard Chess en Unity:

1. Abra la carpeta donde desea ubicar el proyecto
2. Corra Git Bash desde esta carpeta, como se muestra a continuacion:
![imagen](https://user-images.githubusercontent.com/53950535/205787401-fb045dca-1d04-4396-af2c-c17719aeb05b.png)

3. Clone el proyecto en la carpeta deseada, ejecutando el siguiente comando desde la ventana que se abrió de Git Bash
```git
git clone https://github.com/necalero/WizardChess
```
4. Desde Unity Hub, seleccione la opción de abrir un nuevo proyecto y seleccione el directorio donde clonó el proyecto.
![imagen](https://user-images.githubusercontent.com/53950535/205788029-d310abf7-adf6-45e6-a950-a93717fb9a86.png)

### Instrucciones para ejecutar el proyecto de Wizard Chess desde Unity:



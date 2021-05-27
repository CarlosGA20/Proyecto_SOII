# Proyecto_SOII

Dentro del proyecto InfraredBasics-WPF el archivo que pertenece a la materia de Sistemas Operativos 2 es MainWindow.xaml.cs.

Dentro del proyecto ColorBasics-WPF el archivo que pertenece a la materia de Sistemas Operativos 2 es MainWindow.xaml.cs.

Dentro de la carpeta KinectTest/Assets/KinectScripts el script KinectManager.cs pertenece a la materia de Sistema Operativos 2

## Técnicas de transferencia de datos desde el Kinect


Para seleccionar con qué tipo de datos se desea trabajar dentro de los proyectos InfraredBasics-WPF y ColorBasics-WPF primero se debe habilitar la entrada de datos utilizando la instrucción: 

```this.sensor.ColorStream.Enable();```

Para indicar con qué formato de imagen se desea trabajar se utiliza el argumento `ColorImageFormat.InfraredResolution640x480Fps30` para trabajar con el sensor infrarrojo dentro del proyecto InfraredBasics-WPF o el argumento `ColorImageFormat.RgbResolution640x480Fps30` para manejar imágenes a color dentro del proyecto ColorBasics-WPF. La información recibida por medio del sensor infrarrojo o por medio del sensor de color es guardada dentro de un bitmap para poder ser mostrada en pantalla posteriormente.


Dentro del proyecto de Unity para poder mostrar el uso de ambos sensores, se tiene que inicializar la escena llamada Kinect Overlay. Si solo se desea el sensor de profundidad se tiene que utilizar la escena llamada Kinect Gestures. Las lineas especificas donde se miden el tiempo de obtencion de los mapas del Kinect son de la 1113 a la 1130. Dentro de esas lineas se mide el sensor de color y el sensor de profundidad.

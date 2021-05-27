# Proyecto_SOII

Dentro del proyecto InfraredBasics-WPF el archivo que pertenece a la materia de Sistemas Operativos es MainWindow.xaml.cs.

Dentro del proyecto ColorBasics-WPF el archivo que pertenece a la materia de Sistemas Operativos es MainWindow.xaml.cs.


## Técnicas de transferencia de datos desde el Kinect


Para seleccionar con qué tipo de datos se desea trabajar dentro de los proyectos InfraredBasics-WPF y ColorBasics-WPF primero se debe habilitar la entrada de datos utilizando la instrucción: 

```this.sensor.ColorStream.Enable();```

Para indicar con qué formato de imagen se desea trabajar se utiliza el argumento `ColorImageFormat.InfraredResolution640x480Fps30` para trabajar con el sensor infrarrojo dentro del proyecto InfraredBasics-WPF o el argumento `ColorImageFormat.RgbResolution640x480Fps30` para manejar imágenes a color dentro del proyecto ColorBasics-WPF. La información recibida por medio del sensor infrarrojo o por medio del sensor de color es guardada dentro de un bitmap para poder ser mostrada en pantalla posteriormente.

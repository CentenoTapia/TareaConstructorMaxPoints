# TareaConstructorMaxPoints

# Funcionalidades del Código
$Crear Vista de Tabla (TableView):$
- Método createTableView: Crea una vista de tabla con dos columnas: "Constructor Name" y "Total Points". Establece un tamaño y un estilo específico para la tabla.
  
$Cargar Datos Iniciales:$
- Método loadInitialData: Utiliza QueryRepository para obtener la lista de MaxPointConstructor y llena el ObservableList con estos datos.
  
$Inicializar la Interfaz Gráfica:$
- Método start: Configura la interfaz gráfica de la aplicación. Crea y configura un BorderPane, una VBox para la tabla y un HBox para la alineación de elementos. Establece la etiqueta superior y carga los datos iniciales al iniciar la aplicación.
  
$Método Principal (main):$
- Método main: Lanza la aplicación JavaFX.
  
# Detalles del Código

$Clase Principal (ConstructorMaxPoint):$
- Hereda de Application, lo que le permite utilizar las funcionalidades de JavaFX.
- Define un ObservableList<MaxPointConstructor> para mantener los datos que se mostrarán en la tabla.

$Interfaz Gráfica:$
- Utiliza BorderPane para estructurar la interfaz en secciones.
- Utiliza VBox para contener y organizar la tabla.
- Utiliza HBox para centrar los elementos en el panel central.

$Carga de Datos:$
- La clase QueryRepository se utiliza para recuperar los datos de los constructores y sus puntos máximos.
- Los datos se añaden al ObservableList que está enlazado a la TableView.

# Ejecución del código

![4](https://github.com/user-attachments/assets/b8ec714b-ef81-41a0-b7ed-4882e8aac91c)



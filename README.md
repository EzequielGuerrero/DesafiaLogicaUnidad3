# DesafiaLogicaUnidad3

Relación entre las distintas entidades del modelo:

1: Entre la Clase Persona y Empleado he establecido que hay una relación de herencia, ya que la clase empleado puede heredar todos los atributos y métodos de persona para conformarse.

2: Una vez creado el Empleado se le asocia con la clase Departamento haciendo al empleado parte de este último (Relación de composición).

3: Entre la clase Empleados y Categoría existe una relación de asociación. Ya que la categoría se utiliza para establecer su rango, empleo...

Funcionalidad de los métodos:

Clase Persona:

En esta clase Padre he creado los correspondientes Getters y Setters de cada atributo.
Con el fin de poder manipular los atributos de la clase.

Clase Empleados:

En esta clase tendremos todos los atributos y métodos de Persona al heredar de la misma, pero también hemos añadido las propiedades departamento y salario para establecer la información en cada empleado.
También he creado los métodos trabaja, para dar órdenes de trabajo al empleado, setVacaciones y getVacaciones para establecer los distintos días de vacaciones o poder consultarlos. Y el correspondiente setSalario, para establecer un sueldo o getSalario para poder ver el actual o por defecto.

Clase Departamentos:

A los departamentos se les asignan las propiedades nombreDepartamento y responsableDepartamento y se establecen los setters y getters respectivos, además se añaden los métodos verTodosEmpleados para consultar los integrantes del departamento en cuestión y generarInformes que pertenezcan al departamento correspondiente.
También tienen la opción de actualizar los datos de los empleados a través del método actualizarDatosEmpleados...

Clase Categoria:

La clase Categoria muestra una relación de asociación con la de Empleados, por lo que se le añade el atributo nombreCategoria y los correspondientes setters y getters.

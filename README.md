# proyecto-programacion
Sistema De Planilla Hospitalaria

Jimena Solorzano Cubillo | 119530673
Nathalie Garcia Montero | 119960435

Instrucciones Claras de Compilacion: 
En Zinjai, crear un proyecto de consola en C++ y agregar al proyecto todos los archivos .h y .cpp.
Verificar que el estándar de C++ sea C++11 o superior y finalmente compilar y ejecutar.
El programa lee y escribe empleados.txt, departamentos.txt y planilla.txt en la carpeta desde la que se ejecuta y si no existen se crean automáticamente al guardar.

Guia ejecutiva de uso:
Este proyecto es un sistema de planilla para un hospital el cual permite registrar empleados, administrar departamentos, agregar puestos y procesar los pagos de los trabajadores.
El programa fue creado para facilitar el manejo de la información de los empleados y llevar el control de los comprobantes de pago.

Al abrir el programa se muestra el siguiente menú:
1. Registrar empleado: Permite agregar un nuevo empleado al sistema.
2. Listar empleados: Muestra todos los empleados que están registrados.
3. Actualizar empleado: Permite modificar algunos datos de un empleado.
4. Eliminar empleado: Permite eliminar un empleado registrado, siempre que no tenga comprobantes de pago.
5. Registrar departamento: Permite agregar un nuevo departamento al hospital.
6. Agregar puesto a departamento: Permite agregar puestos y sus funciones a un departamento.
7. Listar departamentos: Muestra los departamentos y los puestos que tiene cada uno.
8. Procesar pago de empleado: Permite calcular el salario y generar un comprobante de pago.
9. Listar comprobantes de pago: Muestra los comprobantes que se han generado.
10. Buscar comprobante por número: Permite consultar un comprobante específico.
11. Salir: Guarda la información y cierra el programa.

Para registrar un empleado se debe elegir la opcion 1 que permite registrar tres tipos de empleados: Medico, Enfermero y Administrativo.
Para el Medico se solicitan datos como especialidad, años de experiencia y correo electrónico.
Para el Enfermero se solicita el área, turno y cantidad de pacientes asignados.
Para el Administrativo se solicita el puesto, si está activo y si es bilingüe.
Para los tres están estos datos generales: Código del empleado, Id, Nombre, Salario base mensual, Horas extra, Horas nocturnas, Horas de guardia. Es importante que cada empleado tenga un código diferente, ya que este se utiliza para buscarlo dentro del sistema.

Para agregar un departamento se debe seleccionar la opción 5.
Se solicita: Código del departamento, Nombre del departamento y Nombre del encargado.
Después de registrarlo se puede utilizar la opción 6 para agregar puestos al departamento.
Para agregar un puesto se debe ingresar el código del departamento, el nombre del puesto, indicar si está disponible y escribir sus funciones.

Para procesar un pago se debe seleccionar la opción 8 y estos son los pasos a seguir:
1. Ingresar el código del empleado al que se le realizará el pago.
2. Ingresar el código del departamento correspondiente.
3. Escribir la fecha del pago en formato día/mes/año.
4. El sistema realiza automáticamente el cálculo del salario.
5. Finalmente, muestra el comprobante de pago generado.
El comprobante incluye el salario bruto, las deducciones y el salario neto que recibirá el empleado

En la opción 9 se pueden visualizar todos los comprobantes registrados.
En la opción 10 se puede buscar un comprobante específico escribiendo su número.

La información del sistema se guarda en archivos de texto para que no se pierda al cerrar el programa (empleados.txt, departamentos.txt y planilla.txt)
Cuando se realizan cambios, el sistema guarda la información automáticamente. También la guarda antes de salir del programa.

Este sistema permite llevar un mejor control de los empleados, departamentos y pagos de un hospital.
Su uso es sencillo porque funciona con un menú donde el usuario selecciona la opción que necesita y ademas permite guardar la información para poder verla nuevamente cuando se vuelva a ejecutar el programa.


Para la creacion del Proyecto se utilizo la Inteligencia Artificial Claude como herramienta, estos fueron los siguientes prompts que se utilizaron:

"Quiero que revises mi proyecto de C++ y me ayudes a optimizar el Código. Quiero simplificar funciones que estén demasiado largas y aprovechar mejor las clases que ya estan creadas, tambien mantener la estructura actual del proyecto y no agregar clases innecesarias.
Explícame cada mejora paso a paso y utiliza ejemplos sencillos para que pueda entender cómo funciona."

"Estoy trabajando en un proyecto de C++ que consiste en un sistema de planilla para un hospital. El programa permite registrar empleados, departamentos y comprobantes de pago. Tengo una duda sobre cómo organizar mejor mi código. Estoy trabajando con varias clases y listas enlazadas, pero no sé cuál sería la mejor manera de guardar la información para que no se pierda cuando cierre el programa. Se que es con archivos de texto pero quiero evitar tener todo el código relacionado con guardar y cargar archivos dentro del main.cpp porque siento que se está haciendo muy largo y desordenado. Quiero que me propongas una solución utilizando lenguaje básico, explicándome qué archivos debería crear, qué debería llevar cada uno y cómo conectarlos con las clases que ya tengo.
Es importante que no cambies toda la estructura de mi proyecto, ya que quiero aprovechar lo que ya he realizado y entender cómo funciona cada modificación." 


"Tengo un problema en mi proyecto de C++ y necesito ayuda para solucionarlo, te voy a mandar el código donde aparece el problema y el mensaje de error. Quiero que primero me digas cuál es la causa del error y después me expliques cómo solucionarlo.
NO modifiques otras partes que ya funcionan bien y respeta las clases y estructuras que ya tengo ya hechas."

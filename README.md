# academico
Proyecto de gestión académica
Proyecto a realizar por alumnos de la carrera "Analista de Sistemas" de la Esc. Sup. de Comercio J.J. de Urquiza N° 49

CODIFICACIÓN DE ARCHIVOS FUENTE EN JAVA

Para escribir código en el lenguaje Java se usan convenciones que estan definidas como un estandar a la hora de fabricar programas:

Paquetes: los nombres de paquetes se escriben en minúsculas:
package conjunto_universal.subconjunto.clases;
package conjuntouniversal.subconjunto.*;
Clases: los nombres de clases deben ser escritos en letras minusculas, todas las palabras seguidas y la primera letra de cada palabra en mayuscula, esta forma de nomenclatura tambien es llamada lomo de camello o CamelCase en ingles:
public class Barcos;
class ContabilidadEmpresarial;
class RecursosHumanos;
Métodos: Los metodos deben ser verbos escritas con la palabra inicial en minuscula y las siguientes palabras con la inicial en Mayuscula:
balanceCuenta();
insertarBuque();
mostrarCuadricula();
listarContenedores();
insertarFactura();
borrarFactura();
Variables: Deben escribirse en mayusculas y minusculas, con la inicial en minuscula, con la siguiente palabra con la inicial en mayuscula. Casi no se usan los signos de subrayado (_) y evite el signo de dolar ($).
clienteActual;
contenedorNombre;
nombreEmpleado;
cargoEmpleado;
deptoEmpleado;
Constantes: Las constantes deben escribirse enteramente en mayusculas y separando las palabras mediante underscore (subrayado).
MAX_NUM_CONTENEDORES;
MAX_PESO_PANAMAXMAX;
MAX_NUDOS;
Estructuras de Control: cuando las sentencias forman parte de una estructura de control de flujo  como un for, while, es necesario incluirlas en un paquete de sentencias con los corchetes ({}) aunque solo tengan una linea de código:
for ( i=0; i<MAX_NUM_CONTENEDORES; i++){
sentencia;
sentencia;
}
Espacios: Los espacios son usados para entender mejor el código y distinguir el principio y el fin de las estructuras de control usese de acuerdo a la estructura de control las separaciones por sangria necesarias, por lo regular no son mas de 4. Puede variar de acuerdo a las convenciones usadas.
Comentarios: Use comentarios de una linea o varias, puede inclusive usar JAVADOC. No hay restricción de acuerdo a la forma en que deben estar escritos los comentarios.

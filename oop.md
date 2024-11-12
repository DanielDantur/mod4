# Programación Orientada a Objetos (OOP)

## Clases

Son estructuras que sirven como una plantilla para crear **objetos** al definir sus propiedades (atributos) y comportamientos (métodos).

### Atributos

Son variables definidas dentro una clase que representan el estado de un objeto.

Existen *atributos de clase* que tienen un valor definido aún sin instanciar un objeto y que es común a todos los objetos de esa clase.

### Métodos

Son funciones definidas dentro de una clase que decriben el *comportamiento* de un objeto.

Debido a que es posible definir *métodos de clase* (que pueden ser ejecutadas sin haber instanciado un objeto), los métodos de un objeto se les identifica como *métodos de instacia*.

#### Constructor



## Objetos

Son **instancias** de una clase. Los valores de sus atributos son su estado.

## Herencia

Permite crear una nueva clase a partir de una clase existente, heredando sus propiedades y comportamientos.

Esto permite agrupar código común entre clases en una clase *padre* o **superclase** para evitar la repetición de código, las inconsistencias que se puede crear por accidente y facilitar el mantenimiento del código.

A las clases que heredan de otra clases, se las llaman clases *hijas* o **subclases**

En las subclases se pueden sobreescribir los métodos heredados y definir métodos propios.

### Clases Abstractas

## Polimorfismo (y sobrecarga)

La capacidad de un objeto para tomar diferentes formas, dependiendo del contexto en el que se utilice.

En lenguajes fuertemente tipados (no en Python), se deben declarar los tipos de datos que reciben las funciones como parámetros; en caso de las clases, gracias a la herencia y al polimorfismo, si una función espera un parámetro de una clase, se puede utilizar una subclase de esa clase sin generar errores.

En Python, el polimorfismo se aplica en función a lo que se conoce como *duck typing*, por lo que con que las diferentes clases tengan los mismos métodos que se quieren llamar es suficiente para que el código no falle.

##### Duck typing (tipado de pato)
>"Si camina como pato y grazna como pato, entonces es un pato."

## Encapsulación

Oculta los detalles internos de un objeto y solo expone los métodos necesarios para interactuar con él.

En algunos lenguajes (no en Python) se puede definir la *accesibilidad* de los atributos y métodos de las clases. Estos niveles de accesibilidad suelen ser:

- Privado: Sólo son accesibles dentro de la propia clase.
- Protegido: Son accesibles por la propia clase y clases derivadas.
- Público: Son accesibles fuera de la clase.

En Python se puede simular ese comportamiento agregando dos guiones bajos al principio de los nombres de clases y métodos que se quieran hacer privados.

## Abstracción

Presenta una visión simplificada de un objeto, enfocándose en sus características esenciales.

## Acoplamiento y encapsulación

## Interfaces (Clases abstractas)

# UML

## Diagrama de clases

## Diagrama de casos de uso

## Diagrama de secuencia

## Diagrama de Máquina de Estados

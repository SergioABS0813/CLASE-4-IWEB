# CLASE-4-IWEB

## Diagrama de clases

Cuando dan un diagrama así los (-) significan private y los (+) public

![iweb](https://github.com/SergioABS0813/CLASE-4-IWEB/assets/134556600/2d256364-6a68-4762-8788-6d174739ad84)

## Herencia

![a](https://github.com/SergioABS0813/CLASE-4-IWEB/assets/134556600/d1c10c6a-7fd0-4726-89c5-5ed398b65c0a)

## Palabra EXTENDS

![b](https://github.com/SergioABS0813/CLASE-4-IWEB/assets/134556600/5efccee1-33eb-4496-a825-952e4f600b63)

Ejemplo de designar a una clase para que herede de otra clase:

![a](https://github.com/SergioABS0813/CLASE-4-IWEB/assets/134556600/c4f1ad74-ac58-4689-9b4d-202b26eac4e3)

## Relación clase hijo y padre

Las clases hijos (herederos de alguna clase padre), heredan ATRIBUTOS y MÉTODOS del padre cuyo modificador sea PUBLIC o PROTECTED. NO HEREDA atributos ni métodos privados
pero si se pueden utilizar en la práctica.

## Clase OBJECT (Padre de todas las clases)

![ob](https://github.com/SergioABS0813/CLASE-4-IWEB/assets/134556600/ed4b4b2a-8ba7-4220-bb8c-85bf0ba54dd7)

## Atributos del padre e hijo
Los atributos que se hereden son privados siempre, por lo que teóricamente no podría heredarlos, pero sí se puede MEDIANTE GETTERS Y SETTERS ya que son PUBLIC :D

## Palabra "super" en CONSTRUCTOR
Invoca al constructor de la clase padre.

![as](https://github.com/SergioABS0813/CLASE-4-IWEB/assets/134556600/562439f5-8ea4-4bc0-a6b8-c180b1c8057c)

## Palabra "super" en MÉTODOS
Puede ser usado en cualquier lado de clase hijo.
En Java no se puede hacer super.super.... (como para llegar a un método de clase abuelo).

![xs](https://github.com/SergioABS0813/CLASE-4-IWEB/assets/134556600/447139f7-7546-4c39-9483-69685bbf6b31)

## Sobreescritura de MÉTODOS
Es cuando un clase padre y un clase hijo repiten el nombre del MÉTODO, entonces si instanciamos en la clase hijo, el método será del hijo y no del padre.

PONER IMAGEEEEEN

## Modificadores de acceso en SOBREESCRITURA DE MÉTODOS

Si en clase Padre se tiene un método con modificador protected, en clase hijo el método puede tener modificador public pero no private porque tiene menor visibilidad que protected.

![aaa](https://github.com/SergioABS0813/CLASE-4-IWEB/assets/134556600/724c7474-67f9-4521-b610-bc2eaa19315e)

## Polimorfismo


## Instance of
Sirve para poder diferenciar entre una larga lista de clases hijos cuando esta lista fue creada con el tipo de dato de la clase del Padre.

![instance](https://github.com/SergioABS0813/CLASE-4-IWEB/assets/134556600/950e33a0-efa8-463a-9755-589c23942cbf)

## Remove o add (AÑADIR O ELIMINAR ELEMENTOS DE UNA LISTA)
Lo mismo que remove y add



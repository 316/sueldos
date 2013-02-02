Sistema de liquidacion de sueldos y jornales
========================================

Este es un sistema de gestion de sueldos y jornales, el mismo cuenta con:

* Gestion de sueldos

  * Por mes
  * Por jornal

* Libro de sueldos

  * Por mes
  * Por jornal

Es multiempresa, por cual permite administrar varias empresas en simultaneo.


Gestiones a empleados:
----------------------

* Altas y bajas
* Liquidacion de sueldos
* Detalle de aportes y contribuciones
* Liquidacion de vacaciones (VAC)
* Liquidacion de Sueldo Anual Complementario (SAC)


Gestion de empleadores
----------------------

* Datos del empleador
* Adhesion a gremios
* Categorias para empleados
* Registro de empleados
* Liquidacion de aportes

IMPLEMENTADO
------------

* Las constantes estan declaradas en 00.py
* Las clases personalizadas (tipos y validadores), se encuentran en 01.py
* Declaradas constantes basicas:
  * Tipo de documento
  * Estado Civil
  * Provincias
  * Sexo
* Clase validadora de CUIL/CUIT implementada
* ABM para empleadores
* ABM Empleados (mejorar el estilo y agregar controles)
* Categorias
* Convenios
* Escalas salariales


Todo
----

* ABM para administrar el sistema
* Gestion de empleados
* Mejorar el estilo
* agregar botones en formularios y tablas
* Confeccion de recibo de sueldo
* Libro de sueldos



INSTALACION
-----------

Desarrollado con Web2py_ 2.4, para instalar clonar el repositorio o copiar la carpeta sueldos una vez clonada en web2py/applications et voilá!

.. _Web2py: http://www.web2py.com

USO
---

Usese cuidadosamente, no beba mientras lo hace


Licencia
--------

Este software esta liberado bajo licencia GPL V3 o posteriores, salvo los plugins de terceros como:

- Multi select
- Lazy table
- Twitter bootstrap

y algun otro que use que ire agregando. 

Web2py no se distribuye como parte de este software, aunque dada su caracteristuca de retrocompatibilidad, cualquier version posterior a la 2.4 deberia funcionar.

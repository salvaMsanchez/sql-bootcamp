<a name="top"></a>

<h1 align="center">
  <strong><span>Bootcamp Desarrollo de Apps Móviles</span></strong>
</h1>

---

<p align="center">
  <strong><span style="font-size:20px;">Módulo: Modelado de datos e introducción a SQL</span></strong>
</p>

---

<p align="center">
  <strong>Autor:</strong> Salva Moreno Sánchez
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/salvador-moreno-sanchez/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
</p>

## Índice

* [Contenidos dados en el módulo](#contenidos)
	* [Primera sesión](#primeraSesion)
	* [Segunda sesión](#segundaSesion)
	* [Tercera sesión](#terceraSesion) 
* [Herramientas](#herramientas)
* [Práctica: modelado y SQL](#practica)
	* [Descripción](#descripcion)
	* [Diagrama Entidad-Relación](#diagrama)
	* [Ejemplificaciones del *script* `gestionFlota.sql`](#ejemplos)
	* [Problemas, decisiones y resolución](#problemas)
		* [Planificación y ejecución del diagrama Entidad-Relación](#planificacion) 
* [Complementación de los conceptos vistos](#complemento)

<a name="contenidos"></a>
## Contenidos dados en el módulo

<a name="primeraSesion"></a>
### Primera sesión

* **Modelo Entidad-Relación**
	* Entidades
	* Atributos y tipos de datos
	* ¿Qué es una relación?
		* Relaciones entre entidades
		* Cardinalidad  
* **Normalización**
	* Primera, Segunda y Tercera Forma Normal
	* Desnormalización 

<a name="segundaSesion"></a>
### Segunda sesión

* **DDL (*Data Definition Language*)**
	* Creación de tablas
	* Modificación de tablas
	* Creación de relaciones e índices
* **DML (*Data Manipulation Language*)**
	* Extracción de datos con *Select*
	* Inserción de registros con *Insert* 
	* Actualización de registros con *Update*

<a name="terceraSesion"></a>
### Tercera sesión

* **DML (*Data Manipulation Language*)**
	* Consultas avanzadas haciendo uniones de tablas 
* **Ejercicio práctico:**
	*  Cargar un *set* de datos desnormalizado en Excel en una base de datos normalizada haciendo uso de consultas avanzadas

<a name="herramientas"></a>
## Herramientas

<p align="center">

<a href="https://www.swift.org/documentation/">
    <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgresSQL">
  </a>
  
  <a href="https://developer.apple.com/documentation/xcode">
    <img src="https://img.shields.io/badge/DBeaver-white?style=for-the-badge&logo=data:image/png;base64,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" alt="DBeaver">
  </a>
  
</p>

<a name="practica"></a>
## Práctica: modelado y SQL

<a name="descripcion"></a>
### Descripción

La práctica que nos ocupa en este módulo del *bootcamp* trata de dar solución a la gestión de la flota de vehículos de una empresa, la cual nos pasaría su almacén de datos en formato Excel para construir una **base de datos**.

De esta forma, y atendiendo al tipo de datos que poseemos, debemos adentrarnos en el importante proceso de planificación y conformación del **diagrama Entidad-Relación** para, luego, plasmar todo ello a través del sistema de gestión de bases de datos relacional **PostgreSQL**, en el que tendremos un *script* con los comandos DDL (*Data Definition Language*) para la creación del modelo diseñado, así como los comandos DML (*Data Manipulation Language*) para cargar las tablas.

Dicho *script* (llamado `gestionFlota.sql` en el repositorio) es totalmente autónomo, es decir, al ejecutarlo crea todo lo necesario (tablas, *primary keys*, *foreign keys*, relaciones, atributos, mapeo de los datos desde el modelo no normalizado del cliente al nuestro, etc.).

<a name="diagrama"></a>
### Diagrama Entidad-Relación

Aquí se muestra el diagrama Entidad-Relación realizado para nuestro caso, el cual refleja la representación del modelo de datos normalizado que emplearemos y llevaremos a código para la construcción de nuestra base de datos.

![Diagrama Entidad-Relación](images/diagrama_entidadRelacion.png)

En él, podemos observar las distintas entidades definidas por sus atributos y relaciones, atendiendo a la correspondencia de cardinalidad adecuada.

**Nota:** en este repositorio se encuentra dicho diagrama para poder descargarlo (`diagrama_entidadRelacion.drawio` / `diagrama_entidadRelacion.xml`) y visualizarlo en [draw.io](https://app.diagrams.net), herramienta empleada para la representación del mismo.

<a name="ejemplos"></a>
### Ejemplificaciones del *script* `gestionFlota.sql`

#### Creación de la tabla `coche`

~~~sql
CREATE TABLE gestionFlota.coche (
	matricula VARCHAR(10) primary key not null,
  	modelo VARCHAR(50) not null references gestionFlota.modelo(nombre),
  	id_color INT not null references gestionFlota.color(id),
  	kilometros_totales INT not null,
  	id_compania_aseguradora INT not null references gestionFlota.companiaAseguradora(id),
  	numero_poliza VARCHAR(50) not null,
  	fecha_compra DATE not null
);
~~~

#### Carga de datos en la tabla `coche` desde el modelo no normalizado dado por cliente

~~~sql
INSERT INTO gestionFlota.coche (matricula, modelo, id_color, kilometros_totales, id_compania_aseguradora, numero_poliza, fecha_compra)
SELECT matricula, gestionFlota.modelo.nombre, gestionFlota.color.id, kms_totales, gestionFlota.companiaAseguradora.id, n_poliza, fecha_compra 
FROM gestionFlota.coches
INNER JOIN gestionFlota.color
ON gestionFlota.coches.color = gestionFlota.color.nombre
INNER JOIN gestionFlota.modelo
ON gestionFlota.coches.modelo = gestionFlota.modelo.nombre
INNER JOIN gestionFlota.companiaAseguradora
ON gestionFlota.coches.aseguradora = gestionFlota.companiaAseguradora.nombre;
~~~

#### *Query* final para comprobar nuestro modelo de datos normalizado

Se nos reclama extraer el listado de coches que hay mostrando lo siguiente:

* Modelo, marca y grupo empresarial.
* Fecha de compra.
* Matrícula.
* Nombre del color del coche.
* Kilómetros totales.
* Nombre de la empresa que está asegurando el coche.
* Número de poliza.

~~~sql
SELECT 
modelo, 
gestionFlota.marca.nombre AS marca, gestionFlota.grupoEmpresarial.nombre AS grupo_empresarial, 
fecha_compra, 
matricula,
gestionFlota.color.nombre AS color,
kilometros_totales,
gestionFlota.companiaAseguradora.nombre AS compania_aseguradora,
numero_poliza
FROM gestionFlota.coche
INNER JOIN gestionFlota.color
ON gestionFlota.coche.id_color = gestionFlota.color.id
INNER JOIN gestionFlota.modelo
ON gestionFlota.coche.modelo = gestionFlota.modelo.nombre
INNER JOIN gestionFlota.marca
ON gestionFlota.modelo.id_marca = gestionFlota.marca.id
INNER JOIN gestionFlota.grupoEmpresarial
ON gestionFlota.marca.id_grupo_empresarial = gestionFlota.grupoEmpresarial.id
INNER JOIN gestionFlota.companiaAseguradora
ON gestionFlota.coche.id_compania_aseguradora = gestionFlota.companiaAseguradora.id;
~~~

<a name="problemas"></a>
### Problemas, decisiones y resolución

<a name="planificacion"></a>
#### Planificación y ejecución del diagrama Entidad-Relación

Considero vital la parte de planificación, ya sea para la arquitectura de *software* o, en este caso, para la construcción de una base de datos; la cual tiene su resultado a través de la representación del diagrama Entidad-Relación y que, una vez realizado y contrastado, nos va a facilitar el trabajo en gran medida para luego llevarlo a código.

No he tenido grandes problemas que no me hayan permitido avanzar; sin embargo, puedo destacar que, una vez que tenía casi hecha la base de datos, me percaté de que podía seguir normalizando mi modelo y crear otra entidad. Me ocurrió con el atributo `color` en la entidad `coche`, el cual lo pude abstraer en otra entidad y tenerlo como *foreign key* en `coche`. 

Reflexionando sobre ello, y aunque es un caso simple que tuve que resolver desde un principio en la fase de planificación y normalización del modelo, lo achaco a que no se ha contrastado el diagrama con la visión de otras personas o bajo una batería de pruebas que ayudarían a cerciorarnos de cuán normalizado está nuestro modelo. Lo que significa, para mí, un aprendizaje resultante del trabajo de esta práctica.

<a name="complemento"></a>
## Complementación de los conceptos vistos

Las clases impartidas en este módulo las he querido complementar con el visionado de un curso ofrecido por la plataforma educativa [freeCodeCamp](https://www.freecodecamp.org) llamado [Learn PostgreSQL Tutorial - Full Course for Beginners](https://www.youtube.com/watch?v=qw--VYLpxG4) de 4 horas de duración en el que he podido profundizar en conceptos vistos en el módulo del Bootcamp y, además, aprender nueva sintaxis y a usar PostgreSQL a través de la consola, lo cual me ha permitido abstraer dicha tecnología de la interfaz de usuario de DBeaver.

---

[Subir ⬆️](#top)

# InventarioPro - Sistema de Gestión de Inventario y Ventas

Proyecto integrador propuesto para el curso **Programación Orientada a Objetos**.

## Descripción general

InventarioPro es un sistema académico orientado a la gestión de productos, clientes y ventas.  
Su finalidad es servir como proyecto integrador del curso para que el estudiante construya, de forma progresiva, una solución real aplicando:

- clases y objetos
- atributos, constructores y métodos
- estructuras de control
- clases nativas `Math` y `String`
- colecciones (`ArrayList`, `HashSet`, `Collections`, genéricos)
- herencia
- encapsulamiento
- polimorfismo
- persistencia de datos con JDBC o JPA
- interfaz web básica con JSP y Apache Tomcat

## Objetivo del proyecto

Desarrollar un sistema web básico de inventario y ventas que permita registrar productos, administrar clientes, generar ventas y persistir información, alineando cada avance del sistema con los temas del sílabo.

## Estructura sugerida del proyecto

```text
InventarioPro/
├── README.md
├── .gitignore
├── docs/
│   ├── 01-alcance-del-proyecto.md
│   ├── 02-problematica-y-solucion.md
│   ├── 03-historias-de-usuario.md
│   ├── 04-estructura-tecnica-del-proyecto.md
│
├── prototipo/
│   ├── README.md
│   ├── dashboard.html
│   ├── productos.html
│   ├── clientes.html
│   ├── ventas.html
│   ├── reportes.html
│   ├── css/
│   │   ├── variables.css
│   │   ├── style.css
│   │   ├── layout.css
│   │   ├── components.css
│   │   ├── forms.css
│   │   ├── tables.css
│   │   └── responsive.css
│
├── sandbox/
│   ├── README.md
│   ├── sesion-01-clases-objetos/
│   │   ├── Main.java
│   │   ├── Producto.java
│   │   └── notas.md
│   ├── sesion-02-atributos-constructores-metodos/
│   ├── sesion-03-modelado-caso-real/
│   ├── sesion-04-estructuras-de-control/
│   ├── sesion-05-jsp-tomcat/
│   ├── sesion-06-math/
│   ├── sesion-07-string/
│   ├── sesion-08-colecciones/
│   ├── sesion-09-arraylist-collections/
│   ├── sesion-10-busquedas-ordenamientos/
│   ├── sesion-11-coleccion-de-objetos/
│   ├── sesion-12-genericos/
│   ├── sesion-13-herencia-interfaces/
│   ├── sesion-14-encapsulamiento-polimorfismo/
│   └── sesion-15-jdbc-jpa/
│
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/
│   │       │   └── com/
│   │       │       └── inventariopro/
│   │       │           ├── model/
│   │       │           ├── dao/
│   │       │           ├── service/
│   │       │           ├── controller/
│   │       │           └── util/
│   │       ├── resources/
│   │       │   └── db.properties
│   │       └── webapp/
│   │           ├── WEB-INF/
│   │           ├── index.jsp
│   │           ├── views/
│   │           │   ├── login.jsp
│   │           │   ├── dashboard.jsp
│   │           │   ├── productos.jsp
│   │           │   ├── clientes.jsp
│   │           │   ├── ventas.jsp
│   │           │   └── reportes.jsp
│   │           ├── css/
│   │           └── assets/
│   └── pom.xml
│
└── sql/
    ├── schema.sql
    ├── data.sql
    └── queries-pruebas.sql
```

## Módulos funcionales

- Gestión de productos
- Gestión de clientes
- Registro de ventas
- Consulta básica de reportes
- Persistencia de datos

## Entregables por etapas

- **Etapa 1:** clases, objetos, atributos, constructores y métodos
- **Etapa 2:** validaciones y lógica con estructuras de control
- **Etapa 3:** interfaz web inicial con JSP/Tomcat
- **Etapa 4:** uso de `Math`, `String` y colecciones
- **Etapa 5:** herencia, encapsulamiento y polimorfismo
- **Etapa 6:** conexión a base de datos con JDBC/JPA

## Documentos incluidos

- [Alcance del proyecto](docs/01-alcance-del-proyecto.md)
- [Problemática y solución](docs/02-problematica-y-solucion.md)
- [Historias de usuario](docs/03-historias-de-usuario.md)
- [Estructura técnica del proyecto](docs/04-estructura-tecnica-del-proyecto.md)

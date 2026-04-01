# Apuntes-Unidad-2

## Introduccion 
Los componentes y las librerías representan elementos fundamentales dentro del desarrollo de software moderno, ya que permiten estructurar aplicaciones de manera modular, organizada y eficiente. A medida que los sistemas informáticos se vuelven más complejos, surge la necesidad de dividir el software en partes más pequeñas y manejables, conocidas como componentes, los cuales encapsulan funcionalidades específicas y pueden ser reutilizados en diferentes contextos.

Por otro lado, las librerías o paquetes proporcionan un conjunto de herramientas previamente desarrolladas que facilitan la implementación de soluciones a problemas comunes, evitando que los programadores tengan que desarrollar desde cero cada funcionalidad. Estas librerías pueden ser proporcionadas por el propio lenguaje de programación o desarrolladas por terceros, lo que amplía considerablemente las capacidades del desarrollador.

Además, la creación de componentes y librerías definidas por el usuario permite adaptar el software a necesidades específicas, promoviendo la reutilización del código, la reducción de errores y una mejor organización del sistema. Esta práctica es esencial en el desarrollo de aplicaciones escalables y mantenibles, ya que facilita la actualización y mejora continua del software.

En este contexto, el presente documento tiene como objetivo analizar los conceptos, características y aplicaciones de los componentes y las librerías, así como su importancia en el desarrollo de software, proporcionando una base teórica sólida para su comprensión y uso adecuado.

# Componentes y Librerías en Programación

Este repositorio presenta una recopilación teórica sobre los conceptos fundamentales de los componentes y las librerías en el desarrollo de software. Se abordan definiciones, características, tipos, así como su importancia en la construcción de aplicaciones modernas.

El contenido está orientado a comprender cómo estos elementos permiten estructurar, reutilizar y optimizar el código, facilitando el desarrollo de sistemas más eficientes y escalables.

---

## Contenido

- 2.1 Definición conceptual de componentes y paquetes/librerías  
- 2.2 Uso de librerías proporcionadas por el lenguaje  
- 2.3 Creación de componentes definidos por el usuario  
- 2.4 Creación y uso de paquetes/librerías definidas por el usuario  

---

## 2.1 DEFINICIÓN CONCEPTUAL DE COMPONENTES, PAQUETES / LIBRERÍAS

## ¿QUÉ SON LOS COMPONENTES?

En programación, un componente es una pieza de software reutilizable que realiza una función específica y que puede integrarse dentro de programas más grandes sin necesidad de conocer su código interno. Los componentes actúan como "bloques de construcción" que encapsulan funcionalidad y datos, permitiendo que sean usados por otros programas o sistemas a través de interfaces bien definidas. Pueden ser visuales (como botones, ventanas o menús) o no visuales (como conexiones a bases de datos, gestores de archivos o cálculos matemáticos). Su principal ventaja es que facilitan el desarrollo, permiten ahorrar tiempo y hacen que el código sea más organizado y fácil de mantener.

--
## ¿QUÉ SON LAS LIBRERÍAS O BIBLIOTECAS?

Una librería (o biblioteca) es un conjunto de código preescrito, funciones, clases y recursos que ofrecen funcionalidades específicas para ser utilizadas en otros programas. En lugar de escribir todo desde cero, los programadores pueden usar librerías para aprovechar trabajo ya realizado, optimizando el desarrollo y reduciendo errores. Las librerías suelen estar organizadas por temas: manejo de imágenes, conexiones de red, matemáticas, interfaces gráficas, etc.

--
## ¿QUÉ SON LOS PAQUETES?

Un paquete es una forma de organizar y agrupar varias clases, interfaces o librerías relacionadas dentro de una misma estructura, generalmente con el fin de evitar conflictos de nombres y mantener el código ordenado. En muchos lenguajes, los paquetes corresponden a directorios o carpetas en el sistema de archivos donde se almacenan los archivos de código relacionados. Ayudan a modularizar el proyecto y facilitan su gestión y distribución.

--
## DIFERENCIAS Y RELACIONES
- Componente: Es la unidad funcional que se usa directamente.
- Librería: Es el conjunto de componentes o funciones agrupadas.
- Paquete: Es la forma de organizar y agrupar lógicamente las librerías o clases.

Juntos forman el ecosistema que permite el desarrollo modular y reutilizable de software.

--

## 2.2 USO DE LIBRERÍAS PROPORCIONADAS POR EL LENGUAJEz
--
## VENTAJAS
- No requieren instalación externa.
- Están probadas y optimizadas por los creadores del lenguaje.
- Garantizan compatibilidad y estabilidad.
- Cubren necesidades comunes: manejo de archivos, entrada/salida, matemáticas, fechas, cadenas de texto, estructuras de datos, etc.

--
## EJEMPLO DE USO

Por ejemplo, en Python:
- `import math` para funciones matemáticas.
- `import os` para manejo de archivos y carpetas.
- `import datetime` para trabajar con fechas y horas.

En Java:
- `import java.util.ArrayList` para usar listas dinámicas.
- `import java.io.File` para manejo de archivos.

El uso consiste simplemente en importar la librería o clase necesaria al inicio del programa y luego llamar a sus funciones o métodos cuando se requieran.

--

## 2.3 CREACIÓN DE COMPONENTES (VISUALES Y NO VISUALES) DEFINIDOS POR EL USUARIO

## COMPONENTES VISUALES
Son aquellos que tienen representación en la interfaz gráfica y con los que el usuario puede interactuar directamente. Al crear componentes visuales personalizados, se define su apariencia (colores, formas, tamaño) y su comportamiento (qué hacen al hacer clic, al pasar el mouse, etc.).
Ejemplos: botones personalizados, gráficos, tablas, campos de texto con validación, etc.

--
## COMPONENTES NO VISUALES
Son aquellos que no tienen interfaz gráfica pero realizan tareas importantes en segundo plano. Su creación se centra en la lógica y funcionalidad.
Ejemplos: gestores de base de datos, servicios de red, validadores de datos, generadores de reportes, etc.

--
## CÓMO SE CREAN
Generalmente se crean mediante la definición de clases en programación orientada a objetos. Se encapsulan atributos y métodos, y se exponen solo aquellos que deben ser accesibles para otros partes del programa.
- Para visuales: Se heredan de clases base de interfaces gráficas y se sobrescriben métodos de dibujo o eventos.
- Para no visuales: Se crean clases con la lógica necesaria y métodos públicos para interactuar con ellas.

--

## 2.4 CREACIÓN Y USO DE PAQUETES / LIBRERÍAS DEFINIDAS POR EL USUARIO

## CREACIÓN DE PROPIAS LIBRERÍAS
Cuando desarrollamos funciones, clases o componentes que pueden ser útiles en más de un proyecto, podemos agruparlos y organizarlos como una librería propia. Esto permite reutilizar el código fácilmente y compartirlo con otros desarrolladores.
Pasos generales:
1. Escribir el código con las funcionalidades deseadas.
2. Organizarlo en archivos y carpetas de forma lógica.
3. Documentar su uso.
4. Empaquetarlo si es necesario para su distribución.

--
## CREACIÓN DE PAQUETES
En muchos lenguajes, crear un paquete es tan sencillo como crear una carpeta y colocar dentro los archivos de código fuente, agregando al inicio de cada archivo una declaración que indique a qué paquete pertenece.
Ejemplo en Java:

`package mi_paquete.utilidades;`

Ejemplo en Python: Se usa la presencia de un archivo `__init__.py` para indicar que una carpeta es un paquete.

--
## CÓMO SE USAN
Una vez creados, se utilizan igual que las librerías del lenguaje: mediante sentencias de importación.
`import mi_libreria`
`from mi_paquete import mi_clase`

--
## EJEMPLOS DE CÓDIGO VISTOS EN CLASES

### Ejemplo de codigo de catalogo de tienda tecnologica 

### Ejemplo de graficas grid 
<img width="1285" height="707" alt="image" src="https://github.com/user-attachments/assets/a66502d0-1b45-48f3-b7f0-602cba98193e" />
<img width="1273" height="701" alt="image" src="https://github.com/user-attachments/assets/a344e974-4df5-473b-b21f-aedc05cfa90b" />

### codigo 
    import flet as ft
    import matplotlib.pyplot as plt
    import numpy as np
    from io import BytesIO
    import base64


    def crear_grafica(fig):
    buffer = BytesIO()
    fig.savefig(buffer, format="png")
    buffer.seek(0)
    img_base64 = base64.b64encode(buffer.read()).decode("utf-8")
    plt.close(fig)
    return img_base64


    def grafica_linea():
    x = np.linspace(0, 10, 50)
    y = np.sin(x)

    fig, ax = plt.subplots()
    ax.plot(x, y)
    ax.set_title("Gráfica de Línea")

    return crear_grafica(fig)


    def grafica_barras():
    valores = [10, 20, 15, 30]

    fig, ax = plt.subplots()
    ax.bar(["A", "B", "C", "D"], valores)
    ax.set_title("Gráfica de Barras")

    return crear_grafica(fig)


    def grafica_pie():
    datos = [30, 40, 20, 10]

    fig, ax = plt.subplots()
    ax.pie(datos, labels=["A", "B", "C", "D"], autopct="%1.1f%%")
    ax.set_title("Gráfica de Pastel")

    return crear_grafica(fig)


    def grafica_dispersion():
    x = np.random.rand(50)
    y = np.random.rand(50)

    fig, ax = plt.subplots()
    ax.scatter(x, y)
    ax.set_title("Gráficas")

    return crear_grafica(fig)


    def main(page: ft.Page):

    page.title = "Dashboard de Gráficas"
    page.scroll = "auto"
    page.bgcolor="#FFD1DC"

    img_linea = ft.Image(src="data:image/png;base64," + grafica_linea())
    img_barras = ft.Image(src="data:image/png;base64," + grafica_barras())
    img_dispersion = ft.Image(src="data:image/png;base64," + grafica_dispersion())
    img_pie = ft.Image(src="data:image/png;base64," + grafica_pie())

    grid = ft.GridView(
        expand=True,
        runs_count=2,
        spacing=10,
        run_spacing=10,
        controls=[
            img_linea,
            img_barras,
            img_dispersion,
            img_pie,
        ],
    )

    page.add(grid)


    ft.app(target=main)
### Ejemplo de componentes (class y dataclass) 
### Class

<img width="1272" height="644" alt="image" src="https://github.com/user-attachments/assets/a41f7ffb-e751-47a9-a7f4-c36155c3dd34" />
### codigo 
    import flet as ft

    # Definición del componente personalizado
    class TargetPerfil(ft.Container):

    def __init__(self, nombre, rol, color_borde=ft.Colors.GREEN):
        super().__init__()

        self.nombre = nombre
        self.rol = rol

        self.content = ft.Column(
            controls=[
                ft.Text(nombre, weight=ft.FontWeight.BOLD, size=20),
                ft.Text(rol, italic=True),
                ft.ElevatedButton("Ver perfil", on_click=self.saludar)
            ],
            tight=True
        )

        self.border = ft.border.all(2, color_borde)
        self.padding = 10
        self.border_radius = 10
        self.width = 200

    def saludar(self, e):
        print(f"Interactuando con el componente de {self.nombre}")

    def main(page: ft.Page):
    page.title = "Unidad 2: Componentes Definidos por el Usuario"
    page.horizontal_alignment = ft.CrossAxisAlignment.CENTER

    usuario1 = TargetPerfil("Ana Garcia", "Desarrolladora Senior", ft.Colors.PINK)
    usuario2 = TargetPerfil("Carlos Ruiz", "Arquitecto de Software")

    page.add(
        ft.Text("Lista de Usuarios", size=30, weight=ft.FontWeight.BOLD),
        ft.Row([usuario1, usuario2], alignment=ft.MainAxisAlignment.CENTER)
    )


    ft.app(target=main)

### DataClass 

<img width="1272" height="644" alt="image" src="https://github.com/user-attachments/assets/620ddfe9-4f31-455d-83de-ec1bf8e2e6b0" />
### codigo
    import flet as ft
    from dataclasses import dataclass

    @dataclass
    class TargetPerfil:
    nombre: str
    rol: str
    color_borde: str = ft.Colors.BLUE

    def construir(self):
        return ft.Container(
            content=ft.Column(
                controls=[
                    ft.Text(self.nombre, weight=ft.FontWeight.BOLD, size=20),
                    ft.Text(self.rol, italic=True),
                    ft.ElevatedButton("Ver perfil", on_click=self.saludar)
                ],
                tight=True
            ),
            border=ft.border.all(2, self.color_borde),
            padding=10,
            border_radius=10,
            width=200
        )

    def saludar(self, e):
        print(f"Interactuando con el componente de {self.nombre}")


    def main(page: ft.Page):
    page.title = "Unidad 2: Componentes Definidos por el Usuario"
    page.horizontal_alignment = ft.CrossAxisAlignment.CENTER
    page.bgcolor = ft.Colors.PINK_100

    usuario1 = TargetPerfil("Ana Garcia", "Desarrolladora Senior", ft.Colors.GREEN)
    usuario2 = TargetPerfil("Carlos Ruiz", "Arquitecto de Software")

    page.add(
        ft.Text("Lista de Usuarios", size=30, weight="bold"),
        ft.Row(
            [usuario1.construir(), usuario2.construir()],
            alignment=ft.MainAxisAlignment.CENTER
        )
    )

    ft.app(target=main)
    
### Ejemplo de juego (piedra papel o tijera)
<img width="1258" height="697" alt="image" src="https://github.com/user-attachments/assets/b38feb2b-4fcb-4d47-a76c-0bf4a7112e5a" />

## BIBLIOGRAFÍA 
- Sommerville, I. (2011). Ingeniería del software. Pearson Educación.
- Deitel, P., & Deitel, H. (2017). Java: Cómo programar. Pearson Educación.
- Van Rossum, G., & Drake, F. L. (2018). The Python Tutorial. Python Software Foundation.
- Gamma, E., Helm, R., Johnson, R., & Vlissides, J. (1995). Design Patterns: Elements of Reusable Object-Oriented Software. Addison-Wesley.
- Pressman, R. S. (2010). Ingeniería del software: Un enfoque práctico. McGraw-Hill.


## Conclusion
En conclusión, los componentes y las librerías constituyen pilares fundamentales en la construcción de software eficiente y de calidad. Su uso permite dividir aplicaciones complejas en unidades más pequeñas y manejables, facilitando su desarrollo, comprensión y mantenimiento. La modularidad que ofrecen los componentes favorece la reutilización del código, lo que no solo optimiza el tiempo de desarrollo, sino que también reduce la probabilidad de errores.

Asimismo, las librerías, tanto estándar como definidas por el usuario, proporcionan herramientas que simplifican la implementación de funcionalidades comunes, permitiendo a los desarrolladores enfocarse en aspectos más específicos e innovadores de sus proyectos. La capacidad de crear librerías propias refuerza la organización del código y contribuye al desarrollo de sistemas más escalables y estructurados.

En conjunto, el dominio de estos conceptos no solo mejora la calidad del software, sino que también fomenta el uso de buenas prácticas de programación. Por ello, comprender y aplicar adecuadamente los componentes y las librerías resulta esencial para cualquier desarrollador que busque crear aplicaciones modernas, eficientes y sostenibles en el tiempo.


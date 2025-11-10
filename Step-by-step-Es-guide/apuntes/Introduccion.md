#  **GO (GOLANG)** 
### By: Jairo Mosteiro Campos
## *Guía Completa de Estudio*

<div align="center">

![Go Version](https://img.shields.io/badge/Go-1.21+-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Concurrencia](https://img.shields.io/badge/Concurrencia-Goroutines-00ADD8?style=for-the-badge)
![Estatus](https://img.shields.io/badge/ESTADO-EN_CURSO-blue?style=for-the-badge)

</div>

---

## **Indice**
#### ***Introduccion a Go***
---

## **Objetivos de Aprendizaje**

- **Sintaxis esencial** de Go
- **Programación concurrente** con Goroutines y Channels
- **Desarrollo de APIs** RESTful
- **Manejo de paquetes** y módulos
- **Buenas prácticas** y patrones de diseño

---

## **Tecnologías Relacionadas**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=flat-square&logo=json&logoColor=white)
![Testing](https://img.shields.io/badge/Testing-Green?style=flat-square&logo=testinglibrary&logoColor=white)

---
## Introduccion a Go (Golang)
### Que es Go?
- Go tambien llamado Golang, es un lengua de programacion creado por google en 2009
### Por que lo creearon?
- Por que google tenia un problema:
1. Su gran infraestructura
2. El codigo C++ y Java tardaba mucho en compilar
3. Habia mucha complegidad al manejar la concurrencia 
- #### Go nacio con tres objetivos:
1. Simplicidad: codigo facil de leer y  mantener 
2. Eficiencia: rendimiento cercano al de C
3. Concurrencia facil: gracias a las pequeñas tareas que se ejecutan al mismo tiempo 


## Para que se usa Go?
### Sobretodo para infraestructura y backend
- Servicios web y APIs
- Microservicios
- DevOps y herramientas
- Herramientas para la linea de comandos
## Configuracion de el entorno 
1. paso: Ve a https://go.dev/dl/
2. paso: Descarga el isntalador para tu SO
3. paso: Instalalo con las opciones por defecto
> verificar la instalacion
~~~~
bash:
go version
~~~~
> deberia mostrar algo como:
~~~~
bash:
go version go1.23.2 SO/amd64
~~~~
> Depende de la version SO y mas parametros puede mostrar una cosa o otra 
4. paso: Instalar un editor de codigo por experiencia personal recomiendo VSCODE Enlace de descarga: https://code.visualstudio.com/

5. paso: busca Go en las extensones de vscode y descarga la oficial de Google

## Tu primer "Hola mundo"
~~~~
package main

import "fmt"

fun main() {
    fmt.Println(Hola, Mundo)
}
~~~~
### Explicacion linea por linea 
- Estructura base:
>package main
>>Todo programa en Go pertenece a un paquete. El paquete main indica que es el programa principal (punto de entrada)
>

>import "fmt"
>>Importa el paquete fmt que sirve para formatear texto
>

>func main() {}
>>Define la funcion principalque Go ejecuta al iniciar el programa
>

hola amigo 




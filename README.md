# 📚 Taller CRUD de Libros | Books CRUD Workshop

[🇪🇸 Español](#español) · [🇬🇧 English](#english)

---

# Español

## 📖 Descripción

Aplicación web desarrollada con **React** como parte del taller de Desarrollo Front-End con React.

El proyecto consiste en una aplicación CRUD de libros que permite gestionar una colección de libros mediante una interfaz sencilla e intuitiva, utilizando JSON Server como API REST simulada.

## 🎯 Objetivos

Poner en práctica los conceptos aprendidos durante el taller:

- Desarrollo de componentes con React.
- Gestión de estados y propiedades.
- Creación y gestión de formularios.
- Consumo de APIs REST.
- Realización de peticiones HTTP con Axios.
- Implementación de operaciones CRUD.
- Diseño de interfaces con Tailwind CSS.

## 🛠️ Tecnologías utilizadas

- **React** – Desarrollo de la interfaz de usuario.
- **Tailwind CSS** – Diseño y estilos.
- **Axios** – Gestión de peticiones HTTP.
- **JSON Server** – Simulación de una API REST.
- **Vite** – Entorno de desarrollo.
- **JavaScript** – Lenguaje de programación.

## ⚙️ Funcionalidades

- **Crear libros:** añadir nuevos libros mediante un formulario.
- **Consultar libros:** visualizar el listado de libros almacenados.
- **Editar libros:** modificar la información de los libros existentes.
- **Eliminar libros:** borrar libros de la colección.

## 🚀 Instalación y ejecución

Clonar el repositorio:

```bash
git clone URL_DEL_REPOSITORIO
```

Acceder al directorio del proyecto:

```bash
cd NOMBRE_DEL_PROYECTO
```

Instalar las dependencias:

```bash
npm install
```

Iniciar JSON Server:

```bash
npm run api
```

Iniciar el servidor de desarrollo de React:

```bash
npm run dev
```

La aplicación estará disponible en:

```text
http://localhost:5173
```

La API REST estará disponible en:

```text
http://localhost:3000
```

## 🔄 Operaciones CRUD

| Operación  | Método HTTP | Descripción        |
| ---------- | ----------- | ------------------ |
| Crear      | POST        | Añadir un libro    |
| Leer       | GET         | Obtener los libros |
| Actualizar | PUT / PATCH | Modificar un libro |
| Eliminar   | DELETE      | Eliminar un libro  |

## 📸 Captura de pantalla

Captura de la página de Libros donde se muestra el formulario para añadir nuevos libros y el listado de libros obtenidos desde JSON Server.

[Vista de la aplicación CRUD de libros](./screenshots/books-crud.png)

# English

## 📖 Description

Web application developed with **React** as part of the Front-End Development with React workshop.

The project consists of a Books CRUD application that allows users to manage a book collection through a simple and intuitive interface, using JSON Server as a mock REST API.

## 🎯 Objectives

Apply the concepts learned during the workshop:

- Building components with React.
- Managing state and props.
- Creating and managing forms.
- Consuming REST APIs.
- Making HTTP requests with Axios.
- Implementing CRUD operations.
- Designing user interfaces with Tailwind CSS.

## 🛠️ Technologies

- **React** – User interface development.
- **Tailwind CSS** – Styling and layout.
- **Axios** – HTTP request management.
- **JSON Server** – Mock REST API.
- **Vite** – Development environment.
- **JavaScript** – Programming language.

## ⚙️ Features

- **Create books:** add new books using a form.
- **Read books:** display the list of stored books.
- **Update books:** edit existing book information.
- **Delete books:** remove books from the collection.

## 🚀 Installation and Setup

Clone the repository:

```bash
git clone REPOSITORY_URL
```

Navigate to the project directory:

```bash
cd PROJECT_NAME
```

Install dependencies:

```bash
npm install
```

Start JSON Server:

```bash
npm run api
```

Start the React development server:

```bash
npm run dev
```

The application will be available at:

```text
http://localhost:5173
```

The REST API will be available at:

```text
http://localhost:3000
```

## 🔄 CRUD Operations

| Operation | HTTP Method | Description            |
| --------- | ----------- | ---------------------- |
| Create    | POST        | Add a new book         |
| Read      | GET         | Retrieve the book list |
| Update    | PUT / PATCH | Update a book          |
| Delete    | DELETE      | Remove a book          |

## 📸 Screenshot

Screenshot of the Books page showing the form for adding new books and the list of books retrieved from JSON Server.

[View of the book CRUD application](./screenshots/books-crud.png)

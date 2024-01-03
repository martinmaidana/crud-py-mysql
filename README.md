<h1>Sistema CRUD de Empleados</h1>

<h3>🎯 Objetivo General:</h3>
<p>El objetivo de este CRUD (Create, Read, Update, Delete) es proporcionar una interfaz web para gestionar la información de los empleados. Permite añadir nuevos empleados, editar su información existente, eliminar registros y mostrar una lista completa de los empleados almacenados en la base de datos.</p>
<p>El sistema utiliza Flask como framework principal para manejar las rutas y generar las vistas HTML, junto con MySQL para el almacenamiento de los datos de los empleados. Se emplea también el sistema de archivos del servidor para guardar y gestionar las imágenes de perfil de los empleados.</p>

<h3>🛠️ Tecnologías Implementadas:</h3>
<ul>
  <li><strong>Flask:</strong> Framework de Python para desarrollo web.</li>
  <li><strong>MySQL:</strong> Sistema de gestión de bases de datos relacional.</li>
  <li><strong>HTML y CSS:</strong> Para la estructura y estilos de las páginas web.</li>
  <li><strong>Jinja2:</strong> Motor de plantillas utilizado con Flask para generar contenido dinámico en HTML.</li>
  <li><strong>Datetime:</strong> Librería de Python para trabajar con fechas y horas.</li>
</ul>

<h3>📋 Funcionalidades Principales:</h3>
<ol>
  <li><strong>Listado de Empleados:</strong> Ruta principal ("/") que muestra la lista de empleados con sus detalles desde la base de datos.</li>
  <li><strong>Creación de Empleados:</strong> Ruta ("/create") para agregar nuevos empleados, con campos para nombre, correo y foto.</li>
  <li><strong>Edición y Actualización de Empleados:</strong> Rutas para editar ("/edit/<int:id>") y actualizar ("/update") la información de un empleado existente. La actualización permite modificar nombre, correo y foto del empleado.</li>
  <li><strong>Eliminación de Empleados:</strong> Ruta para eliminar ("/destroy/<int:id>") un empleado seleccionado, incluyendo la eliminación de su foto asociada en el servidor.</li>
</ol>

<h3>🖥️ Vistas de Páginas:</h3>
<ul>
  <li><strong>Listado de Empleados:</strong> <code>index.html</code>: Muestra una tabla con la lista de empleados y sus detalles.</li>
  <li><strong>Creación de Empleados:</strong> <code>create.html</code>: Formulario para agregar nuevos empleados.</li>
  <li><strong>Edición de Empleados:</strong> <code>edit.html</code>: Formulario prellenado con los datos existentes del empleado seleccionado para editar.</li>
</ul>



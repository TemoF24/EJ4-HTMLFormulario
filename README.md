# EJ4HTMLFormulario
[![Jekyll site CI](https://github.com/TemoF24/EJ4HTMLFormulario/actions/workflows/jekyll-docker.yml/badge.svg)](https://github.com/TemoF24/EJ4HTMLFormulario/actions/workflows/jekyll-docker.yml)

# Formulario de Información del Profesor

Este es un formulario HTML diseñado para recopilar información detallada sobre los profesores. El formulario incluye campos como nombre, correo electrónico, teléfono, rol, departamento, estado, y más. Los datos se validan utilizando atributos HTML y estilos CSS para mejorar la experiencia del usuario.

## Características

- **Validación de datos**: Utiliza el atributo `pattern` para asegurar que los datos ingresados sean válidos, como el formato del teléfono, las contraseñas, etc.
- **Campos requeridos**: Algunos campos tienen el atributo `required`, lo que obliga a los usuarios a completarlos antes de enviar el formulario.
- **Estilo básico**: El formulario tiene un diseño sencillo pero atractivo con el uso de CSS para darle un toque profesional.
- **Campos adicionales**: Permite ingresar información adicional como la foto de perfil y notas adicionales del profesor.
- **Contraseña segura**: Se requiere que la contraseña contenga al menos una letra mayúscula, una minúscula, un número y un carácter especial, con un mínimo de 8 caracteres.

## Estructura del Formulario

El formulario incluye los siguientes campos:

- **Nombre**: Campo de texto para el nombre del profesor.
- **Número de Identificación**: Campo de texto para ingresar un número de identificación.
- **Correo Electrónico**: Campo de correo electrónico que valida el formato correcto de correo.
- **Número de Teléfono**: Campo de texto que acepta números de teléfono con un patrón específico (por ejemplo, (+34) 612345678).
- **Dirección**: Área de texto para que el profesor ingrese su dirección.
- **Fecha de Nacimiento**: Campo para seleccionar la fecha de nacimiento del profesor.
- **Género**: Campo de selección con opciones para masculino, femenino, u otro.
- **Rol**: Campo de selección para elegir el rol del profesor (Profesor, Coordinador, Jefe de Departamento).
- **Departamento**: Campo de selección para elegir el área o departamento del profesor.
- **Tipo de Contrato**: Campo de selección para elegir el tipo de contrato (Tiempo Completo, Medio Tiempo, Sustituto).
- **Fecha de Ingreso**: Campo para seleccionar la fecha en que el profesor ingresó a la institución.
- **Estado**: Campo de selección para el estado actual del profesor (Activo, En Licencia, Inactivo).
- **Foto de Perfil**: Campo para cargar una foto del profesor.
- **Notas Adicionales**: Área de texto para ingresar notas adicionales sobre el profesor.
- **Contraseña**: Campo de texto para ingresar la contraseña del profesor con una validación de seguridad.
- **Confirmar Contraseña**: Campo para confirmar que la contraseña ingresada es correcta.
- **Centro**: Campo de selección para elegir el centro al que pertenece el profesor (Escuela Secundaria A, Colegio ABC).

## Requisitos

- Un navegador moderno que soporte formularios HTML5 y validación.
- No se requiere un servidor específico para probar el formulario, pero se recomienda implementar un backend para gestionar el envío de los datos.

## Instrucciones de uso

1. **Abrir el archivo**: Abre el archivo `index.html` en cualquier navegador web.
2. **Completar el formulario**: Rellena los campos con la información del profesor.
3. **Enviar el formulario**: Haz clic en el botón "Enviar" para enviar el formulario. Para procesar los datos del formulario, necesitarás configurar un servidor backend que maneje el envío.

## Personalización

Puedes modificar este formulario fácilmente para agregar o eliminar campos según tus necesidades. Solo necesitas actualizar el HTML y agregar el procesamiento de los datos en el servidor.

## Contribuciones

Si deseas contribuir al proyecto, puedes hacer un *fork* y enviar un *pull request* con tus mejoras o correcciones.

## Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.



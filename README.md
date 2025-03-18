# Sorteo de Amigo Secreto

Proyecto en JavaScript que permite realizar un sorteo de amigo secreto de manera sencilla y automática.

## Características
- Permite ingresar nombres de participantes hasta un máximo de 7 personas.
- Verifica que no se repitan nombres.
- Realiza el sorteo asegurando que nadie se asigne a sí mismo.
- Muestra los resultados y borra los datos después de 10 segundos.
- Deshabilita la entrada una vez alcanzado el límite de participantes.

## Tecnologías utilizadas
- **HTML** para la estructura de la página.
- **CSS** para los estilos.
- **JavaScript** para la lógica del sorteo.

## Instalación y uso
1. Clonar el repositorio:
   ```sh
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
   ```
2. Abrir el archivo `index.html` en un navegador.
3. Ingresar los nombres de los participantes en el campo de texto.
4. Presionar el botón "Agregar" para añadir un participante.
5. Una vez ingresados al menos 2 participantes, presionar el botón "Sortear".
6. Los resultados se mostrarán en pantalla y desaparecerán después de 10 segundos.

## Funcionalidades del código
- **agregarAmigo()**: Agrega un nuevo participante a la lista verificando que el nombre sea válido.
- **actualizarLista()**: Actualiza la lista visual de participantes.
- **sortearAmigo()**: Realiza la asignación aleatoria asegurando que nadie se asigne a sí mismo.
- **mostrarResultados()**: Muestra los resultados en pantalla.
- **mostrarMensaje()**: Muestra mensajes de error o información.
- **limpiarPantalla()**: Borra los datos después del sorteo.

Cualquier sugerencia o mejora es bienvenida. ¡Disfruta del sorteo de amigo secreto! 🎉


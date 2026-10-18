# Mi libreta

Registro de hábitos personalizables con aspecto de cuaderno. Aplicación sin backend, sin login y sin dependencias externas.

## Uso diario

1. En Mi libreta, añade, renombra o desactiva tus hábitos y una frase para el mes.
2. En Hoy, marca lo que has cumplido y escribe algo reseñable. Se guarda automáticamente.
3. La casilla de revisión permite registrar un día con cero hábitos.
4. En Mes, revisa las anotaciones, marca casillas o toca una fila para editar ese día.
5. El gráfico adapta su escala al número de hábitos activos del mes. Los días sin registro quedan vacíos.

Puedes consultar meses anteriores e imprimir la vista mensual en A4 horizontal. En el móvil, desliza la tabla hacia los lados. Añade la web a la pantalla de inicio desde el menú del navegador para tenerla a mano.

## Copias y privacidad

Los registros se guardan en IndexedDB, en este navegador y dispositivo. No se envían a GitHub. La web es pública, pero cada navegador tiene su propia libreta. No hay sincronización ni control de acceso.

Exporta una copia JSON con frecuencia desde Mi libreta. Para cambiar de dispositivo, importa esa copia allí. La importación valida el formato y pide confirmación antes de sustituir todos los registros. No subas tus copias personales a este repositorio público.

Borrar los datos del sitio o usar navegación privada puede eliminar tus registros. Edita en una sola pestaña para evitar que se sobrescriban cambios.

## Configuración de hábitos

Los nombres y la frase se guardan por mes. Los meses nuevos heredan los hábitos del último mes anterior. Renombrar un hábito modifica el significado de esa columna durante todo ese mes, por eso conviene configurarlos antes de empezar. Desactivar un hábito lo oculta y deja de contarlo en ese mes, pero conserva sus marcas para poder reactivarlo. Puedes dejar todos desactivados y usar solo las anotaciones.

## Publicación

Toda la aplicación está en index.html. GitHub Pages publica la rama main desde la carpeta raíz. No necesita instalación ni compilación.

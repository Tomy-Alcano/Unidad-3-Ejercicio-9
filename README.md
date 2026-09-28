# Unidad-3-Ejercicio-9
Prog 3 Unidad 3 Ejercicio 9
Ejercicio 9 — Eliminación de clientes con DELETE
Este ejercicio completa el ciclo ABM incorporando la operación de baja: eliminar un registro de la base de datos a partir de la selección en la tabla.

Tomá como base el ejercicio anterior y agregá la siguiente funcionalidad:

Un botón con el texto "Eliminar cliente", que inicie deshabilitado
El botón debe habilitarse únicamente cuando haya una fila seleccionada en la tabla
Al presionar "Eliminar cliente", debe mostrarse un diálogo de confirmación usando JOptionPane con el mensaje: "¿Estás seguro de que querés eliminar este cliente? Esta acción no se puede deshacer."
Si el usuario confirma, debe ejecutarse un DELETE en la base de datos para el cliente seleccionado
Tras la eliminación, la tabla debe recargarse, los campos deben limpiarse y el botón debe volver a deshabilitarse
💡 Tip: usá JOptionPane.showConfirmDialog para mostrar el diálogo de confirmación y verificá que la respuesta sea JOptionPane.YES_OPTION antes de ejecutar el DELETE.
<img width="858" height="616" alt="image" src="https://github.com/user-attachments/assets/bc75bd2f-4b08-472a-9fc0-dc2b0bf5de5d" />
<img width="857" height="616" alt="image" src="https://github.com/user-attachments/assets/72a177f5-2b0e-4bbf-be3e-faddebaa68af" />
<img width="860" height="620" alt="image" src="https://github.com/user-attachments/assets/4e8cf6f7-af57-4f17-9cc6-47ec7e53caa9" />
<img width="857" height="618" alt="image" src="https://github.com/user-attachments/assets/bcaa597a-81fe-4db5-a798-23a07f91f516" />

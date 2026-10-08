# Capítulo III: Requirements Specification

## 3.1 To-Be Scenario Mapping

<div align="center">
  <img src="../assets/chapter-3/image24.png" width="700" />
</div>

## 3.2 User Stories

<table>
<colgroup>
<col style="width: 12%" />
<col style="width: 15%" />
<col style="width: 20%" />
<col style="width: 39%" />
<col style="width: 13%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Epic / User</strong></p>
<p><strong>Story ID</strong></p></th>
<th><strong>Título</strong></th>
<th><strong>Descripción</strong></th>
<th><strong>Criterios de aceptación</strong></th>
<th><strong>Relacionado con (Epic ID)</strong></th>
</tr>
<tr class="odd">
<th>US-01</th>
<th>Ver sección Home</th>
<th>Como visitante (proveedor), quiero ver una sección de inicio que resuma el valor de FuelBridge para comprender rápidamente el objetivo del sistema.</th>
<th><p>Escenario 1: Visualización de resumen del sistema</p>
<p>Dado que el visitante (proveedor) accede al sitio web,</p>
<p>Cuando se encuentra en la sección Home,</p>
<p>Entonces puede ver un resumen claro del sistema.</p>
<p>Escenario 2: Acceso a call to action desde Home</p>
<p>Dado que el visitante (proveedor) revisa la sección Home,</p>
<p>Cuando desliza hacia abajo,</p>
<p>Entonces encuentra un botón que lo invita a conocer más sobre FuelBridge.</p></th>
<th>EP01</th>
</tr>
<tr class="header">
<th>US-02</th>
<th>Ver sección About Us</th>
<th>Como visitante de ambos segmentos, quiero conocer quiénes están detrás de FuelBridge para confiar en el sistema.</th>
<th><p>Escenario 1: Información visible del equipo</p>
<p>Dado que el visitante de ambos segmentos accede a About Us,</p>
<p>Cuando se carga la sección,</p>
<p>Entonces puede leer una descripción del equipo detrás del sistema.</p>
<p>Escenario 2: Ver valores o misión</p>
<p>Dado que el visitante de ambos segmentos revisa la sección completa,</p>
<p>Cuando llega al final del contenido,</p>
<p>Entonces puede conocer los valores o misión de la empresa.</p></th>
<th>EP01</th>
</tr>
<tr class="odd">
<th>US-03</th>
<th>Ver sección How it works?</th>
<th>Como visitante de ambos segmentos, quiero entender cómo funciona FuelBridge paso a paso para evaluar si se ajusta a mis necesidades.</th>
<th><p>Escenario 1: Comprensión del flujo de pedidos</p>
<p>Dado que el visitante de ambos segmentos accede a How it works?,</p>
<p>Cuando lee la sección,</p>
<p>Entonces entiende el flujo de pedido desde solicitud hasta entrega.</p>
<p>Escenario 2: Interacción clara entre usuarios</p>
<p>Dado que el visitante de ambos segmentos busca claridad,</p>
<p>Cuando revisa la sección,</p>
<p>Entonces puede comprender cómo interactúan solicitante y proveedor.</p></th>
<th>EP01</th>
</tr>
<tr class="header">
<th>US-04</th>
<th>Enviar mensaje de contacto</th>
<th>Como visitante de ambos segmentos, quiero enviar un mensaje desde Contact Us para solicitar más información.</th>
<th><p>Escenario 1: Envío exitoso de mensaje</p>
<p>Dado que el visitante de ambos segmentos completa el formulario correctamente,</p>
<p>Cuando presiona "Enviar",</p>
<p>Entonces el mensaje es registrado para revisión.</p>
<p>Escenario 2: Validación de campos obligatorios</p>
<p>Dado que el visitante de ambos segmentos deja campos vacíos,</p>
<p>Cuando intenta enviar el formulario,</p>
<p>Entonces el sistema muestra una advertencia.</p>
<p>Escenario 3: Confirmación visual del envío</p>
<p>Dado que el visitante de ambos segmentos envía el formulario exitosamente,</p>
<p>Cuando el mensaje es registrado,</p>
<p>Entonces recibe una confirmación visual o notificación.</p></th>
<th>EP01</th>
</tr>
<tr class="odd">
<th>US-05</th>
<th>Registrar nuevo pedido</th>
<th>Como solicitante, quiero registrar un pedido con tipo y cantidad de combustible para que el proveedor lo procese.</th>
<th><p>Escenario 1: Registro exitoso del pedido</p>
<p>Dado que el solicitante accede al formulario de pedidos,</p>
<p>Cuando completa los campos requeridos,</p>
<p>Entonces puede enviar un nuevo pedido.</p>
<p>Escenario 2: Validación de campos</p>
<p>Dado que el solicitante deja un campo obligatorio vacío,</p>
<p>Cuando intenta enviar el pedido,</p>
<p>Entonces el sistema muestra un mensaje de error.</p>
<p>Escenario 3: Confirmación del cambio de estado</p>
<p>Dado que el solicitante envió el pedido,</p>
<p>Cuando el proveedor lo aprueba,</p>
<p>Entonces su estado se actualiza automáticamente.</p></th>
<th>EP02</th>
</tr>
<tr class="header">
<th>US-06</th>
<th>Consultar estado del pedido</th>
<th>Como solicitante, quiero ver el estado de mis pedidos para saber si están aprobados, en tránsito o entregados.</th>
<th><p>Escenario 1: Consulta de estado en el panel</p>
<p>Dado que el solicitante accede a su panel,</p>
<p>Cuando revisa la lista de pedidos,</p>
<p>Entonces ve el estado actualizado.</p>
<p>Escenario 2: Actualización dinámica de estado</p>
<p>Dado que el solicitante está visualizando el panel de pedidos,</p>
<p>Cuando el pedido cambia de estado,</p>
<p>Entonces el cambio se refleja correctamente al recargar el panel.</p></th>
<th>EP02</th>
</tr>
<tr class="odd">
<th>US-07</th>
<th>Confirmar recepción de pedido</th>
<th>Como solicitante, quiero confirmar que recibí el pedido para que el proveedor lo cierre.</th>
<th><p>Escenario 1: Confirmación exitosa de recepción</p>
<p>Dado que el solicitante recibió el pedido,</p>
<p>Cuando lo confirma en el sistema,</p>
<p>Entonces su estado cambia a "Entregado".</p>
<p>Escenario 2: Prevención de doble confirmación</p>
<p>Dado que el solicitante ya confirmó la entrega,</p>
<p>Cuando intenta volver a confirmar,</p>
<p>Entonces el sistema bloquea la acción y notifica al usuario.</p></th>
<th>EP02</th>
</tr>
<tr class="header">
<th>US-08</th>
<th>Registrar información de pago</th>
<th>Como solicitante, quiero ingresar la información de los pagos correspondientes para validar el pedido ante el proveedor.</th>
<th><p>Escenario 1: Registro exitoso de depósitos</p>
<p>Dado que el solicitante ingresa la información de depósitos,</p>
<p>Cuando registra el pedido,</p>
<p>Estos quedan vinculados a él.</p>
<p>Escenario 2: Validación del formulario de ingreso de depósitos</p>
<p>Dado que el solicitante intenta ingresar los datos del depósito,</p>
<p>Cuando excede el límite de caracteres,</p>
<p>Entonces el sistema muestra un mensaje de error.</p>
<p>Escenario 3: Validación de depósitos ya registrados</p>
<p>Dado que el solicitante ingresa un depósito con un número de operación repetido,</p>
<p>Cuando intenta seguir con el registro,</p>
<p>Entonces el sistema notifica el error.</p></th>
<th>EP02</th>
</tr>
<tr class="odd">
<th>US-09</th>
<th>Ver historial de pedidos</th>
<th>Como solicitante, quiero ver mis pedidos anteriores para tener control sobre mi consumo.</th>
<th><p>Escenario 1: Visualización del historial</p>
<p>Dado que el solicitante accede al historial,</p>
<p>Cuando se listan los pedidos,</p>
<p>Entonces puede ver fecha, tipo y estado de cada uno.</p>
<p>Escenario 2: Historial vacío</p>
<p>Dado que el solicitante aún no ha realizado pedidos,</p>
<p>Cuando accede al historial,</p>
<p>Entonces se muestra un mensaje informativo.</p>
<p>Escenario 3: Acceso a detalles desde historial</p>
<p>Dado que el solicitante ve la lista de pedidos anteriores,</p>
<p>Cuando selecciona uno,</p>
<p>Entonces puede revisar sus detalles.</p></th>
<th>EP02</th>
</tr>
<tr class="header">
<th>US-10</th>
<th>Ver pedidos pendientes</th>
<th>Como proveedor, quiero ver todos los pedidos pendientes para analizarlos y tomar acción.</th>
<th><p>Escenario 1: Listado de pedidos pendientes</p>
<p>Dado que el proveedor accede al panel,</p>
<p>Cuando ve los pedidos pendientes,</p>
<p>Entonces puede revisar sus detalles básicos.</p>
<p>Escenario 2: Filtro por fechas o cliente</p>
<p>Dado que el proveedor tiene muchos pedidos,</p>
<p>Cuando aplica filtros por fecha o empresa,</p>
<p>Entonces puede localizar los pedidos relevantes.</p></th>
<th>EP03</th>
</tr>
<tr class="odd">
<th>US-11</th>
<th>Aprobar pedido</th>
<th>Como proveedor, quiero aprobar pedidos según los depósitos hechos a mis cuentas bancarias.</th>
<th><p>Escenario 1: Aprobación de pedido con depósitos válidos</p>
<p>Dado que el proveedor tiene el pago completo del pedido,</p>
<p>Cuando intenta aprobarlo,</p>
<p>Entonces el estado cambia a "Aprobado".</p>
<p>Escenario 2: No aprobar el pedido por pago incompleto</p>
<p>Dado que el proveedor no cuenta con los depósitos suficientes para completar el pago del pedido,</p>
<p>Cuando intenta aprobarlo,</p>
<p>Entonces se muestra un mensaje indicando que el pedido no fue pagado por completo.</p></th>
<th>EP03</th>
</tr>
<tr class="header">
<th>US-12</th>
<th>Marcar pedido como despachado</th>
<th>Como proveedor, quiero marcar cuándo un pedido sale a entrega para notificar al cliente.</th>
<th><p>Escenario 1: Despacho exitoso de un pedido</p>
<p>Dado que el proveedor tiene un pedido aprobado,</p>
<p>Cuando marca el pedido como despachado,</p>
<p>Entonces el estado cambia a "Despachado".</p>
<p>Escenario 2: Restricción de despacho sin aprobación previa</p>
<p>Dado que el proveedor intenta despachar un pedido sin pasar por la liberación correspondiente,</p>
<p>Cuando ejecuta la acción,</p>
<p>Entonces el sistema impide el cambio de estado y muestra un mensaje.</p></th>
<th>EP03</th>
</tr>
<tr class="odd">
<th>US-13</th>
<th>Cerrar pedido</th>
<th>Como proveedor, quiero cerrar el pedido cuando el cliente confirme la entrega para finalizar el proceso.</th>
<th><p>Escenario 1: Cierre correcto del pedido tras confirmación</p>
<p>Dado que el solicitante ya confirmó la entrega,</p>
<p>Cuando el proveedor cierra el pedido,</p>
<p>Entonces este no puede modificarse más.</p>
<p>Escenario 2: Intento de cierre sin confirmación previa</p>
<p>Dado que el proveedor intenta cerrar el pedido,</p>
<p>Cuando el solicitante aún no ha confirmado la entrega,</p>
<p>Entonces el sistema impide esta acción.</p></th>
<th>EP03</th>
</tr>
<tr class="header">
<th>US-14</th>
<th>Generar reporte de ventas</th>
<th>Como proveedor, quiero generar reportes de ventas para tener registro de operaciones realizadas.</th>
<th><p>Escenario 1: Generación de reporte con datos disponibles</p>
<p>Dado que el proveedor selecciona un rango de fechas válido,</p>
<p>Cuando solicita el reporte,</p>
<p>Entonces se genera un archivo con los datos de ventas.</p>
<p>Escenario 2: Generación sin datos en el rango</p>
<p>Dado que el proveedor selecciona un rango sin ventas,</p>
<p>Cuando solicita el reporte,</p>
<p>Entonces el sistema informa que no hay resultados.</p>
<p>Escenario 3: Descarga del archivo generado</p>
<p>Dado que el reporte se genera correctamente,</p>
<p>Cuando finaliza el proceso,</p>
<p>Entonces el proveedor puede descargar el archivo.</p></th>
<th>EP03</th>
</tr>
<tr class="odd">
<th>US-15</th>
<th>Iniciar sesión</th>
<th>Como usuario registrado, quiero iniciar sesión con correo y contraseña para acceder a mi cuenta.</th>
<th><p>Escenario 1: Inicio de sesión exitoso</p>
<p>Dado que el usuario registrado ingresa credenciales válidas,</p>
<p>Cuando presiona iniciar sesión,</p>
<p>Entonces accede a su dashboard.</p>
<p>Escenario 2: Error por credenciales incorrectas</p>
<p>Dado que el usuario registrado ingresa datos incorrectos,</p>
<p>Cuando intenta iniciar sesión,</p>
<p>Entonces el sistema muestra un mensaje de error.</p>
<p>Escenario 3: Validación de campos vacíos</p>
<p>Dado que el usuario deja campos vacíos,</p>
<p>Cuando intenta iniciar sesión,</p>
<p>Entonces el sistema solicita completar los campos.</p></th>
<th>EP04</th>
</tr>
<tr class="header">
<th>US-16</th>
<th>Recuperar contraseña</th>
<th>Como usuario registrado, quiero recuperar mi contraseña para volver a acceder si la olvidé.</th>
<th><p>Escenario 1: Envío de enlace de recuperación</p>
<p>Dado que el usuario registrado ingresa su correo válido,</p>
<p>Cuando solicita recuperación,</p>
<p>Entonces recibe un enlace al correo.</p>
<p>Escenario 2: Error por correo no registrado</p>
<p>Dado que el usuario ingresa un correo inexistente,</p>
<p>Cuando solicita recuperación,</p>
<p>Entonces se le informa que el correo no está registrado.</p>
<p>Escenario 3: Validación de campo vacío</p>
<p>Dado que el usuario no completa el campo de correo,</p>
<p>Cuando intenta enviar la solicitud,</p>
<p>Entonces el sistema solicita completarlo.</p></th>
<th>EP04</th>
</tr>
<tr class="odd">
<th>US-17</th>
<th>Cerrar sesión</th>
<th>Como usuario registrado, quiero poder cerrar sesión para mantener segura mi cuenta.</th>
<th><p>Escenario 1: Cierre exitoso de sesión</p>
<p>Dado que el usuario está autenticado,</p>
<p>Cuando selecciona "Cerrar sesión",</p>
<p>Entonces la sesión se finaliza y es redirigido al login.</p>
<p>Escenario 2: Confirmación de cierre de sesión</p>
<p>Dado que el usuario cierra sesión,</p>
<p>Cuando termina la acción,</p>
<p>Entonces el sistema muestra un mensaje de despedida o confirmación.</p></th>
<th>EP04</th>
</tr>
<tr class="header">
<th>US-18</th>
<th>Ver resumen de pedidos (Solicitante)</th>
<th>Como solicitante, quiero ver un resumen de mis pedidos para identificar cuántos están en proceso o completados.</th>
<th><p>Escenario 1: Visualización de resumen con datos disponibles</p>
<p>Dado que el solicitante tiene pedidos registrados,</p>
<p>Cuando accede a su dashboard,</p>
<p>Entonces visualiza los KPIs por estado: pendientes, aprobados, despachados, finalizados y rechazados.</p>
<p>Escenario 2: Sin pedidos registrados</p>
<p>Dado que el solicitante no tiene pedidos,</p>
<p>Cuando accede al dashboard,</p>
<p>Entonces ve un mensaje informando "No hay pedidos registrados".</p>
<p>Escenario 3: Error al cargar datos del resumen</p>
<p>Dado que el solicitante accede al dashboard,</p>
<p>Cuando ocurre un error de carga,</p>
<p>Entonces el sistema muestra un mensaje e intenta recargar los datos automáticamente.</p></th>
<th>EP05</th>
</tr>
<tr class="odd">
<th>US-19</th>
<th>Validar disponibilidad de transporte</th>
<th>Como proveedor, quiero saber qué vehículos están disponibles antes de asignarlos para vincularlos correctamente.</th>
<th><p>Escenario 1: Vehículo no disponible por superposición</p>
<p>Dado que el proveedor visualiza el listado de vehículos,</p>
<p>Cuando un vehículo está asignado a otro pedido para la misma fecha y hora estimada,</p>
<p>Entonces el sistema lo muestra como no disponible.</p>
<p>Escenario 2: Vehículo disponible</p>
<p>Dado que el proveedor visualiza un vehículo sin conflictos de agenda,</p>
<p>Cuando se carga el listado de vehículos,</p>
<p>Entonces dicho vehículo se muestra como seleccionable.</p>
<p>Escenario 3: Conflicto en tiempo real</p>
<p>Dado que el proveedor intenta seleccionar un vehículo que fue asignado recientemente por otro usuario,</p>
<p>Cuando realiza la acción,</p>
<p>Entonces el sistema bloquea la selección y muestra un mensaje de actualización.</p></th>
<th>EP08</th>
</tr>
<tr class="header">
<th>US-20</th>
<th>Ver perfil de usuario</th>
<th>Como usuario registrado, quiero ver mis datos de perfil para revisar mi información registrada.</th>
<th><p>Escenario 1: Visualización exitosa del perfil</p>
<p>Dado que el usuario tiene sesión activa,</p>
<p>Cuando accede a su perfil,</p>
<p>Entonces ve su nombre, correo y rol.</p>
<p>Escenario 2: Error en la carga de datos</p>
<p>Dado que el usuario accede a su perfil y ocurre un error al obtener los datos,</p>
<p>Cuando se carga la vista,</p>
<p>Entonces se muestra un mensaje de error y se sugiere reintentar.</p>
<p>Escenario 3: Restricción de datos de otros usuarios</p>
<p>Dado que el usuario tiene sesión activa,</p>
<p>Cuando intenta ver otro perfil,</p>
<p>Entonces el sistema restringe el acceso y muestra su propia información.</p></th>
<th>EP09</th>
</tr>
<tr class="odd">
<th>US-21</th>
<th>Editar datos de perfil</th>
<th>Como usuario registrado, quiero editar mis datos para mantener mi información actualizada.</th>
<th><p>Escenario 1: Edición y guardado exitoso</p>
<p>Dado que el usuario modifica uno o más campos del formulario,</p>
<p>Cuando la información ingresada es válida,</p>
<p>Entonces el sistema guarda los cambios correctamente.</p>
<p>Escenario 2: Campo obligatorio vacío</p>
<p>Dado que el usuario deja un campo obligatorio vacío,</p>
<p>Cuando intenta guardar,</p>
<p>Entonces el sistema muestra un mensaje de validación indicando el campo requerido.</p>
<p>Escenario 3: Error del servidor al guardar</p>
<p>Dado que el usuario intenta guardar y ocurre un fallo en el servidor,</p>
<p>Cuando se realiza la acción,</p>
<p>Entonces se muestra un mensaje de error y los datos ingresados permanecen visibles.</p></th>
<th>EP09</th>
</tr>
<tr class="header">
<th>US-22</th>
<th>Ver sección de preguntas frecuentes</th>
<th>Como visitante de ambos segmentos, quiero acceder a una sección de preguntas frecuentes para resolver dudas rápidamente.</th>
<th><p>Escenario 1: Visualización de preguntas comunes</p>
<p>Dado que el visitante accede a la sección,</p>
<p>Cuando se carga el contenido,</p>
<p>Entonces puede leer las preguntas y respuestas más frecuentes.</p>
<p>Escenario 2: Organización por categorías</p>
<p>Dado que el visitante accede a la sección de preguntas frecuentes con muchas entradas,</p>
<p>Cuando navega por la sección,</p>
<p>Entonces puede visualizarlas clasificadas en categorías.</p>
<p>Escenario 3: Error al cargar FAQs</p>
<p>Dado que el visitante accede a la sección y ocurre un fallo en la carga,</p>
<p>Cuando intenta visualizar las preguntas frecuentes,</p>
<p>Entonces se muestra un mensaje de error o un contenido informativo alternativo.</p></th>
<th>EP10</th>
</tr>
<tr class="odd">
<th>US-23</th>
<th>Acceder a información de contacto rápido</th>
<th>Como usuario de ambos segmentos, quiero ver datos de contacto directo (teléfono o correo) para hacer consultas urgentes.</th>
<th><p>Escenario 1: Visualización de datos de contacto</p>
<p>Dado que el usuario accede a la sección de soporte,</p>
<p>Cuando se carga la página,</p>
<p>Entonces puede visualizar claramente el correo de soporte y número telefónico.</p>
<p>Escenario 2: Acceso al correo de cliente</p>
<p>Dado que el usuario hace clic en la dirección de correo,</p>
<p>Cuando tiene una app de correo configurada,</p>
<p>Entonces se abre automáticamente su aplicación de correo predeterminada.</p>
<p>Escenario 3: Falla en la configuración de contacto</p>
<p>Dado que el usuario accede a la página y los datos de contacto no están bien configurados,</p>
<p>Cuando se carga la sección de contacto,</p>
<p>Entonces el sistema muestra un mensaje genérico invitando a intentar más tarde.</p></th>
<th>EP10</th>
</tr>
<tr class="header">
<th>US-24</th>
<th>Buscar pedido por código</th>
<th>Como usuario de ambos segmentos, quiero buscar un pedido específico por su código para encontrarlo rápidamente.</th>
<th><p>Escenario 1: Pedido encontrado</p>
<p>Dado que el usuario escribe un código válido,</p>
<p>Cuando existe un pedido con ese código,</p>
<p>Entonces se muestra el resultado correspondiente.</p>
<p>Escenario 2: Pedido no encontrado</p>
<p>Dado que el usuario digita un código no correspondiente a ningún pedido,</p>
<p>Cuando finaliza la búsqueda,</p>
<p>Entonces el sistema muestra un mensaje de que no hay coincidencias.</p></th>
<th>EP11</th>
</tr>
<tr class="odd">
<th>US-25</th>
<th>Filtrar pedidos por estado</th>
<th>Como usuario de ambos segmentos, quiero filtrar mis pedidos por estado (pendiente, aprobado, entregado) para facilitar la revisión.</th>
<th><p>Escenario 1: Aplicar filtro correctamente</p>
<p>Dado que el usuario selecciona un estado,</p>
<p>Cuando se aplica el filtro,</p>
<p>Entonces solo se muestran los pedidos con ese estado.</p>
<p>Escenario 2: No hay pedidos en ese estado</p>
<p>Dado que el usuario selecciona un estado que no tiene coincidencias,</p>
<p>Cuando ejecuta el filtro,</p>
<p>Entonces se muestra un mensaje indicando que no hay pedidos para ese estado.</p></th>
<th>EP11</th>
</tr>
<tr class="header">
<th>US-26</th>
<th>Recibir notificación de aprobación</th>
<th>Como solicitante, quiero recibir una notificación cuando un pedido sea aprobado o rechazado para estar informado.</th>
<th><p>Escenario 1: Visualización de notificación</p>
<p>Dado que el proveedor cambia el estado del pedido,</p>
<p>Cuando el solicitante inicia sesión,</p>
<p>Entonces ve una notificación del evento.</p>
<p>Escenario 2: Pedido actualizado desde otra sesión</p>
<p>Dado que el solicitante aún no ha leído la notificación,</p>
<p>Cuando actualiza la interfaz,</p>
<p>Entonces la notificación se mantiene visible hasta que sea marcada como leída.</p></th>
<th>EP12</th>
</tr>
<tr class="odd">
<th>US-27</th>
<th>Notificación de pedido despachado</th>
<th>Como solicitante, quiero recibir una notificación cuando un pedido haya sido despachado para estar informado.</th>
<th><p>Escenario 1: Pedido marcado como despachado</p>
<p>Dado que el proveedor marca el pedido como despachado,</p>
<p>Cuando el solicitante consulta su cuenta,</p>
<p>Entonces puede ver la notificación correspondiente.</p>
<p>Escenario 2: Visualización posterior del evento</p>
<p>Dado que el pedido fue despachado anteriormente,</p>
<p>Cuando el solicitante accede en otro momento,</p>
<p>Entonces la notificación sigue disponible hasta ser archivada o leída.</p></th>
<th>EP12</th>
</tr>
<tr class="header">
<th>US-28</th>
<th>Ver listado de empresas</th>
<th>Como proveedor, quiero ver una lista de empresas solicitantes para identificar a mis clientes frecuentes.</th>
<th><p>Escenario 1: Visualización del listado</p>
<p>Dado que el proveedor accede al módulo de empresas,</p>
<p>Cuando se carga el listado,</p>
<p>Entonces se muestran nombre, pedidos activos y total histórico por empresa.</p>
<p>Escenario 2: Lista vacía o sin datos</p>
<p>Dado que el proveedor accede al módulo y no hay empresas registradas,</p>
<p>Cuando se carga la vista,</p>
<p>Entonces se muestra un mensaje indicando que no hay empresas disponibles.</p></th>
<th>EP13</th>
</tr>
<tr class="odd">
<th>US-29</th>
<th>Ver detalles de empresa</th>
<th>Como proveedor, quiero ver información detallada de una empresa solicitante para analizar su historial de pedidos.</th>
<th><p>Escenario 1: Acceso a detalle de empresa</p>
<p>Dado que el proveedor selecciona una empresa,</p>
<p>Cuando se carga el detalle,</p>
<p>Entonces visualiza pedidos realizados, cantidades solicitadas y fechas.</p>
<p>Escenario 2: Empresa sin historial de pedidos</p>
<p>Dado que el proveedor selecciona una empresa que aún no ha realizado pedidos,</p>
<p>Cuando se accede a su perfil,</p>
<p>Entonces se muestra un mensaje indicando que no hay historial disponible.</p></th>
<th>EP13</th>
</tr>
<tr class="header">
<th>US-30</th>
<th>Ver gráfico de consumo (Solicitante)</th>
<th>Como solicitante, quiero ver un gráfico de mi consumo mensual para tener control sobre el uso del combustible.</th>
<th><p>Escenario 1: Gráfico con datos disponibles</p>
<p>Dado que el solicitante ha realizado pedidos,</p>
<p>Cuando accede al módulo de reportes,</p>
<p>Entonces se visualiza un gráfico con galones consumidos por mes.</p>
<p>Escenario 2: Sin datos de consumo</p>
<p>Dado que el solicitante no ha hecho pedidos aún,</p>
<p>Cuando accede al gráfico,</p>
<p>Entonces se muestra un mensaje de que no hay datos suficientes.</p></th>
<th>EP14</th>
</tr>
<tr class="odd">
<th>US-31</th>
<th>Ver gráfico de ventas (Proveedor)</th>
<th>Como proveedor, quiero ver un gráfico de ventas por mes para monitorear el rendimiento del negocio.</th>
<th><p>Escenario 1: Datos disponibles para graficar</p>
<p>Dado que el proveedor ha despachado pedidos,</p>
<p>Cuando accede al módulo de reportes,</p>
<p>Entonces se visualiza un gráfico con las ventas mensuales totales.</p>
<p>Escenario 2: Sin pedidos registrados</p>
<p>Dado que el proveedor no ha realizado ventas aún,</p>
<p>Cuando accede al gráfico,</p>
<p>Entonces se muestra un mensaje de que no hay datos suficientes.</p></th>
<th>EP14</th>
</tr>
<tr class="header">
<th>US-32</th>
<th>Descargar reporte PDF</th>
<th>Como usuario de ambos segmentos, quiero descargar un resumen de pedidos o ventas en formato PDF para archivarlo o compartirlo.</th>
<th><p>Escenario 1: Generación de PDF con datos</p>
<p>Dado que el usuario hace clic en "Descargar",</p>
<p>Cuando hay datos en el periodo seleccionado,</p>
<p>Entonces se genera un archivo PDF descargable.</p>
<p>Escenario 2: No hay datos en el periodo seleccionado</p>
<p>Dado que el usuario no tiene registros en el periodo seleccionado,</p>
<p>Cuando se solicita la descarga,</p>
<p>Entonces el sistema notifica que no hay contenido para exportar.</p>
<p>Escenario 3: Falla en la generación del PDF</p>
<p>Dado que el usuario intenta descargar el archivo y ocurre un error en el backend al generar el PDF,</p>
<p>Cuando hace clic en el botón de descargar,</p>
<p>Entonces se muestra un mensaje de error sin afectar la sesión.</p></th>
<th>EP14</th>
</tr>
<tr class="odd">
<th>US-33</th>
<th>Ver sección Benefits</th>
<th>Como visitante de ambos segmentos, quiero conocer las principales ventajas con las que puedo contar para evaluar la implementación de la plataforma.</th>
<th><p>Escenario 1: Visualizar beneficios</p>
<p>Dado que el visitante de ambos segmentos accede a la sección "¿Por qué elegir FuelBridge?",</p>
<p>Cuando visualiza los múltiples beneficios,</p>
<p>Entonces puede identificar nuestra ventajas frente a nuestros competidores.</p>
<p>Escenario 2: Visualizar beneficios</p>
<p>Dado que el visitante de ambos segmentos accede a la sección "¿Por qué elegir FuelBridge?",</p>
<p>Cuando observa la lista de beneficios,</p>
<p>Entonces ve como le podría beneficiar usar FuelBridge.</p></th>
<th>EP01</th>
</tr>
<tr class="header">
<th>US-34</th>
<th>Ver sección Lo que Dicen Nuestros Clientes</th>
<th>Como visitante de ambos segmentos, quiero conocer los testimonios de los usuarios de FuelBridge para tener confianza en la plataforma y saber que otras empresas ya la están usando.</th>
<th><p>Escenario 1: Ver testimonios de clientes</p>
<p>Dado que el visitante de ambos segmentos está interesado en los comentarios de los clientes,</p>
<p>Cuando accede a la sección,</p>
<p>Entonces puede leer un breve testimonio sobre experiencias usando FuelBridge.</p>
<p>Escenario 2: Visualizar testimonios recientes</p>
<p>Dado que el visitante de ambos segmentos accede a la sección y esta se actualiza regularmente,</p>
<p>Cuando se carga la información,</p>
<p>Entonces visualiza las últimos testimonios que se han unido a FuelBridge.</p></th>
<th>EP01</th>
</tr>
<tr class="odd">
<th>US-35</th>
<th>Ver sección Planes y Precios</th>
<th>Como visitante (ambos segmentos), quiero saber que planes se adecuan a mis necesidades para poder iniciar un proceso de registro o solicitud.</th>
<th><p>Escenario 1: Ver información sobre ser solicitante de combustible</p>
<p>Dado que el visitante entra a la sección Precios y Planes,</p>
<p>Cuando visualiza los diferentes precios y las features incluidas,</p>
<p>Entonces entiende que existe flexibilidad para adaptar FuelBridge a su empresa.</p>
<p>Escenario 2: Seleccionar un plan</p>
<p>Dado que el visitante está interesado en obtener un plan específico,</p>
<p>Cuando hace clic en el call to action,</p>
<p>Entonces es redirigido a la página de registro.</p></th>
<th>EP01</th>
</tr>
<tr class="header">
<th>US-36</th>
<th>Cambiar idioma</th>
<th>Como visitante de ambos segmentos, quiero poder cambiar entre inglés y español para entender la plataforma en mi idioma preferido.</th>
<th><p>Escenario 1: Cambiar idioma a español</p>
<p>Dado que el visitante de ambos segmentos está viendo la página en inglés,</p>
<p>Cuando selecciona la opción de español,</p>
<p>Entonces toda la interfaz de la página se muestra en español.</p>
<p>Escenario 2: Cambiar idioma a inglés</p>
<p>Dado que el visitante está viendo la página en español,</p>
<p>Cuando selecciona la opción de inglés,</p>
<p>Entonces toda la interfaz de la página se muestra en inglés.</p></th>
<th>EP01</th>
</tr>
<tr class="odd">
<th>US-37</th>
<th>Registrar empresa solicitante</th>
<th>Como visitante (solicitante), quiero registrar mi empresa en la plataforma para comenzar a realizar pedidos de combustible.</th>
<th><p>Escenario 1: Registro exitoso de empresa</p>
<p>Dado que el visitante completa todos los campos requeridos del formulario de registro,</p>
<p>Cuando presiona "Registrar empresa",</p>
<p>Entonces se crea la cuenta y es redirigido a su dashboard.</p>
<p>Escenario 2: RUC o correo ya registrado</p>
<p>Dado que el visitante ingresa un RUC o correo que ya existe en el sistema,</p>
<p>Cuando intenta completar el registro,</p>
<p>Entonces el sistema muestra un mensaje indicando que ya existe una cuenta con esos datos.</p>
<p>Escenario 3: Campos obligatorios vacíos</p>
<p>Dado que el visitante deja uno o más campos obligatorios sin completar,</p>
<p>Cuando intenta continuar con el registro,</p>
<p>Entonces el sistema resalta los campos faltantes y solicita completarlos.</p></th>
<th>EP04</th>
</tr>
<tr class="header">
<th>US-38</th>
<th>Registrar empresa proveedora</th>
<th>Como visitante (proveedor), quiero registrar mi empresa distribuidora en la plataforma para comenzar a gestionar pedidos de combustible.</th>
<th><p>Escenario 1: Registro exitoso de proveedor</p>
<p>Dado que el visitante proveedor completa todos los campos del formulario,</p>
<p>Cuando confirma el registro,</p>
<p>Entonces se crea la cuenta y puede acceder a su panel de gestión.</p>
<p>Escenario 2: Datos de empresa duplicados</p>
<p>Dado que el visitante ingresa un RUC que ya está registrado como proveedor,</p>
<p>Cuando intenta finalizar el registro,</p>
<p>Entonces el sistema notifica que ya existe una empresa con ese RUC.</p>
<p>Escenario 3: Formato inválido en campos</p>
<p>Dado que el visitante ingresa datos con formato incorrecto,</p>
<p>Cuando intenta avanzar en el formulario,</p>
<p>Entonces el sistema muestra un mensaje de validación por campo.</p></th>
<th>EP04</th>
</tr>
<tr class="odd">
<th>US-39</th>
<th>Rechazar pedido</th>
<th>Como proveedor, quiero rechazar un pedido cuando no pueda atenderlo para notificar al solicitante oportunamente.</th>
<th><p>Escenario 1: Rechazo exitoso con motivo</p>
<p>Dado que el proveedor decide no atender un pedido pendiente,</p>
<p>Cuando selecciona "Rechazar" e ingresa un motivo,</p>
<p>Entonces el estado del pedido cambia a "Rechazado" y el solicitante recibe una notificación.</p>
<p>Escenario 2: Intento de rechazo sin motivo</p>
<p>Dado que el proveedor intenta rechazar un pedido sin ingresar motivo,</p>
<p>Cuando ejecuta la acción,</p>
<p>Entonces el sistema solicita ingresar un motivo obligatorio antes de confirmar.</p>
<p>Escenario 3: Rechazo de pedido ya procesado</p>
<p>Dado que el proveedor intenta rechazar un pedido que ya fue aprobado o despachado,</p>
<p>Cuando ejecuta la acción,</p>
<p>Entonces el sistema impide la acción y muestra el estado actual del pedido.</p></th>
<th>EP03</th>
</tr>
<tr class="header">
<th>US-40</th>
<th>Ver detalle de pedido</th>
<th>Como usuario de ambos segmentos, quiero ver el detalle completo de un pedido para revisar toda la información asociada.</th>
<th><p>Escenario 1: Visualización completa del detalle</p>
<p>Dado que el usuario selecciona un pedido desde su panel,</p>
<p>Cuando se carga la vista de detalle,</p>
<p>Entonces puede ver tipo de combustible, cantidad, estado, fechas, datos de pago y asignación logística.</p>
<p>Escenario 2: Pedido no encontrado</p>
<p>Dado que el usuario intenta acceder al detalle de un pedido inexistente,</p>
<p>Cuando se carga la vista,</p>
<p>Entonces el sistema muestra un mensaje de error y ofrece regresar al listado.</p>
<p>Escenario 3: Restricción de acceso a pedidos ajenos</p>
<p>Dado que el usuario intenta acceder al detalle de un pedido que no le pertenece,</p>
<p>Cuando carga la URL directamente,</p>
<p>Entonces el sistema restringe el acceso y redirige a su propio panel.</p></th>
<th>EP02</th>
</tr>
<tr class="odd">
<th>US-41</th>
<th>Gestionar vehículos de flota</th>
<th>Como proveedor, quiero registrar y administrar los vehículos de mi flota para tenerlos disponibles al momento de asignarlos a pedidos.</th>
<th><p>Escenario 1: Registro exitoso de vehículo</p>
<p>Dado que el proveedor accede al módulo de flota y completa los datos del vehículo,</p>
<p>Cuando guarda el registro,</p>
<p>Entonces el vehículo queda disponible para ser asignado a pedidos.</p>
<p>Escenario 2: Placa duplicada</p>
<p>Dado que el proveedor intenta registrar un vehículo con una placa ya existente,</p>
<p>Cuando intenta guardar,</p>
<p>Entonces el sistema muestra un error indicando que la placa ya está registrada.</p>
<p>Escenario 3: Eliminación de vehículo</p>
<p>Dado que el proveedor elimina un vehículo de la flota,</p>
<p>Cuando confirma la acción,</p>
<p>Entonces el vehículo deja de aparecer como opción en la asignación de pedidos.</p></th>
<th>EP08</th>
</tr>
<tr class="header">
<th>US-42</th>
<th>Gestionar conductores</th>
<th>Como proveedor, quiero registrar y administrar los conductores de mi empresa para asignarlos correctamente a los despachos.</th>
<th><p>Escenario 1: Registro exitoso de conductor</p>
<p>Dado que el proveedor completa los datos del conductor (nombre, DNI, licencia),</p>
<p>Cuando guarda el registro,</p>
<p>Entonces el conductor queda disponible para ser asignado a pedidos.</p>
<p>Escenario 2: DNI duplicado</p>
<p>Dado que el proveedor intenta registrar un conductor con un DNI ya existente,</p>
<p>Cuando intenta guardar,</p>
<p>Entonces el sistema notifica que el conductor ya está registrado.</p>
<p>Escenario 3: Edición de datos de conductor</p>
<p>Dado que el proveedor actualiza los datos de un conductor existente,</p>
<p>Cuando guarda los cambios,</p>
<p>Entonces la información se actualiza correctamente en el sistema.</p></th>
<th>EP08</th>
</tr>
<tr class="odd">
<th>US-43</th>
<th>Gestionar inventario de combustibles</th>
<th>Como proveedor, quiero registrar, editar y eliminar los productos de combustible de mi catálogo para que estén disponibles como opciones al crear un pedido.</th>
<th><p>Escenario 1: Registro y visualización de productos en el inventario</p>
<p>Dado que el proveedor accede al módulo de inventario y completa los campos requeridos del formulario de producto (nombre, tipo de combustible, precio por litro y unidad),</p>
<p>Cuando guarda el registro,</p>
<p>Entonces el producto aparece listado en el inventario con su información completa y queda disponible para ser referenciado en nuevos pedidos.</p>
<p>Escenario 2: Edición y eliminación de un producto existente</p>
<p>Dado que el proveedor selecciona un producto ya registrado en el inventario,</p>
<p>Cuando actualiza sus datos o confirma su eliminación,</p>
<p>Entonces los cambios se reflejan de inmediato en el listado y el producto editado o eliminado no genera inconsistencias en pedidos en curso.</p></th>
<th>EP16</th>
</tr>
<tr class="header">
<th>US-44</th>
<th>Ver Dashboard principal del proveedor</th>
<th>Como proveedor, quiero acceder a un panel principal con KPIs de operación y un gráfico de tendencia de ventas para tener visibilidad en tiempo real del estado de mi negocio.</th>
<th><p>Escenario 1: Visualización de KPIs y gráfico de tendencia</p>
<p>Dado que el proveedor accede al dashboard principal,</p>
<p>Cuando se cargan los datos del periodo activo,</p>
<p>Entonces visualiza las tarjetas de KPIs (combustible total vendido, pedidos pendientes) y un gráfico de tendencia con opción de filtrar por vista diaria, semanal o mensual.</p>
<p>Escenario 2: Navegación desde el dashboard hacia otras secciones</p>
<p>Dado que el proveedor revisa el panel principal y desea profundizar en un indicador,</p>
<p>Cuando selecciona el acceso directo a pedidos activos o al módulo de reportes,</p>
<p>Entonces es redirigido a la vista correspondiente sin perder el contexto de sesión.</p></th>
<th>EP05</th>
</tr>
<tr class="odd">
<th>US-45</th>
<th>Ver distribución de ventas por sector</th>
<th>Como proveedor, quiero ver la distribución de mis ventas por sector industrial para identificar cuáles son mis clientes más relevantes por rubro.</th>
<th><p>Escenario 1: Visualización de distribución con datos disponibles</p>
<p>Dado que el proveedor accede al módulo de reportes de clientes,</p>
<p>Cuando existen ventas registradas en más de un sector industrial,</p>
<p>Entonces el sistema muestra un gráfico de barras con el volumen y porcentaje de participación por sector.</p>
<p>Escenario 2: Sin distribución por sector disponible</p>
<p>Dado que el proveedor aún no tiene ventas registradas o todos sus clientes pertenecen al mismo sector,</p>
<p>Cuando accede a la sección de distribución,</p>
<p>Entonces el sistema muestra un mensaje indicando que no hay datos suficientes para mostrar la distribución.</p></th>
<th>EP14</th>
</tr>
<tr class="header">
<th>US-46</th>
<th>Asignar recursos a despacho</th>
<th>Como proveedor, quiero asignar un vehículo y un conductor a un pedido aprobado en una sola operación para agilizar la preparación del despacho.</th>
<th><p>Escenario 1: Asignación exitosa de recursos al despacho</p>
<p>Dado que el proveedor selecciona un pedido aprobado y elige un vehículo y conductor disponibles,</p>
<p>Cuando confirma la asignación,</p>
<p>Entonces ambos recursos quedan vinculados al pedido y el despacho queda registrado con estado "Asignado".</p>
<p>Escenario 2: Recursos no disponibles para la fecha del pedido</p>
<p>Dado que el proveedor intenta asignar recursos a un pedido y tanto el vehículo como el conductor seleccionados ya tienen compromisos en esa fecha,</p>
<p>Cuando ejecuta la asignación,</p>
<p>Entonces el sistema muestra cuáles recursos están en conflicto e impide completar la operación.</p></th>
<th>EP08</th>
</tr>
<tr class="odd">
<th>TS-01</th>
<th>Endpoint: Login</th>
<th>Como developer, quiero un endpoint para autenticar usuarios.</th>
<th><p>Escenario 1: Autenticación exitosa</p>
<p>Dado que el developer incluye credenciales válidas en el request,</p>
<p>Cuando lo envía al endpoint de autenticación,</p>
<p>Entonces recibe un token JWT y un status 200 como respuesta.</p>
<p>Escenario 2: Credenciales inválidas</p>
<p>Dado que el developer incluye credenciales incorrectas en el request,</p>
<p>Cuando se procesa la solicitud,</p>
<p>Entonces se retorna status 401 con un mensaje de error.</p>
<p>Escenario 3: Error interno del servidor</p>
<p>Dado que el developer realiza un request y ocurre un problema en el backend,</p>
<p>Cuando se procesa la autenticación,</p>
<p>Entonces se retorna status 500 con un mensaje genérico de error.</p></th>
<th>EP06</th>
</tr>
<tr class="header">
<th>TS-02</th>
<th>Endpoint: Recuperar contraseña</th>
<th>Como developer, quiero un endpoint para que permita enviar correo de recuperación.</th>
<th><p>Escenario 1: Solicitud válida</p>
<p>Dado que el developer envía un request con un correo que existe en la base de datos,</p>
<p>Cuando el request llega al endpoint de recuperación,</p>
<p>Entonces el sistema genera un token y envía el correo de recuperación.</p>
<p>Escenario 2: Correo inexistente</p>
<p>Dado que el developer envía un request con un correo no registrado,</p>
<p>Cuando se procesa la solicitud,</p>
<p>Entonces se retorna status 404 y no se envía ningún correo.</p>
<p>Escenario 3: Error en el envío del correo</p>
<p>Dado que el developer ejecuta la acción y ocurre un fallo en el servicio de correo,</p>
<p>Cuando se intenta enviar el mensaje,</p>
<p>Entonces se retorna status 500 y se registra el error en los logs del servidor.</p></th>
<th>EP06</th>
</tr>
<tr class="odd">
<th>TS-03</th>
<th>Endpoint: Logout</th>
<th>Como developer, quiero un endpoint para cerrar sesión.</th>
<th><p>Escenario 1: Logout exitoso</p>
<p>Dado que el developer envía un token de sesión válido,</p>
<p>Cuando llama al endpoint de logout,</p>
<p>Entonces la sesión se invalida y se retorna status 200.</p>
<p>Escenario 2: Token inválido o expirado</p>
<p>Dado que el developer incluye un token no válido o expirado,</p>
<p>Cuando se llama al endpoint de logout,</p>
<p>Entonces se retorna status 401 y no se realiza ninguna acción.</p>
<p>Escenario 3: Falla del servidor</p>
<p>Dado que el developer realiza un request y ocurre un error interno en el servidor,</p>
<p>Cuando se procesa el logout,</p>
<p>Entonces se retorna status 500 con un mensaje genérico.</p></th>
<th>EP06</th>
</tr>
<tr class="header">
<th>TS-04</th>
<th>Endpoint: Crear pedido</th>
<th>Como developer, quiero un endpoint para registrar un nuevo pedido de combustible.</th>
<th><p>Escenario 1: Petición con datos completos</p>
<p>Dado que el developer envía una petición con todos los campos requeridos,</p>
<p>Cuando se procesa el POST,</p>
<p>Entonces se retorna status 201 con el ID del nuevo pedido.</p>
<p>Escenario 2: Petición incompleta</p>
<p>Dado que el developer envía una petición con campos obligatorios faltantes,</p>
<p>Cuando se procesa la solicitud,</p>
<p>Entonces se retorna status 400 con un mensaje de validación.</p></th>
<th>EP07</th>
</tr>
<tr class="odd">
<th>TS-05</th>
<th>Endpoint: Consultar pedidos por usuario</th>
<th>Como developer, quiero un endpoint para obtener todos los pedidos de un usuario.</th>
<th><p>Escenario 1: Usuario con pedidos registrados</p>
<p>Dado que el usuario tiene pedidos en el sistema,</p>
<p>Cuando se llama al endpoint,</p>
<p>Entonces retorna un array con sus pedidos y status 200.</p>
<p>Escenario 2: Usuario sin pedidos</p>
<p>Dado que el usuario no ha realizado pedidos,</p>
<p>Cuando se ejecuta la solicitud,</p>
<p>Entonces retorna un array vacío con status 200.</p></th>
<th>EP07</th>
</tr>
<tr class="header">
<th>TS-06</th>
<th>Endpoint: Registro de usuario</th>
<th>Como developer, quiero un endpoint para registrar nuevos usuarios en la plataforma (sign-up).</th>
<th>Ver especificación del endpoint de registro de usuarios.</th>
<th>EP08</th>
</tr>
<tr class="odd">
<th>TS-07</th>
<th>Endpoint: Consultar usuarios</th>
<th>Como developer, quiero endpoints para listar todos los usuarios y consultar uno por su ID.</th>
<th>Ver especificación de consulta de usuarios.</th>
<th>EP08</th>
</tr>
<tr class="header">
<th>TS-08</th>
<th>Endpoint: CRUD de empresas compradoras</th>
<th>Como developer, quiero endpoints para registrar, listar, consultar y actualizar empresas compradoras.</th>
<th>Ver especificación CRUD de buyer companies.</th>
<th>EP08</th>
</tr>
<tr class="odd">
<th>TS-09</th>
<th>Endpoint: CRUD de empresas proveedoras</th>
<th>Como developer, quiero endpoints para registrar, listar, consultar y actualizar empresas proveedoras.</th>
<th>Ver especificación CRUD de provider companies.</th>
<th>EP08</th>
</tr>
<tr class="header">
<th>TS-10</th>
<th>Endpoint: Actualizar perfil de usuario</th>
<th>Como developer, quiero un endpoint para que un usuario autenticado actualice los datos de su propio perfil.</th>
<th>Ver especificación de actualización de perfil.</th>
<th>EP08</th>
</tr>
<tr class="odd">
<th>TS-11</th>
<th>Endpoint: CRUD de productos de combustible</th>
<th>Como developer, quiero endpoints para crear, listar, consultar, actualizar y eliminar productos de combustible.</th>
<th>Ver especificación CRUD de productos.</th>
<th>EP09</th>
</tr>
<tr class="header">
<th>TS-12</th>
<th>Endpoint: Actualizar stock de producto</th>
<th>Como developer, quiero un endpoint para actualizar el stock disponible de un producto de combustible.</th>
<th>Ver especificación de actualización de stock.</th>
<th>EP09</th>
</tr>
<tr class="odd">
<th>TS-13</th>
<th>Endpoint: Consultar pedidos</th>
<th>Como developer, quiero endpoints para listar todos los pedidos y consultarlos por ID, por empresa compradora y por proveedor.</th>
<th><p>Escenario 1: Consulta exitosa por ID</p>
<p>Dado que el developer envía un ID de pedido existente,</p>
<p>Cuando se llama al endpoint de consulta,</p>
<p>Entonces se retorna el pedido correspondiente con status 200.</p>
<p>Escenario 2: Consulta por empresa compradora o proveedor</p>
<p>Dado que el developer envía el identificador de una empresa compradora o proveedora,</p>
<p>Cuando se ejecuta la solicitud,</p>
<p>Entonces se retorna un array con los pedidos asociados y status 200.</p>
<p>Escenario 3: Pedido no encontrado</p>
<p>Dado que el developer envía un ID que no corresponde a ningún pedido registrado,</p>
<p>Cuando se procesa la solicitud,</p>
<p>Entonces se retorna status 404 con un mensaje de error.</p></th>
<th>EP07</th>
</tr>
<tr class="header">
<th>TS-14</th>
<th>Endpoint: Confirmar / cancelar pedido</th>
<th>Como developer, quiero endpoints para confirmar o cancelar un pedido existente.</th>
<th><p>Escenario 1: Confirmación exitosa del pedido</p>
<p>Dado que el developer envía una solicitud de confirmación sobre un pedido válido,</p>
<p>Cuando se procesa el request,</p>
<p>Entonces el estado del pedido cambia a confirmado y se retorna status 200.</p>
<p>Escenario 2: Cancelación exitosa del pedido</p>
<p>Dado que el developer envía una solicitud de cancelación sobre un pedido que aún puede cancelarse,</p>
<p>Cuando se procesa el request,</p>
<p>Entonces el estado del pedido cambia a cancelado y se retorna status 200.</p>
<p>Escenario 3: Intento de acción sobre pedido ya cerrado</p>
<p>Dado que el developer intenta confirmar o cancelar un pedido que ya fue cerrado o cancelado previamente,</p>
<p>Cuando se procesa la solicitud,</p>
<p>Entonces se retorna status 400 con un mensaje indicando que la acción no es válida para el estado actual.</p></th>
<th>EP07</th>
</tr>
<tr class="odd">
<th>TS-15</th>
<th>Endpoint: Solicitudes de combustible</th>
<th>Como developer, quiero endpoints para crear, listar, aceptar y rechazar solicitudes de combustible.</th>
<th>Ver especificación de fuel requests.</th>
<th>EP10</th>
</tr>
<tr class="header">
<th>TS-16</th>
<th>Endpoint: Consultar solicitud por ID</th>
<th>Como developer, quiero un endpoint para consultar el detalle de una solicitud de combustible específica.</th>
<th>Ver especificación de consulta de solicitud.</th>
<th>EP10</th>
</tr>
<tr class="odd">
<th>TS-17</th>
<th>Endpoint: Gestión de entregas</th>
<th>Como developer, quiero endpoints para crear, despachar, completar, marcar como fallida y consultar entregas.</th>
<th>Ver especificación de entregas.</th>
<th>EP10</th>
</tr>
<tr class="header">
<th>TS-18</th>
<th>Endpoint: CRUD de conductores</th>
<th>Como developer, quiero endpoints para registrar, consultar, actualizar y eliminar conductores</th>
<th>Ver especificación CRUD de conductores.</th>
<th>EP10</th>
</tr>
<tr class="odd">
<th>TS-19</th>
<th>Endpoint: CRUD de vehículos</th>
<th>Como developer, quiero endpoints para registrar, consultar, actualizar y eliminar vehículos.</th>
<th>Ver especificación CRUD de vehículos.</th>
<th>EP10</th>
</tr>
<tr class="header">
<th>TS-20</th>
<th>Endpoint: Registrar y procesar pagos</th>
<th>Como developer, quiero endpoints para registrar pagos, completarlos y procesar reembolsos.</th>
<th>Ver especificación de pagos.</th>
<th>EP11</th>
</tr>
<tr class="odd">
<th>TS-21</th>
<th>Endpoint: Consultar pagos</th>
<th>Como developer, quiero endpoints para consultar pagos por distintos criterios.</th>
<th>Ver especificación de consultas de pago.</th>
<th>EP11</th>
</tr>
<tr class="header">
<th>TS-22</th>
<th>Endpoint: Calificaciones de proveedores</th>
<th>Como developer, quiero endpoints para crear, listar y actualizar calificaciones de proveedores.</th>
<th>Ver especificación de provider ratings.</th>
<th>EP12</th>
</tr>
<tr class="odd">
<th>TS-23</th>
<th>Endpoint: Gestión de equipos</th>
<th>Como developer, quiero endpoints para registrar, actualizar, listar y consultar equipos.</th>
<th>Ver especificación de equipos.</th>
<th>EP12</th>
</tr>
<tr class="header">
<th>TS-24</th>
<th>Endpoint: Asignar proveedor favorito</th>
<th>Como developer, quiero un endpoint para asignar un proveedor favorito a un equipo.</th>
<th>Ver especificación de proveedor favorito.</th>
<th>EP12</th>
</tr>
<tr class="odd">
<th>TS-25</th>
<th>Endpoint: Eliminar equipo</th>
<th>Como developer, quiero un endpoint para eliminar un equipo registrado.</th>
<th>Ver especificación de eliminación de equipos.</th>
<th>EP12</th>
</tr>
<tr class="header">
<th>TS-26</th>
<th>Endpoint: Sistema de notificaciones</th>
<th>Como developer, quiero endpoints para crear, consultar y marcar notificaciones como leídas.</th>
<th>Ver especificación de notificaciones.</th>
<th>EP13</th>
</tr>
<tr class="odd">
<th>TS-27</th>
<th>Endpoint: Reportes y analítica</th>
<th>Como developer, quiero endpoints para obtener indicadores y estadísticas de la plataforma.</th>
<th>Ver especificación de analítica.</th>
<th>EP14</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.3 Impact Map

En el Impact Mapping del modelo de negocio digital de FuelBridge, desarrollado por la startup HaloFuel, el equipo elaboró el mapa partiendo de un Business Goal principal que cumple los criterios SMART: “Optimizar la gestión y distribución de combustible, alcanzando 300 empresas solicitantes activas y 100 proveedores registrados en el primer año de operación, reduciendo en un 40% los tiempos de gestión de pedidos”. A partir de esta meta se incorporaron como Actors/Personas a los User Personas previamente definidos: Carlos Ramírez (empresa solicitante) y Andrea López (proveedora de combustible). Para cada uno se identificaron los Impacts esperados, es decir, cómo se busca cambiar su comportamiento para lograr el objetivo: en el caso de Carlos, la digitalización del registro de pedidos, la reducción de la dependencia de canales informales, el seguimiento en tiempo real y una mejor toma de decisiones basada en datos; en el caso de Andrea, la centralización de pedidos, la optimización de la planificación logística, la mejora en la comunicación con clientes y el uso de métricas para el control operativo.

A partir de estos impactos se definieron los Deliverables que la plataforma FuelBridge debe ofrecer para generar dichos cambios en los actores. Entre ellos se incluyen el módulo de registro y gestión de pedidos, el sistema de tracking en tiempo real, el panel de control con métricas operativas, la planificación logística automatizada, el historial de pedidos y el sistema de notificaciones y comunicación integrada. Finalmente, en la columna de User Stories se detallaron historias en formato “Como \[persona\] deseo \[acción\] para \[beneficio\]” (por ejemplo, registro de pedidos, consulta de estado, actualización de entregas, coordinación logística y generación de reportes), lo que permite trazar una línea clara desde los objetivos de negocio hasta las funcionalidades del sistema, asegurando la alineación entre Business Goals, Impacts, Deliverables y el desarrollo de la solución.

<div align="center">
  <img src="../assets/chapter-3/image23.png" width="700" />
</div>

## 3.4 Product Backlog

| **\#Orden** | **ID** | **Título**                                 | **Descripción**                                                                                                                                                                    | **Story Points** |
|-------------|--------|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|
| **01**      | US-05  | Registrar nuevo pedido                     | Como solicitante, quiero registrar un pedido con tipo y cantidad de combustible para que el proveedor lo procese.                                                                  | **5**            |
| **02**      | US-06  | Consultar estado del pedido                | Como solicitante, quiero ver el estado de mis pedidos para saber si están aprobados, en tránsito o entregados.                                                                     | **2**            |
| **03**      | US-08  | Registrar información de pago              | Como solicitante, quiero ingresar la información de los pagos correspondientes para validar el pedido ante el proveedor.                                                           | **3**            |
| **04**      | US-07  | Confirmar recepción de pedido              | Como solicitante, quiero confirmar que recibí el pedido para que el proveedor lo cierre.                                                                                           | **2**            |
| **05**      | US-09  | Ver historial de pedidos                   | Como solicitante, quiero ver mis pedidos anteriores para tener control sobre mi consumo.                                                                                           | **2**            |
| **06**      | US-43  | Ver detalle de pedido                      | Como usuario de ambos segmentos, quiero ver el detalle completo de un pedido para revisar toda la información asociada.                                                            | **2**            |
| **07**      | US-10  | Ver pedidos pendientes                     | Como proveedor, quiero ver todos los pedidos pendientes para analizarlos y tomar acción.                                                                                           | **2**            |
| **08**      | US-11  | Aprobar pedido                             | Como proveedor, quiero aprobar pedidos según los depósitos hechos a mis cuentas bancarias.                                                                                         | **3**            |
| **09**      | US-42  | Rechazar pedido                            | Como proveedor, quiero rechazar un pedido cuando no pueda atenderlo para notificar al solicitante oportunamente.                                                                   | **2**            |
| **10**      | US-12  | Marcar pedido como despachado              | Como proveedor, quiero marcar cuándo un pedido sale a entrega para notificar al cliente.                                                                                           | **2**            |
| **11**      | US-13  | Cerrar pedido                              | Como proveedor, quiero cerrar el pedido cuando el cliente confirme la entrega para finalizar el proceso.                                                                           | **2**            |
| **12**      | US-14  | Generar reporte de ventas                  | Como proveedor, quiero generar reportes de ventas para tener registro de operaciones realizadas.                                                                                   | **3**            |
| **13**      | US-46  | Gestionar inventario de combustibles       | Como proveedor, quiero registrar, editar y eliminar los productos de combustible de mi catálogo para que estén disponibles como opciones al crear un pedido.                       | **3**            |
| **14**      | US-44  | Gestionar vehículos de flota               | Como proveedor, quiero registrar y administrar los vehículos de mi flota para tenerlos disponibles al asignarlos a pedidos.                                                        | **3**            |
| **15**      | US-45  | Gestionar conductores                      | Como proveedor, quiero registrar y administrar los conductores de mi empresa para asignarlos correctamente a los despachos.                                                        | **3**            |
| **16**      | US-49  | Asignar recursos a despacho                | Como proveedor, quiero asignar un vehículo y un conductor a un pedido aprobado en una sola operación para agilizar la preparación del despacho.                                    | **5**            |
| **17**      | US-22  | Validar disponibilidad de transporte       | Como proveedor, quiero saber qué vehículos están disponibles antes de asignarlos para vincularlos correctamente.                                                                   | **5**            |
| **18**      | US-18  | Ver resumen de pedidos (Solicitante)       | Como solicitante, quiero ver un resumen de mis pedidos para identificar cuántos están en proceso o completados.                                                                    | **3**            |
| **19**      | US-47  | Ver Dashboard principal del proveedor      | Como proveedor, quiero acceder a un panel principal con KPIs de operación y un gráfico de tendencia de ventas para tener visibilidad en tiempo real del estado de mi negocio.      | **3**            |
| **20**      | US-29  | Recibir notificación de aprobación         | Como solicitante, quiero recibir una notificación cuando un pedido sea aprobado o rechazado para estar informado.                                                                  | **2**            |
| **21**      | US-30  | Notificación de pedido despachado          | Como solicitante, quiero recibir una notificación cuando un pedido haya sido despachado para estar informado.                                                                      | **2**            |
| **22**      | US-27  | Buscar pedido por código                   | Como usuario de ambos segmentos, quiero buscar un pedido específico por su código para encontrarlo rápidamente.                                                                    | **2**            |
| **23**      | US-28  | Filtrar pedidos por estado                 | Como usuario de ambos segmentos, quiero filtrar mis pedidos por estado para facilitar la revisión.                                                                                 | **2**            |
| **24**      | US-31  | Ver listado de empresas                    | Como proveedor, quiero ver una lista de empresas solicitantes para identificar a mis clientes frecuentes.                                                                          | **2**            |
| **25**      | US-32  | Ver detalles de empresa                    | Como proveedor, quiero ver información detallada de una empresa solicitante para analizar su historial de pedidos.                                                                 | **2**            |
| **26**      | US-33  | Ver gráfico de consumo (Solicitante)       | Como solicitante, quiero ver un gráfico de mi consumo mensual para tener control sobre el uso del combustible.                                                                     | **3**            |
| **27**      | US-34  | Ver gráfico de ventas (Proveedor)          | Como proveedor, quiero ver un gráfico de ventas por mes para monitorear el rendimiento del negocio.                                                                                | **3**            |
| **28**      | US-48  | Ver distribución de ventas por sector      | Como proveedor, quiero ver la distribución de mis ventas por sector industrial para identificar cuáles son mis clientes más relevantes por rubro.                                  | **2**            |
| **29**      | US-35  | Descargar reporte PDF                      | Como usuario de ambos segmentos, quiero descargar un resumen de pedidos o ventas en formato PDF para archivarlo o compartirlo.                                                     | **3**            |
| **30**      | US-01  | Ver sección Home                           | Como visitante (proveedor), quiero ver una sección de inicio que resuma el valor de FuelBridge para comprender rápidamente el objetivo del sistema.                                  | **2**            |
| **31**      | US-02  | Ver sección About Us                       | Como visitante de ambos segmentos, quiero conocer quiénes están detrás de FuelBridge para confiar en el sistema.                                                                     | **1**            |
| **32**      | US-03  | Ver sección How it works?                  | Como visitante de ambos segmentos, quiero entender cómo funciona FuelBridge paso a paso para evaluar si se ajusta a mis necesidades.                                                 | **2**            |
| **33**      | US-36  | Ver sección Benefits                       | Como visitante de ambos segmentos, quiero conocer las principales ventajas para evaluar la implementación de la plataforma.                                                        | **1**            |
| **34**      | US-37  | Ver sección Lo que Dicen Nuestros Clientes | Como visitante de ambos segmentos, quiero conocer los testimonios de usuarios de FuelBridge para tener confianza en la plataforma.                                                   | **2**            |
| **35**      | US-38  | Ver sección Planes y Precios               | Como visitante de ambos segmentos, quiero saber qué planes se adecuan a mis necesidades para poder iniciar un proceso de registro.                                                 | **3**            |
| **36**      | US-39  | Cambiar idioma                             | Como visitante de ambos segmentos, quiero poder cambiar entre inglés y español para entender la plataforma en mi idioma preferido.                                                 | **3**            |
| **37**      | US-04  | Enviar mensaje de contacto                 | Como visitante de ambos segmentos, quiero enviar un mensaje desde Contact Us para solicitar más información.                                                                       | **3**            |
| **38**      | US-23  | Ver perfil de usuario                      | Como usuario registrado, quiero ver mis datos de perfil para revisar mi información registrada.                                                                                    | **1**            |
| **39**      | US-24  | Editar datos de perfil                     | Como usuario registrado, quiero editar mis datos para mantener mi información actualizada.                                                                                         | **2**            |
| **40**      | US-25  | Ver sección de preguntas frecuentes        | Como visitante de ambos segmentos, quiero acceder a una sección de preguntas frecuentes para resolver dudas rápidamente.                                                           | **2**            |
| **41**      | US-26  | Acceder a información de contacto rápido   | Como usuario de ambos segmentos, quiero ver datos de contacto directo (teléfono o correo) para hacer consultas urgentes.                                                           | **1**            |
| **42**      | US-40  | Registrar empresa solicitante              | Como visitante (solicitante), quiero registrar mi empresa en la plataforma para comenzar a realizar pedidos de combustible.                                                        | **3**            |
| **43**      | US-41  | Registrar empresa proveedora               | Como visitante (proveedor), quiero registrar mi empresa distribuidora en la plataforma para comenzar a gestionar pedidos de combustible.                                           | **3**            |
| **44**      | US-15  | Iniciar sesión                             | Como usuario registrado, quiero iniciar sesión con correo y contraseña para acceder a mi cuenta.                                                                                   | **2**            |
| **45**      | US-16  | Recuperar contraseña                       | Como usuario registrado, quiero recuperar mi contraseña para volver a acceder si la olvidé.                                                                                        | **2**            |
| **46**      | US-17  | Cerrar sesión                              | Como usuario registrado, quiero poder cerrar sesión para mantener segura mi cuenta.                                                                                                | **1**            |
| **47**      | TS-01  | Endpoint: Login                            | Como developer, quiero un endpoint para autenticar usuarios.                                                                                                                       | **2**            |
| **48**      | TS-02  | Endpoint: Recuperar contraseña             | Como developer, quiero un endpoint que permita enviar correo de recuperación.                                                                                                      | **2**            |
| **49**      | TS-03  | Endpoint: Logout                           | Como developer, quiero un endpoint para cerrar sesión.                                                                                                                             | **1**            |
| **50**      | TS-04  | Endpoint: Crear pedido                     | Como developer, quiero un endpoint para registrar un nuevo pedido de combustible.                                                                                                  | **3**            |
| **51**      | TS-05  | Endpoint: Consultar pedidos por usuario    | Como developer, quiero un endpoint para obtener todos los pedidos de un usuario.                                                                                                   | **2**            |
| **52**      | TS-06  | Endpoint: Registro de usuario              | Como developer, quiero un endpoint para registrar nuevos usuarios en la plataforma (sign-up).                                                                                      | **3**            |
| **53**      | TS-07  | Endpoint: Consultar usuarios               | Como developer, quiero endpoints para listar todos los usuarios y consultar uno por su ID.                                                                                         | **5**            |
| **54**      | TS-08  | Endpoint: CRUD de empresas compradoras     | Como developer, quiero endpoints para registrar, listar, consultar y actualizar empresas compradoras (buyer companies).                                                            | **5**            |
| **55**      | TS-09  | Endpoint: CRUD de empresas proveedoras     | Como developer, quiero endpoints para registrar, listar, consultar y actualizar empresas proveedoras (provider companies).                                                         | **3**            |
| **56**      | TS-10  | Endpoint: Actualizar perfil de usuario     | Como developer, quiero un endpoint para que un usuario autenticado actualice los datos de su propio perfil.                                                                        | **5**            |
| **57**      | TS-11  | Endpoint: CRUD de productos de combustible | Como developer, quiero endpoints para crear, listar, consultar (por ID y por proveedor), actualizar y eliminar productos de combustible.                                           | **2**            |
| **58**      | TS-12  | Endpoint: Actualizar stock de producto     | Como developer, quiero un endpoint para actualizar el stock disponible de un producto de combustible.                                                                              | **3**            |
| **59**      | TS-13  | Endpoint: Consultar pedidos                | Como developer, quiero endpoints para listar todos los pedidos y consultarlos por ID, por empresa compradora y por proveedor.                                                      | **3**            |
| **60**      | TS-14  | Endpoint: Confirmar / cancelar pedido      | Como developer, quiero endpoints para confirmar o cancelar un pedido existente.                                                                                                    | **5**            |
| **61**      | TS-15  | Endpoint: Solicitudes de combustible       | Como developer, quiero endpoints para crear, listar, aceptar y rechazar solicitudes de combustible (fuel requests).                                                                | **2**            |
| **62**      | TS-16  | Endpoint: Consultar solicitud por ID       | Como developer, quiero un endpoint para consultar el detalle de una solicitud de combustible específica.                                                                           | **5**            |
| **63**      | TS-17  | Endpoint: Gestión de entregas              | Como developer, quiero endpoints para crear, despachar, completar, marcar como fallida y consultar entregas (todas, por ID, por proveedor y por pedido).                           | **5**            |
| **64**      | TS-18  | Endpoint: CRUD de conductores              | Como developer, quiero endpoints para registrar, listar por proveedor, consultar, actualizar y eliminar conductores.                                                               | **5**            |
| **65**      | TS-19  | Endpoint: CRUD de vehículos                | Como developer, quiero endpoints para registrar, listar por proveedor, consultar, actualizar y eliminar vehículos.                                                                 | **3**            |
| **66**      | TS-20  | Endpoint: Registrar y procesar pagos       | Como developer, quiero endpoints para registrar un pago, marcarlo como completado y procesar su reembolso.                                                                         | **3**            |
| **67**      | TS-21  | Endpoint: Consultar pagos                  | Como developer, quiero endpoints para listar todos los pagos y consultarlos por ID, por pedido y por empresa.                                                                      | **3**            |
| **68**      | TS-22  | Endpoint: Calificaciones de proveedores    | Como developer, quiero endpoints para crear, listar y actualizar calificaciones de proveedores.                                                                                    | **5**            |
| **69**      | TS-23  | Endpoint: Gestión de equipos               | Como developer, quiero endpoints para registrar, actualizar, listar y consultar equipos (por ID y por empresa).                                                                    | **2**            |
| **70**      | TS-24  | Endpoint: Asignar proveedor favorito       | Como developer, quiero un endpoint para asignar un proveedor favorito a un equipo.                                                                                                 | **2**            |
| **71**      | TS-25  | Endpoint: Eliminar equipo                  | Como developer, quiero un endpoint para eliminar un equipo registrado.                                                                                                             | **5**            |
| **72**      | TS-26  | Endpoint: Sistema de notificaciones        | Como developer, quiero endpoints para crear notificaciones, marcarlas como leídas y consultarlas por usuario, por empresa compradora, por proveedor y las no leídas de un usuario. | **5**            |
| **73**      | TS-27  | Endpoint: Reportes y analítica             | Como developer, quiero endpoints para obtener el resumen general de la plataforma y la analítica de un proveedor o comprador específico.                                           | **5**            |

<div align="center">
  <img src="../assets/chapter-3/image8.png" width="700" />
</div>

Link del Trello: **[https://trello.com/invite/b/69e2fd01ee5b055b2d967a45/ATTI05a9ebca4c1da02108fc92fa76bfa07e412172F6/fulltank](https://trello.com/invite/b/69e2fd01ee5b055b2d967a45/ATTI05a9ebca4c1da02108fc92fa76bfa07e412172F6/fulltank)**

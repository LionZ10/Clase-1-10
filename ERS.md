# Especificación de Requerimientos de Software (ERS)
**Proyecto:** App de Mensajería Instantánea | **Estándar:** IEEE 830-1998
**Autor/a:** Lionel Sanchez

## 1. Introducción
El presente documento define los requerimientos para el desarrollo de la aplicación.

## 2. Glosario de Términos
* **Cifrado punto a punto:** Método de seguridad que evita la lectura de mensajes por terceros.
* **Notificación Push:** Mensaje de alerta enviado al dispositivo del usuario.
* **Copia de seguridad:** Respaldo de los chats y archivos del usuario almacenado en servidores en la nube.
* **Confirmación de lectura:** Indicador visual que muestra al usuario emisor que el usuario receptor ha leído el mensaje.

## 3. Requerimientos Funcionales (El QUÉ)
* **RF01:** El sistema debe permitir registrar usuarios mediante número telefónico.
* **RF02:** El sistema debe permitir enviar mensajes de texto en chats individuales.
* **RF03:** El sistema debe permitir eliminar mensajes previamente enviados.
* **RF04:** El sistema debe permitir la creación de grupos de chat para más usuarios.
* **RF05:** El sistema debe permitir adjuntar y enviar archivos (imágenes, videos, etc).
* **RF06:** El sistema debe permitir al usuario bloquear contactos para impedir la comunicación del usuario bloqueado

## 4. Requerimientos No Funcionales (El CÓMO)
* **RNF01 (Seguridad):** Los mensajes deben almacenarse encriptados en la base de datos.
* **RNF02 (Rendimiento):** El tiempo de envío de mensajes debe ser menor a 2 segundos.
* **RNF03 (Seguridad):** Si el usuario cambia de dispositivo, la sesión del dispositivo anterior se tiene que cerrar automáticamente.
* **RNF04 (Tiempo):** El tiempo de carga de la pantalla principal con la lista de chats al iniciar la aplicación no debe superar los 3 segundos.

## 5. Requerimientos de Dominio
* **RD01:** La aplicación necesita sí o sí una conexión a internet activa para funcionar.
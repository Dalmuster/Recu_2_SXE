# Recu_2_SXE

#OWNCLOUD

![imagen](https://github.com/user-attachments/assets/0bd60c1c-4716-477a-ba09-459bd895a482)

![imagen](https://github.com/user-attachments/assets/346bb0ac-0b65-4274-84e7-95f0e14a5ed3)

#ADMINER

![imagen](https://github.com/user-attachments/assets/11d61d29-1a9e-471d-afd0-5f123cf65e4d)

![imagen](https://github.com/user-attachments/assets/63ef1e2c-c0b8-4b2c-afa7-bdad67c7ab29)

-1. Si ejecutas un contenedor con el siguiente comando: docker run -it alpine, ¿qué sucederá cuando salgas de la sesión interactiva del contenedor? ¿Por qué el contenedor se detiene automáticamente?

El contenedor se detendra cuando salgas de la sesion, se detiene automaticamente por las opciones -it.

2. Si lanzas un contenedor de Docker sin usar volúmenes ni “bind mount”, y luego haces cambios dentro del contenedor (como crear archivos o carpetas), ¿se mantendrán esos cambios cuando detengas el contenedor y lo vuelvas a arrancar? ¿Por qué?

No se mantendran dado que no tiene donde guardar los cambios.

3. Si ejecutas docker run -p 8090:79 httpd (imagen httpd) E intentas acceder con el navegador a: <Dirección-ip del anfitrión del contenedor>:8080 ¿Qué sucederá?¿Por qué?

No conseguira acceder dado que las ips son diferentes.

# examen
Ejecutar el comando en PowerShell
Abre PowerShell como administrador

Pulsa Win + X y selecciona PowerShell (Admin) o Terminal (Admin).
Ejecuta el siguiente comando:

powershell
Copiar
Editar
Enable-WindowsOptionalFeature -Online -FeatureName $("Microsoft-Hyper-V", "Containers") -All
Confirma la instalación
Si el sistema te pide confirmación, escribe Y y presiona Enter.
Paso 2: Reiniciar la computadora
Después de ejecutar el comando, reinicia tu PC para que los cambios surtan efecto.
![Imagen de WhatsApp 2025-02-20 a las 09 52 55_64fddf89](https://github.com/user-attachments/assets/a2b8c838-5f24-4303-afe0-cc65edac85c2)
para que pueda descargar la imagen debemos cambiar los contenedor de linux a windows en nuestro docker pero al hacerlo tenemos que iniciar otra vez el mismo proceso,una vez eso tarda y pesa 4Gig

*Descargar y ejecutar el contenedor de IIS
Ahora vamos a instalar y ejecutar IIS dentro de un contenedor.

Descargar la imagen de IIS
Abre PowerShell o CMD y escribe:

powershell
Copiar
Editar
docker pull mcr.microsoft.com/windows/servercore/iis
Esto descargará la imagen oficial de IIS basada en Windows Server Core.
![image](https://github.com/user-attachments/assets/f40e6fd0-a232-4f16-8d87-7ebfa2d5a903)

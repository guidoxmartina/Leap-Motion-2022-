# Leap-Motion-2022-



Usando la version [V2](https://drive.google.com/file/d/1mdqdSRl7GCfDIMR5I8fk5hmJNTLVyDIW/view?usp=sharing)<br> https://developer.leapmotion.com/legacy-v2/ <br>

siguiendo [este](https://forums.leapmotion.com/t/resolved-windows-10-fall-creators-update-bugfix/6585/14) posteo <br>
```
-Open up services.msc and pause or stop LeapService<br>
-Navigate to your Leap Motion software installation folder and go to the Core Services folder (default C:\Program Files (x86)\Leap Motion\Core Services)<br>
-Backup LeapSvc.exe and LeapSvc64.exe in a separate folder<br>
-For V2 users, download and unzip this file5.7k into the Core Services folder, replacing LeapSvc.exe and LeapSvc64.exe<br>

-Return to services.msc and restart LeapService<br>
-Launch a Leap Motion enabled application and test!<br>

Si sigue apareciendo como desconectado se puede solucionar asi :<br>
 - @DARKKi did it show the red 'Disconnected' indicator in diagnostics?

If so, running this worked for me after reinstalling Leap Motion Control Panel: C:\Program Files (x86)\Leap Motion\Core Services\Drivers\dpinst64.exe
<br>

For me this was solved by reinstalling the drivers (instead of editing the hexes), i.e:

C:\Program Files (x86)\Leap Motion\Core Services\Drivers\cyfx3.inf
and

C:\Program Files (x86)\Leap Motion\Core Services\Drivers\ov580.inf
rightclick each file and choose install.

Don't know how persistent that is but got rid of the red "disconnected" anyways and my leap motion works like before now
```
## Usar mano como mouse
![image](https://user-images.githubusercontent.com/48781895/185792397-4c88650b-e4fd-4ca1-90ec-317344899306.png)

con [este](https://uwyn.com/gamewave/) software podemos mapear todos los movimientos que detecta el leap
<br>



### Agregar una aplicación para que se ejecute automáticamente al inicio en Windows 10

```
Selecciona el botón Inicio  y desplázate hasta encontrar la aplicación que quieras ejecutar en el inicio.

Haz clic con el botón derecho en la aplicación, selecciona Más y después Abrir ubicación del archivo. Esto abre la ubicación donde se guarda el acceso directo a la aplicación. Si no existe una opción de Abrir ubicación del archivo, eso significa que la aplicación no se puede ejecutar en el inicio.

Con la ubicación del archivo abierta, presiona la tecla del logotipo de Windows  + R, escribe shell:startup y luego selecciona Aceptar. Esto hará que se abra la carpeta Inicio.

Copia y pega el acceso directo a la aplicación desde la ubicación del archivo a la carpeta Inicio.
```

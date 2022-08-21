# Leap-Motion-2022-



Usando la version https://developer.leapmotion.com/legacy-v2/ <br>

siguiendo este posteo https://forums.leapmotion.com/t/resolved-windows-10-fall-creators-update-bugfix/6585/14<br>

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

#Usar mano como mouse

https://uwyn.com/gamewave/<br>

https://gallery.leapmotion.com/handwave/

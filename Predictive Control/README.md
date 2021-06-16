Para poder ejecutar la simulación:

1. En configuración de simulación (ctrl + e), en initial step size borre "auto" y luego "apply", 
   luego volver a poner "auto" y seguidamente "apply".

2. Los componentes "MPC" y "Microcontroller" son componentes personalizados, para poder usarlos
   vaya a file >  plecs preference > Libraries. En search path vayan hasta la carpeta "Custom LIbrary" y lo abren 
   y en User Library ponen el archivo de "Controller_lib.plecs".

3. Si aún así tira error, quitan el componente del error y
   abran la librería (crtl+L) y ahí estan los componentes personalizados y
   solo los reemplazan por el mismo. 	

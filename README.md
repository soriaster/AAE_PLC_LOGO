# AAE_PLC_LOGO
Controlador de Alimentador Automático desarrollado en PLC Logo de Siemens

Controlador desarrollado para PLC Logo de Siemens, que permite el seteo de tiempos de Actividad e Inactividad para alimentar camarones. 
Este sietema fue probado en una Camaronera Ecuatoriana, dando excelentes resultados.

El sistema cuenta con 3 ciclos de activación dado un horario de operación.
Ej:
      Horario de operación -> 8:00 - 19:00, parámetro que se dividirá en 3 subhorarios
      
      Subhorario_1 -> 08:00 - 11:00, parámetro que es seteado en el menu del sistema
        Tiempo de activación -> Ton -> 10 [s], parámetro que es seteado en el menu del sistema
        Tiempo de desactivación -> Toff -> 30 [min], parámetro que es seteado en el menu del sistema
        
      Subhorario_2 -> 11:00 - 16:00
        Tiempo de activación -> Ton -> 7 [s], parámetro que es seteado en el menu del sistema
        Tiempo de desactivación -> Toff ->20 [min], parámetro que es seteado en el menu del sistema
        
      Subhorario_3 -> 16:00 - 19:00
        Tiempo de activación -> Ton -> 10 [s], parámetro que es seteado en el menu del sistema
        Tiempo de desactivación -> Toff -> 40 [min], parámetro que es seteado en el menu del sistema
        
    El horario y los subhorarios dependerán del estudio realizado por el biólogo de la camaronera 

# EDA-caso-1
# **Proyecto BD empresa local**
***Oscar David Ulloa Borja 2180395***
# Absentismo laboral y liquidacion de empleados
**Liquidacion de empleados y horas laborales**
# IMPOSTANTE
Los nombres, identificaciones y demas datos personales han sido eliminados para la proteccion de los mismos, se utilizanron otras variables para el analisis e identificacion.

# Contexto
Para este proyecto se contacto con la empresa ####### para proponer un analisis exploratorio de datos a uno de sus software para registros de empleados de empresas.

La empresa brindo una base de datos comleta en formato SQL en la cual mostraba todo el funcionamiento del software en cuanto a estructura de registro y calculo de liquidaciones para empleados.

En esta primera parte del proyecto se busca realizar una limpieza general de la base de datos, imputacion y correccion de datos y por ultimo un analisis exploratorio preliminar para pasar a un manejo de la informacion en SQL de nuevo. Esta version teine sugerencias de eliminacion, tratamiento o limitacion de los datos por parte de la empresa por lo que algunas caracteristicas u omiciones son en base a estas mismas.

# Planteamiento del proyecto

1.   Preparacion de la base de datos en SQL
2.   Importacion de la base a Python
3.   Limpieza e imputacion de datos
4.   Analsis exploratorio de datos

# ¿Que se desea conocer?
La necesidad expresada fue conocer los dias y horasios donde las personas presentaban mayor absentismo laboral, tambien en base a ello la representacion de tiempo invertido por los empleados y si se requiere una intervencion o no.

# Archivos necesarios
1. AnalisisDatosCaso1
2. Tablaprog
3. tablaliq
4. tablaemp
complementario(No son necesarios para el codigo principal
1.DATOSCSV
2.proyectoGAD (SQL)

# Diccionario de variables

Descripcion: Tipo de turno con fecha de entrada y salida + dia o informacion adicional
HTRAB: Horas trabajadas
HO: Horas ordinarias
HDES: Horas descanso
HED: Horas Extra dominicales
HEN: Horas extra nocturnas
HEDF:Horas extra festivo
RN: Recargo nocturno
TempDomLab: Tiempo dominical laborado
HRET: Horas retardo
HSANT: Horas salida anticipada

# Conclusiones (Luego del analisis)
Se puede concluir que existe un patrón notable de ausencias en ciertos días de la semana, específicamente los sábados, viernes y martes sugiriendo posibles factores o razones subyacentes que contribuyen a una menor asistencia en estos días en particular.

Por otro lado, las salidas anticipadas los fines de semana señala la posibilidad de que los empleados estén ansiosos por comenzar su tiempo libre y, por lo tanto, opten por irse antes del horario regular de salida. 

Para finalizar, los retardos para entrar los miércoles deben investigarse mas a fondo ya que no se encuentra una posible relacion o motivo al menos con el contexto dado hasta la realizacion de este analisis.


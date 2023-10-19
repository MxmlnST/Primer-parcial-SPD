# Alumno
Maximiliano Torrez
# Descripción
Trabajando sobre el proyecto de la parte II se agregó un nuevo componente: La fotoresistencia. Este componente disminuye su resistencia con el aumento de la intensidad de la luz incidente.
Registrando los valores de la fotorresistencia conectándolo a través del pin A1, se aprovechó la funcionalidad de la fotoresistencia para que los displays solo se enciendan durante la noche, y se apaguen durante el día.
Para ello se creó la función "funcionamiento_nocturno", la cual lee el valor de resistencia registrado en el pin A1. Los valores mayores a 10 corresponden a la noche, y al ser registrados la función retornara un 1. 

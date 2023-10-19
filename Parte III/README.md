# Alumno
Maximiliano Torrez
# Descripción
Trabajando sobre el proyecto de la parte II se agregó un nuevo componente: La fotoresistencia. Este componente disminuye su resistencia con el aumento de la intensidad de la luz incidente.
Registrando los valores de la fotorresistencia conectándolo a través del pin A1, se aprovechó su funcionalidad para que los displays solo se enciendan durante la noche, y se apaguen durante el día.
Para ello se creó la función "funcionamiento_nocturno", la cual lee el valor de resistencia registrado en el pin A1. Los valores mayores a 10 corresponden a la noche, y al ser registrados la función retornará un 1, en el caso contrario retornará un 0. Al código de la función displays(), que controla el encendido de los displays, se lo puso dentro de un condicional que tiene como condición: funcionamiento_nocturno() == 1. Así, los displays se encenderán solo cuando la función retorne 1, es decir, cuando sea de noche.
# link al proyecto
https://www.tinkercad.com/things/3FIRt7IUjw4

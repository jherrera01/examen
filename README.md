# examen
realizar estadistica.



Ejercicio: completar las estadísticas
Calificaciones parciales: 75, 80, 80, 80, 75 Calificaciones finales: 90, 70, 95, 90, 90
Preguntar originales: ¿Cuál es la media para el examen final? R=90
 ¿Cuál es el rango medio de las calificaciones parciales? R=77.5
 ¿Cuál es la calificación promedio de los estudiantes en el examen final? R=87 ¿Cuál es la moda para las calificaciones del examen final? R=90 
¿Cuál es el rango de las calificaciones parciales? R=5
Preguntas complemento: ¿Cuál es la media para el examen parcial? R=70
 ¿Cuál es el rango medio de las calificaciones finales? R=80 
¿Cuál es la calificación promedio de los estudiantes en el examen parcial? R=75 ¿Cuál es la moda para las calificaciones del examen parcial? R=70
 ¿Cuál es el rango de las calificaciones finales? R=25
 
 
Codigo de la grafica:
numest = [75,90; 80,70; 80,95; 80,90; 75,90]; bar (numest); str = {'JORGE', 'NABI', 'DAVID', 'GUSTAVO', 'FRANSISCO'}; set (gca, 'XTickLabel', str)
p=[75,80,80,80,75] p =
75 80 80 80 75
f=[90,70,95,90,90] f =
90 70 95 90 90
sort(p) ans = 75 75 80 80 80  sort(f) ans = 70 90 90 90 95 median(p) ans = 70 median(f) ans = 90 mode(p) ans = 70 mode(f) ans = 90 mean(p) ans = 75 mean(f) ans = 87


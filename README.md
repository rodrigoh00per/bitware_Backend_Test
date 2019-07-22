#e-bitware_Backend_Test
Backend hecho con node y express

Backend Creado con Node de  acuerdo al siguiente Ejercicio.

1. Realiza el Siguiente POST para agregar un Cliente
POST /NutriNET/Cliente
Con la siguiente estructura JSON (Diferentes Valores)
{
"Nombre": "Juan",
"Apellidos": "Perez Hernandez", "Nombre_Usuario": "Ju", "Correo_Electronico": "jperez@hotmail.com", "Contraseña": "juanitoperez"
}
Regresa en Pantalla un Alert del número de ID del Cliente (CVE_MENSAJE).
2. RealizaunGet
GET /NutriNET/Cliente
Recibe el resultado como JSON y muéstralo en una tabla HTML
3. Realiza el siguiente PUT, para modificar el peso y la estatura del Cliente 59
PUT /NutriNET/Cliente/59
{
"Edad": 39
"Estatura": 1.80 "Peso": 60 "GEB": 1500
}
Regresa en Pantalla un Alert del número de ID del Cliente (CVE_MENSAJE).


Se hizo deploy en heroku y el url es https://examenrestbitware.herokuapp.com/

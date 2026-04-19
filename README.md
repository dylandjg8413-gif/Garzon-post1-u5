# RetrofitLab - Consumo de API (Unidad 5)

Aplicación móvil desarrollada en Android con Kotlin que consume una API REST y muestra una lista de datos con paginación y manejo de estados en la interfaz.

---

# Características

- Consumo de API REST
- Lista de elementos en pantalla
- Paginación con botón "Cargar más"
- Manejo de estados en la UI:
  - Loading
  - Success
  - Error
  - Empty
- Interfaz construida con Jetpack Compose

---

# Estructura del proyecto

El proyecto está organizado en capas:


data/
domain/
presentation/
di/


---

# Requisitos

- Android Studio
- SDK 36
- Conexión a internet

---

Evidencias de funcionamiento

Lista cargada (Estado Success)
![App](Post5_Evidencia/App.png)

Paginación (Botón "Cargar más")
![Carga mas](Post5_Evidencia/Carga_mas.png)

Carga de más elementos
![Cargar mas](Post5_Evidencia/Cargar_mas.png)

Estado de error (Sin conexión)
![Error](Post5_Evidencia/Error.png)

Funcionalidad
Al iniciar la app se cargan los datos automáticamente
Se muestran en una lista
Al presionar "Cargar más":
Se agregan nuevos elementos
No se eliminan los anteriores
Si no hay internet:
Se muestra un mensaje de error
Aparece el botón "Reintentar"
Pruebas realizadas

✔ Carga inicial de datos
✔ Funcionamiento de paginación
✔ Visualización de estados
✔ Manejo de error sin conexión
✔ Recuperación con botón "Reintentar"

Autor

Dylan Garzón
Ingeniería de Sistemas - UDES Cúcuta

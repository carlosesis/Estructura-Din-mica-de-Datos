# Árbol Genealógico de Sucesión Dinámica

## 📄 Descripción del proyecto  
Este programa en C++ permite gestionar una familia a través de un árbol genealógico, con datos cargados desde un archivo CSV. Ofrece las siguientes funcionalidades:

- Cargar datos desde `familia.csv` (o generar un CSV de ejemplo si no existe).  
- Construir un árbol genealógico (padre → hijos / hermanos).  
- Mostrar la línea de sucesión actual, incluyendo solo los miembros vivos.  
- Aplicar una sucesión automática cuando el rey/reina actual muere o supera la edad límite (70 años), con reglas básicas de herencia: prioridad a varón vivo menor de 70 años; en ausencia de varones, considerar una mujer válida.  
- Editar los datos de cualquier persona (nombre, apellido, género, edad, estado de vida, estado de realeza), salvo `id` e `id_father`.  

## 📁 Estructura del proyecto  
├── main.cpp ← código principal: carga, menú, llamada a funciones
├── familia.csv ← datos de la familia (si no existe, se genera)
└── README.md ← este archivo de documentación

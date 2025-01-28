# Grupo4_Desarrollo

# Delimind

**Delimind** es una plataforma web inteligente que utiliza inteligencia artificial para recomendar los mejores platos de restaurantes en Quito, basándose en calidad, precio y ubicación. Este proyecto busca ofrecer a los usuarios una experiencia gastronómica personalizada y única, conectándolos con las mejores opciones gastronómicas de la ciudad.

## 🚀 Características

- Recomendación de platos mediante IA (API de OpenAI).
- Filtros avanzados por precio, calidad y ubicación.
- Sistema de búsqueda personalizada.
- Integración con mapas para localizar restaurantes cercanos.
- Interfaz moderna y responsiva creada con React.

## 🛠️ Tecnologías Utilizadas

### Frontend
- **React**: Para construir una interfaz de usuario interactiva y fácil de usar.
- **React Router**: Para la navegación entre páginas.
- **Axios**: Para consumir la API.

### Backend
- **Skarway (en evaluación)**: Se está considerando usar la nube de infraestructura de Skarway para alojar y ejecutar los servicios del backend.

### APIs
- **OpenAI API**: Para el motor de recomendación basado en IA.
- **Google Maps API**: Para geolocalización y búsqueda de restaurantes cercanos.

## 📂 Estructura del Proyecto

Delimind/
│
├── frontend/            # Código fuente del frontend (React)
│   ├── public/          # Archivos estáticos
│   ├── src/
│       ├── components/  # Componentes reutilizables
│       ├── pages/       # Páginas principales
│       ├── services/    # Servicios (e.g., consumo de API)
│       └── App.js       # Componente principal
│
├── backend/             # Carpeta del backend (en construcción)
│
└── README.md            # Documentación del proyecto



## 💻 Instalación y Configuración

### Frontend
1. Clona este repositorio:
   ```bash
   git clone https://github.com/BryanS1996/delimind.git
   cd delimind/frontend
2. Instala las dependencias:
   npm install

3. Crea un archivo .env en la carpeta frontend con las siguientes variables:
   env
   Copiar
   Editar
   REACT_APP_OPENAI_API_KEY=tu_clave_openai
   REACT_APP_GOOGLE_MAPS_API_KEY=tu_clave_google_maps

### Backend
El backend está en construcción y se evaluará si se implementa en la nube de Skarway. Las instrucciones específicas se incluirán en futuras actualizaciones.

📋 Roadmap
    Diseño inicial del frontend.
    Implementación del motor de recomendaciones con OpenAI.
    Desarrollo del backend.
    Integración con Skarway o alternativas de infraestructura en la nube.
    Implementación de filtros avanzados y mapas.
    Sistema de calificaciones y reseñas de usuarios.
 
## 🤝 Contribuciones
-Kevin Amaguaña
-Kenny Cisneros
-Bryan Chileno
-María Fernanda LLano

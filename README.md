# Burger-Queen
Requisitos previos
Node.js (v18+ recomendado)

npm (v9+ recomendado)

Ionic CLI

VS Code

Instalación y ejecución
Clonar el repositorio

git clone https://github.com/tu-usuario/tu-repo.git
cd tu-repo

Instalar dependencias
npm install

Configurar variables de entorno

Edita el archivo src/environments/environment.ts con las URL y claves API correspondientes (por ejemplo, Stripe keys y URL del backend).

Levantar la app en desarrollo
ionic serve

Probar en dispositivo o emulador

Si usas Capacitor, primero sincroniza:
npx cap sync

Luego abre el proyecto en Android Studio o Xcode, o ejecuta:
ionic capacitor run android
ionic capacitor run ios

Notas importantes
El backend debe estar corriendo y accesible en la URL configurada en environment.urlApi.

La integración de Stripe requiere claves de API válidas y el backend debe exponer el endpoint para generar Payment Intents.

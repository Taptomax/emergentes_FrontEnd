Ejecuta en tu terminal:
git clone https://github.com/Taptomax/emergentes_FrontEnd.git
cd emergentes_FrontEnd

Instalar herramientas de expo de forma global:
npm install -g expo-cli

Instalar las dependencias locales del proyecto:
npm install

Configurar la direccion del Servidor:
Abre el archivo App.js y edita la linea 7:
const API_URL = 'http://TU_IP_LOCAL:8000/analizar-foto/';

Preparar el celular (Instalar Expo Go):

Ve a la Play Store 
Busca e instala la aplicacion oficial llamada Expo Go.

OBLIGATORIO: Asegurate de que tanto tu computadora como tu telefono movil esten conectados exactamente a la misma red Wi-Fi (o al mismo modem por cable).

Ejecutar la aplicacion:
npx expo start
# Fanzzy

Plataforma de suscripción con pagos vía PayPal y Skrill, subida de videos a Cloudflare R2, e interfaz básica con login vía token.

## 🚀 Requisitos

- Node.js 16+
- GitHub o Render para deploy
- Cuenta de PayPal (developer)
- Cuenta de Skrill (merchant)
- Cloudflare R2 o S3-compatible para almacenar videos

## 📁 Estructura

- `index.js`: Servidor Express
- `public/index.html`: Interfaz principal
- `.env.example`: Variables necesarias
- `package.json`: Dependencias y scripts

## 🔧 Variables de entorno necesarias

Crea un archivo `.env` a partir de `.env.example` y llena con tus credenciales reales:


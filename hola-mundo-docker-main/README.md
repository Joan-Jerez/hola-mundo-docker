# 🐳 Hola Mundo Docker

Mi primera aplicación web containerizada con Docker.

## 📋 Descripción

Aplicación web "Hola Mundo" desarrollada en Node.js y containerizada usando Docker.

## 🛠️ Tecnologías

- **Node.js** - Entorno de ejecución
- **Express** - Framework web
- **Docker** - Containerización

## 🚀 Cómo usarlo

### Construir la imagen
```bash
docker build -t joanjerez53/hola-mundo:1.0 .
```

### Ejecutar el contenedor
```bash
docker run -p 3000:3000 joanjerez53/hola-mundo:1.0
```

### Acceder a la app
```
http://localhost:3000
```

### Imagen en Docker Hub
```bash
docker pull joanjerez53/hola-mundo:1.0
```

## 📁 Estructura

```
docker/
├── public/
│   └── index.html    # Página web
├── index.js          # Servidor Express
├── package.json      # Dependencias
└── Dockerfile        # Configuración Docker
```

## 📝 Licencia

MIT
# /app viene con esa carpeta
FROM node:19.2-alpine3.16

# cd /app
WORKDIR /app

# copiar el proyecto a la carpeta /app
COPY . .

# instalar dependencias
RUN npm install

# eliminar archivo y directorio
# RUN rm -rf Dockerfile .dockerignore
# RUN rm -rf Dockerfile && rm -rf .dockerignore

# ejecutar el proyecto
CMD [ "node", "app.js" ]

# docker build -t ticket .
# docker run -p 3000:3000 ticket



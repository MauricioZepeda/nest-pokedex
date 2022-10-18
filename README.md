<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el repositorio
```
git clone ...
```

2. Clonar el archivo __.env.template__ y renombrar la copia a __.env__

3. LLenar las variabels de entorno definidas en  __.env__

4. Instalar los paquetes
```
yarn install
```

5. Tener Nest CLI instalado
```
npm i -g @nest/cli
```

6. Levantar la base de datos
```
docker-compose up -d
```

7. Iniciar la aplicación en modo desarrollo
```
yarn start:dev
```

8. Reconstruir la base de datos con la semilla
```
http://localhost:3000/api/v2/seed
```


## Stack usado
* MongoDB
* Nest
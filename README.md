# Desarrollo Server

Desarrollo del servidor del proyecto del curso de GraphQL en Escalab

# GraphQL

Es un lenguaje creado por Facebook en 2012 para **manipular y realizar consultas de datos**.

Describe las **las capacidades y los requsitos** de los modelos de datos para aplicaciones cliente-servidor.

![](images/GraphQL1.png)

## Diccionario de datos


1. **Type defs** Definición de tu arquitectura de datos de tu api

2. **Query**: Definición de una consulta

3. **Mutation**: Querys encargadas de modificar y actualizar datos.

4. **Subscriptions**: Forma en que GraphQL maneja los eventos que emite un servidor el cual diferentes clientes puden subscribirse.

5. **Resolvers**: Encargados de darle la lógica a las querys de tu API.

6. **Apollo Server**: Define tu servidor con graphql y la comunicación de tu API.

## Diagrama de GraphQL

![](images/GraphQL.png)


## Creación carpeta proyecto

```
mkdir live-graphql
cd live-graphql
```


## Iniciar Proyecto
```bash
# Inicio del servidor con node
npm init -y

# Reestructurar carpeta node_modules
yarn install o npm install

# Instalación de dependencias
yarn add nodemon@2.0.2 -D
yarn add apollo-server@2.11.0 
yarn add apollo-server-express@2.11.0
yarn add dotenv@8.2.0
yarn add express@4.17.1
yarn add graphql@15.0.0
yarn add graphql-tools@7.0.2
yarn add mongoose@5.9.7
```

## Ejecución Proyecto
```bash
# Ejecución 
yarn start
```

## Codigos GIT
```bash
# Revisar logs
git log --pretty=oneline
#Cargar cambios y versiones
git branch -M main
git push -u origin main
# Generar Tags
           (Version) 
git tag -a V1.0.0 -m "Mensaje"
git push --tags
#branches (Ramas)
git add .
git checkout -b room
git commit -m "Agregado de dependencias"
git push origin room
#Unir Ramas a main
git checkout main
git merge <Nombre Rama> -m "Mensaje rama"
```

## Demostración del proyecto

```bash

```
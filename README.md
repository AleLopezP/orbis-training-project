### Comando para construir imagen
```javascript
  docker build -t orbis-training-docker:0.1.0 .
```
### Pasos para subir una imagen
```javascript
  docker tag orbis-training-docker:0.1.0 janethugarcia/orbis-training-docker:0.1.0

  docker push janethugarcia/orbis-training-docker:0.1.0
```

### Cambio de versión
```js
  docker tag orbis-training-docker:0.1.0 janethugarcia/orbis-training-docker:0.2.0
```
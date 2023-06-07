## Ejecución del proyecto
* git clone repo
* npm i -g serverless
* npm i
* npm start
* Ejecutamos el siguiente endpoint de tipo POST con postman 
```git
curl --location 'http://localhost:4000/dev/sender-queue/' \
--header 'x-api-key: f98d8cd98h73s204e3456998ecl9427j'
```

## Comandos
* Iniciar solo servicio elasticmq
```cmd
npm run queue-start
```
* Iniciar solo servicio serverless-offline
```cmd
npm run serverless-offline
```
* Iniciar el servicio de elasticmq y serverless
```cmd
npm start
```

